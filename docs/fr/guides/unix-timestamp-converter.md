# Guide pratique · Convertisseur d’horodatage Unix



Convertissez des secondes, millisecondes, microsecondes ou nanosecondes Unix en UTC et inversement, sans perte de chiffres.





## Exemple



### Entrée



```
0 secondes
```



### Résultat attendu



```
1970-01-01T00:00:00.000Z
```





<a id="case-study"></a>



## Une nanoseconde avant l’époque



1. Sélectionnez ns et entrez -1. L’heure UTC est 1969-12-31T23:59:59.999999999Z. Inversez le sens pour retrouver le même entier.
2. 1970-01-01T05:44:59.999999999+05:45 désigne le même instant. Copiez une unité ou exportez les quatre sur une seule ligne CSV.



[Essayer l’exemple](<https://toolpony.com/fr/tools/unix-timestamp-converter/#example-before-epoch>)





## Essayer

[Ouvrir l’outil complet · Convertisseur d’horodatage Unix](<https://toolpony.com/fr/tools/unix-timestamp-converter/>)





## Méthode de calcul



Le temps Unix part de 1970-01-01T00:00:00Z et ignore les secondes intercalaires. Les dates UTC de 1900 à 9999 acceptent neuf décimales avec un décalage explicite.







## Mode de calcul





### Horodatage → Date



- Horodatage Unix
- Unité · Secondes / Millisecondes / Microsecondes / Nanosecondes







### Date → Horodatage



- Date ISO 8601 avec décalage UTC
- Unité · Secondes / Millisecondes / Microsecondes / Nanosecondes







**Références de la méthode** [GNU · Seconds since the Epoch](<https://www.gnu.org/software/coreutils/manual/html_node/Seconds-since-the-Epoch.html>) · [IETF · RFC 3339](<https://www.rfc-editor.org/rfc/rfc3339>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Funix-timestamp-converter%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/unix-timestamp-converter/)
