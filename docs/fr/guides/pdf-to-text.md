# Convertir un PDF en texte



Extrayez le texte sélectionnable des pages PDF en TXT ou JSON sur votre appareil.





## Prise en main



1. Ouvrez un PDF qui contient du texte sélectionnable.
2. Indiquez l’ordre des pages et extrayez le texte. Enregistrez en TXT ou en JSON avec les numéros des pages d’origine.







## Exemple



### Entrée



```
PDF avec « One » et « Two » sur les deux premières pages, sélection 2, 1
```

[Exemple · PDF](<https://toolpony.com/samples/toolpony-pages.pdf>)

### Résultat attendu



```
JSON avec la page 2 « Two », puis la page 1 « One »
```





<a id="case-study"></a>



## Repérer une page sans texte dans un PDF mixte



1. Le PDF d’exemple contient « Order 417 » en page 1, un simple échantillon bleu en image en page 2 et « Total 42 » en page 3. Dans l’outil complet, le bouton d’essai du PDF mixte charge le fichier, sélectionne 3, 2, 1 et choisit la sortie JSON.
2. Après extraction, le premier enregistrement contient « Total 42 » de la page 3, le deuxième conserve la page 2 avec un champ text vide, et le dernier donne « Order 417 » de la page 1. Le résultat signale aussi le numéro d’origine 2.
3. Avant d’importer votre texte dans un autre logiciel, vérifiez les pages signalées. Un schéma peut rester une image. Pour un texte imprimé numérisé, utilisez l’OCR pour créer une couche de texte.



[Convertir un PDF en JPG ou PNG](<https://toolpony.com/fr/tools/pdf-to-jpg/>)



[toolpony-mixed-pages.pdf](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)





## Essayer

[Ouvrir l’outil complet · Convertir un PDF en texte](<https://toolpony.com/fr/tools/pdf-to-text/>)





## Limites



Limite de 30 Mo, 300 pages, deux millions de caractères et 200 000 segments. L’ordre interne du PDF est conservé. Les pages numérisées nécessitent une reconnaissance de caractères (OCR). Les PDF chiffrés sont refusés.



Si un scan lisible ne donne aucun texte, essayez de sélectionner un mot dans un lecteur PDF. Une page photographiée doit d’abord recevoir une couche de texte par OCR. Pour un document mixte, le JSON permet de repérer les champs text vides et les numéros de page correspondants.





**Références de la méthode** [PDF Association · ISO 32000-2](<https://pdfa.org/resource/iso-32000-2/>) · [Adobe · PDF / OCR](<https://helpx.adobe.com/acrobat/desktop/create-documents/scan-documents-to-pdfs/recognize-text.html>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fpdf-to-text%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/pdf-to-text/)
