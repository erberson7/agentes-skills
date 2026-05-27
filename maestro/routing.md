# Roteamento de Intencoes

## Logica de roteamento

| Intencao do usuario | Agente(s) acionado(s) |
|---------------------|----------------------|
| Criar post para Instagram | roteirizador -> identidade-visual -> criador-imagem |
| Criar carrossel | roteirizador -> identidade-visual -> criador-imagem |
| Criar legenda | agente-roteirizador |
| Criar identidade visual | agente-identidade-visual |
| Gerar imagem | agente-criador-imagem |

## Fluxo padrao
1. Usuario envia instrucao via WhatsApp
2. Diretor Geral interpreta intencao
3. Diretor Geral resume o plano para o usuario
4. Usuario confirma
5. Agentes sao acionados em sequencia
6. Resultado entregue para validacao final
