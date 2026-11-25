# Guide pratique · Convertisseur Unicode



Convertissez points de code, octets UTF-8 et échappements JavaScript. Examinez les caractères et comparez leurs formes normalisées.





## Exemple



### Entrée



```
🐴
```



### Résultat attendu



```
U+1F434 ou F0 9F 90 B4
```





<a id="case-study"></a>



## Comparer deux écritures de é



1. Un e suivi de U+0301, une espace et 🐴 totalisent 3 graphèmes, 4 points de code, 5 unités UTF-16 et 8 octets UTF-8. En NFC, l’accent forme U+00E9 et le total passe à 7 octets. 🐴 reste un point de code et deux unités UTF-16.



[Essayer l’exemple](<https://toolpony.com/fr/tools/unicode-converter/#example-combining-accent>)





## Essayer

[Ouvrir l’outil complet · Convertisseur Unicode](<https://toolpony.com/fr/tools/unicode-converter/>)





## Méthode de calcul



Le mode code-point traite un caractère supplémentaire comme un scalaire. UTF-16 utilise deux unités de code pour un tel caractère. Les séquences de substitution non valides et les octets UTF-8 non valides sont rejetés.







## Mode de calcul





### Encoder le texte



- Entrée
- Encodage · Points de code Unicode / Octets UTF-8 hexadécimaux / Séquences d’échappement UTF-16 JavaScript / Échappements JS par point de code







### Décoder le texte



- Entrée
- Encodage · Points de code Unicode / Octets UTF-8 hexadécimaux / Séquences d’échappement UTF-16 JavaScript / Échappements JS par point de code







### Examiner les caractères



- Entrée
- Normalisation · Original / NFC / NFD / NFKC / NFKD







**Références de la méthode** [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>) · [Unicode · UAX \#15](<https://www.unicode.org/reports/tr15/>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Funicode-converter%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/unicode-converter/)
