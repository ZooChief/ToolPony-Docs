# Stundenzettel-Rechner



Erfassen Sie eine Woche mit Schichten, Pausen, Rundung, Lohnregeln und CSV.





## Erste Schritte



1. Uhrzeiten wie 08:30, 8.30 oder 8:30 AM sind möglich. Pausen werden als Stunden und Minuten angegeben, etwa 00:30.
2. Wählen Sie Rundung und optionale Lohnregeln. Laden Sie CSV herunter oder drucken Sie den Bericht. Ein Entwurf kann lokal gespeichert werden.







## Beispiel



### Eingabe



```
08:30–17:00 mit 00:30 Pause
```



### Erwartetes Ergebnis



```
08:00:00
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/time-card-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Ziehen Sie die Pause ab und runden Sie die Nettozeit. Eine frühere Endzeit liegt am Folgetag. Tages- und Wochengrenzen sowie Lohnsätze sind Eingaben.



$$
t_i=(e_i-s_i)\bmod 1440-b_i,\qquad t'_i=q\,\operatorname{round}(t_i/q)\quad(q>0)
$$



$$
P=(t_{\rm base}+m\,t_{\rm overtime})r/60
$$

[Dokumentation](https://docs.toolpony.com/de/guides/time-card-calculator/)
