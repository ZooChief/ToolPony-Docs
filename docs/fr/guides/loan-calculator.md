# Calculateur de prêt



Calculez des versements, une durée à partir de la mensualité ou des remboursements supplémentaires datés, puis exportez l’échéancier.





## Prise en main



1. Choisissez une durée fixe, un versement mensuel cible ou des suppléments datés.
2. Indiquez le premier mois de versement. Saisissez les versements ponctuels ligne par ligne, par exemple 2026-06, 500.
3. Calculez puis sélectionnez l’échéancier à télécharger.







## Exemple



### Entrée



```
100 000 sur 10 ans à 6 %, versement mensuel
```



### Résultat attendu



```
≈1 110,21 par mois
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/loan-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Les versements utilisent le taux nominal converti à leur fréquence. Les suppléments datés suivent le versement mensuel prévu. Le taux est fixe et les montants intermédiaires restent non arrondis.



$$
M=\frac{Pr}{1-(1+r)^{-n}},\qquad M=\frac Pn\quad(r=0)
$$



$$
n=\frac{-\ln(1-Pr/M)}{\ln(1+r)},\qquad M>Pr\quad(r>0)
$$



$$
I_k=r B_{k-1},\qquad B_k=\max(0,B_{k-1}-(M-I_k)-E_k)
$$



P est le capital, r le taux par période, M le versement prévu et n le nombre de périodes. Pour la durée et les suppléments datés, divisez le pourcentage annuel par 1 200. B est le solde, I les intérêts et E le supplément imputé au capital.



Pour 45 000 à 6,3 % et 785 par mois, la durée estimée est de 68,38 mois. En mois entiers, il y a 69 versements et le dernier est réduit. Sélectionnez un échéancier avant le téléchargement.







## Mode de calcul



**Versements échelonnés**

- Capital emprunté
- Années
- Mois
- Taux annuel · %
- Capitalisation
- Fréquence de remboursement · Annuelle / Semestrielle / Trimestrielle / Mensuelle / Deux fois par mois / Toutes les deux semaines / Hebdomadaire / Quotidienne
- Supplément par versement





**Durée à partir du versement mensuel**

- Capital emprunté
- Versement mensuel
- Taux annuel · %





**Versements supplémentaires datés**

- Capital emprunté
- Années
- Mois
- Taux annuel · %
- Mois du premier versement
- Supplément mensuel
- Début du supplément mensuel
- Supplément annuel
- Début du supplément annuel
- Versements ponctuels (AAAA-MM, montant)





**Versement unique à l’échéance**

- Capital emprunté
- Années
- Mois
- Taux annuel · %
- Capitalisation





**Valeur actuelle d’une somme future**

- Somme due à l’échéance
- Années
- Mois
- Taux annuel · %
- Capitalisation

[Documentation](https://docs.toolpony.com/fr/guides/loan-calculator/)
