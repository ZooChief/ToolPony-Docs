# Guide pratique · Générateur de mots de passe



Générer localement des mots de passe avec des jeux de caractères, des exclusions personnalisées et des caractères uniques optionnels.





## Exemple



### Entrée



```
20 caractères, quatre groupes de caractères
```



### Résultat attendu



```
Un nouveau mot de passe aléatoire
```





<a id="case-study"></a>



## Des codes de test à recopier



1. Générez six codes de 16 caractères en majuscules et chiffres. Excluez 2Z5S8B pour écarter trois paires difficiles à distinguer sur papier.
2. Chaque ligne contient les deux groupes, sans caractère répété. Copiez une ligne dans le formulaire à tester. Rouvrir l’exemple produit de nouvelles valeurs sur votre appareil.



[Essayer l’exemple](<https://toolpony.com/fr/tools/password-generator/#example-readable-codes>)





## Essayer

[Ouvrir l’outil complet · Générateur de mots de passe](<https://toolpony.com/fr/tools/password-generator/>)





## Méthode de calcul



Lorsque les groupes requis sont activés, un caractère est sélectionné dans chaque groupe, puis les positions sont reformulées. Les mots de passe vivent dans la page actuelle jusqu'à ce que vous partiez ou que vous l'effaciez.





**Références de la méthode** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fpassword-generator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/password-generator/)
