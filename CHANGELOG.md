# FamCalcaer-Bot: Changelog
This is the changelog of the FamCalcaer-Bot.

How to read it:
First find the major version and read it's general information. Inside the major version search the minor version and read the version specific information.  \
Then each version has it's sub-versions with information of the Fixes.

All versions inside a category are ordered descending.

___

<!-- Current -->
- ## v1 (TBA)
  Erster Release
<!-- Older -->

- ## v0 (05.03.2021)
  Start des Projekts und erste Test-Versionen.

  - ### v0.13 (09.04.2021 01:20 Uhr)
    Commands `/version` und `/changelog` hinzugefügt.

  - ### v0.12 (01.04.2021 14:02 Uhr)
    Bot antwortet nur noch Familien-Mitgliedern und der Gruppe.

    - #### v0.12.1 (09.04.2021 00:29 Uhr)
      **Fix**: Anzeige der Windrichtung definiert nun, ob der Wind aus oder in diese Richtung geht.
      **Fix**: Bot speichert wieder den Essensplan in seiner Datenbank.

  - ### v0.11 (27.03.2021 07:49 Uhr)
    Wetter-API hinzugefügt.

    - #### v0.11.3 (01.04.2021 11:29 Uhr)
      **Fix**: Anzeige der Windrichtung in Worte geändert, um Anzeigefehler zu vermeiden.

    - #### v0.11.2 (29.03.2021 01:14 Uhr)
      **Bugfix**: Sonntagspost wurde wieder zu 18 Uhr verschoben.

    - #### v0.11.1 (28.03.2021 08:27 Uhr)
      Aktuelles Wetter kann mit `/heute` abgerufen werden.

  - ### v0.10 (18.03.2021 01:34 Uhr)
    Neues Übersichts-System:
    1. Commands zum Abrufen von Terminen für Tage und Wochen hinzugefügt.
    2. Automatische Übersichten wurden geändert:
       1. Zeiten wurden auf 8 und 20 Uhr gesetzt.
       2. Inhalt wurde um Termine erweitert.
       3. Nur eine Wochenübersicht wird angepinnt.

    - #### v0.10.14 (25.03.2021 11:32 Uhr)
      **Fix**: Typo in Start-Skript

    - #### v0.10.13 (25.03.2021 11:23 Uhr)
      Neues Start-Skript mit Hinweis-Output.

    - #### v0.10.12 (25.03.2021 10:58 Uhr)
      **Bugfix**: Wöchentliche Nachricht konnte nicht losgelöst werden, da die Group-ID nicht übergeben wurde.

    - #### v0.10.11 (25.03.2021 10:52 Uhr)
      *Update v0.10.10 released*

    - #### v0.10.10 (25.03.2021 10:34 Uhr)
      **Bugfix**: Tägliche Nachricht konnte nicht losgelöst werden, da die Group-ID nicht übergeben wurde.

    - #### v0.10.9 (22.03.2021 19:14 Uhr)
      **Bugfix**: Nachrichten-ID wird in Datenbank-Datei gespeichert, statt des Nachrichten-Objekts.

    - #### v0.10.8 (19.03.2021 09:13 Uhr)
      Tägliche Nachricht wird nun auch angepinnt.
      **Bugfix**: *Internes* Laden der falschen Config-Datei für die ID der angepinnten Nachrichten.

    - #### v0.10.7 (19.03.2021 07:37 Uhr)
      Link zur Changelog in der Readme hinzugefügt.

    - #### v0.10.6 (19.03.2021 07:22 Uhr)
      *Interne* Changelog vervollständigt

    - #### v0.10.5 (19.03.2021 06:11 Uhr)
      Alte Einträge werden jetzt jeden Monat am 01. um 6 Uhr mit einer Woche Abstand gelöscht.  \
      Die Essen werden in ein Archiv gespeichert.

      **Bugfix**: Typo beim `/bald`-Command wurde von "Diese Woche" auf "Nächste Woche" geändert.

    - #### v0.10.4 (18.03.2021 02:28 Uhr)
      Präfixe "E." (Eltern), "K." (Kinder) und "A." (Alle) werden nun verarbeitet.

    - #### v0.10.3 (18.03.2021 02:12 Uhr)
      Commands `/morgen` und `/bald` zur Vorschau des nächsten Tages und der nächsten Woche hinzugefügt.

    - #### v0.10.2 (18.03.2021 01:46 Uhr)
      *Update v0.10.1 released*

    - #### v0.10.1 (18.03.2021 01:39 Uhr)
      **Bugfix**: Update-Nachrichten werden noch gelöscht und neu gepostet, aber nicht mehr angepinnt.

  - ### v0.9 (16.03.2021 04:24 Uhr)
    Google Kalender wurde hinzugefügt

    - #### v0.9.9 (17.03.2021 21:24 Uhr)
      Der Bot schreibt nun, dass ein Termin für morgen ansteht, wenn er nach 18 Uhr gefragt wird.

    - #### v0.9.8 (16.03.2021 21:30 Uhr)
      Verbesserungen an Meta-Dateien.

    - #### v0.9.7 (16.03.2021 21:07 Uhr)
      Anpassungen an Meta-Dateien.

    - #### v0.9.6 (16.03.2021 21:02 Uhr)
      Springt beim /termine Command ab 18 Uhr auf den nächsten Tag um.

    - #### v0.9.5 (16.03.2021 17:41 Uhr)
      **Bugfix**: Einträge beim Wochenplan werden nun nicht mehr einen Tag versetzt angezeigt.

    - #### v0.9.4 (16.03.2021 17:38 Uhr)
      **Bugfix**: Der Bot sucht nun die richtige Woche beim Wochenplan raus.

    - #### v0.9.3 (16.03.2021 04:48 Uhr)
      Alle Nachrichten des Bots werden nun lautlos verschickt.

    - #### v0.9.2 (16.03.2021 04:29 Uhr)
      *Update v0.9.1 released*

    - #### v0.9.1 (16.03.2021 04:27 Uhr)
      Kalender-ID vom Test-Kalender auf den Familien-Kalender geändert.

  - ### v0.8 (13.03.2021 20:22 Uhr)
      Neuer Code zur Erkennung von Daten-Zeilen im Essensplan

    - #### v0.8.1 (15.03.2021 01:46 Uhr)
      Zeiten am Sonntag angepasst

  - ### v0.7 (08.03.2021 22:56 Uhr)
    Neuer `/wochenplan`-Command

    - #### v0.7.1 (13.03.2021 19:23 Uhr)
      Tägliche Essens-Nachrichten von 8 und 18 Uhr auf 10 und 20 Uhr verschoben.

  - ### v0.6 (08.03.2021 04:45 Uhr)
    **Bugfix**: Die kopierte Nachricht des Essensplans wird nun korrekt escaped.

    - #### v0.6.1 (08.03.2021 19:26 Uhr)
      Beim `/essen`-Command wird ab 18 Uhr der nächste Tag angezeigt.

  - ### v0.5 (05.03.2021 03:53 Uhr)
    Neue automatische Posts des Essens des Tages zwei mal täglich und des Wochenplans sonntags.

    - #### v0.5.3 (06.03.2021 21:20 Uhr)
      **Bugfix**: Die Abend-Nachricht zeigt nun den Plan des nächsten Tages an.

    - #### v0.5.2 (05.03.2021 21:23 Uhr)
      Ein Datensatz wird nun auch erkannt, wenn die Zeile `No.:` als Prefix hat, um einen Wochentag-unabhängigen Datensatz zu erstellen.

      **Bugfix**: Die tägliche Nachricht postet nun den aktuellen Tag, statt den Nächsten.

    - #### v0.5.1 (05.03.2021 03:58 Uhr)
      *Interne* Änderungen an den Zeiten der täglichen Posts.

  - ### v0.4 (05.03.2021 02:24 Uhr)
    Nachrichten werden nun formatiert.

    - #### v0.4.4 (05.03.2021 02:50 Uhr)
      *Update v0.4.3 released*

    - #### v0.4.3 (05.03.2021 02:49 Uhr)
      *Internes Start-Skript entfernt*

    - #### v0.4.2 (05.03.2021 02:40 Uhr)
      *Update-Skript überarbeitet*

    - #### v0.4.1 (05.03.2021 02:27 Uhr)
      *Internes Start-Skript hinzugefügt*

  - ### v0.3 (05.03.2021 01:56 Uhr)
    Stabilität für Input-Daten verbessert.

  - ### v0.2 (05.03.2021 01:30 Uhr)
    Bot stürzt nicht mehr ab, wenn eine Nachricht nicht mehr angepinnt ist.

  - ### v0.1 (05.03.2021 00:17 Uhr)
    1. Projekt gestartet
       1. Projekt-Grundstruktur geschaffen
       2. Dependencies eingetragen
    2. Essen eines Essensplans parsen und speichern
    3. Der `/essen`-Command zeigt das heutige Essen an.
