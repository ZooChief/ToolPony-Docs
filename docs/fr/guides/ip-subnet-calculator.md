# Guide pratique · Calculateur de sous-réseau IP



Inspectez les réseaux IPv4 et IPv6, les masques, les gammes et le nombre d'adresses, ou testez si une IP appartient à un bloc CIDR.





## Exemple



### Entrée



```
192.0.2.129 /27
```



### Résultat attendu



```
Réseau 192.0.2.128/27, 30 hôtes utilisables
```





<a id="case-study"></a>



## Vérifier une limite de préfixe



1. 192.0.2.128/27 se termine à .159 inclus, adresse de diffusion IPv4. .160 est hors préfixe et une adresse IPv6 appartient à une autre famille.



[Essayer l’exemple](<https://toolpony.com/fr/tools/ip-subnet-calculator/#example-subnet-boundary>)





## Deux extrémités IPv6



2001:db8::8/127 contient ::8 et ::9 aux positions 1 et 2. IPv6 ne définit pas d’adresse de diffusion.



[Essayer l’exemple](<https://toolpony.com/fr/tools/ip-subnet-calculator/#example-ipv6-endpoints>)







## Essayer

[Ouvrir l’outil complet · Calculateur de sous-réseau IP](<https://toolpony.com/fr/tools/ip-subnet-calculator/>)





## Méthode de calcul



AND the address with a prefix mask to find the first address. The host part has 2^(address bits − prefix) possibilities. IPv4 /31 utilise le comptage d'hôte par défaut, avec une option point à point RFC 3021. Un préfixe CIDR en ligne a priorité.



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



IPv4 accepte une longueur préfixe ou un masque pointillé contigu. Par exemple, 192.0.2.129 avec 255.255.25.5.224 donne le même réseau que 192.0.2.129/27.



La catégorie de taille du préfixe suit la convention A/B/C de l’outil de référence. La classe historique de l’adresse est affichée séparément. Utilisez la plage d’adresses pour vérifier l’appartenance à un bloc CIDR. L’option point à point change uniquement le comptage des hôtes pour /31.







## Mode de calcul





### IPv4



- Adresse IPv4 ou CIDR
- Masque préfixe ou sous-net
- Utilisez les deux adresses sur les liens point à point /31







### IPv6



- Adresse IPv6 ou CIDR
- Préfixe







### Vérifier l'adresse de l'adhésion



- Réseau CIDR
- Adresse à vérifier







**Références de la méthode** [IETF · RFC 4632 (CIDR)](<https://www.rfc-editor.org/rfc/rfc4632>) · [IETF · RFC 3021 (/31 links)](<https://www.rfc-editor.org/rfc/rfc3021>) · [IETF · RFC 5952 (IPv6 text)](<https://www.rfc-editor.org/rfc/rfc5952>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fip-subnet-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/ip-subnet-calculator/)
