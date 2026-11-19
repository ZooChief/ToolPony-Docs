# CSV-Vergleich



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







## Ausprobieren

[Vollständiges Werkzeug öffnen · CSV-Vergleich](<https://toolpony.com/de/tools/csv-compare/>)





## Grenzen



Je Tabelle bis 1 MiB UTF-8, 5.000 Datenzeilen und 80 Spalten. Text wird exakt verglichen, auch führende Nullen. Doppelte und leere Schlüssel erscheinen getrennt. Datensatznummern beginnen bei der Kopfzeile.



Nutzen Sie bei Inventarlisten eine stabile Artikelnummer als Schlüssel. Steht im alten Export 0012 und im neuen 12, erscheint je ein entfernter und ein neuer Datensatz. Behalten Sie in beiden Exporten die führenden Nullen bei, um Mengenänderungen demselben Artikel zuzuordnen.

[Dokumentation](https://docs.toolpony.com/de/guides/csv-compare/)
