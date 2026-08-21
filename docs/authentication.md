# Autenticação e acesso

O Portal Nexa é a autoridade central de identidade e acesso da SWNexa. A pessoa ou empresa realiza um cadastro único e passa a utilizar a mesma identidade em todo o ecossistema.

## Fluxo conceitual

1. O usuário se autentica no Portal Nexa.
2. O Portal determina quais produtos estão disponíveis conforme autorização e assinatura.
3. Ao abrir um produto autorizado, o acesso é estabelecido automaticamente por um fluxo controlado de SSO.
4. Quando necessário, cada produto estabelece sua própria sessão para suas responsabilidades.
5. Um acesso direto a produto sem sessão ou autorização válida é encaminhado ao Portal para o fluxo adequado.

## Trial e assinaturas

Uma nova conta recebe acesso inicial a todos os produtos por 14 dias corridos, sem bloqueio de módulos. Após o trial, o acesso depende da seleção de uma assinatura.

As assinaturas podem conceder acesso a módulos individuais ou ao conjunto da plataforma. O Portal possui integração com Stripe para operações de assinatura gerenciadas pelo usuário, incluindo cancelamento, renovação automática e gerenciamento de plano.

## Limite de divulgação

Este documento não publica formatos de tokens, endpoints, segredos, tempos de expiração, claims ou outros detalhes que possam reduzir a segurança da plataforma.

**TODO:** Adicionar uma jornada visual do usuário após revisão e sanitização.
