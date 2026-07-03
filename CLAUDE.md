# Olhar Engenharia — contexto do projeto

Site da Olhar Engenharia, empresa de autovistoria predial no Rio de Janeiro.
Idioma do projeto e da comunicação: **português (pt-BR)**.

## Identidade visual (usar sempre)

- Cores da marca: dourado `#C69A5E` (destaques/CTAs) e azul marinho `#164B8C` / `#0E2E52` (fundos e títulos).
- Logotipo: marca em "folha" recriada em SVG inline (não depender das imagens JPEG do repositório para o logo).
- Slogan: **"Observando detalhes para você"**.
- Tipografia: Montserrat (títulos) + Source Sans 3 (texto), via Google Fonts.

## Dados da empresa

- WhatsApp/telefone: 21 99780-6003 (`https://wa.me/5521997806003`, com mensagem pré-preenchida de orçamento)
- E-mail: contato.olharengenharia@gmail.com
- Instagram: @olhar.engenharia
- Serviços: Autovistoria Predial, Vistoria Técnica, Vistoria de Fachada com Drone, Mapeamento de Fachada, Laudo Técnico Detalhado.
- Base legal: Lei Estadual nº 6400/RJ, em vigor desde 05/03/2013 (autovistoria obrigatória no Estado do RJ).

## Padrão de qualidade esperado (validado pelo cliente)

O `index.html` atual é o resultado de referência para pedidos de páginas/landing pages.
Ao criar ou alterar páginas, manter esse padrão:

- **Arquivo único e estático** (HTML + CSS + JS inline), sem build, pronto para GitHub Pages.
- Estrutura completa: hero com slogan e CTAs → faixa da Lei 6400 → cards de serviços →
  seção da Lei 6400 (argumento para síndicos) → "Como funciona" em passos → diferenciais →
  FAQ → CTA final com todos os contatos → rodapé + botão flutuante de WhatsApp.
- Totalmente responsivo (menu hambúrguer no mobile), com animações sutis de reveal ao rolar.
- SEO básico: `<title>`, meta description, Open Graph, favicon SVG em data URI.
- CTAs de WhatsApp em vários pontos da página, sempre com mensagem pré-preenchida.

## Fluxo de trabalho

- Antes de entregar, **verificar visualmente**: renderizar com Playwright/Chromium
  (screenshot desktop de página inteira + mobile 390px) e enviar as prévias ao cliente.
- Commitar e fazer push no branch designado da sessão; não abrir PR sem pedido explícito.
