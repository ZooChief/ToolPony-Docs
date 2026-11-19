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

[Vollständiges Werkzeug öffnen · YAML in JSON](<https://toolpony.com/de/tools/yaml-to-json/>)





## Hinweise



Mehrere Dokumente, benutzerdefinierte Tags, zyklische Aliase und Werte, die JSON nicht repräsentieren kann, werden abgelehnt.







## Grenzen



Bis zu 1 MB. Benutzerdefinierte Tags, mehrere Dokumente, Schlüssel außer Zeichenketten, zu viele Aliasse, zyklische Strukturen und Werte ohne verlustfreie JSON-Darstellung werden abgewiesen.





**Quellen zur Methode** [YAML 1.2.2](<https://yaml.org/spec/1.2.2/>) · [IETF · RFC 8259 (JSON)](<https://www.rfc-editor.org/rfc/rfc8259>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fyaml-to-json%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/yaml-to-json/)
