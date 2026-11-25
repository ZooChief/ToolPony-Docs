# Anleitung: CSV-Vergleich



Fügen Sie alte und neue Tabelle ein. Behalten Sie die Kopfzeile und wählen Sie Trennzeichen und Schlüsselspalten. Vergleichen und filtern Sie die Änderungen. CSV eignet sich für Tabellenprogramme, JSON bewahrt Originaltext und den vollständigen Bericht.





## Erste Schritte



1. Fügen Sie alte und neue Tabelle ein. Behalten Sie die Kopfzeile und wählen Sie Trennzeichen und Schlüsselspalten.
2. Vergleichen und filtern Sie die Änderungen. CSV eignet sich für Tabellenprogramme, JSON bewahrt Originaltext und den vollständigen Bericht.







## Beispiel



### Eingabe



```
ID,Name,Qty
001,Oak,2
002,Pine,1
004,Ash,3

Qty,ID,Name
4,001,Oak
1,003,Fir
3,004,Ash
```



### Erwartetes Ergebnis



```
Hinzugefügt 1 · Entfernt 1 · Geändert 1
```





<a id="case-study"></a>



## Zwei Inventarlisten mit geänderter Spaltenreihenfolge abgleichen



1. Laden Sie das Inventarbeispiel und wählen Sie ID als Schlüssel. Die alte Datei verwendet ID, Name, Qty. In der neuen steht Qty zuerst. Vergleichen Sie beide Exporte.
2. Die Menge für ID 001 (Oak) steigt von 2 auf 4. ID 002 entfällt, 003 kommt hinzu und 004 bleibt gleich. Trotz neuer Spaltenreihenfolge gibt es je einen geänderten, entfernten und neuen Datensatz.
3. Ändern Sie nur 001 in der neuen Datei zu 1. Es ergeben sich zwei Zugänge, zwei Abgänge und keine Änderung. Mit führenden Nullen in beiden Exporten stimmen die Artikel wieder überein.





## Ausprobieren

[Vollständiges Werkzeug öffnen · CSV-Vergleich](<https://toolpony.com/de/tools/csv-compare/#example-inventory>)





## Grenzen



Je Tabelle bis 1 MiB UTF-8, 5.000 Datenzeilen und 80 Spalten. Text wird exakt verglichen, auch führende Nullen. Doppelte und leere Schlüssel erscheinen getrennt. Datensatznummern beginnen bei der Kopfzeile.



Nutzen Sie bei Inventarlisten eine stabile Artikelnummer als Schlüssel. Steht im alten Export 0012 und im neuen 12, erscheint je ein entfernter und ein neuer Datensatz. Behalten Sie in beiden Exporten die führenden Nullen bei, um Mengenänderungen demselben Artikel zuzuordnen.





**Quellen zur Methode** [IETF · RFC 4180 (CSV)](<https://www.rfc-editor.org/rfc/rfc4180>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fcsv-compare%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/csv-compare/)
