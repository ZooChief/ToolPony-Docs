# IP-Subnetzrechner



Überprüfen Sie IPv4- und IPv6-Netzwerke, Masken, Bereiche und Adresszahlen oder testen Sie, ob eine IP zu einem CIDR-Block gehört.





## Erste Schritte



1. Verwenden Sie das Beispiel oder geben Sie eigene Werte ein.
2. Berechnen Sie das Ergebnis und kopieren oder laden Sie die Details herunter.







## Beispiel



### Eingabe



```
192.0.2.129 /27
```



### Erwartetes Ergebnis



```
Netzwerk 192.0.2.128/27, 30 nutzbare Hosts
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/ip-subnet-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Und die Adresse mit einer Präfixmaske, um die erste Adresse zu finden. Der Host-Teil hat 2^(Adressbits - Präfix) Möglichkeiten. IPv4 /31 verwendet standardmäßig eine Legacy-Host-Zählung mit einer Punkt-zu-Punkt-Option RFC 3021. Ein Inline-CIDR-Präfix hat Vorrang.



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



IPv4 akzeptiert eine Präfixlänge oder eine zusammenhängende gepunktete Maske, z. B. 192.0.2.129 mit 255.255.255.224 ergibt das gleiche Netzwerk wie 192.0.2.129/27.



Die Präfix-Größenkategorie folgt der A/B/C-Konvention des Vergleichstools. Die historische Adressklasse wird separat angezeigt. Verwenden Sie den Adressbereich für die CIDR-Mitgliedschaft. Die optionale Punkt-zu-Punkt-Einstellung ändert sich nur /31 Host-Zählung.







## Berechnungsmodus



**IPv4**

- IPv4-Adresse oder CIDR
- Präfix- oder Subnetzmaske
- Verwenden Sie beide Adressen auf /31 Punkt-zu-Punkt-Links





**IPv6**

- IPv6-Adresse oder CIDR
- Präfix





**Adress-Mitgliedschaft überprüfen**

- CIDR-Netz
- Anschrift zur Überprüfung

[Dokumentation](https://docs.toolpony.com/de/guides/ip-subnet-calculator/)
