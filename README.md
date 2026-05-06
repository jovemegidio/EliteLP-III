# Elite Company Digital — Landing Page v2.0

> Landing page de alta performance para uma agência de marketing digital brasileira. HTML/CSS/JS puro — sem frameworks, sem build, pronto para produção.

**[→ Ver ao vivo](https://jovemegidio.github.io/EliteLP-II/)**

---

## Preview

![Elite Company Digital Hero](uploads/IMG_9818.PNG)

---

## O que tem aqui

Uma landing page em arquivo único, projetada para conversão. Cada pixel serve a um objetivo: levar o visitante ao WhatsApp.

```
index.html          ← página completa (HTML + CSS + JS, auto-contido)
uploads/            ← screenshots de referência da marca
.nojekyll           ← configuração para GitHub Pages
```

---

## Destaques Técnicos

| Área | Abordagem |
|---|---|
| **Layout** | CSS Grid + Flexbox, sem framework |
| **Tipografia** | Sora · Instrument Serif · JetBrains Mono (Google Fonts) |
| **Animações** | Keyframes CSS puro — float, ticker, reveal no scroll |
| **Scroll reveal** | IntersectionObserver vanilla, sem biblioteca |
| **Logo** | SVG inline com gradient defs — nítido em qualquer tamanho |
| **Performance** | 1 requisição HTTP para o markup · Fontes carregadas de forma assíncrona |
| **Hospedagem** | GitHub Pages (estático, com CDN) |

---

## Funcionalidades

- **Header fixo** com blur + transparência no scroll
- **Ticker animado** — loop contínuo de prova social
- **Hero com logo real** — símbolo da marca com glow CSS e animação flutuante
- **Cards flutuantes** — ROAS, taxa de conversão, lead em tempo real
- **Bento grid** — seção sobre com efeito de borda mágica no hover
- **Cards de serviço** com ícone + lift no hover
- **Timeline de processo** — etapas numeradas com linhas conectoras
- **Seção de resultados** com cards de métricas
- **Accordion de FAQ** — JS puro, transição suave com max-height
- **Seção CTA** — todos os botões com link direto para WhatsApp e mensagem pré-preenchida
- **Responsivo** — 3 breakpoints, mobile-first
- **HTML semântico** — `<header>`, `<nav>`, `<section>`, `<footer>` e atributos ARIA corretos

---

## Design System

```css
/* Tokens de cor */
--bg-0: #03060d          /* fundo mais escuro */
--blue-500: #1f8bff      /* azul primário da marca */
--cyan-400: #2cc8ff      /* ciano de destaque */
--grad-blue: linear-gradient(135deg, #6ee2ff → #0a52b8)

/* Escala tipográfica */
Hero h1:   clamp(56px, 9.6vw, 152px)
Seções:    clamp(44px, 5.6vw, 78px)
Corpo:     16px / 1.6
```

---

## Como rodar localmente

Nenhum passo de build necessário:

```bash
# Clonar
git clone https://github.com/jovemegidio/EliteLP-II.git
cd EliteLP-II

# Abrir direto no navegador
start index.html          # Windows
open index.html           # macOS
xdg-open index.html       # Linux
```

Ou com qualquer servidor estático:

```bash
npx serve .
# → http://localhost:3000
```

---

## Contexto de Negócio

Desenvolvido para a **Elite Company Digital**, agência de marketing de performance liderada por Daniel Brito (São Paulo, Brasil).

| Métrica | Resultado |
|---|---|
| Impressões geradas | 13M+ |
| Empresas atendidas | 120+ |
| ROAS médio | 7,4× |
| Vendas geradas para clientes | R$ 4M+ |

A página posiciona o **Método Elite Performance** da agência — foco em estratégia, resultados mensuráveis e crescimento real.

---

## Personalização

**Número do WhatsApp** — substitua `5511990157500` pelo número real (DDD + número, apenas dígitos):

```bash
# macOS / Linux
sed -i 's/5511990157500/SEU_NUMERO/g' index.html

# Windows PowerShell
(Get-Content index.html) -replace '5511990157500','SEU_NUMERO' | Set-Content index.html
```

---

## Licença

Projeto privado. Todos os direitos reservados — Elite Company Digital © 2026.
