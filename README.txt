Trainingsanalyse - Web-Version für GitHub Pages
==================================================

Diese drei Elemente auf https://github.com/rolandkoll99-droid/Trainings-Analyse
hochladen (Repo-Hauptseite -> "Add file" -> "Upload files" -> alle drei
Elemente hineinziehen -> unten "Commit changes"):

  - index.html
  - auth.js
  - vendor/  (Ordner mit xlsx.full.min.js darin)

WICHTIG: Die Datei muss "index.html" heißen (nicht 04_Trainingsanalyse.html),
sonst funktioniert die Adresse ohne Dateinamen am Ende
(https://rolandkoll99-droid.github.io/Trainings-Analyse/) nicht.

Falls GitHub Pages für dieses Repository noch nicht aktiviert ist:
  Repo -> Settings -> Pages -> "Build and deployment" -> Source:
  "Deploy from a branch" -> Branch: main / (root) -> Save.

Nach ein bis zwei Minuten ist die Seite unter der QR-Code-Adresse erreichbar.

Wichtig zu wissen: Diese Web-Version ist eine eigenständige Kopie von
04_Trainingsanalyse.html. Sie läuft komplett unabhängig vom Raspberry Pi im
Vereinsheim - jedes Mitglied trägt seine Trainingsdaten direkt im Browser
seines eigenen Handys ein (persönliches Trainingstagebuch), es findet KEINE
Übertragung zum Raspberry Pi oder zu anderen Mitgliedern statt. Die
Spielerliste ist die eingebaute Standardliste (22 Namen) und unabhängig von
der Spielerverwaltung im Vereinsheim.

Neu:
  - Oben rechts gibt es einen "?"-Button mit einer kurzen Erklärung, was die
    Seite macht und wie man sie bedient - gedacht für Personen, die die
    Seite zum ersten Mal über den QR-Code öffnen.
  - Der Spielername kann jetzt auch frei eingetippt werden (nicht nur über
    das Dropdown auswählen). Das erlaubt es auch neuen oder neugierigen
    Personen, die noch nicht in der Liste stehen, die App sofort
    unverbindlich auszuprobieren - die Spieler-ID wird dabei automatisch
    vergeben.
