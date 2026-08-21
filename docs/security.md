# Segurança

A segurança é considerada no acesso, no comportamento das aplicações e na operação. Práticas adequadas para divulgação pública incluem:

- cookies HttpOnly para sessões, quando aplicável;
- proteção contra CSRF e controles de CORS;
- autenticação, autorização e RBAC, quando aplicável;
- validação de entrada e respostas de erro controladas;
- tratamento centralizado de erros e logging estruturado;
- request IDs para apoiar rastreabilidade entre serviços;
- proteção de dados sensíveis na documentação e nos fluxos operacionais.

Os detalhes exatos de implementação, configuração e operação são omitidos intencionalmente. Assim, o repositório apresenta as preocupações de engenharia sem divulgar informações que possam facilitar uso indevido.

**TODO:** Publicar checklist de revisão de segurança sanitizado para o portfólio.
