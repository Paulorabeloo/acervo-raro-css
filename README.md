# Acervo Raro - CSS do site / Site CSS

[🇧🇷 Português](#-português) · [🇺🇸 English](#-english)

---

## 🇧🇷 Português

CSS customizado da home da loja [acervoraro.com.br](https://acervoraro.com.br), uma curadoria de perfumaria de nicho em decants. A loja roda no tema **Ipanema** da Nuvemshop, e todo o estilo abaixo foi aplicado por cima do tema, bloco a bloco, pelo editor da plataforma.

### Demonstração

🎬 **[Assista ao vídeo da home](demo-acervo-raro.mp4)** (48 s, MP4)

### Arquivos

| Arquivo | Conteúdo |
|---|---|
| `acervo-raro-css.css` | Todos os blocos `<style>` da home, organizados por seção, com a paleta de cores no final |
| `demo-acervo-raro.mp4` | Vídeo da home em funcionamento |

### O que o CSS cobre

1. Variáveis do header (cores, paddings, altura do logo)
2. Slideshow principal (sem paginação)
3. Barra de selos de benefícios, com marquee animado no mobile
4. Vitrines de produtos "Os mais pedidos" e "O Acervo", com hover que revela o selo **DECANT**
5. Carrossel de logos das casas em marquee contínuo
6. Banners de categoria (Para elas · Compartilháveis · Para eles)
7. Vitrine "Frascos lacrados"
8. Blocos imagem + texto ("A experiência" e "O que é o Acervo Raro")
9. Depoimentos, com cards em scroll horizontal no mobile
10. CTA escuro do Clube Acervo Raro
11. Rodapé

### Paleta

| Uso | Cor |
|---|---|
| Dourado principal | `#b8893c` |
| Dourado escuro (hover) | `#a07b3f` |
| Marrom quase preto | `#1a1308` |
| Marrom texto | `#6f5d48` |
| Bege fundo | `#fff4eb` |
| Bege claro (cards) | `#fffaf5` |
| Bege borda | `#ecdcc8` / `#d9c9b5` |

Fontes: **Playfair Display** (títulos) e **Public Sans** (sobretítulos).

### Como usar

Cada bloco é prefixado pelo `id` da seção no tema (`#ns-section-...`). Para reaproveitar em outra loja, troque o prefixo pelo id da sua seção ou remova-o para aplicar globalmente.

---

## 🇺🇸 English

Custom CSS for the home page of [acervoraro.com.br](https://acervoraro.com.br), a curated niche-perfume decant shop. The store runs on Nuvemshop's **Ipanema** theme, and every style below was layered on top of the theme, block by block, through the platform's editor.

### Demo

🎬 **[Watch the home page video](demo-acervo-raro.mp4)** (48 s, MP4)

### Files

| File | Contents |
|---|---|
| `acervo-raro-css.css` | Every `<style>` block from the home page, organized by section, with the color palette at the end |
| `demo-acervo-raro.mp4` | Video of the home page in action |

### What the CSS covers

1. Header variables (colors, paddings, logo height)
2. Main slideshow (pagination hidden)
3. Benefits badge bar, with an animated marquee on mobile
4. "Most requested" and "The Collection" product carousels, with a hover that reveals the **DECANT** badge
5. Brand logo carousel as a continuous marquee
6. Category banners (For her · Shareable · For him)
7. "Sealed bottles" product carousel
8. Image + text blocks ("The experience" and "What Acervo Raro is")
9. Testimonials, with horizontally scrolling cards on mobile
10. Dark call-to-action for the Acervo Raro Club
11. Footer

### Palette

| Use | Color |
|---|---|
| Primary gold | `#b8893c` |
| Dark gold (hover) | `#a07b3f` |
| Near-black brown | `#1a1308` |
| Body text brown | `#6f5d48` |
| Beige background | `#fff4eb` |
| Light beige (cards) | `#fffaf5` |
| Beige border | `#ecdcc8` / `#d9c9b5` |

Fonts: **Playfair Display** (headings) and **Public Sans** (eyebrows).

### How to use

Every block is scoped by the theme's section `id` (`#ns-section-...`). To reuse it in another store, swap the prefix for your own section id, or drop it to apply the rules globally.
