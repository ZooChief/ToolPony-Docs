# Anleitung: IP-Subnetzrechner



Überprüfen Sie IPv4- und IPv6-Netzwerke, Masken, Bereiche und Adresszahlen oder testen Sie, ob eine IP zu einem CIDR-Block gehört.





## Beispiel



### Eingabe



```
192.0.2.129 /27
```



### Erwartetes Ergebnis



```
Netzwerk 192.0.2.128/27, 30 nutzbare Hosts
```





<a id="case-study"></a>



## Subnetzgrenze prüfen



1. 192.0.2.128/27 endet einschließlich .159, der IPv4-Broadcast-Adresse. .160 liegt außerhalb, IPv6 gehört zu einer anderen Adressfamilie.



[Beispiel ausführen](<https://toolpony.com/de/tools/ip-subnet-calculator/#example-subnet-boundary>)





## Zwei IPv6-Endpunkte



2001:db8::8/127 umfasst ::8 und ::9. Sie haben die Positionen 1 und 2. IPv6 verwendet keine Broadcast-Adresse.



[Beispiel ausführen](<https://toolpony.com/de/tools/ip-subnet-calculator/#example-ipv6-endpoints>)







## Ausprobieren

[Vollständiges Werkzeug öffnen · IP-Subnetzrechner](<https://toolpony.com/de/tools/ip-subnet-calculator/>)





## Berechnungsmethode



Und die Adresse mit einer Präfixmaske, um die erste Adresse zu finden. Der Host-Teil hat 2^(Adressbits - Präfix) Möglichkeiten. IPv4 /31 verwendet standardmäßig eine Legacy-Host-Zählung mit einer Punkt-zu-Punkt-Option RFC 3021. Ein Inline-CIDR-Präfix hat Vorrang.



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



IPv4 akzeptiert eine Präfixlänge oder eine zusammenhängende gepunktete Maske, z. B. 192.0.2.129 mit 255.255.255.224 ergibt das gleiche Netzwerk wie 192.0.2.129/27.



Die Präfix-Größenkategorie folgt der A/B/C-Konvention des Vergleichstools. Die historische Adressklasse wird separat angezeigt. Verwenden Sie den Adressbereich für die CIDR-Mitgliedschaft. Die optionale Punkt-zu-Punkt-Einstellung ändert sich nur /31 Host-Zählung.







## Berechnungsmodus





### IPv4



- IPv4-Adresse oder CIDR
- Präfix- oder Subnetzmaske
- Verwenden Sie beide Adressen auf /31 Punkt-zu-Punkt-Links







### IPv6



- IPv6-Adresse oder CIDR
- Präfix







### Adress-Mitgliedschaft überprüfen



- CIDR-Netz
- Anschrift zur Überprüfung







**Quellen zur Methode** [IETF · RFC 4632 (CIDR)](<https://www.rfc-editor.org/rfc/rfc4632>) · [IETF · RFC 3021 (/31 links)](<https://www.rfc-editor.org/rfc/rfc3021>) · [IETF · RFC 5952 (IPv6 text)](<https://www.rfc-editor.org/rfc/rfc5952>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fip-subnet-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/ip-subnet-calculator/)
