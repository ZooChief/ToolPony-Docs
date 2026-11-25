# Anleitung: PDF in Text umwandeln



Extrahieren Sie auswählbaren Text lokal aus PDFs und speichern Sie ihn als TXT oder JSON.





## Erste Schritte



1. Öffnen Sie ein PDF mit auswählbarem Text.
2. Geben Sie die Reihenfolge der Seiten an und extrahieren Sie den Text. Speichern Sie TXT oder JSON mit den Originalseitenzahlen.







## Beispiel



### Eingabe



```
Gemischtes PDF, Ausgabe als JSON, Seitenfolge 3, 2, 1. Seite 2 enthält nur ein blaues Farbmuster.
```

[Beispiel · PDF](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)

### Erwartetes Ergebnis



```
[{"page":3,"text":"Total 42"},{"page":2,"text":""},{"page":1,"text":"Order 417"}]
```





<a id="case-study"></a>



## Seiten ohne Text in einem gemischten PDF finden



1. Das gemischte Beispiel enthält „Order 417“ auf Seite 1, nur ein blaues Farbmuster als Bild auf Seite 2 und „Total 42“ auf Seite 3. Die Beispielschaltfläche im vollständigen Werkzeug lädt das PDF, wählt 3, 2, 1 und stellt JSON ein.
2. Nach der Extraktion enthält der erste Eintrag „Total 42“ von Seite 3, der mittlere ein leeres text-Feld für Seite 2 und der letzte „Order 417“ von Seite 1. Seite 2 wird zusätzlich mit ihrer ursprünglichen Nummer aufgeführt.
3. Prüfen Sie die aufgeführten Seiten vor dem Import in ein anderes System. Ein Diagramm können Sie als Bild erhalten. Für einen Scan mit gedruckten Wörtern lässt sich per OCR eine Textebene erzeugen.



[PDF in JPG oder PNG umwandeln](<https://toolpony.com/de/tools/pdf-to-jpg/>)



[toolpony-mixed-pages.pdf](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · PDF in Text umwandeln](<https://toolpony.com/de/tools/pdf-to-text/#example-mixed-pdf>)





## Hinweise



Maximal 30 MB, 300 Seiten, zwei Millionen Zeichen und 200.000 Textabschnitte. Die Textreihenfolge folgt der PDF-Datei. Gescannte Seiten erfordern OCR. Verschlüsselte PDFs werden abgelehnt. Bei bis zu acht Seiten können Sie die Auswahl leeren und die Seitenzahlen in der gewünschten Reihenfolge antippen. Bei längeren Dokumenten lassen sich gerade oder ungerade Seiten auf einmal wählen.







## Grenzen



Maximal 30 MB, 300 Seiten, zwei Millionen Zeichen und 200.000 Textabschnitte. Die Textreihenfolge folgt der PDF-Datei. Gescannte Seiten erfordern OCR. Verschlüsselte PDFs werden abgelehnt.



Wenn ein lesbarer Scan keinen Text liefert, markieren Sie ein Wort im PDF-Reader. Fotografierte Seiten benötigen zunächst eine OCR-Textebene. Bei gemischten Dokumenten zeigen ein leeres text-Feld im JSON und die ursprüngliche Seitennummer, welche Seiten eine Texterkennung benötigen.





**Quellen zur Methode** [PDF Association · ISO 32000-2](<https://pdfa.org/resource/iso-32000-2/>) · [Adobe · PDF / OCR](<https://helpx.adobe.com/acrobat/desktop/create-documents/scan-documents-to-pdfs/recognize-text.html>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fpdf-to-text%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/pdf-to-text/)
