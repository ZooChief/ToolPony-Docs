# Anleitung: Farbkonverter



CSS-Farben in HEX, RGB, HSL und OKLCH umrechnen, einschließlich Deckkraft und sRGB-Ersatzfarbe.





## Beispiel



### Eingabe



```
rgb(102, 51, 153)
```



### Erwartetes Ergebnis



```
#663399, hsl(270 50% 40%)
```





<a id="case-study"></a>



## Eine sRGB-Ersatzfarbe für ein Asset ermitteln



1. color(display-p3 0 1 0 / 70%) einfügen. Das Grün liegt außerhalb von sRGB. Die Farbfelder zeigen Original und Ersatzfarbe. Die Abbildung ergibt \#00FB29B3.
2. Die RGB-Zeile erhält die Deckkraft von 0,7. Im achtstelligen HEX-Wert steht B3 für 179/255.



[Beispiel ausführen](<https://toolpony.com/de/tools/color-converter/#example-wide-gamut>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Farbkonverter](<https://toolpony.com/de/tools/color-converter/>)





## Berechnungsmethode



HEX rundet sRGB-Kanäle auf Bytes. Farben außerhalb von sRGB werden entlang der OKLCH-Chroma abgebildet. Die Quellvorschau behält den Eingabefarbraum.





**Quellen zur Methode** [W3C · CSS Color 4](<https://www.w3.org/TR/css-color-4/>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fcolor-converter%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/color-converter/)
