# Technical Knowledge Repository Template

Template para repositórios de conhecimento técnico corporativo em IA, com foco em documentação como código, rastreabilidade e evolução segura.

## Objetivo

Padronizar repositórios como:

- `enterprise-ai-architect`;
- `ai-agent-governance`;
- `hybrid-ai-deployment`;
- `enterprise-ai-devex`;
- `responsible-ai-engineering`.

## Modelo

O template combina, de forma pragmática:

- Diátaxis para organizar conhecimento;
- ADRs para decisões arquiteturais;
- C4 enxuto e diagramas como código;
- specs simplificadas para trabalhos complexos;
- experimentos isolados de conteúdo estável;
- assessments comparativos, de maturidade e risco;
- rastreabilidade entre requisitos, evidências, decisões e comunicação executiva.

## Estrutura

| Área | Finalidade |
|---|---|
| `docs/` | Conhecimento consolidado e reutilizável |
| `docs/architecture/decisions/` | Log de decisões arquiteturais |
| `specs/` | Capacidades e mudanças estruturadas |
| `experiments/` | Hipóteses, PoCs e benchmarks |
| `assessments/` | Avaliações de tecnologia, maturidade e risco |
| `references/` | Fontes, glossário e bibliografia |
| `templates/` | Modelos reutilizáveis de artefatos |
| `.github/` | Governança de contribuição e verificações mínimas |
| `AGENTS.md` | Contrato operacional para agentes de IA |

O scaffold é deliberadamente completo para funcionar como GitHub Template Repository. Pastas ainda sem conteúdo real são preservadas com `.gitkeep`; remova o marcador quando adicionar o primeiro artefato.

## Como usar

1. Gere um repositório a partir deste template.
2. Substitua este README pelo objetivo e escopo do domínio.
3. Ajuste owners e CODEOWNERS.
4. Remova áreas que comprovadamente não se aplicam ao domínio.
5. Classifique cada novo artefato antes de criá-lo.
6. Use PR para mudanças relevantes, mesmo trabalhando sozinho.

## Princípios

- Não tratar hipótese como fato.
- Não promover experimento diretamente a padrão aceito.
- Registrar decisões significativas como ADR.
- Nunca reescrever silenciosamente uma ADR aceita.
- Preferir fontes primárias e registrar datas de revisão.
- Separar evidência, interpretação, recomendação e decisão.
- Preservar histórico, links relativos e rastreabilidade.
- Automatizar problemas observados, não complexidade hipotética.

## Primeiros passos

- Consulte [`AGENTS.md`](AGENTS.md).
- Classifique o trabalho com os READMEs de cada área.
- Copie o modelo adequado de [`templates/`](templates/README.md).
- Consulte o [Architecture Decision Log](docs/architecture/decisions/README.md) antes de propor uma decisão.
