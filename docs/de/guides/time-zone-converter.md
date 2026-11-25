# Anleitung: Zeitzonenumrechner



Rechnen Sie Datum und Uhrzeit zwischen IANA-Zonen oder festen UTC-Abständen um.





## Beispiel



### Eingabe



```
2026-01-15 09:00, Asia/Shanghai → America/New_York
```



### Erwartetes Ergebnis



```
2026-01-14 20:00:00
```





<a id="case-study"></a>



## Ein Termin in der doppelten Stunde



1. Am 1. November 2026 ist es in New York zweimal 01:30 Uhr. In Shanghai ist es beim ersten Mal 13:30 Uhr, beim zweiten 14:30 Uhr. Wählen Sie die Uhrzeit der Einladung und kopieren Sie den UTC-Zeitpunkt. Beim Tauschen der Städte bleibt der Termin erhalten.



[Beispiel ausführen](<https://toolpony.com/de/tools/time-zone-converter/#example-repeated-meeting>)





## Ein Anruf im November in Havanna



Kuba blieb im November 2026 bei UTC−04:00. Ein Anruf am 23. November um 09:00 Uhr in Havanna findet um 13:00 UTC statt. Für einen Termin in Ortszeit gelten mit America/Havana die Regeln des gewählten Tages.



[Beispiel ausführen](<https://toolpony.com/de/tools/time-zone-converter/#example-havana-clock>)







## Wenn die Uhr 30 Minuten überspringt



Am 4. Oktober 2026 springt die Uhr auf Lord Howe Island von 01:59:59 auf 02:30:00. Geben Sie 02:15 ein. Verschieben Sie den Termin um eine halbe Stunde auf 01:45 oder 02:45. Letzteres entspricht dem 3. Oktober um 15:45 UTC.



[Beispiel ausführen](<https://toolpony.com/de/tools/time-zone-converter/#example-half-hour-change>)







## Ausprobieren

[Vollständiges Werkzeug öffnen · Zeitzonenumrechner](<https://toolpony.com/de/tools/time-zone-converter/>)





## Berechnungsmethode



Für die Ortszeit gelten die IANA-Regeln des gewählten Datums. Eine doppelte Ortszeit entspricht zwei UTC-Zeitpunkten. Beim Vorstellen entsteht eine Lücke. Ein fester UTC-Abstand bleibt konstant.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## Berechnungsmodus





### IANA



- Datum
- Ortszeit
- IANA-Quellzeitzone
- IANA-Zielzeitzone
- Doppelte Stunde · Früheres Vorkommen / Späteres Vorkommen







### Feste UTC-Abstände



- Datum
- Ortszeit
- Quellabstand
- Zielabstand







**Quellen zur Methode** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Ftime-zone-converter%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/time-zone-converter/)
