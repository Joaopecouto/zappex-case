<h1 align="center">zappex</h1>

<p align="center">
  CRM Kanban dentro do WhatsApp Web, em extensão de navegador com backend próprio.<br>
  <sub><i>Kanban CRM inside WhatsApp Web, built as a Chrome extension with its own backend.</i></sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white">
  <img src="https://img.shields.io/badge/Chrome_Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white">
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white">
  <img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white">
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white">
</p>

> Case study. O código é privado; este repositório documenta o que foi construído. · <i>Source code is private; this repository documents what was built.</i>

## O que faz · What it does

- **Board Kanban dentro do WhatsApp Web:** colunas, cards de contato e a camada de integração com a página, em extensão do Chrome.
- **Envio agendado e automações:** mensagens saem na hora marcada, uma sequência é tudo ou nada e há teto de envios por origem.
- **Gravação de áudio** embutida na interface.
- **Backend NestJS** com fila de envio, webhook serializado por conta e rota de saúde.

## Cobrança · Billing

- Assinatura com **Stripe**: produto, webhook e portal do cliente configurados por script via API.
- Planos gratuito e Pro, com recursos bloqueados no plano gratuito e tela de planos; o plano anual mostra o valor por mês e a economia.

## Privacidade · Privacy

- Aceite com versão, opt-out, política de retenção, exportação completa dos dados e exclusão de conta.
- Sentry configurado sem dados pessoais.

## Qualidade · Quality

| | |
| --- | --- |
| Testes automatizados | **6.086** passando em 05/11/2026 (2.014 no backend e 4.072 na extensão) |
| E2E | suíte que dirige um Chromium real com a extensão carregada |
| Lint | regras estritas de TypeScript ligadas e zeradas nos dois pacotes |
| Auditoria | rodadas de QA e de segurança sobre envio e cobrança |

<sub>Contato · Contact: <a href="mailto:joaopecouto77@gmail.com">joaopecouto77@gmail.com</a> · <a href="https://joaocouto.alcetus.com">joaocouto.alcetus.com</a></sub>
