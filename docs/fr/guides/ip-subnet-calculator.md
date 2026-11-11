# Calculateur de sous-réseau IP



Inspectez les réseaux IPv4 et IPv6, les masques, les gammes et le nombre d'adresses, ou testez si une IP appartient à un bloc CIDR.





## Prise en main



1. Utilisez l’exemple ou saisissez vos propres valeurs.
2. Calculez, puis copiez le résultat ou téléchargez les détails.







## Exemple



### Entrée



```
192.0.2.129 /27
```



### Résultat attendu



```
Réseau 192.0.2.128/27, 30 hôtes utilisables
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/ip-subnet-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



AND the address with a prefix mask to find the first address. The host part has 2^(address bits − prefix) possibilities. IPv4 /31 utilise le comptage d'hôte par défaut, avec une option point à point RFC 3021. Un préfixe CIDR en ligne a priorité.



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



IPv4 accepte une longueur préfixe ou un masque pointillé contigu. Par exemple, 192.0.2.129 avec 255.255.25.5.224 donne le même réseau que 192.0.2.129/27.



La catégorie de taille du préfixe suit la convention A/B/C de l’outil de référence. La classe historique de l’adresse est affichée séparément. Utilisez la plage d’adresses pour vérifier l’appartenance à un bloc CIDR. L’option point à point change uniquement le comptage des hôtes pour /31.







## Mode de calcul



**IPv4**

- Adresse IPv4 ou CIDR
- Masque préfixe ou sous-net
- Utilisez les deux adresses sur les liens point à point /31





**IPv6**

- Adresse IPv6 ou CIDR
- Préfixe





**Vérifier l'adresse de l'adhésion**

- Réseau CIDR
- Adresse à vérifier

[Documentation](https://docs.toolpony.com/fr/guides/ip-subnet-calculator/)
