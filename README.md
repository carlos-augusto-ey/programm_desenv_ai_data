# Programa de Desenvolvimento de Talentos Internos

Repositório-base para formação técnica de profissionais internos em trilhas de Dados e IA, com metodologia de sprints, avaliação contínua e integração com Banco de Talentos.

## Objetivo

Estruturar uma jornada de desenvolvimento para perfis diferentes (trainee, desalocado, baixo rendimento, transição de área e grupos de afinidade), com foco em:

- formação prática orientada a projetos
- avaliação por sprint
- prontidão para alocação em projetos reais

## Estrutura do repositório

```text
.
├── tracks/                 # Trilhas técnicas e sprints
│   ├── 01-data-engineering/
│   ├── 02-data-science/
│   ├── 03-ai-engineering/
│   ├── 04-data-governance/
│   └── 05-ai-governance/
├── methodology/            # Metodologia do programa
│   ├── sprint-template/
│   ├── entry-profiles/
│   └── affinity-groups/
├── talent-bank/            # Artefatos de assessment e tracking
│   ├── intake/
│   ├── profiles/
│   └── tracking/
├── apresentation/          # Materiais executivos (PPTX)
└── test_api_eyq_incubator.py # Exemplo isolado de integração Azure OpenAI
```

## Trilhas

- **01 — Engenharia de Dados**: trilha detalhada com 3 sprints (Python/SQL -> Azure -> Databricks)
- **03 — Engenharia de IA**: trilha detalhada com 3 sprints (API LLM -> RAG -> Agente)
- **02, 04, 05**: estrutura criada, com conteúdo ainda em evolução

## Metodologia (4 semanas por sprint)

1. **Learn**: fundamentos e setup
2. **Build (parte 1)**: implementação inicial
3. **Build (parte 2)**: finalização, testes e documentação
4. **Present & Defend**: demo e defesa técnica

Referência: `methodology/sprint-template/README.md`

## Perfis de entrada

O programa atende 5 perfis:

1. Trainee / Entry-level
2. Desalocado programado
3. Baixo rendimento técnico
4. Transição de área
5. Grupos de afinidade (camada de suporte adicional)

Referência: `methodology/entry-profiles/README.md`

## Banco de Talentos

Arquivos para operação do programa:

- assessment inicial: `talent-bank/intake/assessment-template.md`
- perfil técnico por profissional: `talent-bank/profiles/profile-template.md`
- dashboard e fluxo de estado: `talent-bank/tracking/tracking-model.md`

## Como navegar (ordem sugerida)

1. `methodology/sprint-template/README.md`
2. `methodology/entry-profiles/README.md`
3. `tracks/01-data-engineering/README.md` ou `tracks/03-ai-engineering/README.md`
4. `talent-bank/tracking/tracking-model.md`

## Status atual

Este repositório está mais orientado a **framework de formação** (guides, templates e governança) do que a um único produto de software pronto para execução ponta a ponta.