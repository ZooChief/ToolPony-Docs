# Guide pratique · Encoder et décoder une URL



Encodez ou décodez des URL et des valeurs de formulaire, ou modifiez les paramètres dans l’ordre en gardant doublons et valeurs vides.





## Exemple



### Entrée



```
Encoder le composant : a+b & c
```



### Résultat attendu



```
a%2Bb%20%26%20c
```





<a id="case-study"></a>



## Conserver les signes plus dans une recherche



1. Encodez C++ &amp; tea comme valeur de formulaire pour obtenir C%2B%2B+%26+tea. Un plus devient %2B, une espace devient + et &amp; devient %26. Inversez pour retrouver la saisie. En composant URI une espace devient %20.
2. Dans l’exemple aux deux paramètres tag, remplacez le second par UI &amp; UX. Le premier, la valeur vide et \#filters restent intacts. La valeur modifiée devient UI+%26+UX.



[Essayer l’exemple](<https://toolpony.com/fr/tools/url-encoder-decoder/#example-query-plus>)





## Essayer

[Ouvrir l’outil complet · Encoder et décoder une URL](<https://toolpony.com/fr/tools/url-encoder-decoder/>)





## Méthode de calcul



Un composant encode les séparateurs réservés, une URL complète les conserve. En formulaire, + représente une espace. Les noms et valeurs sont encodés séparément sans changer le chemin ni le fragment.





**Références de la méthode** [IETF · RFC 3986](<https://www.rfc-editor.org/rfc/rfc3986>) · [WHATWG · Form encoding](<https://url.spec.whatwg.org/#application/x-www-form-urlencoded>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Furl-encoder-decoder%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/url-encoder-decoder/)
