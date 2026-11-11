# Calculatrice de probabilités



Calculer les probabilités d'événement, récupérer les probabilités indépendantes à partir de deux valeurs connues, ou utiliser un intervalle normal.





## Prise en main



1. Utilisez l’exemple ou saisissez vos propres valeurs.
2. Calculez, puis copiez le résultat ou téléchargez les détails.







## Exemple



### Entrée



```
Événements indépendants A = 0,31, B = 0,56
```



### Résultat attendu



```
Au moins un événement 0,6964
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/probability-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Pour les événements dépendants, entrez directement l'intersection. Les essais répétés multiplient leurs probabilités, et la probabilité d'au moins un succès utilise le complément.



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## Mode de calcul



**Deux événements indépendants**

- Probabilité de A
- Probabilité de B





**intersection connue**

- Probabilité de A
- Probabilité de B
- Les deux événements





**Récupérer des événements indépendants**

- Première quantité connue · Probabilité de A / Probabilité de B / Pas A / Pas B / Les deux événements / Au moins un événement / Exactement un événement / Aucun des deux événements
- Première probabilité
- Deuxième quantité connue · Probabilité de A / Probabilité de B / Pas A / Pas B / Les deux événements / Au moins un événement / Exactement un événement / Aucun des deux événements
- Deuxième probabilité





**Essais indépendants répétés**

- Probabilité de A
- Procès de A
- Probabilité de B
- Procès de B





**Intervalle de distribution normal**

- Moyenne
- Écart-type
- Borne inférieure
- Borne supérieure

[Documentation](https://docs.toolpony.com/fr/guides/probability-calculator/)
