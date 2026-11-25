# Guide pratique · Générateur de nombres aléatoires



Tirez des entiers au hasard, bornes comprises, avec tri et tirage sans répétition au choix.





## Exemple



### Entrée



```
Minimum 1, maximum 10, nombre 5
```



### Résultat attendu



```
Cinq entiers aléatoires de 1 à 10
```





<a id="case-study"></a>



## Tirer quatre billets



1. Numérotez 12 billets de 101 à 112 et tirez-en quatre sans remise. Triez pour annoncer les numéros, puis désactivez le tri pour revenir à l’ordre du tirage. Le CSV conserve le rang initial de chaque billet.



[Essayer l’exemple](<https://toolpony.com/fr/tools/random-number-generator/#example-ticket-draw>)





## Essayer

[Ouvrir l’outil complet · Générateur de nombres aléatoires](<https://toolpony.com/fr/tools/random-number-generator/>)





## Méthode de calcul



Les nombres aléatoires proviennent de Web Crypto. L’échantillonnage par rejet évite le biais modulo. Générez jusqu’à 1 000 entiers entre −1 000 000 000 et 1 000 000 000.





**Références de la méthode** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Frandom-number-generator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/random-number-generator/)
