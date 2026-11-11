# Rundungsrechner



Runde exakte Dezimalstellen nach Dezimalstellen oder einen Binärbruch mit neun Rundungsmodi.





## Erste Schritte



1. Verwenden Sie das Beispiel oder geben Sie eigene Werte ein.
2. Berechnen Sie das Ergebnis und kopieren oder laden Sie die Details herunter.







## Beispiel



### Eingabe



```
-2,5, Einsen, halb bis gerade
```



### Erwartetes Ergebnis



```
−2
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/rounding-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Vergleichen Sie den genauen Dezimalrest mit einem halben Schritt. Wählen Sie für Bindungen eine Richtungs- oder Paritätsregel.



$$
x=qs+r,\qquad 0\le r<s,\qquad r=\tfrac{s}{2}\text{ at a tie}
$$



Ein Platz von 2 Runden zu Hundertstel, 0 Runden zu Einheiten und -2 Runden zu Hunderten. Ein gebrochener Schritt rundet zu einem Vielfachen wie 1/4 oder 1/16.



Halb-zu-gerade wählt das gerade Vielfache nur an einer exakten Bindung. Zum Beispiel geht -2.5 zu -2 und -3.5 geht zu -4. Die Decke bewegt sich immer in Richtung positive Unendlichkeit.

[Dokumentation](https://docs.toolpony.com/de/guides/rounding-calculator/)
