# YAML in JSON



Fügen Sie ein YAML-Dokument ein und konvertieren Sie es in JSON. Mappings müssen String-Tasten verwenden; die Ausgabe ist formatiert und kann kopiert oder heruntergeladen werden.





## Erste Schritte



1. Fügen Sie ein YAML-Dokument mit String-Mapping-Schlüssel ein.
2. Konvertieren Sie zu JSON.
3. Überprüfen, kopieren oder herunterladen des Ergebnisses.







## Beispiel



### Eingabe



```
name: ToolPony
ready: true
```



### Erwartetes Ergebnis



```
{
  "name": "ToolPony",
  "ready": true
}
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/yaml-to-json/>)







## Hinweise



Mehrere Dokumente, benutzerdefinierte Tags, zyklische Aliase und Werte, die JSON nicht repräsentieren kann, werden abgelehnt.







## Grenzen



Bis zu 1 MB. Benutzerdefinierte Tags, mehrere Dokumente, Schlüssel außer Zeichenketten, zu viele Aliasse, zyklische Strukturen und Werte ohne verlustfreie JSON-Darstellung werden abgewiesen.

[Dokumentation](https://docs.toolpony.com/de/guides/yaml-to-json/)
