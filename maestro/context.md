# Contexto de Sessao

## Como usar
Este arquivo armazena variaveis de contexto da sessao ativa. Nao deve acumular historico completo, apenas o estado atual.

## Variaveis de contexto
- sessao_id: identificador unico da sessao
- usuario: nome do usuario ativo
- ultima_tarefa: ultima tarefa executada
- agentes_acionados: lista de agentes usados na sessao
- pendencias: itens aguardando aprovacao do usuario

## Regra de limpeza
Ao iniciar nova sessao, limpar variaveis anteriores e registrar apenas o contexto novo.
