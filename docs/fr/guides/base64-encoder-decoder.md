# Encoder et décoder en Base64



Encoder le texte UTF-8 comme standard ou URL-safe Base64 et valider le texte décodé.





## Exemple



### Entrée



```
Encoder hello
```



### Résultat attendu



```
aGVsbG8=
```







## Essayer

[Ouvrir l’outil complet · Encoder et décoder en Base64](<https://toolpony.com/fr/tools/base64-encoder-decoder/>)





## Méthode de calcul



Le texte est converti en UTF-8. Le mode URL-safe utilise "-" et "\_" et omet le rembourrage en sortie. Jusqu'à 500 000 caractères d'entrée.





**Références de la méthode** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fbase64-encoder-decoder%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/base64-encoder-decoder/)
