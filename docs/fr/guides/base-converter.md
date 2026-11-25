# Guide pratique · Convertisseur et calculatrice de bases



Convertir des entiers signés entre les bases 2–36 et effectuer des opérations arithmétiques, résiduelles ou bitwise exactes.





## Exemple



### Entrée



```
FF, base 16 à base 10
```



### Résultat attendu



```
255
```





<a id="case-study"></a>



## Lire un grand identifiant hexadécimal



1. Convertissez 0x20\_0000\_0000\_0001 en décimal. Le dernier 1 est conservé dans 9007199254740993. Inversez les bases ou copiez la ligne binaire sans espaces.



[Essayer l’exemple](<https://toolpony.com/fr/tools/base-converter/#example-large-hex-id>)





## Essayer

[Ouvrir l’outil complet · Convertisseur et calculatrice de bases](<https://toolpony.com/fr/tools/base-converter/>)





## Méthode de calcul



BigInt préserve chaque chiffre. La conversion accepte les entiers de 4 096 bits au plus et le calcul accepte 256 chiffres par opérande. La division entière tronque vers zéro. Les espaces et tirets bas peuvent séparer les chiffres.







## Mode de calcul





### Convertir la base



- Entier
- Base d'entrée
- Produit de base
- Chiffres minimaux de sortie







### Arithmétique entière



- Premier entier
- Deuxième entier
- Base d'entrée
- Produit de base
- Chiffres minimaux de sortie
- Opération · Ajouter / Soustraire / Multiplier / Diviser / Reste / AND / OR / XOR







[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fbase-converter%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/base-converter/)
