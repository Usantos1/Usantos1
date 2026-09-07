## Uander Santos

Construo sistemas para quem vende serviço: atendimento, anúncios, gestão e
conteúdo. Cada ferramenta nasce de um problema real da operação, roda na
Prime Camp antes de virar produto — e só então vira produto.

**[uandersts.com](https://uandersts.com)** &nbsp;·&nbsp; Campinas/SP

---

## Ecossistema Ativa

### [ATIVAVID](https://ativavid.com) — edição de vídeo com IA, na sua máquina

Você joga o vídeo bruto. Ele corta, legenda, escreve a manchete, escolhe a
trilha e entrega pronto para postar. O processamento é **local**: as
gravações não sobem para servidor nenhum.

- Aplicativo de desktop para Windows, com atualização automática
- Motor de render próprio, medido quadro a quadro contra o desenho de
  referência
- 85 estilos de legenda e 55 de manchete, com efeitos por palavra
- Transcrição, corte, roteiro e legenda do post assistidos por IA

[Baixar](https://github.com/Usantos1/Ativavid-Instalador/releases/latest) ·
[Notas de versão](https://github.com/Usantos1/Ativavid-Instalador/releases)

### [Ativa CRM](https://ativacrm.com.br) — atendimentos rápidos com IA

Funil de vendas centralizado, com automações e bots para WhatsApp e
Instagram.

- Painel de agência multi-cliente: licenças, contratos, onboarding,
  materiais e solicitações
- Área de membros com trilha de progresso e certificados verificáveis
- Editor de páginas e propostas comerciais
- Portal de status e suporte com anexos

### [Ativa Dash](https://ativadash.com) — onde você está perdendo dinheiro nos anúncios

Meta Ads, Google Ads, leads, saldo e metas numa visão só — sem planilha e
sem print.

- Multi-tenant, para empresários, gestores de tráfego e agências
- Integração com Google Ads por OAuth
- React + TypeScript no front; Node, Express, Prisma e PostgreSQL na API

### [Ativa FIX](https://ativafix.com) — gestão de assistência e vendas

Do orçamento ao relatório, e também o time.

- Orçamentos, pedidos, painel de alertas e relatórios de gestão
- Módulo de RH: portal de vagas, candidaturas com etapas e entrevistas
- Perfil comportamental (DISC) do candidato dentro do processo

---

## Outras plataformas

- **Matti Academy** — formação online com área de membros (cursos, aulas em
  vídeo, progresso) e painel administrativo. Supabase: Postgres, Auth e Edge
  Functions.
- Sistemas sob medida para clientes — CRM, captação de leads, diagnóstico
  conversacional e painel, em produção.

## Prime Camp

Assistência técnica de celulares em Campinas/SP. É a operação onde tudo
acima é testado antes de virar produto.

---

## Stack

**Front-end** · TypeScript, React, Vite, Tailwind, shadcn/ui sobre Radix,
TanStack Query e Router, React Hook Form + Zod, Zustand, Recharts, Framer
Motion, i18next

**Back-end** · Node com Express e Fastify, Prisma, PostgreSQL, Supabase
(Auth e Edge Functions), JWT com refresh e multi-tenant, Helmet, rate
limiting, node-cron, Docker

**Mobile** · Capacitor (iOS e Android) no Ativa FIX

**Integrações** · Meta Ads, Google Ads por OAuth, WhatsApp e Instagram,
Efí (Pix e cobrança), Stripe, ElevenLabs

**No ATIVAVID** · Python, FFmpeg, NumPy, Pillow, OpenCV, ONNX Runtime
(recorte de pessoa), Remotion como referência de desenho e um **motor de
render próprio** que a substitui, transcrição local com faster-whisper,
empacotamento com Inno Setup e atualização automática

**Do dia a dia** · PDF e planilha no navegador (jsPDF, html2canvas, xlsx),
código de barras e QR, editor de texto rico, mapas com Leaflet, testes com
Vitest e Playwright, deploy em VPS, Cloudflare e Vercel
