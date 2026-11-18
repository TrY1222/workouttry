# Cindy – 20-Min-AMRAP

Eine kleine Web-App fürs Körpergewicht-Workout nach dem „Cindy“-Prinzip: ein Knopf, und die App führt dich durchs komplette Training. Du zählst nur deine Runden – nach knapp 30 Minuten bist du fertig.

## Ablauf

1. **Aufwärmen – 3 Min:** 6 Übungen à 30 Sek. mit Countdown und Kurzanleitung
2. **AMRAP – 20 Min:** so viele Runden wie möglich, nach jeder Runde auf „+1 Runde“ tippen
3. **Dehnen – 5 Min:** 8 Dehnübungen für Brust, Schultern, Rücken, Beine und Hüfte
4. **Abschluss:** Rundenzahl, Rekord-Check und kleine Statistik

## Varianten

| Variante | Eine Runde |
|---|---|
| Cindy (Original) | 5 Klimmzüge · 10 Liegestütze · 15 Kniebeugen |
| Ohne Stange | 10 Australian Rows unterm Tisch · 10 Liegestütze · 15 Kniebeugen |
| Beine & Core | 10 Ausfallschritte · 10 Mountain Climber · 15 Sit-ups |
| Push-Fokus | 5 Pike Push-ups · 10 Liegestütze · 15 Jump Squats |

Jede Übung hat eine leichtere Alternative (Stufe „Leicht“, z. B. Knie-Liegestütze oder negative Klimmzüge). Rekorde zählen getrennt je Variante und Stufe.

Die App schlägt jeden Tag eine Variante vor: Nach einem Oberkörper-Tag kommt „Beine & Core“, damit die Schultern Pause bekommen, sonst die Variante, die am längsten nicht dran war. Du kannst aber jederzeit selbst wählen.

## Funktionen

- **Streak:** zählt deine Trainingstage in Folge – bis zu 2 Ruhetage dazwischen sind erlaubt
- **Pausen-Hinweis:** nach 3 Trainingstagen am Stück heißt es „Gönn dir heute Pause“
- **Rekord-Tempo:** während des AMRAP siehst du, ob du vor oder hinter deinem Rekord liegst
- **Signale:** Ton und Vibration bei 10, 5 und 1 Minute Restzeit und am Ende (Vibration nicht auf dem iPhone)
- **Bildschirm bleibt an** während des Trainings (Wake Lock)
- **Verlauf:** Diagramm und Liste deiner Runden pro Variante

## Benutzung

1. Den Link oben auf dem Handy öffnen – am besten über „Teilen → Zum Home-Bildschirm“ als App ablegen.
2. Variante und Stufe wählen, **Start** tippen.
3. Im AMRAP nach jeder Runde auf **+1 Runde** tippen. Vertippt? **−1** korrigiert, auf dem Ergebnis-Bildschirm geht es auch noch mit **+ / −**.

**Testmodus:** `#test` an den Link hängen – alles läuft 20× schneller und nichts wird gespeichert. Praktisch, um den Ablauf in 1,5 Minuten durchzuklicken.

## Technik

Eine einzige `index.html` (HTML, CSS, JavaScript), kein Backend, kein Build-Schritt. Alle Daten bleiben im `localStorage` deines Browsers und verlassen dein Gerät nicht. Die einzige externe Quelle sind die Schriften von Google Fonts – ohne Netz greift automatisch eine Systemschrift.
