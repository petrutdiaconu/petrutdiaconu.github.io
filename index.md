![Text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

#### Cuprins

[Elemente avansate de Markdown](avansate.md)

[Formule cu mathjax](mathjax.md)

[Matrice si ecuatii cu MathJax](mathjax2.md)

[Diagrame Mermaid](/diagrame/mermaid.md)

# Implementarea relatiilor in Markdown

## Implemetarea relatiilor / legaturilor catre alte fisiere.

Fisierele accesate prin link-uri pot fii:
  1. Gazduite pe alte servere (de ex: accesarea unui alt site)
  2. Gazduite pe server-ul site-ului curent.
De asemenea, prin aceste link-uri se pot accesa si sectiunii din alte pagini ale aceluiasi  site.

### Sintaxa unui link Markdown

Tipuri de link-uri in Markdown
  1. Link-uri clasice (normale)
  2. Link-uri referentiate

#### Link-uri clasice

[Textul link-ului](https://google.com)

[Textul link-ului](https://google.com "Acecesare site Google")

#### Linkuri referentiale

Iata un [link][link1] catre site-ul Google.

[link1]: https://google.com/

Varianta prescurtata a link-urilor referentiale

Iata un link [important] catre siteul Google.

[important]: https://google.com/

#### Link-uri catre imaginii

#### Cuprins

![Text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)
