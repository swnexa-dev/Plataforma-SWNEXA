# Infraestrutura

## Visão pública de alto nível

```text
Cliente
   │
   ▼
Vercel / Cloudflare
   │
   ▼
Aplicações de backend
   ├── AWS Lightsail + Ubuntu (infraestrutura principal)
   └── Render (infraestrutura secundária)
          │
          ▼
       MongoDB
```

```text
Aplicações
├── Amazon S3 (arquivos)
├── Stripe (pagamentos e assinaturas)
└── Resend (e-mail)
```

## Operação

O frontend é entregue pela Vercel. Os backends utilizam AWS Lightsail com Ubuntu como infraestrutura principal, complementada por uma infraestrutura secundária no Render. Essa segunda camada é tratada como secondary deployment ou fallback deployment; esta documentação não afirma failover automático.

MongoDB atende a camada de dados, com bancos de dados próprios por produto. Amazon S3, Stripe e Resend integram recursos de arquivos, assinaturas e comunicação por e-mail. GitHub é utilizado no fluxo de código, e Cloudflare atende domínio e edge.

Por segurança operacional, esta documentação não inclui IPs, portas privadas, hostnames, nomes de servidores, identificadores de conta, variáveis de ambiente, connection strings ou configurações de deploy.

**TODO:** Adicionar diagrama visual sanitizado de deploy e responsabilidade por camada.
