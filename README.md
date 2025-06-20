# Cascade CDN Scroll

Jednostránková knihovna pro **precizní scroll animace**, která spojuje všechny závislosti (Font Awesome, GSAP + pluginy) z jednoho CDN (jsDelivr).

## Funkce

- **Motion Path Animation**  
  Vlastní cesty s automatickou rotací a synchronizací na pozici scrollu.

- **Opacity & Fade Effects**  
  Plynulé odhalování elementů se scrub efektem.

- **Rotation & 3D Effects**  
  Otočení na ose Z s možností kombinovat s dalšími transformacemi.

- **Staggered Animations**  
  Sekvenční efekty s volitelným zpožděním.

- **Scale Transformations**  
  Dynamické změny velikosti s bounce/elastic easing.

## Instalace

1. **Stažení HTML/CSS/JS**  
   Zajistěte si kopii `index.html`, ve které jsou všechny styly inline a skripty na jednom CDN.

2. **Vložení do projektu**  
   Stačí zkopírovat `index.html` do vašeho projektu a případně přizpůsobit obsah sekcí.

## Rychlý start

1. V `<head>` nahraďte linky na CDN podle vzoru výše.
2. V `<body>` ponechte strukturu sekcí s odpovídajícími `id`:
   
   ```html
   <section id="motion">…</section>
   <section id="fade">…</section>
   <section id="rotate">…</section>
   <section id="stagger">…</section>
   <section id="scale">…</section>
   ```
