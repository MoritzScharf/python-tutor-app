# Python-Tutor

## Was ist das?

Der Python-Tutor ist ein Programm zum Python-Lernen, ganz ohne Vorwissen. Du bekommst Lektionen zu allen Grundthemen von
Python (von `print` bis zu Klassen), viele Aufgaben aus dem Alltag (Mensa, WG-Kasse, Kino …), einen Schritt-für-Schritt-Debugger
und eine Probeklausur.

Du musst nichts weiter installieren: Python bringt das Programm selbst mit. Wenn du magst, hilft dir Claude
(die KI von Anthropic) mit Denkanstößen und Zusatzaufgaben. Das ist freiwillig.

## Herunterladen

1. Öffne die Seite **https://github.com/MoritzScharf/python-tutor-app/releases**.
2. Nimm ganz oben die neueste Version und klick dort unter „Assets“ auf die passende Datei:
   - **Windows:** `Python-Tutor-Setup-<Version>.exe`
   - **Mac mit Apple-Chip** (M1, M2, M3 …): `Python-Tutor-<Version>-arm64.dmg`
   - **Mac mit Intel-Prozessor:** `Python-Tutor-<Version>-x64.dmg`
     (Welchen Chip dein Mac hat, siehst du im Apple-Menü unter „Über diesen Mac“.)

## Installieren

Das Programm ist (noch) nicht bei Microsoft oder Apple „signiert“. Deshalb warnen Windows und macOS einmal beim
ersten Start. Das ist normal, das Programm ist in Ordnung.

### Windows

1. Doppelklick auf die heruntergeladene `.exe`-Datei. Du brauchst keine Administratorrechte.
2. Erscheint **„Der Computer wurde durch Windows geschützt“**: Klick auf **„Weitere Informationen“** und dann auf
   **„Trotzdem ausführen“**.
3. Die Installation läuft von selbst. Danach findest du **Python-Tutor** im Startmenü und auf dem Desktop.

### Mac

1. Doppelklick auf die `.dmg`-Datei und zieh **Python-Tutor** in den Ordner „Programme“.
2. Doppelklick auf **Python-Tutor** in „Programme“. Der Mac meldet jetzt, dass er das Programm nicht prüfen konnte,
   und öffnet es nicht. Klick auf **„Fertig“** (oder „OK“).
3. Öffne **Systemeinstellungen → Datenschutz & Sicherheit** und scrolle ganz nach unten. Dort steht eine Meldung zum
   Python-Tutor. Klick auf **„Dennoch öffnen“**, gib dein Mac-Passwort ein (oder nutze Touch ID) und bestätige noch
   einmal mit **„Öffnen“**. Das musst du nur beim ersten Start tun.
4. Auf älteren Macs (macOS 14 und früher) geht es auch so: **Rechtsklick** auf das Programm → **„Öffnen“** → noch
   einmal **„Öffnen“**. Ab macOS 15 klappt das nicht mehr, nimm dort den Weg über Schritt 3.

Die Mac-Fassung ist neu und noch wenig getestet. Wenn etwas hakt, sag Bescheid (siehe unten).

## Deine Daten

Dein Fortschritt und dein Code liegen im Ordner **`Dokumente/Python-Tutor-Daten`** (darin `meine-daten`).
Der Ordner bleibt bei einem Update und bei einer Deinstallation erhalten: **nicht löschen!** Willst du an einem
anderen Rechner weitermachen, nimm den Ordner mit.

## Claude verbinden

Die Knöpfe **„Frag Claude“** und **„Erklär mir den Fehler“** öffnen Claude mit einer fertigen Frage. Du musst sie nur
noch mit **Enter** abschicken. Dafür brauchst du ein eigenes Konto bei Claude. Ist **Claude Desktop** installiert,
öffnet sich das, sonst claude.ai im Browser. Klappt das Öffnen nicht, kopiert das Programm die Frage. Dann in Claude mit
**Strg+V** (Mac: **Cmd+V**) einfügen und Enter drücken.

