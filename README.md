<div align="center">

# discord-know-or-guess

<p>
<img src=https://img.shields.io/badge/Beta_Version-1.0.1-yellow>
<p>
</div>

<br>

Welches Team hat alle Fragen gewusst oder doch nur richtig geraten?! Duelliere dich in Teams mit deinen Freunden über Discord in über 6000 Fragen aus 40 Kategorien. Einfach den Bot einladen und kurz einrichten, fertig!

 [Lade den Bot jetzt auf deinen Server ein und werde zum Quizmaster 😃](https://discord.com/api/oauth2/authorize?client_id=822529025666187355&permissions=8&scope=bot)

## Features

<img src="https://github.com/Frosch2010/discord-know-or-guess/blob/main/screenshots/Frage.jpg" align="right">

* Fast **7000 Fragen** aus **40 Kategorien**

* Verschiedene Spielmodi (Derzeit nur einer verfügbar, aber weitere sind geplant.)

* Getrennte Audiochannels für die Teambesprechung etc., in die Spieler automatisch verschoben werden. (Team- & Globalchannels)

* Einfache und schnelle Einrichtung über Discord

* Fragen, auf die garantiert nicht jeder eine Antwort hat

‌‌ [Lade den Bot jetzt auf deinen Server ein ❤️](https://discord.com/api/oauth2/authorize?client_id=822529025666187355&permissions=8&scope=bot)

## Spielmodis & Spielablauf

<img src="https://github.com/Frosch2010/discord-know-or-guess/blob/main/screenshots/Kategoriewahl.jpg" align="left">

Zu Beginn wird beim Start ein Spielmodus ausgewählt. Je nach Modus unterscheidet sich das Spiel etwas. (Derzeit gibt es nur einen Spielmodus, aber weitere sind geplant.)

**Spielmodis:**

‌‌💯 = Zuerst stimmen alle Spieler ab, aus welcher Kategorie die nächste Frage kommen soll. Anschließend wird beiden Teams die gleiche Frage gestellt. Wird diese richtig beantwortet, gibt es einen Punkt. Dies geht solange, bis ein Team die Punktzahl zum gewinnen erreicht hat. Sollte ein Gleichstand entstehen, wird wieder eine Kategeorie ausgewählt und im Anschluss gewinnt das Team, was zuerst die folgende Frage richtig beantwortet. Wird diese jedoch falsch beantwortet, gewinnt das andere Team.

‌‌ 

## Einrichtung

1. [Lade den Bot auf deinen Server ein.](https://discord.com/api/oauth2/authorize?client_id=822529025666187355&permissions=8&scope=bot)
2. Erstelle 4 Textchannels (Bsp.: Join, Admin, Team-1 & Team-2)
3. Erstelle 3 Voicechannels (Bsp.: Global, Team-1 & Team-2)
4. Lasse dir mit **!kg setup** alle Befehle anzeigen (**Wichtig! Hierfür musst du Administratorrechte auf dem Server haben.**)
5. Füge mit **!kg setup setchannel** **[channel]** **[channel-id]** die Channels zum Bot hinzu bzw. stelle sie entsprechend ein.
6. **Viel Spaß beim Spielen mit deinen Freunden :)**

## Befehle

Die folgenden Befehle sind nur in den jeweiligen Channels verfügbar.

**Join-Channel:**
```
!kg join                          = Trete einem neuen Spiel bei.
!kg start [Fragen-/Punkteanzahl]  = Starte ein neues Spiel. Über die Fragen-/Punkteanzahl kann die Standartanzahl an zu erreichenden Fragen/Punkten zum Gewinn für diese Runde geändert werden.
```

**Admin-Channel:**
```
!kg stop  = Stoppe das aktuell laufende Spiel.
```

Diese Befehle sind überall verfügbar:
```
!kg help [thema]  = Ruft die Hilfe oder das jeweilige Hilfe-Thema auf.

!kg setup         = Ruft eine Liste aller Setup-Befehle inklusive Erklärungen auf. (Administratorrechte sind nötig, um die jeweiligen Einstellungen ändern zu können.)
```

## Fehler, Fragen oder Wünsche?

Erstelle ein Pull-Request 😃
