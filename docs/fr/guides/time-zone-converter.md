# Convertisseur de fuseaux horaires



Convertissez date et heure entre fuseaux IANA ou décalages UTC fixes.





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

[Ouvrir l’outil complet · Convertisseur de fuseaux horaires](<https://toolpony.com/fr/tools/time-zone-converter/>)





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







**Références de la méthode** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Ftime-zone-converter%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/time-zone-converter/)