Noch bequemer geht es mit einer kleinen **Erweiterung für Claude Desktop**. Dann sieht Claude selbst, an welcher Aufgabe
du gerade sitzt, und kann dir Zusatzaufgaben anlegen. Du richtest sie einmal ein. Klick im Programm links auf
**„Claude verbinden“** und folge den drei Schritten:

1. **Claude Desktop** öffnen → **Einstellungen → Erweiterungen**.
2. Auf **„Erweiterung installieren…“** klicken (manchmal unter „Erweiterte Einstellungen“) und die Datei
   **`python-tutor.mcpb`** wählen. Du kannst die Datei auch in das Fenster ziehen. Im Programm zeigt dir der Knopf
   **„Datei im Ordner zeigen“**, wo sie liegt.
3. Claude Desktop **neu starten**, dann im Programm auf **„Verbindung prüfen“** klicken. Dort steht danach
   „Verbunden“.

Beim Öffnen von Claude steht oben eine Warnung. Sie ist normal. Steht dort „Cowork“, wähle „Chat“.

Mit einem **Gratis-Konto** gelten die Gratis-Limits von Claude. Das Programm selbst braucht kein Abo, hat keinen
eigenen Claude-Zugang und benutzt nie fremde Konten: Du fragst immer mit deinem eigenen Konto.

Geht die Erweiterung bei dir nicht, ist das kein Problem: Die Knöpfe funktionieren auch so. Eine Zusatzaufgabe holst du
dir dann über Claude und fügst sie unter „Extra von Claude“ mit **„Aufgabe aus Zwischenablage einfügen“** ein.

## Lernstand aus der VS-Code-Fassung übernehmen

Hast du schon mit der älteren Fassung in VS Code gelernt? Dann nimmst du deinen Lernstand mit:

- Beim ersten Start sucht das Programm in Dokumente, Downloads, Desktop, deinem Benutzerordner und auf anderen
  Laufwerken (Windows) nach dem alten Ordner. Das geht schnell im Hintergrund und braucht höchstens ein paar Sekunden;
  das Programm startet währenddessen ganz normal. Findet es den Ordner, fragt es oben: **„Übernehmen?“** Klick auf
  **Übernehmen**.
- Hat es ihn nicht gefunden, klick links auf **„Lernstand aus Ordner übernehmen …“** und wähl den alten Ordner
  `Python-Tutor` aus.

Das Programm kopiert deine Fortschritte, deinen Code und deine Zusatzaufgaben. Im alten Ordner ändert sich nichts.
Übernehmen geht nur in ein noch leeres Programm. Hast du hier schon gelernt, kopier den Ordner `meine-daten` von Hand
und starte das Programm neu.

## Neue Version

- **Windows:** Das Programm holt neue Versionen selbst und installiert sie beim nächsten Start. Oben steht ein Hinweis.
- **Mac:** Oben steht ein Hinweis mit dem Knopf **„Herunterladen“**. Lade die neue `.dmg` und zieh das Programm wieder in
  „Programme“ (die alte Version ersetzen).

Dein Lernstand bleibt dabei immer erhalten.

## Wenn etwas nicht klappt

- **Windows oder macOS warnt beim Start:** Siehe „Installieren“. Das ist beim ersten Start normal.
- **Die Frage kommt nicht in Claude an:** Das Programm hat sie dann kopiert. In Claude mit **Strg+V** (Mac: **Cmd+V**)
  einfügen und **Enter** drücken.
- **„Noch nicht verbunden“ bei „Claude verbinden“:** Hast du die Erweiterung installiert und Claude Desktop danach
  ganz neu gestartet? Dann klick noch einmal auf **„Verbindung prüfen“**.
- **„Claude Desktop ist auf diesem Rechner nicht zu finden“:** Installier Claude Desktop oder nutz die Knöpfe mit dem
  Browser. Das geht auch.
- **Du hast eine Fehlermeldung oder ein Problem gefunden:** Sag der Person Bescheid, von der du den Link hast, am besten
  mit einem Foto von der Meldung.
