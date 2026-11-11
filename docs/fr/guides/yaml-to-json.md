# YAML en JSON



Collez un document YAML et convertissez-le en JSON. Les cartes doivent utiliser des touches de chaîne; la sortie est formatée et prête à être copiée ou téléchargée.





## Prise en main



1. Coller un document YAML avec des touches de mappage de chaînes.
2. Convertir en JSON.
3. Inspectez, copiez ou téléchargez le résultat.







## Exemple



### Entrée



```
name: ToolPony
ready: true
```



### Résultat attendu



```
{
  "name": "ToolPony",
  "ready": true
}
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/yaml-to-json/>)







## Notes



Plusieurs documents, balises personnalisées, alias cycliques et valeurs que JSON ne peut représenter sont rejetés. Citer une valeur si vous voulez dire une chaîne plutôt qu'un booléen ou un nombre.







## Limites



Jusqu'à 1 Mo. Les étiquettes personnalisées, les documents multiples, les clés non string, les alias excessifs, les structures cycliques et les valeurs que JSON ne peut pas préserver sont rejetés.

[Documentation](https://docs.toolpony.com/fr/guides/yaml-to-json/)
