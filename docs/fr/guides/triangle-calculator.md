# Calculateur de triangle



À partir de trois mesures, calculez les angles, hauteurs, médianes et centres des cercles.





## Prise en main



1. Saisissez trois mesures dont au moins un côté.
2. Choisissez les radians pour π/2. En CCA, un angle aigu et son supplémentaire peuvent tous deux donner un triangle valide.
3. Dans le tableau, A est à l’origine et B sur l’axe x positif. Exportez le tableau sélectionné en CSV.







## Exemple



### Entrée



```
a = 7, b = 10, A = 30°
```



### Résultat attendu



```
Deux solutions, avec c ≈ 13,55923 et 3,76127.
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/triangle-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Utilisez une unité de longueur unique. Le côté a est opposé à l’angle A, de même pour b/B et c/C. Les angles seuls ne fixent pas la taille.



$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad a^2=b^2+c^2-2bc\cos A
$$



$$
\Delta=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac{a+b+c}{2},\quad h_a=2\Delta/a
$$



$$
m_a=\tfrac12\sqrt{2b^2+2c^2-a^2},\qquad r=\Delta/s,\qquad R=abc/(4\Delta)
$$







## Mode de calcul



**Valeurs connues**

- Côté a
- Côté b
- Côté c
- Angle A
- Angle B
- Angle C
- Unité d’angle · Degrés / Radians





**Trois côtés (CCC)**

- Côté a
- Côté b
- Côté c





**Deux côtés et angle compris (CAC)**

- Côté b
- Côté c
- Angle A · °





**Deux angles et un côté**

- Angle A · °
- Angle B · °
- Côté connu · a / b / c
- Côté





**Deux côtés et un angle opposé (CCA)**

- Côté a
- Côté b
- Angle A · °





**Côtés de l’angle droit**

- Côté a
- Côté b

[Documentation](https://docs.toolpony.com/fr/guides/triangle-calculator/)
