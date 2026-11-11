# Calcul de hachage de fichiers et de texte



Choisissez un texte ou des fichiers, sélectionnez un algorithme SHA-2 et calculez. Collez un digest attendu pour vérifier une correspondance ou télécharger les résultats sous CSV.





## Prise en main



1. Choisissez un texte ou sélectionnez un ou plusieurs fichiers.
2. Sélectionnez SHA-256, SHA-384 ou SHA-512, puis calculez.
3. Coller un hash attendu pour le vérifier, ou télécharger le résultat CSV.







## Exemple



### Entrée



```
Texte: abc, UTF-8, SHA-256
```



### Résultat attendu



```
ba7816bf8f01cfea414140de5dae2223b00361a396177a9cb410ff61f20015ad
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/file-hash-calculator/>)







## Notes



La vérification Hash compare les octets. Un codage différent, une fin de ligne ou même un octet modifié produit un digest différent.







## Limites



Jusqu'à 16 fichiers et 64 Mo combinés, ou un million de caractères de texte. Le texte utilise UTF-8. Les fichiers sont traités séquentiellement dans le navigateur.

[Documentation](https://docs.toolpony.com/fr/guides/file-hash-calculator/)
