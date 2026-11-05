<h1 align="center">zappex</h1>

<p align="center">CRM Kanban dentro do WhatsApp Web · <i>Kanban CRM inside WhatsApp Web</i></p>

<p align="center">
  <img src="./assets/chips/react.png" alt="React" height="30"> <img src="./assets/chips/typescript.png" alt="TypeScript" height="30"> <img src="./assets/chips/nestjs.png" alt="NestJS" height="30"> <img src="./assets/chips/stripe.png" alt="Stripe" height="30"> <img src="./assets/chips/chrome-extension.png" alt="Chrome extension" height="30"> <img src="./assets/chips/sentry.png" alt="Sentry" height="30"> <img src="./assets/chips/vitest.png" alt="Vitest" height="30">
</p>

> **PT** Case study. O código é privado; este repositório documenta o que foi construído.
> **EN** Case study. The source code is private; this repository documents what was built.

## Português

### O que faz

- **Board Kanban dentro do WhatsApp Web:** colunas, cards de contato e a camada de integração com a página, em extensão do Chrome.
- **Envio agendado e automações:** as mensagens saem na hora marcada, uma sequência é tudo ou nada e há teto de envios por origem.
- **Gravação de áudio** embutida na interface.
- **Backend NestJS** com fila de envio, webhook serializado por conta e rota de saúde.

### Cobrança e privacidade

- Assinatura com **Stripe**: produto, webhook e portal do cliente configurados por script via API. Planos gratuito e Pro, com recursos bloqueados no gratuito; o plano anual mostra o valor por mês e a economia.
- Aceite com versão, opt-out, política de retenção, exportação completa dos dados e exclusão de conta. Sentry configurado sem dados pessoais.

### Qualidade

| | |
| --- | --- |
| Testes automatizados | **6.086** passando em 05/11/2026 (2.014 no backend e 4.072 na extensão) |
| E2E | suíte que dirige um Chromium real com a extensão carregada |
| Lint | regras estritas de TypeScript ligadas e zeradas nos dois pacotes |
| Auditoria | rodadas de QA e de segurança sobre envio e cobrança |

## English

### What it does

- **Kanban board inside WhatsApp Web:** columns, contact cards and the page integration layer, built as a Chrome extension.
- **Scheduled sending and automations:** messages go out at the set time, a sequence is all or nothing, and there is a per-source sending cap.
- **Audio recording** built into the interface.
- **NestJS backend** with a send queue, per-account serialized webhooks and a health route.

### Billing and privacy

- **Stripe** subscriptions: product, webhook and customer portal configured by script through the API. Free and Pro plans, with features locked on the free plan; the annual plan shows the monthly price and the savings.
- Versioned consent, opt-out, a retention policy, full data export and account deletion. Sentry is configured without personal data.

### Quality

| | |
| --- | --- |
| Automated tests | **6,086** passing on 2026-11-05 (2,014 backend and 4,072 extension) |
| E2E | a suite that drives a real Chromium with the extension loaded |
| Lint | strict TypeScript rules enabled and at zero in both packages |
| Audits | QA and security rounds covering sending and billing |

<sub>[joaocouto.alcetus.com](https://joaocouto.alcetus.com) · [joaopecouto77@gmail.com](mailto:joaopecouto77@gmail.com)</sub>
