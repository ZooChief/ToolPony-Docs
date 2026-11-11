# Abstandsrechner



Finden Sie den Abstand zwischen zwei 2D- oder 3D-Punkten oder schätzen Sie den Oberflächenabstand zwischen den geografischen Koordinaten ab.





## Erste Schritte



1. Verwenden Sie das Beispiel oder geben Sie eigene Werte ein.
2. Berechnen Sie das Ergebnis und kopieren oder laden Sie die Details herunter.







## Beispiel



### Eingabe



```
2D: (0, 0) bis (3, 4)
```



### Erwartetes Ergebnis



```
Abstand 5
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/distance-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Die kartesische Distanz verwendet die euklidische Norm. Geographische Modi verwenden das WGS 84-Ellipsoid und die Lambert-Approximation. Nahezu antipodische Punkte verwenden eine sphärische Approximation. Dies ist eine Oberflächenschätzung.



$$
d=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}
$$



Verwenden Sie den 2D- oder 3D-Modus für Koordinaten, die bereits eine lineare Skala teilen.



Bei geographischen Koordinaten sind Nord und Ost positiv, wenn eine Erhebung getrennte Winkelfelder ergibt, wird der Verlauf einer ellipsoiden Oberfläche geschätzt.







## Berechnungsmodus



**2D**

- X1
- Y1
- X2
- Y2





**3D**

- X1
- Y1
- Z1
- X2
- Y2
- Z2





**Breite und Länge**

- erster Breitengrad · °
- Erste Länge · °
- zweiter Breitengrad · °
- Zweite Länge · °





**Grad, Minuten und Sekunden**

- Erste Breitengrade
- Erste Breitenminuten
- erste Breitensekunden
- Hemisphäre erster Breitengrad · N / S
- Erster Längengrad
- Erste Längengradminuten
- Erste Längensekunden
- Erste Längenhalbkugel · E / W
- Zweite Breitengrade
- Zweite Breitenminuten
- zweite Breitensekunden
- Zweite Breitenhalbkugel · N / S
- Zweiter Längengrad
- Zweite Längenminuten
- zweite Längensekunden
- Zweite Längenhalbkugel · E / W

[Dokumentation](https://docs.toolpony.com/de/guides/distance-calculator/)
