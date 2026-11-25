# Guide pratique · Formateur JSON



Collez JSON, choisissez une indentation, et formatez ou minifiez-la. Copiez le résultat ou téléchargez un fichier JSON. Cmd/Ctrl + Enter lance la matière.





## Prise en main



1. Coller un document JSON.
2. Choisissez deux ou quatre espaces, puis formatez; utilisez Minify pour un résultat compact.
3. Copiez le résultat ou téléchargez le fichier JSON.







## Exemple



### Entrée



```
{"name":"ToolPony","ready":true}
```



### Résultat attendu



```
{
  "name": "ToolPony",
  "ready": true
}
```







## Essayer

[Ouvrir l’outil complet · Formateur JSON](<https://toolpony.com/fr/tools/json-formatter/>)





## Notes



Les clés et les chaînes de caractères ont besoin de guillemets doubles. Les commentaires et les virgules qui suivent ne sont pas JSON. Les nombres en dehors de la précision sûre sont rejetés pour éviter de changer silencieusement leurs valeurs.







## Limites



Jusqu'à 1 Mo. JSON non valide et précision numérique dangereuse sont rejetés. Le formatage ne se valide pas sur un schéma d'application.





**Références de la méthode** [IETF · RFC 8259 (JSON)](<https://www.rfc-editor.org/rfc/rfc8259>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fjson-formatter%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/json-formatter/)
