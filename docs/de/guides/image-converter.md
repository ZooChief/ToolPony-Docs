# Anleitung: Bildformat konvertieren



Füge Bilder in verschiedenen Formaten hinzu. Das Eingabeformat wird am Dateiinhalt erkannt. Wähle Format, Qualität und Hintergrund je Bild und lade die Ergebnisse einzeln oder als ZIP herunter.





## Erste Schritte



1. Füge Bilder in verschiedenen Formaten hinzu. Das Eingabeformat wird am Dateiinhalt erkannt.
2. Wähle Format, Qualität und Hintergrund je Bild und lade die Ergebnisse einzeln oder als ZIP herunter.







## Beispiel



### Eingabe



```
PNG · 64 × 32 px (transparente Ecken) → JPEG · weißer Hintergrund
```

[Beispiel · PNG](<https://toolpony.com/samples/toolpony-64x32.png>)

### Erwartetes Ergebnis



```
JPEG · 64 × 32 px (weiße Ecken)
```





<a id="case-study"></a>



## Den Hintergrund eines transparenten PNG beim JPEG-Export prüfen



1. Wählen Sie im leeren Konverter „Beispieldateien ausprobieren“. Er lädt ein transparentes PNG und ein deckendes JPEG mit je 64 × 32 px. Die Ausgabeformate sind JPEG für das PNG und PNG für das JPEG.
2. Vergleichen Sie Original und Ausgabe nebeneinander. Per Klick auf ein Bild sehen Sie die tatsächliche Pixelgröße. Das erste JPEG hat weiße Ecken. Auch das PNG aus dem JPEG hat deckende Ecken, weil die weißen Pixel bereits in der Quelle lagen. Wählen Sie für das erste Bild PNG und einen transparenten Hintergrund, um seine Transparenz zu erhalten.
3. Bei langen Bannern stehen die Ausgabemaße in der Dateizeile. Aus 10.000 × 100 px werden proportional 8.192 × 82 px. Die Qualitätseinstellung beeinflusst nur die Kodierung.
4. Öffnen Sie das Beispiel-JPEG zur Kontrolle in der Farbpipette und prüfen Sie (0, 0). Chromium dekodierte dort RGBA (255, 255, 243, 255). Das daraus exportierte PNG behielt diese Werte. Der Alphawert 255 steht für volle Deckkraft.



[Farbpipette für Bilder](<https://toolpony.com/de/tools/image-color-picker/>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Bildformat konvertieren](<https://toolpony.com/de/tools/image-converter/#example-mixed-images>)





## Grenzen



Bis zu 20 MB und 24 Megapixel, je Ausgabeseite 8.192 Pixel. AVIF hängt vom Browser ab. Animationen werden Standbilder. Ursprüngliche Metadaten werden entfernt. Bis zu 12 Bilder und insgesamt 64 MiB pro Stapel.



Wählen Sie PNG für Transparenz und JPEG für Fotos und Kompatibilität. JPEG füllt transparente Bereiche mit dem gewählten Hintergrund. WebP unterstützt Transparenz und einstellbare Qualität. AVIF erscheint als Ausgabeoption, wenn der Browser es kodieren kann.



Ein WebP-Logo mit transparenten Bereichen kann etwa als transparentes PNG gespeichert werden. Für Formulare, die JPEG verlangen, eignet sich ein weißer Hintergrund. Ein als PNG gespeichertes JPEG behält seine sichtbaren Details.





**Quellen zur Methode** [W3C · PNG](<https://www.w3.org/TR/png-3/>) · [WHATWG · HTML Canvas](<https://html.spec.whatwg.org/multipage/canvas.html#dom-canvas-toblob-dev>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fimage-converter%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/image-converter/)
