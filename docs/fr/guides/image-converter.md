# Convertisseur d’images



Ajoutez des images de différents formats. Le format est détecté à partir du contenu du fichier. Choisissez le format, la qualité et le fond pour chaque image. Téléchargez les fichiers séparément ou en ZIP.





## Prise en main



1. Ajoutez des images de différents formats. Le format est détecté à partir du contenu du fichier.
2. Choisissez le format, la qualité et le fond pour chaque image. Téléchargez les fichiers séparément ou en ZIP.







## Exemple



### Entrée



```
PNG · 64 × 32 px (coins transparents) → JPEG · fond blanc
```

[Exemple · PNG](<https://toolpony.com/samples/toolpony-64x32.png>)

### Résultat attendu



```
JPEG · 64 × 32 px (coins blancs)
```





<a id="case-study"></a>



## Vérifier le fond d’un PNG transparent avant un envoi en JPEG



1. Dans le convertisseur vide, choisissez « Essayer les fichiers exemples ». Un PNG transparent et un JPEG opaque de 64 × 32 px sont chargés. Les sorties sont réglées respectivement sur JPEG et PNG.
2. Après conversion, cliquez sur chaque miniature pour voir la sortie. Le JPEG a des coins blancs. Le PNG issu du JPEG conserve aussi des coins opaques car les pixels blancs figuraient dans la source. Pour garder la transparence du premier fichier, exportez-le en PNG avec un fond transparent.
3. Pour une bannière, vérifiez les dimensions de sortie sur la ligne du fichier. Une image de 10 000 × 100 px passe proportionnellement à 8 192 × 82 px. Le réglage de qualité agit uniquement sur l’encodage.
4. Pour vérifier le pixel, ouvrez le JPEG d’exemple dans la pipette à la position (0, 0). Dans Chromium, la valeur décodée était RGBA (255, 255, 243, 255). Le PNG issu du même JPEG conserve ces valeurs, dont l’alpha de 255 pour une opacité totale.



[Pipette de couleurs d’image](<https://toolpony.com/fr/tools/image-color-picker/>)





## Essayer

[Ouvrir l’outil complet · Convertisseur d’images](<https://toolpony.com/fr/tools/image-converter/>)





## Limites



Limite de 20 Mo, 24 mégapixels et 8 192 pixels par côté en sortie. Le décodage AVIF dépend du navigateur. Les animations deviennent des images fixes. Les métadonnées d’origine sont supprimées. Jusqu’à 12 images et 64 Mio au total par lot.



Choisissez le PNG pour conserver la transparence et le JPEG pour les photos et la compatibilité. Le JPEG remplit les zones transparentes avec l’arrière-plan choisi. Le WebP prend en charge la transparence et une qualité réglable. L’AVIF apparaît si le navigateur sait l’encoder.



Un logo WebP transparent peut devenir un PNG transparent. Pour un formulaire exigeant du JPEG, choisissez un fond blanc. Un JPEG converti en PNG conserve les détails visibles de l’image.





**Références de la méthode** [W3C · PNG](<https://www.w3.org/TR/png-3/>) · [WHATWG · HTML Canvas](<https://html.spec.whatwg.org/multipage/canvas.html#dom-canvas-toblob-dev>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fimage-converter%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/image-converter/)
