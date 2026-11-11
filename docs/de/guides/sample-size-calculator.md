# Stichprobenumfang-Rechner



Finden Sie eine minimale Umfragestichprobe oder schätzen Sie die Fehlerspanne mit Finite-Populationskorrektur.





## Erste Schritte



1. Verwenden Sie das Beispiel oder geben Sie eigene Werte ein.
2. Berechnen Sie das Ergebnis und kopieren oder laden Sie die Details herunter.







## Beispiel



### Eingabe



```
95% Vertrauen, 4% Marge, 35% Anteil, N = 1.000
```



### Erwartetes Ergebnis



```
354 Proben
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/sample-size-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Die Anfangsgröße ist z2p(1−p)/e2. Für eine endliche Population dividieren Sie diese Größe durch 1 + (Anfangsgröße-1)/N und runden Sie auf. Die Fehlerberechnung verwendet das gleiche Verhältnis und das Modell der endlichen Population.



$$
n_0=\frac{z^2p(1-p)}{e^2},\qquad n=\left\lceil\frac{n_0}{1+(n_0-1)/N}\right\rceil
$$







## Berechnungsmodus



**Stichprobenumfang**

- Konfidenzniveau · %
- Fehlerspanne · %
- Bevölkerungsanteil · %
- Bevölkerungsgröße (0 für unbegrenzt)





**Fehlermarge finden**

- Konfidenzniveau · %
- Stichprobenumfang
- Bevölkerungsanteil · %
- Bevölkerungsgröße (0 für unbegrenzt)

[Dokumentation](https://docs.toolpony.com/de/guides/sample-size-calculator/)
