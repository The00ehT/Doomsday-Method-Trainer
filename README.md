# Weekday Trainer · Wochentag-Trainer

A small offline web app for practising mental weekday calculation: it shows a random date from a range you choose, you tap the weekday, and it measures your time, analyses your mistakes and rewards your progress.
### ▶ [Play now](https://the00eht.github.io/Doomsday-Method-Trainer/)

No download, no account, works in any browser. Available in English and German.
*Deutsch weiter unten.*

## Features

- Random dates from any range between 1583 and 9999 (Gregorian calendar)
- Optional countdown before each date (off, 1, 2, 3 or 5 seconds), then the clock starts
- A fixed one-screen training view (no scrolling), weekday keys at the bottom within thumb reach, "Next" at the top right
- Tap the weekday or use the keyboard: `1`–`6` = Monday–Saturday, `0` = Sunday, `Space`/`Enter` = next
- Short shake on a wrong answer, a green glow on a right one
- Optional working shown after each answer, step by step with the Doomsday method
- **Step-by-step mode** (Settings → Training mode): a date is split into three separate, timed tasks – century (20xx), year (xx45) and day (24.07.). For each you tap the offset 0–6 on the usual weekday keys (1 = Monday … 0 = Sunday)
- **Statistics:** accuracy, average/median/best time, correct-answer streak, daily practice streak with the last 14 days (swipe across the boxes to see how active you were each day), response-time trend and a histogram of your answer times, recent answers
- **Time or error rate by weekday, month, decade and century** as bar charts, compared with your overall average. Touch and drag across a chart to read exact values and how many answers make up each bar
- **Weekday × month heatmap** showing which combinations are slow or error-prone
- **Step-by-step statistics:** pie chart of how your time splits between century anchor, year offset and date offset, with ✅/❌ per step
- **Randomness check:** how often each weekday came up, as bars with the expected line or as a pie, plus a chi-square test
- **Error analysis:** estimates where your mistakes come from (year arithmetic, century anchor, leap year, swapped memory date), shows how far off you usually are and which month/century combinations trip you up most
- **Slowest dates** with a button to practise exactly those again
- **Achievements:** 37 emoji badges (6 of them for step-by-step mode) – tap one to see it as a floating 3D coin you can spin with your finger – and nine evolution stages on a swipeable timeline – Australopithecus, Homo habilis, Homo erectus, Neanderthal, Cro-Magnon, Homo sapiens, Scholar, Inventor and Einstein. Each stage is shown as a silhouette scene – reaching into an acacia, holding up a fresh hand axe, sitting on the ground by a glowing campfire, a club, a spear throw, a wheat sheaf, a book by a column, a machine crank, and Einstein thinking in front of E = mc² … Tap a stage to see it large together with its requirements.
- Filter statistics by today, 7 days, 30 days or all time
- **CSV export and import** of all your answers
- English and German, switchable in Settings (dates, numbers and the working follow the language)
- Light, dark or system appearance; explanations in the statistics can be hidden
- Works offline once opened, installs to the iPhone home screen with its own icon

## Install on iPhone

1. Open the app's address in **Safari**.
2. Tap **Share → Add to Home Screen → Add**.
3. Open it once from the home screen while you are online. After that it also works offline.

## Your data

All results are saved automatically on your device (browser storage). Nothing is uploaded anywhere, and this repository contains only the app itself.

Deleting the app from the home screen also deletes its data. Use **Settings → Export CSV** now and then and keep the file, for example in Files. **Import CSV** adds an export back in, for example on a new phone. Answers that are already there are skipped, so importing the same file twice does no harm. The CSV opens directly in Excel or Numbers, and exports from either language can be imported in both.

## Updating the app (for the repository owner)

Upload the changed files and raise the version number at `CACHE` in `sw.js` (e.g. `v21` → `v22`). Then open the app once while online and reload it; the new version appears from the second start.


## Deutsch

Eine kleine Offline-Web-App zum Trainieren der Wochentagsberechnung im Kopf. Sie zeigt ein zufälliges Datum aus einem frei wählbaren Zeitraum, du tippst den Wochentag an, und die App misst deine Zeit, wertet deine Fehler aus und belohnt deinen Fortschritt.

**Funktionen**

