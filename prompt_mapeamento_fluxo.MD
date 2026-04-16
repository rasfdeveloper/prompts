Você é um engenheiro de software especialista em mapeamento de fluxos.

Preciso que você mapeie o fluxo completo de uma rota específica da aplicação Python Quart.

ROTA A MAPEAR: [INFORME AQUI — ex: POST /credito/reserva]

PASSO 1 — MAPEAMENTO (leia os arquivos nesta ordem):
1. Localize o arquivo de rotas/blueprints do Quart e identifique a rota informada
2. Siga o fluxo: route → handler → service → client HTTP
3. Identifique a chamada de API para a aplicação de crédito (URL, método, payload)
4. Na aplicação de crédito, localize o endpoint chamado
5. Siga o fluxo interno da aplicação de crédito até a resposta final

A cada arquivo lido, informe:
- Nome do arquivo
- O que ele faz no contexto do fluxo
- Próximo arquivo a seguir

PASSO 2 — DIAGRAMA
Após mapear todos os arquivos, gere um diagrama Mermaid sequenceDiagram com:
- Cliente HTTP (quem chama a aplicação Quart)
- Cada camada da aplicação Quart (route → handler → service → client)
- A chamada HTTP entre as duas aplicações
- Cada camada da aplicação de crédito (controller → service → repository)
- Resposta de volta ponta a ponta

REGRAS:
- Leia no máximo 5 arquivos por vez, me informe o que encontrou antes de continuar
- Não invente nomes de funções ou arquivos — use apenas o que encontrar no código
- Se não conseguir seguir o fluxo em algum ponto, sinalize com [VERIFICAR: motivo]
- O diagrama final deve mostrar mensagens reais (nomes de métodos, endpoints, payloads)