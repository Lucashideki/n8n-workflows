# n8n Workflows & Automation Portfolio

Portfólio de workflows e automações desenvolvidas com foco em:

Eficiência operacional  
Automação de processos  
Integrações entre sistemas  
Redução de tarefas manuais  
Escalabilidade  

---

## Sobre

Sou **Lucas Hideki**, desenvolvedor com background em Product Owner e forte atuação em automação, integrações e IA.

Minha abordagem combina visão de produto, lógica de negócio e viabilidade técnica, estruturando soluções que:

- Otimizam fluxos operacionais  
- Reduzem fricções e erros manuais  
- Padronizam processos  
- Aumentam escalabilidade  

Utilizo o **n8n** como plataforma central para orquestração de integrações, regras e automações.

---

## Projetos

### 🔹 [Cobrança Inteligente de Boletos](./projects/cobranca-boletos)

Automação de fluxo de cobrança com cálculo de atraso, definição de etapas e envio automatizado baseado em regras de negócio.

**Stack:** n8n • Google Sheets • JavaScript • APIs  

---

### 🔹 [Assistente Virtual WhatsApp](./projects/assistente-whatsapp)

Assistente virtual com IA, processamento multimodal (texto, áudio, imagem), memória conversacional e integrações externas.

**Stack:** n8n • OpenAI • PostgreSQL • Redis • Supabase • APIs  

---

### 🔹 [Lembrete Automático de Agendamentos](./projects/lembrete-agendamentos)

Workflow para envio automático de lembretes de agendamento, evitando no-show e reduzindo esforço manual.

**Stack:** n8n • PostgreSQL • APIs • WhatsApp  

---

### 🔹 [RAG AI Agent](./projects/rag-ai-agent)

Arquitetura de RAG (Retrieval-Augmented Generation) com embeddings, vector store (Pinecone) e AI Agent para consultas baseadas em documentos.

**Stack:** n8n • OpenAI • Pinecone  

---

### 🔹 [Monitoramento de Instância WhatsApp](./projects/monitoramento-instancia-whatsapp)

Monitoramento contínuo de instância WhatsApp com alerta automático via Telegram em caso de queda, originado de um problema real identificado em produção.

**Stack:** n8n • JavaScript • Evolution API • Telegram

---

### 🔹 [Versionamento](./projects/versionamento)

Automação para versionamento contínuo de workflows no n8n, criada para resolver a falta de diff e rastreabilidade clara de mudanças. A solução consulta a API, compara `versionId` e realiza commit automático no GitHub.

**Stack:** n8n • JavaScript • API n8n • GitHub API

---

### 🔹 [Dashboard](./projects/dashboard)

Painel de monitoramento em tempo real para workflows em produção, originado de um problema real identificado com cliente. Monitora todos os workflows `[PROD]`, exibindo taxa de sucesso, histórico de erros e status de cada workflow com atualização automática a cada 30 segundos.

**Stack:** n8n • JavaScript • API n8n • Chart.js

Este workflow está publicado oficialmente no marketplace do n8n.

🔗 [Ver template](https://n8n.io/workflows/13665)

---

### 🔹 [Self-Healing Workflow](./projects/self-healing-workflow)

Sistema de monitoramento inteligente que aprende o comportamento normal de cada workflow e detecta anomalias automaticamente. Identifica alta taxa de erro, execuções lentas e workflows que pararam de rodar, salvando no banco e disparando alerta no Telegram antes que virem problema.

**Stack:** n8n • JavaScript • PostgreSQL • Telegram Bot API

---

### 🔹 [Multi-Tenant Automation Engine](./projects/multi-tenant)

Sistema de automação centralizado que atende múltiplos clientes a partir de um único workflow. Cada tenant tem sua própria configuração de canal, template de mensagem e janela de tempo para disparo, tudo definido no banco, sem duplicar workflows. Suporte a Schedule, Webhook e cadastro via formulário.

**Stack:** n8n • JavaScript • PostgreSQL • Telegram • WhatsApp • Gmail • Twilio

---

### 🔹 [Survey](./projects/survey)

Plataforma de pesquisas e votações disparadas via WhatsApp. Cada tenant tem sua própria base de clientes, grupos e configurações. O n8n orquestra o disparo e os relatórios. O Flask entrega o produto.

**Stack:** n8n • JavaScript • PostgreSQL • Python • Flask • Gmail • WhatsApp

---

### 🔹 [Pulse](./projects/cv-analyzer)

Analisador de currículos com IA para times de RH. O RH cria a vaga, faz upload dos PDFs e recebe score, gaps e perguntas de entrevista gerados por prompts encadeados no n8n. O Flask entrega o produto.

**Stack:** n8n • JavaScript • PostgreSQL • Python • Flask • OpenAI GPT-4.1-mini • weasyprint

---

## Principais Competências Demonstradas

Automação de processos  
Workflow Design  
Integrações via API  
Regras e lógica em JavaScript  
Arquitetura de automações  
IA aplicada (LLMs / RAG / Multimodal)  
Eficiência operacional  

---

## Contato

📧 **lucashidekitb@gmail.com**  
🔗 **LinkedIn:** https://www.linkedin.com/in/lucas-hideki-tb  
💻 **GitHub:** https://github.com/Lucashideki  

---

