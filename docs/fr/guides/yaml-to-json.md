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

[Ouvrir l’outil complet · YAML en JSON](<https://toolpony.com/fr/tools/yaml-to-json/>)





## Notes



Plusieurs documents, balises personnalisées, alias cycliques et valeurs que JSON ne peut représenter sont rejetés. Citer une valeur si vous voulez dire une chaîne plutôt qu'un booléen ou un nombre.







## Limites



Jusqu'à 1 Mo. Les étiquettes personnalisées, les documents multiples, les clés non string, les alias excessifs, les structures cycliques et les valeurs que JSON ne peut pas préserver sont rejetés.





**Références de la méthode** [YAML 1.2.2](<https://yaml.org/spec/1.2.2/>) · [IETF · RFC 8259 (JSON)](<https://www.rfc-editor.org/rfc/rfc8259>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fyaml-to-json%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/yaml-to-json/)
