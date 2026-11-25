# Guide pratique · Calculatrice de probabilités



Comparez les probabilités conditionnelles à partir d’effectifs ou de probabilités, puis étudiez les événements indépendants et les essais répétés.





## Exemple



### Entrée



```
Événements indépendants A = 0,31, B = 0,56
```



### Résultat attendu



```
Au moins un événement 0,6964
```





<a id="case-study"></a>



## Présence à deux ateliers



1. Sur 50 personnes, 18 ont suivi les deux séances, 12 seulement le matin (AM), 6 seulement l’après-midi (PM) et 14 aucune. Parmi les 24 présentes l’après-midi, 18 étaient là le matin (75 %). Parmi les 30 du matin, 18 sont revenues (60 %).



[Essayer l’exemple](<https://toolpony.com/fr/tools/probability-calculator/#example-workshop-attendance>)





## Essayer

[Ouvrir l’outil complet · Calculatrice de probabilités](<https://toolpony.com/fr/tools/probability-calculator/>)





## Méthode de calcul



L’union vaut la somme des probabilités marginales moins leur intersection. Parmi B, la part de A vaut P(A ∩ B) / P(B). Pour des événements indépendants, l’intersection est le produit des marginales.



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## Mode de calcul





### Deux événements indépendants



- Probabilité de A
- Probabilité de B







### intersection connue



- Saisie · Probabilités / Effectifs
- Probabilité de A
- Probabilité de B
- Les deux événements
- Nom de l’événement A
- Nom de l’événement B
- A ∩ B
- A ∩ ¬B
- ¬A ∩ B
- ¬A ∩ ¬B







### Récupérer des événements indépendants



- Première quantité connue · Probabilité de A / Probabilité de B / Pas A / Pas B / Les deux événements / Au moins un événement / Exactement un événement / Aucun des deux événements
- Première probabilité
- Deuxième quantité connue · Probabilité de A / Probabilité de B / Pas A / Pas B / Les deux événements / Au moins un événement / Exactement un événement / Aucun des deux événements
- Deuxième probabilité







### Essais indépendants répétés



- Probabilité de A
- Procès de A
- Probabilité de B
- Procès de B







### Intervalle de distribution normal



- Moyenne
- Écart-type
- Borne inférieure
- Borne supérieure







**Références de la méthode** [OpenStax · Contingency Tables](<https://openstax.org/books/introductory-statistics-2e/pages/3-4-contingency-tables>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fprobability-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/probability-calculator/)
