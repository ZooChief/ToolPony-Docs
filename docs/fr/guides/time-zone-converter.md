# Convertisseur de fuseaux horaires



Convertissez date et heure entre fuseaux IANA ou décalages UTC fixes.





## Prise en main



1. Utilisez l’exemple ou saisissez vos propres valeurs.
2. Calculez, puis copiez le résultat ou téléchargez les détails.







## Exemple



### Entrée



```
2026-01-15 09:00, Asia/Shanghai → America/New_York
```



### Résultat attendu



```
2026-01-14 20:00:00
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/time-zone-converter/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Les fuseaux IANA suivent les règles du navigateur. Une heure répétée donne deux instants, une heure sautée aucun. Un décalage UTC fixe reste constant.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## Mode de calcul



**IANA**

- Date
- Heure locale
- Fuseau IANA de départ
- Fuseau IANA de destination
- Heure répétée · Première occurrence / Deuxième occurrence





**Décalages UTC fixes**

- Date
- Heure locale
- Décalage de départ
- Décalage de destination

[Documentation](https://docs.toolpony.com/fr/guides/time-zone-converter/)
