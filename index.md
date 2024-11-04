![Text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=720)

**Cuprins**:

[Elemente avansate de Markdown](avansate.md)

[Formule cu mathjax](mathjax.md)

[Matrice si ecuatii cu MathJax](mathjax2.md)

[Diagrame Mermaid](/diagrame/)

***


# Implementarea relatiilor in Markdown 

## Implementarea relatiilor/legaturilor catre alte fisiere

Fisierele accesate prin link-uri pot fi:
1. Gazduite pe alte servere ( de ex. : accesarea unui alt site)
2. Gazduite pe severul site-ului curent.

De asemenea, prin aceste linkuri se pot accesa si sectiuni din pagina curenta sau sectiuni din alte pagini ale sectiunii.

### Sintaxa unui link Markdown

Tipuri de linkuri in Markdown

1. Linkuri clasice (normale)
2. Linkuri referentiale

## Linkurile clasice
**Variante**
[Textul linkului](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=720)
[Textul linkului](https://google.com/)

#### Linkurile referentiale

Iata un [link][link1] catre site-ul Google.

[link1]: https://google.com/

Varianta prescurtata a linkurilor referentiale :

Iata un link [important] catre site ul Google.
[important]: https://google.com/

#### Linkuri catre imagini 

![Text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=720).
