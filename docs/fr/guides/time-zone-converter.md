# Guide pratique · Convertisseur de fuseaux horaires



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





<a id="case-study"></a>



## Un rendez-vous à l’heure répétée



1. Le 1er novembre 2026, il est deux fois 01:30 à New York. À Shanghai, la première occurrence correspond à 13:30 et la seconde à 14:30. Choisissez celle de l’invitation et copiez l’instant UTC. Inverser les villes conserve le même rendez-vous.



[Essayer l’exemple](<https://toolpony.com/fr/tools/time-zone-converter/#example-repeated-meeting>)





## Un appel en novembre à La Havane



Cuba a conservé UTC−04:00 en novembre 2026. Le 23 novembre, un appel à 09:00 à La Havane correspond à 13:00 UTC. Pour un rendez-vous en heure locale, choisissez America/Havana pour appliquer les règles de cette date.



[Essayer l’exemple](<https://toolpony.com/fr/tools/time-zone-converter/#example-havana-clock>)







## Quand l’horloge avance de 30 minutes



Le 4 octobre 2026, l’île Lord Howe passe de 01:59:59 à 02:30:00. Essayez 02:15. Vous pouvez décaler le rendez-vous d’une demi-heure vers 01:45 ou 02:45. Cette dernière correspond au 3 octobre à 15:45 UTC.



[Essayer l’exemple](<https://toolpony.com/fr/tools/time-zone-converter/#example-half-hour-change>)







## Essayer

[Ouvrir l’outil complet · Convertisseur de fuseaux horaires](<https://toolpony.com/fr/tools/time-zone-converter/>)





## Méthode de calcul



Les règles IANA de la date choisie déterminent l’heure locale. Une heure répétée correspond à deux instants UTC. Avancer l’horloge crée un intervalle sauté. Un décalage fixe reste constant.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## Mode de calcul





### IANA



- Date
- Heure locale
- Fuseau IANA de départ
- Fuseau IANA de destination
- Heure répétée · Première occurrence / Deuxième occurrence







### Décalages UTC fixes



- Date
- Heure locale
- Décalage de départ
- Décalage de destination







**Références de la méthode** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Ftime-zone-converter%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/time-zone-converter/)
