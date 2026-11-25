# Anleitung: Base64 kodieren und dekodieren



UTF-8-Text oder Hex-Bytes mit Base64 oder Base64url kodieren und die dekodierten Bytes als Datei speichern.





## Beispiel



### Eingabe



```
hello kodieren
```



### Erwartetes Ergebnis



```
aGVsbG8=
```





<a id="case-study"></a>



## Bytes aus Base64url wiederherstellen



1. Dekodieren, URL-sicher und Hex-Bytes wählen. \_wCA7w ergibt FF 00 80 EF, einschließlich Nullbyte und ungültiger UTF-8-Werte. Der Byte-Download enthält genau diese vier Bytes.



[Beispiel ausführen](<https://toolpony.com/de/tools/base64-encoder-decoder/#example-binary-bytes>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Base64 kodieren und dekodieren](<https://toolpony.com/de/tools/base64-encoder-decoder/>)





## Berechnungsmethode



Standard nutzt + und /, Base64url nutzt - und \_ ohne Ausgabepadding. UTF-8 wird geprüft, ein führendes U+FEFF bleibt erhalten. Maximal 500.000 UTF-16-Einheiten oder 500.000 Bytes.





**Quellen zur Methode** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>) · [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fbase64-encoder-decoder%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/base64-encoder-decoder/)
