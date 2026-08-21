# Decisões de engenharia

Este documento é um índice vivo de decisões que serão detalhadas à medida que houver contexto adequado para divulgação pública.

## Por que um Portal central?

O Portal Nexa concentra a identidade única, o contexto de conta, as decisões de acesso, o catálogo de produtos e as assinaturas da plataforma.

**TODO:** Registrar trade-offs e aprendizados em um ADR público e conciso.

## Por que produtos modulares?

Produtos modulares permitem focar necessidades operacionais específicas sem exigir a adoção de uma plataforma empresarial completa. Cada um preserva responsabilidades claras e ciclos de evolução próprios.

**TODO:** Adicionar exemplos públicos e seguros de fronteiras entre produtos.

## Evolução da autenticação

A autenticação evoluiu para uma abordagem centralizada, com acesso controlado entre Portal e produtos por SSO.

**TODO:** Adicionar linha do tempo sanitizada dessa evolução.

## Separação de backend

Frontends, backends, dados e deploys são independentes por produto, favorecendo responsabilidade clara e publicação isolada.

**TODO:** Documentar os trade-offs dessa separação sem expor detalhes internos.

## Evolução da infraestrutura

A infraestrutura evolui em torno de latência, controle operacional, responsabilidades separadas e deploy independente, com uma camada secundária de backend.

**TODO:** Adicionar narrativa visual de evolução sem identificadores de infraestrutura.

## Erros padronizados e observabilidade

Erros consistentes, validação, request IDs e logging estruturado apoiam manutenção, troubleshooting e operação.

**TODO:** Incluir exemplos sanitizados de convenções de resposta e logging.
