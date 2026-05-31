# Workflows: Agente Geral

## Workflow principal
- Nome sugerido no n8n: WF – Agente Geral
- Entrada esperada: user_message (mensagem do usuario), opcionalmente destinatario/metadata.
- Saida: texto de resposta no campo definido pelo workflow (ex.: agent_general_response ou text).

## Como pode ser usado
- Chamado diretamente quando a mensagem do WhatsApp comecar com comando (ex.: @agente).
- Usado como fallback "inteligente" quando o maestro/roteirizador nao localizar um workflow especializado.
