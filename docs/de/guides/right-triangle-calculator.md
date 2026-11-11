# Rechner für rechtwinklige Dreiecke



Berechne Katheten, Hypotenuse und Winkel aus zwei Werten, etwa Höhe, Fläche oder Umfang.





## Erste Schritte



1. Gib zwei Werte ein, darunter eine Länge, Fläche oder den Umfang.
2. In den beiden Lösungen sind die Bezeichnungen der Katheten und spitzen Winkel vertauscht.







## Beispiel



### Eingabe



```
c = 5, h = 2,4
```



### Erwartetes Ergebnis



```
Katheten 3 und 4, Fläche 6, Umfang 12. Beide Katheten können a sein.
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/right-triangle-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



c ist die Hypotenuse, h die Höhe auf c. Verwende für Längen dieselbe Einheit und für die Fläche deren Quadrat.



$$
c^2=a^2+b^2,\quad h=ab/c,\quad S=ab/2,\quad P=a+b+c
$$



$$
a,b=\frac{\sqrt{c^2+2ch}\;\pm\;\sqrt{c^2-2ch}}{2}
$$

[Dokumentation](https://docs.toolpony.com/de/guides/right-triangle-calculator/)
