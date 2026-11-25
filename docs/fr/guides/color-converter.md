# Guide pratique · Convertisseur de couleurs



Convertissez les couleurs CSS en HEX, RGB, HSL et OKLCH, avec opacité et équivalent sRGB.





## Exemple



### Entrée



```
rgb(102, 51, 153)
```



### Résultat attendu



```
#663399, hsl(270 50% 40%)
```





<a id="case-study"></a>



## Préparer une couleur de repli sRGB



1. Collez color(display-p3 0 1 0 / 70%). Ce vert dépasse le gamut sRGB. Les deux échantillons montrent la source et son équivalent, ici \#00FB29B3.
2. La ligne RGB garde une opacité exacte de 0,7. En HEX à huit chiffres, B3 représente 179/255.



[Essayer l’exemple](<https://toolpony.com/fr/tools/color-converter/#example-wide-gamut>)





## Essayer

[Ouvrir l’outil complet · Convertisseur de couleurs](<https://toolpony.com/fr/tools/color-converter/>)





## Méthode de calcul



HEX arrondit les canaux sRGB en octets. Les couleurs hors gamut sont ramenées vers sRGB suivant la chroma OKLCH. L’aperçu source conserve son espace initial.





**Références de la méthode** [W3C · CSS Color 4](<https://www.w3.org/TR/css-color-4/>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fcolor-converter%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/color-converter/)
