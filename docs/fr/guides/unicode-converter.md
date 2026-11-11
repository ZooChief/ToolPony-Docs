# Convertisseur Unicode



Convertir le texte en points de code Unicode, en octets hexadécimaux UTF-8 ou en sorties UTF-16, et les décoder en texte.





## Prise en main



1. Utilisez l’exemple ou saisissez vos propres valeurs.
2. Calculez, puis copiez le résultat ou téléchargez les détails.







## Exemple



### Entrée



```
🐴
```



### Résultat attendu



```
U+1F434 ou F0 9F 90 B4
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/unicode-converter/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Le mode code-point traite un caractère supplémentaire comme un scalaire. UTF-16 utilise deux unités de code pour un tel caractère. Les séquences de substitution non valides et les octets UTF-8 non valides sont rejetés.







## Mode de calcul



**Encoder le texte**

- Entrée
- Encodage · Points de code Unicode / Octets UTF-8 hexadécimaux / Séquences d’échappement UTF-16 JavaScript





**Décoder le texte**

- Entrée
- Encodage · Points de code Unicode / Octets UTF-8 hexadécimaux / Séquences d’échappement UTF-16 JavaScript

[Documentation](https://docs.toolpony.com/fr/guides/unicode-converter/)
