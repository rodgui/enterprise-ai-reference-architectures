# Instruções para agentes de IA

## Objetivo do repositório

Este repositório registra conhecimento, decisões, avaliações, especificações e experimentos relacionados a arquitetura corporativa de IA.

## Princípios fundamentais

1. Não tratar hipótese como fato.
2. Não tratar resultado experimental como padrão aceito.
3. Nunca alterar silenciosamente uma ADR `Accepted`; criar nova ADR e marcar a anterior como `Superseded`.
4. Priorizar fontes primárias e registrar data de acesso ou revisão quando a informação for temporal.
5. Diferenciar explicitamente evidência, interpretação, recomendação e decisão.
6. Não duplicar conteúdo existente.
7. Usar links relativos entre documentos do repositório.
8. Preservar histórico e rastreabilidade.
9. Preferir alterações pequenas, reversíveis e revisáveis.
10. Declarar limitações, incertezas e horizonte de validade.

## Classificação dos artefatos

| Artefato | Finalidade |
|---|---|
| `docs/` | Conhecimento consolidado |
| `docs/architecture/decisions/` | Decisões arquiteturais |
| `specs/` | Mudança ou capacidade a definir |
| `experiments/` | Hipóteses, PoCs e testes |
| `assessments/` | Avaliações estruturadas |
| `references/` | Fontes e terminologia |
| `docs/executive/` | Comunicação orientada a decisão |

## Antes de criar ou alterar conteúdo

O agente deve:

1. Ler o README da área de destino.
2. Pesquisar documentos relacionados e possíveis duplicações.
3. Verificar ADRs existentes e possíveis conflitos.
4. Classificar o artefato pelo estágio de maturidade, não apenas pelo assunto.
5. Declarar os arquivos que serão criados ou alterados.
6. Preparar plano quando a mudança envolver mais de três arquivos.
7. Confirmar com o usuário antes de uma reorganização ampla ou migração.

## Regras para ADR

- Criar ADR somente para decisões arquitetonicamente significativas.
- Usar apenas: `Proposed`, `Accepted`, `Rejected`, `Superseded`, `Deprecated`.
- Registrar contexto, forças, alternativas, decisão, justificativa, consequências, riscos, validação e evidências.
- Não apagar ADRs rejeitadas ou substituídas.
- Ao mudar uma decisão aceita: criar nova ADR, atualizar as referências cruzadas e o índice.

## Regras para experimentos

- Declarar pergunta, hipótese, escopo, ambiente e procedimento antes dos resultados.
- Registrar evidências reproduzíveis e limitações.
- Não converter resultado isolado em recomendação arquitetural.
- Promover conclusões somente após revisão e, quando aplicável, ADR.

## Regras para specs

- Usar specs em implementação, automação, laboratório complexo, definição de plataforma ou trabalho multi-etapas.
- Manter `spec.md`, `plan.md`, `tasks.md` e `validation.md` no mesmo diretório numerado.
- Mapear requisitos a evidências verificáveis.

## Regras de evidência

Ordem preferencial:

1. documentação oficial;
2. normas, políticas e padrões;
3. publicações técnicas dos responsáveis pela tecnologia;
4. pesquisa acadêmica;
5. fontes secundárias reconhecidas.

Afirmações temporais, regulatórias, técnicas ou comerciais relevantes devem possuir fonte identificável e data de revisão. Não inventar referências nem preencher lacunas históricas como se fossem fatos.

## Metadados

Quando aplicável, usar front matter com:

- `status`: `draft`, `review`, `stable`, `deprecated` ou `archived`;
- `maturity`: `hypothesis`, `observed`, `validated` ou `adopted`;
- `last_reviewed` e `review_cycle`;
- owners, tags e artefatos relacionados.

Combinações incoerentes, como `status: stable` e `maturity: hypothesis`, devem ser reportadas.

## Qualidade mínima antes de concluir

- verificar links e referências;
- verificar conflitos com ADRs;
- confirmar que conclusões são suportadas pelas evidências;
- declarar limitações e confiança;
- atualizar índices, README, ROADMAP ou CHANGELOG quando aplicável;
- validar nomes, estados e links relativos;
- inspecionar o diff Git;
- executar as verificações disponíveis.

## Escopo destas instruções

Repositórios gerados a partir deste template podem estender estas regras. Regras específicas não devem enfraquecer silenciosamente os princípios de evidência, rastreabilidade, segurança ou preservação de ADRs.
