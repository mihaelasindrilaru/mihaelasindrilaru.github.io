<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


![Text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=720)

[homepage](index.md)  

# Inserarea ecuatiilor si formulelor `MathJax`

**Sintaxa**

Formulele `MathJax` sunt inserate in aceeasi linie daca sunt plasate intr-o pereche de simboluri `$` .

Exemplu: Aceasta este o ecuatie $a=bc$

Formulele `Latex` (prin `MathJax`) se introduc pe rand nou intre doua perechi de simboluri

*Exemplu:*

$$a=b^c$$

# Ridicarea la putere

Se foloseste meta-caracterul `Latex` : `^`

Exemplu:

$$a=10^7$$

# `Subscript`

Se foloseste meta-caracterul `Latex` : `_`

*Exemplu:*

$$a_i = b^c$$



# Gruparea elementelor din formule

Elementele din formule se grupeaza prin meta-comutare :  `{` si `}`


$$ 10^{10} $$

# Litere grecesti 

*Exemple:*

`\alpha` - alpha litera mica ($\alpha$)
`\Alpha` - alpha litera mare ($\Alpha$) 

# Parantezele

- Parantezele rotunde se scriu direct ( nu au un inteles special `Latex` )
- Parantezele drepte se scriu direct ( nu au un inteles special `Latex` )
- Acoladele, deoarece ele sunt metacaractere de grupare, vor fi renderizate corect daca sunt `escapare` de intelesul lor special, punand in fata lor `metacaracterul` `\`

*Exemple:*

$$a = (b+c)^{3x} - [3+6x]$$

# Fractiile

*Exemplu:*

`\frac{numarator}{numitor}

$$ a = \frac{(a+bc)}{(d-c)} $$


