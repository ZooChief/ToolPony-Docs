# Anleitung: URL kodieren und dekodieren



URLs und Formularwerte umwandeln oder geordnete Abfrageparameter mit gleichen Namen und leeren Werten bearbeiten.





## Beispiel



### Eingabe



```
Kodierungskomponente: a+b & c
```



### Erwartetes Ergebnis



```
a%2Bb%20%26%20c
```





<a id="case-study"></a>



## Pluszeichen in einem Suchbegriff erhalten



1. C++ &amp; tea als Formularwert ergibt C%2B%2B+%26+tea. Ein echtes Plus wird zu %2B, Leerraum zu + und &amp; zu %26. Die Rückwandlung liefert das Original. Im URI-Komponentenmodus wird Leerraum zu %20.
2. Im Beispiel mit zwei tag-Einträgen den zweiten Wert auf UI &amp; UX setzen. Der erste tag, der leere Wert und \#filters bleiben erhalten; der neue Wert lautet UI+%26+UX.



[Beispiel ausführen](<https://toolpony.com/de/tools/url-encoder-decoder/#example-query-plus>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · URL kodieren und dekodieren](<https://toolpony.com/de/tools/url-encoder-decoder/>)





## Berechnungsmethode



Komponenten kodieren reservierte Trennzeichen, vollständige URLs behalten sie bei. Im Formular steht + für Leerzeichen. Abfrageparameter kodieren Namen und Wert einzeln und erhalten Pfad und Fragment.





**Quellen zur Methode** [IETF · RFC 3986](<https://www.rfc-editor.org/rfc/rfc3986>) · [WHATWG · Form encoding](<https://url.spec.whatwg.org/#application/x-www-form-urlencoded>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Furl-encoder-decoder%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/url-encoder-decoder/)
