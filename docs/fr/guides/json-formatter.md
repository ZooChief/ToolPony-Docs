# Formateur JSON



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



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/json-formatter/>)







## Notes



Les clés et les chaînes de caractères ont besoin de guillemets doubles. Les commentaires et les virgules qui suivent ne sont pas JSON. Les nombres en dehors de la précision sûre sont rejetés pour éviter de changer silencieusement leurs valeurs.







## Limites



Jusqu'à 1 Mo. JSON non valide et précision numérique dangereuse sont rejetés. Le formatage ne se valide pas sur un schéma d'application.

[Documentation](https://docs.toolpony.com/fr/guides/json-formatter/)
