# CloudInk Theme | Hugo

[![Hugo](https://img.shields.io/badge/Hugo-%5E0.128.0-ff4088?style=flat-square&logo=hugo)](https://gohugo.io/)
[![License](https://img.shields.io/github/license/pescarcena/CloudInk?style=flat-square)](https://github.com/pescarcena/CloudInk/blob/main/LICENSE)

> **CloudInk** is a **clean**, **elegant** but **advanced** blog theme for [Hugo](https://gohugo.io/), tailored for DevOps & Cloud blogs.

Forked from the [LoveIt](https://github.com/dillonzq/LoveIt) theme by [Dillon](https://dillonzq.com), which was originally based on [LeaveIt](https://github.com/liuzc/LeaveIt) and [KeepIt](https://github.com/Fastbyte01/KeepIt).

![CloudInk Theme](https://img.shields.io/badge/Theme-CloudInk-667eea?style=for-the-badge)

## What's New in CloudInk

CloudInk builds on top of LoveIt with significant improvements:

### Design & Typography
* Modern **tech-focused font stack**: Inter (body), Space Grotesk (headings), JetBrains Mono (code)
* Rebranded UI with a **clean, ink-inspired design language**
* Improved **Light/Dark mode** transitions

### Landing Page
* **Profile section** with avatar, animated typing subtitle, and social links
* **Skills section** with icon-based technology grid
* **Customizable navigation sections** for the home page

### Performance & Deployment
* **Cloudflare Pages** optimized with dedicated CDN endpoint (`jsdelivr.cloudflare`)
* **Multiple CDN profiles** supported (jsdelivr, jsdelivr.fastly, jsdelivr.cloudflare)
* **WebP image support** via `<picture>` elements with lazy loading fallback
* **SRI (Subresource Integrity)** with SHA256 fingerprinting for all assets

### Analytics
* **Google Analytics 4** (GA4) with Do Not Track support
* **Fathom Analytics**, **Plausible Analytics**, **Yandex Metrica**, and **GoatCounter** supported
* Ready for custom event tracking integration

### Updated Dependencies
* Font Awesome **7.2.0**
* Mermaid **11.5.0**
* KaTeX **0.16.21**
* ECharts **5.6.0**
* LightGallery **2.5.0**
* Lazysizes **5.3.2**

## Features (inherited from LoveIt)

### Performance and SEO
* Optimized for **performance**: 99/100 on mobile and 100/100 on desktop in [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights)
* Optimized SEO performance with a correct **SEO SCHEMA** based on JSON-LD
* **Multilanguage** supported and i18n ready

### Appearance and Layout
* **Desktop/Mobile Responsive** layout
* **Light/Dark** mode
* **Pagination** supported
* Easy-to-use and self-expanding **table of contents**
* Beautiful **CSS animation**

### Extended Features
* **Search** supported by [Lunr.js](https://lunrjs.com/), [Algolia](https://www.algolia.com/), [Fuse.js](https://fusejs.io/), or [Pagefind](https://pagefind.app/)
* Automatically **highlighting** code with copy to clipboard
* **Images gallery** supported by [lightGallery](https://github.com/sachinchoolur/lightgallery)
* Extended Markdown syntax for **[Font Awesome](https://fontawesome.com/) icons**
* **Mathematical formula** supported by [KaTeX](https://katex.org/)
* **Diagrams** shortcode supported by [Mermaid](https://github.com/mermaid-js/mermaid)
* **Charts** supported by [ECharts](https://echarts.apache.org/)
* **Animated typing** supported by [TypeIt](https://typeitjs.com/)
* **Cookie consent** banner supported

## Quick Start

```bash
# Add as a submodule
git submodule add https://github.com/pescarcena/CloudInk.git themes/CloudInk

# Set the theme in your hugo.toml
echo 'theme = "CloudInk"' >> hugo.toml
```

## Documentation

Build the example site locally:

```bash
hugo server --source=exampleSite
```

## License

CloudInk is licensed under the **MIT** license. Check the [LICENSE file](https://github.com/pescarcena/CloudInk/blob/main/LICENSE) for details.

## Acknowledgments

CloudInk is a fork of the [LoveIt](https://github.com/dillonzq/LoveIt) theme, originally created by [Dillon](https://dillonzq.com). LoveIt was itself based on [LeaveIt](https://github.com/liuzc/LeaveIt) by [LiuZhiChao](https://liuzhichao.com) and [KeepIt](https://github.com/Fastbyte01/KeepIt) by [Fastbyte01](https://www.fsb01.com/).

We are grateful to the original authors for their work. This theme is released under the same [MIT License](LICENSE) as the original projects.