- Zufällige Daten von 1583 bis 9999 (gregorianischer Kalender)
- Countdown vor jedem Datum einstellbar: aus, 1, 2, 3 oder 5 Sekunden
- Bedienung per Fingertipp oder Tastatur: `1`–`6` = Montag–Samstag, `0` = Sonntag, Leertaste/Enter = weiter
- Festes Trainingsfenster ohne Scrollen, Wochentagstasten unten in Daumenreichweite, „Weiter“ oben rechts
- Kurzes Wackeln bei falscher Antwort, grünes Aufleuchten bei richtiger
- Rechenweg nach der Doomsday-Methode in vier übersichtlichen Schritten
- **Schritt-für-Schritt-Modus** (Einstellungen → Trainingsmodus): ein Datum wird in drei einzelne, getimte Aufgaben zerlegt – Jahrhundert (20xx), Jahr (xx45) und Tag (24.07.). Du tippst jeweils den Offset 0–6 auf den gewohnten Wochentagstasten (1 = Montag … 0 = Sonntag)
- **Statistik:** Trefferquote, Ø-, Median- und Bestzeit, Serie richtiger Antworten, tägliche Serie mit den letzten 14 Tagen (über die Kästchen streichen zeigt, wie aktiv du an dem Tag warst), Zeitverlauf und Histogramm der Antwortzeiten, letzte Antworten
- **Zeit oder Fehlerquote nach Wochentag, Monat, Jahrzehnt und Jahrhundert** als Balkendiagramm, im Vergleich zu deinem Durchschnitt. Mit dem Finger darüberziehen zeigt genaue Werte und die Anzahl der Antworten hinter jedem Balken
- **Heatmap Wochentag × Monat:** zeigt, welche Kombinationen langsam oder fehleranfällig sind
- **Schritt-Statistik:** Kuchendiagramm, wie sich deine Zeit auf Jahrhundert-Anker, Jahres-Offset und Datums-Offset verteilt, mit ✅/❌ je Schritt
- **Zufälligkeitsanalyse:** wie oft jeder Wochentag als Lösung kam, als Balken mit Erwartungslinie oder als Kuchen, mit Chi-Quadrat-Test
- **Fehleranalyse:** schätzt, woher deine Fehler kommen (Jahr verrechnet, Jahrhundert-Anker, Schaltjahr, Merktag verwechselt), zeigt, um wie viele Tage du meist danebenliegst, und welche Kombinationen aus Monat und Jahrhundert dir am schwersten fallen
- **Langsamste Daten** mit Knopf, um genau diese Daten nachzuüben
- **Erfolge:** 37 Errungenschaften mit Emoji-Abzeichen (6 davon für den Schritt-Modus) – ein Tipp zeigt sie als schwebende 3D-Münze, die du mit dem Finger drehen kannst – und neun Entwicklungsstufen auf einem wischbaren Zeitstrahl – Australopithecus, Homo habilis, Homo erectus, Neandertaler, Cro-Magnon, Homo sapiens, Gelehrter, Erfinder und Einstein. Jede Stufe ist eine Silhouetten-Szene – Griff in die Akazie, ein frisch geschlagener Faustkeil, am Boden vor dem leuchtenden Lagerfeuer sitzend, Keule, Speerwurf, Weizengarbe, Buch an der Säule, Kurbel einer Maschine und Einstein nachdenklich vor E = mc² … Ein Tipp auf eine Stufe zeigt sie groß zusammen mit ihren Bedingungen.
- Statistik filterbar nach Heute, 7 Tagen, 30 Tagen oder Gesamt
- **CSV-Export und -Import** aller Antworten
- Deutsch und Englisch, umschaltbar in den Einstellungen (Datums- und Zahlenformat sowie Rechenweg passen sich an)
- Hell, dunkel oder wie das System; Erklärtexte in der Statistik lassen sich ausblenden
- Offline nutzbar und als App mit eigenem Symbol auf dem iPhone installierbar

**Installieren auf dem iPhone:** Adresse in Safari öffnen, dann **Teilen → Zum Home-Bildschirm → Hinzufügen**. Die App einmal mit Internet öffnen, danach funktioniert sie auch offline.

**Deine Daten:** Alle Ergebnisse werden automatisch auf deinem Gerät gespeichert und nirgends hochgeladen. Wenn du die App vom Home-Bildschirm löschst, sind auch die Daten weg. Sichere sie deshalb ab und zu über **Einstellungen → CSV exportieren**, zum Beispiel in der Dateien-App. Mit **CSV importieren** holst du sie zurück, etwa auf einem neuen Handy. Bereits vorhandene Antworten werden dabei übersprungen. Die CSV-Datei lässt sich direkt in Excel oder Numbers öffnen.

**Aktualisieren:** Geänderte Dateien hochladen und in `sw.js` die Versionsnummer bei `CACHE` erhöhen (z. B. `v21` → `v22`). Danach die App einmal mit Internet öffnen und neu laden; ab dem zweiten Start ist die neue Version da.
