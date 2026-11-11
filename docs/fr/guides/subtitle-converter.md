# Convertisseur de sous-titres



Convertissez SRT et WebVTT, décalez ou redimensionnez les temps et vérifiez les chevauchements.





## Prise en main



1. Collez le texte ou importez un SRT ou VTT, puis choisissez le format de sortie.
2. Un décalage positif retarde les sous-titres. Multipliez le temps relatif à l’ancrage par l’échelle, puis ajoutez le décalage. Vérifiez les coupures et chevauchements.







## Exemple



### Entrée



```
1
00:00:00,120 --> 00:00:01,400
A line
Second line

2
00:00:01,350 --> 00:00:02,700
Overlap 50 ms
```



### Résultat attendu



```
WEBVTT

00:00:00.120 --> 00:00:01.400
A line
Second line

00:00:01.350 --> 00:00:02.700
Overlap 50 ms
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/subtitle-converter/>)







## Limites



Jusqu’à 1 Mio de texte et 10 000 sous-titres. Les sous-titres finissant avant zéro sont supprimés et ceux qui traversent zéro y commencent. SRT ne représente pas tous les styles, positions ou identifiants WebVTT.

[Documentation](https://docs.toolpony.com/fr/guides/subtitle-converter/)
