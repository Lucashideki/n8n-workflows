# Dashboard

Painel de monitoramento em tempo real para workflows n8n em produção.

Originado de um problema real: um cliente ligou perguntando por que o WhatsApp não notificava mais seus clientes. A instância havia caído horas antes e só ficamos sabendo quando a mensagem chegou.

---

## O Problema

Sem visibilidade sobre o que roda em produção, falhas só são descobertas quando o cliente reclama.

A solução imediata foi um alerta via Telegram para quedas de instância. Mas isso resolvia só um workflow.

**E os outros?**

---

## A Solução

Dashboard que monitora todos os workflows marcados como `[PROD]` em tempo real, consumindo diretamente a API do n8n — sem dependência de ferramentas externas.

O painel se atualiza automaticamente a cada 30 segundos. Pode ser deixado aberto em um monitor separado durante o trabalho.

---

## Métricas Exibidas

- Total de workflows monitorados
- Workflows saudáveis vs com erro
- Taxa de sucesso por workflow
- Histórico de erros dos últimos 7 dias
- Timestamp do último erro de cada workflow

---

## Workflow

![Workflow](./workflow.png)

## Dashboard

![dashboard-1](./dashboard-1.png)
![dashboard-2](./dashboard-1.png)


Acessado via browser pela URL do webhook. Cada acesso consulta a API do n8n em tempo real e retorna o dashboard atualizado.

---

## Decisão Técnica

O retry automático foi conscientemente descartado.

Em sistemas de produção, retry cego pode duplicar mensagens, gerar cobranças duplas ou criar registros duplicados no banco. A decisão foi monitorar e alertar — não interferir automaticamente.

---

## Stack

- **Orquestração:** n8n
- **Fonte de dados:** API n8n
- **Visualização:** Chart.js
- **Lógica:** Code Node (JavaScript)

---

## Projetos Relacionados

- [Versionamento](../versionamento) — CI/CD automático para workflows
- [Monitoramento de Instância WhatsApp](../monitoramento-instancia-whatsapp) — alerta via Telegram em caso de queda

---

## Contato

📧 lucashidekitb@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/lucas-hideki-tb