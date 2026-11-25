# Guide pratique · Encoder et décoder en Base64



Encodez du texte UTF-8 ou des octets hexadécimaux en Base64 ou Base64url et enregistrez les octets décodés.





## Exemple



### Entrée



```
Encoder hello
```



### Résultat attendu



```
aGVsbG8=
```





<a id="case-study"></a>



## Retrouver les octets d’un Base64url



1. Choisissez décodage, alphabet URL et octets hexadécimaux. \_wCA7w donne FF 00 80 EF, avec un octet nul et une séquence UTF-8 invalide. Le téléchargement binaire conserve les quatre octets.



[Essayer l’exemple](<https://toolpony.com/fr/tools/base64-encoder-decoder/#example-binary-bytes>)





## Essayer

[Ouvrir l’outil complet · Encoder et décoder en Base64](<https://toolpony.com/fr/tools/base64-encoder-decoder/>)





## Méthode de calcul



Le format standard utilise + et /, le format URL - et \_ sans remplissage en sortie. Le texte UTF-8 est validé et garde le U+FEFF initial. Limites de 500 000 unités UTF-16 ou 500 000 octets.





**Références de la méthode** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>) · [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fbase64-encoder-decoder%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/base64-encoder-decoder/)
