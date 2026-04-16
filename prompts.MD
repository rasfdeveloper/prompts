Sessão 1 — Visão Geral + Interface

Você é um engenheiro de software sênior documentando um projeto Python.
Leia APENAS os seguintes arquivos e gere a seção 1 do README:

- app/src/__init__.py
- app/src/interface/controllers/atualizar_risco_controller.py
- app/src/interface/controllers/consulta_controller.py
- app/src/interface/controllers/reserva_onera_controller.py
- app/src/interface/controllers/segmentacao_controller.py
- app/src/interface/controllers/health_check.py
- app/app.py
- app/run.py

Documente:
1. Propósito do serviço (1 parágrafo)
2. Endpoints disponíveis (tabela: método, rota, descrição)
3. Como executar localmente

NÃO leia nenhum outro arquivo além dos listados acima.
Responda em português brasileiro.

Sessão 2 — Application + Domain

Você é um engenheiro de software sênior documentando um projeto Python.
Leia APENAS os seguintes arquivos e gere a seção 2 do README:

- app/src/application/models/ (todos os arquivos)
- app/src/application/services/ (todos os arquivos)
- app/src/domain/validators.py

Documente:
1. Modelos de dados (tabela: nome, campos principais, descrição)
2. Serviços de aplicação (responsabilidade de cada service)
3. Regras de domínio e validações

NÃO leia nenhum outro arquivo além dos listados acima.
Responda em português brasileiro.

Sessão 3 — Infrastructure

Você é um engenheiro de software sênior documentando um projeto Python.
Leia APENAS os seguintes arquivos e gere a seção 3 do README:

- app/src/infrastructure/client/ (todos os arquivos)
- app/src/infrastructure/secrets_manager/ (todos os arquivos)
- app/src/infrastructure/utils/ (todos os arquivos)

Documente:
1. Integrações externas (quais sistemas o serviço consome)
2. Gerenciamento de secrets (como as credenciais são obtidas)
3. Utilitários disponíveis

NÃO leia nenhum outro arquivo além dos listados acima.
Responda em português brasileiro.

Sessão 4 — Infra/Deploy + Testes

Você é um engenheiro de software sênior documentando um projeto Python.
Leia APENAS os seguintes arquivos e gere a seção 4 do README:

- Dockerfile
- Makefile
- requirements.txt
- sonar-project.properties
- tox.ini
- infra/terraform/aws-ecs-service-credito-orquestrador.tf
- infra/terraform/environment.tf
- .iupipes.yml

Documente:
1. Arquitetura de deploy (ECS Fargate, variáveis de ambiente necessárias)
2. Pipeline CI/CD (etapas do .iupipes.yml)
3. Como rodar os testes (comandos do Makefile/tox)
4. Configuração do SonarQube

NÃO leia nenhum outro arquivo além dos listados acima.
Responda em português brasileiro.

