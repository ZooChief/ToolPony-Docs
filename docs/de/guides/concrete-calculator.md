# Betonmengenrechner



Geschätztes Betonvolumen, Gewicht und ganze Säcke für Platten, Fußböden, Rohre, Bordsteine und Treppen.





## Erste Schritte



1. Wählen Sie für jede Messung die passende Form und die eingestellten Einheiten. Ein Rohr verwendet Außendurchmesser und Innendurchmesser.
2. Bei Treppen sind die Anzahl der Anstiege und die Länge der oberen Plattform separat einzutragen und die Anzahl der identischen Teile für andere Formen zu verwenden.
3. Ersetzen Sie die Standarddichte durch den Wert auf dem Materialetikett, falls bekannt, und verwenden Sie die Whole-Bag-Tabelle für Bestellungen.







## Beispiel



### Eingabe



```
7 ft × 3 ft × 5 in Bramme, Menge 2
```



### Erwartetes Ergebnis



```
17,5 ft³, bei 133 lb/ft³ 2.327,50 lb
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/concrete-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Das Volumen entspricht der Querschnittsfläche mal Länge. Der Standard verwendet 133 lb/ft3 für Pfund und 2,130 kg/m3 für Kilogramm. Eine benutzerdefinierte Dichte konvertiert beide Ergebnisse aus einem Wert. Fügen Sie jede Zulage hinzu, bevor Sie eine Bestellung auf ganze Beutel runden.



$$
V_{\rm slab}=lwhq,\quad V_{\rm tube}=\pi hq(d_o^2-d_i^2)/4
$$



$$
V_{\rm stairs}=brn\left[p+u(n-1)/2\right],\qquad m=V\rho
$$



In der Treppenformel ist b die Breite, r die Steighöhe, u die Auftrittstiefe, n die Anzahl der Steigungen und p die Tiefe des oberen Podests. Der Körper umfasst n−1 Stufen und das obere Podest.



Zwei Platten von 7 ft × 3 ft × 5 in wiegen bei 133 lb/ft³ zusammen 2.327,50 lb. Das entspricht 38,79 Säcken zu je 60 lb. Die Bestelltabelle rundet vor dem Zuschlag auf 39 Säcke auf.







## Berechnungsmodus



**Platten- oder Rechteckfüße**

- Länge
- Längeneinheit
- Breite
- Breiteneinheit
- Dicke oder Höhe
- Dicken- oder Höheneinheit
- Menge
- Betondichte nach Maß · lb/ft³
- Abfallentschädigung · %





**Säule oder runder Fuß**

- Durchmesser
- Durchmessereinheit
- Tiefe oder Höhe
- Tiefen- oder Höheneinheit
- Menge
- Betondichte nach Maß · lb/ft³
- Abfallentschädigung · %





**Kreisförmige Platte oder Rohr**

- Außendurchmesser
- Außendurchmessereinheit
- Innendurchmesser
- Innendurchmessereinheit
- Tiefe oder Höhe
- Tiefen- oder Höheneinheit
- Menge
- Betondichte nach Maß · lb/ft³
- Abfallentschädigung · %





**Bordstein und Rinne**

- Bordsteintiefe
- Bordsteintiefeneinheit
- Rinnenbreite
- Rinnenbreiteneinheit
- Bordsteinhöhe über der Rinne
- Bordsteinhöhe über der Rinneneinheit
- Flaggendicke
- Flaggendickeneinheit
- Länge
- Längeneinheit
- Menge
- Betondichte nach Maß · lb/ft³
- Abfallentschädigung · %





**Feste Treppen und Plattform**

- Lauf pro Schritt
- Lauf pro Schritteinheit
- Anstieg pro Stufe
- Anstieg pro Schritteinheit
- Breite der Treppe
- Treppenbreiteneinheit
- Tiefe des oberen Bahnsteigs
- Obere Bahnsteigtiefeneinheit
- Anzahl der Schritte
- Betondichte nach Maß · lb/ft³
- Abfallentschädigung · %

[Dokumentation](https://docs.toolpony.com/de/guides/concrete-calculator/)
