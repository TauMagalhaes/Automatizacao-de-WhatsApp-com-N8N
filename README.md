# Automatizacao-de-WhatsApp-com-N8N
Descrição do Projeto

Este projeto mostra como criar um chatbot no WhatsApp totalmente gratuito, utilizando:

N8N para automação de fluxos,

WAHA (WhatsApp HTTP API) como API de conexão com o WhatsApp,

Docker para orquestração dos serviços,

Redis e Postgres para suporte e armazenamento.

Com essa integração, é possível:

Conectar o WhatsApp via QR Code no WAHA.

Configurar o N8N para receber e processar mensagens.

Criar workflows inteligentes que usam agentes de IA (ex.: Google Gemini).

Implementar memória de conversas com Redis.

Responder mensagens automaticamente no WhatsApp de forma personalizada.

O fluxo inclui:

Configuração do Docker com docker-compose.yml.

Conexão do número do WhatsApp ao WAHA.

Integração com N8N e ativação de nodes comunitários (n8n-nodes-waha).

Criação de workflow com Webhook → Switch → AI Agent → Redis Memory → WAHA Send Message.

No final, você terá um chatbot inteligente no WhatsApp, sem custos de API, rodando 100% local ou em servidor (VPS).
