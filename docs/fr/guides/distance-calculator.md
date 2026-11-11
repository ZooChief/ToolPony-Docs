# Calculatrice de distance



Trouvez la distance entre deux points 2D ou 3D, ou estimez la distance de surface entre les coordonnées géographiques.





## Prise en main



1. Utilisez l’exemple ou saisissez vos propres valeurs.
2. Calculez, puis copiez le résultat ou téléchargez les détails.







## Exemple



### Entrée



```
2D: (0, 0) à (3, 4)
```



### Résultat attendu



```
Distance 5
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/distance-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



La distance cartésienne utilise la norme euclidienne. Les modes géographiques utilisent l'approximation WGS 84 ellipsoïde et Lambert. Presque les points antipodes utilisent une approximation sphérique.



$$
d=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}
$$



Utilisez le mode 2D ou 3D pour les coordonnées qui partagent déjà une échelle linéaire. Convertissez les deux points à la même unité d'abord.



Pour les coordonnées géographiques, le nord et l'est sont positifs. Utilisez le mode degré-minute-seconde lorsqu'un relevé donne des champs angulaires séparés. Le résultat estime un chemin de surface ellipsoïdale.







## Mode de calcul



**2D**

- X1
- Y1
- X2
- Y2





**3D**

- X1
- Y1
- Z1
- X2
- Y2
- Z2





**Latitude et longitude**

- Première latitude · °
- Première longitude · °
- Deuxième latitude · °
- Deuxième longitude · °





**Degrés, minutes et secondes**

- Première latitude degrés
- Première minute de latitude
- Première latitude secondes
- Premier hémisphère latitude · N / S
- Première longitude degrés
- Première minute de longitude
- Première longitude secondes
- Premier hémisphère longitude · E / W
- Deuxième degré de latitude
- Deuxième minute de latitude
- Deuxième latitude secondes
- Hémisphère de deuxième latitude · N / S
- Deuxième degré de longitude
- Deuxième minute de longitude
- Deuxième longitude secondes
- Deuxième hémisphère longitude · E / W

[Documentation](https://docs.toolpony.com/fr/guides/distance-calculator/)
