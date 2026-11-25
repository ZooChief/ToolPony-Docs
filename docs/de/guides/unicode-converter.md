# Anleitung: Unicode-Konverter



Codepunkte, UTF-8-Bytes und JavaScript-Escapes umwandeln, Zeichen untersuchen und Normalisierungsformen vergleichen.





## Beispiel



### Eingabe



```
🐴
```



### Erwartetes Ergebnis



```
U+1F434 oder F0 9F 90 B4
```





<a id="case-study"></a>



## Zwei Schreibweisen von é vergleichen



1. Ein e mit U+0301, ein Leerzeichen und 🐴 ergeben 3 Graphemcluster, 4 Codepunkte, 5 UTF-16-Einheiten und 8 UTF-8-Bytes. NFC verbindet den Akzent zu U+00E9 und verkürzt UTF-8 auf 7 Bytes. 🐴 bleibt ein Codepunkt mit zwei UTF-16-Einheiten.



[Beispiel ausführen](<https://toolpony.com/de/tools/unicode-converter/#example-combining-accent>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Unicode-Konverter](<https://toolpony.com/de/tools/unicode-converter/>)





## Berechnungsmethode



Der Code-Point-Modus behandelt ein Zusatzzeichen als einen Skalar. UTF-16 verwendet zwei Codeeinheiten für ein solches Zeichen. Ungültige Ersatzsequenzen und ungültige UTF-8-Bytes werden abgelehnt.







## Berechnungsmodus





### Codetext



- Eingabe
- Kodierung · Unicode-Codepunkte / UTF-8-Bytes in Hexadezimal / JavaScript-UTF-16-Escapes / JavaScript-Codepunkt-Escapes







### Dekodierungstext



- Eingabe
- Kodierung · Unicode-Codepunkte / UTF-8-Bytes in Hexadezimal / JavaScript-UTF-16-Escapes / JavaScript-Codepunkt-Escapes







### Zeichen untersuchen



- Eingabe
- Normalisierung · Original / NFC / NFD / NFKC / NFKD







**Quellen zur Methode** [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>) · [Unicode · UAX \#15](<https://www.unicode.org/reports/tr15/>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Funicode-converter%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/unicode-converter/)
