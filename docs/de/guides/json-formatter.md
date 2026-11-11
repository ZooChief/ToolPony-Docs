# JSON-Formatierer



Fügen Sie JSON ein, wählen Sie eine Einrückung und formatieren oder verkleinern Sie sie. Kopieren Sie das Ergebnis oder laden Sie eine JSON-Datei herunter. Cmd/Ctrl + Enter führt den Formatierer aus.





## Erste Schritte



1. Fügen Sie ein JSON-Dokument ein.
2. Wählen Sie zwei oder vier Leerzeichen, dann formatieren; Verwenden Sie Minify für ein kompaktes Ergebnis.
3. Kopieren Sie das Ergebnis oder laden Sie die JSON-Datei herunter.







## Beispiel



### Eingabe



```
{"name":"ToolPony","ready":true}
```



### Erwartetes Ergebnis



```
{
  "name": "ToolPony",
  "ready": true
}
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/json-formatter/>)







## Hinweise



Anmerkungen und Nachkommas sind nicht JSON. Zahlen, die außerhalb der sicheren Präzision liegen, werden abgelehnt, um zu vermeiden, dass ihre Werte stillschweigend geändert werden.







## Grenzen



Bis zu 1 MB. Ungültiges JSON und Zahlen außerhalb der sicheren Genauigkeit werden abgewiesen. Das Formatieren prüft kein Anwendungsschema.

[Dokumentation](https://docs.toolpony.com/de/guides/json-formatter/)
