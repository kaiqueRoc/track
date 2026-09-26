# TRACK — Trilhas com propósito

Landing page conceitual para a **TRACK**, uma marca fictícia de guias de trilha na Serra do Espinhaço, Minas Gerais. Projeto desenvolvido como case de portfólio (design/direção de arte), simulando um site real de uma empresa de ecoturismo e hiking.

## Sobre o projeto

Site com estética dark e atmosférica, inspirada em marcas de outdoor de alto impacto visual. Cobre toda a jornada de um site de marca de serviços:

- **Hero** full-screen com foto dramática de montanha, social proof (avatar stack) e CTAs
- **Manifesto** — faixa com citação dos fundadores sobre a filosofia da marca
- **Serviços** — Day Hike, Expedição Multi-dia e Hike Privado
- **Trilhas em destaque** — layout dividido (foto | lista com nível e distância)
- **Galeria** — grid assimétrico com 5 fotos
- **Guias** — 3 cards com foto, especialidade e bio
- **Depoimentos** — 3 avaliações com estrelas e localização
- **CTA final** — banner sobre foto de pico com chamada para reserva
- **Footer** — navegação, contato e redes sociais

## Tecnologias

Site estático, sem build nem dependências:

- HTML5 semântico
- CSS puro (custom properties, grid, flexbox, animações)
- Fontes [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) + [Inter](https://fonts.google.com/specimen/Inter), via Google Fonts
- Imagens de [Unsplash](https://unsplash.com), sob a [Unsplash License](https://unsplash.com/license), embutidas como base64

## Estrutura

```
.
├── index.html   # site completo (HTML + CSS + imagens embutidas)
└── README.md
```

## Rodando localmente

Não precisa de servidor nem instalação — é um único arquivo HTML autocontido:

```bash
git clone https://github.com/kaiqueRoc/track.git
cd track
open index.html   # ou clique duas vezes no arquivo
```

## Publicando no GitHub Pages

1. Faça upload do `index.html` para um repositório público no GitHub
2. Vá em **Settings → Pages**
3. Em **Source**, selecione a branch `main` e a pasta `/ (root)`
4. Salve — em alguns minutos o site fica no ar em `kaiqueroc.github.io/track`

## Créditos

- Design e desenvolvimento: **Kaique**
- Projeto conceitual/fictício, criado para fins de portfólio — a marca TRACK não existe
- Fotografias: Unsplash (licença livre para uso)
