# Enterprise AI Reference Architectures

Padrões arquiteturais reutilizáveis, blueprints de integração e implementações de referência para sistemas de IA corporativa.

## Objetivo

Consolidar padrões arquiteturais validados para acelerar o design e a implementação de workloads de IA em ambientes corporativos Azure-first.

## Escopo

- Padrões de referência para arquiteturas de IA generativa em escala;
- Blueprints de integração com sistemas legados;
- Implementações de referência para padrões de governança e segurança;
- Diagramas e documentação técnica reutilizáveis.

## Princípios

- Patterns testados e validados, não teóricos
- Azure-first com extensibilidade multi-cloud
- Documentação como código (diagramas, specs, ADRs)
- Reutilização com adaptação contextual, não cópia cega

## Estrutura

| Área | Finalidade |
|---|---|
| `docs/architecture/` | Visão geral, princípios, atributos de qualidade, riscos, decisões |
| `docs/architecture/diagrams/` | Diagramas de referência (C4, fluxos, deployment) |
| `docs/security/` | Padrões de identidade, acesso e segurança |
| `docs/governance/` | Controles e operating model por padrão |
| `docs/guides/` | Guias de implementação por cenário |
| `docs/reference/` | Detalhes técnicos e consultivos |
| `docs/explanations/` | Contexto e raciocínio arquitetural |
| `docs/fundamentals/` | Conceitos fundamentais |
| `docs/devex/` | Experiência de desenvolvimento e plataforma |
| `docs/operations/` | Operações, observabilidade e resiliência |
| `docs/responsible-ai/` | Controles de Responsible AI por padrão |
| `docs/executive/` | Briefs orientados a decisão |
| `assessments/` | Avaliações de tecnologias e maturidade |
| `specs/` | Especificações de implementações de referência |
| `experiments/` | Experimentos, PoCs e validações de padrões |
| `templates/` | Templates para novos padrões e blueprints |
| `references/` | Fontes, glossário e bibliografia |
| `tools/scripts/` | Automações de validação |

## Relação com outros repositórios

- `technical-knowledge-repository-template`: base do scaffold compartilhado
- `enterprise-ai-architect-roadmap`: trilha de desenvolvimento do arquiteto
- `ai-agent-governance-framework`: policy e controles de governança
- `hybrid-ai-platform-engineering`: deployment e plataforma
- `responsible-ai-engineering`: safety e evaluation

## Status

Repositório criado em julho de 2026. Conteúdo será populado conforme padrões forem validados nos demais repositórios e projetos corporativos.