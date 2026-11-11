# Convertir un PDF en texte



Extrayez le texte sélectionnable des pages PDF en TXT ou JSON sur votre appareil.





## Prise en main



1. Ouvrez un PDF qui contient du texte sélectionnable.
2. Indiquez l’ordre des pages et extrayez le texte. Enregistrez en TXT ou en JSON avec les numéros des pages d’origine.







## Exemple



### Entrée



```
PDF avec « One » et « Two » sur les deux premières pages, sélection 2, 1
```



### Résultat attendu



```
JSON avec la page 2 « Two », puis la page 1 « One »
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/pdf-to-text/>)







## Limites



Limite de 30 Mo, 300 pages, deux millions de caractères et 200 000 segments. L’ordre interne du PDF est conservé. Les pages numérisées nécessitent une reconnaissance de caractères (OCR). Les PDF chiffrés sont refusés.

[Documentation](https://docs.toolpony.com/fr/guides/pdf-to-text/)
