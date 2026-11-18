# Zeitzonenumrechner



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







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/time-zone-converter/>)







## Berechnungsmethode



IANA-Zonen nutzen Browserregeln. Eine doppelte Stunde hat zwei Zeitpunkte, eine übersprungene keinen. Feste UTC-Abstände bleiben im Jahr gleich.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## Berechnungsmodus



**IANA**

- Datum
- Ortszeit
- IANA-Quellzeitzone
- IANA-Zielzeitzone
- Doppelte Stunde · Früheres Vorkommen / Späteres Vorkommen





**Feste UTC-Abstände**

- Datum
- Ortszeit
- Quellabstand
- Zielabstand

[Dokumentation](https://docs.toolpony.com/de/guides/time-zone-converter/)
