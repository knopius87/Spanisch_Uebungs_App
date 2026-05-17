# Spanisch_Uebungs_App a_tope
Spanisch-Lern-App — Version 7
Begleit-App zu «a_tope nueva edición» für den Gymnasialeinsatz
Stand: Mai 2026 · Einzelne HTML-Datei · Keine Installation erforderlich

1. Was ist a_tope?
a_tope ist eine browserbasierte Spanisch-Lern-App für Gymnasialschülerinnen und -schüler, die mit dem Lehrwerk a_tope nueva edición arbeiten. Die App läuft als einzelne HTML-Datei direkt im Browser — ohne Installation, ohne Konto und ohne Internetverbindung nach dem ersten Laden.

Unterstützte Plattformen: iOS (Safari), Android (Chrome), Desktop (alle modernen Browser)
Datenspeicherung: Ausschließlich lokal im Browser (localStorage). Keine Server, keine Konten, keine E-Mail-Adresse.

2. Funktionen im Überblick

Icon	Funktion	Beschreibung
⚡	Schnell-Runde	7 Fragen gemischt aus Vokabeln, Grammatik und Konjugation — in ca. 3 Minuten.
📖	Lernmodus	Karteikarten-System: Spanisch vorne → umdrehen → Deutsch. Kein Zeitdruck, keine XP. Bonus-XP bei 5er-Streak.
📚	Vokabeln	Thematische Übungsrunden aus den Unidades des Lehrwerks.
🔀	Konjugation	Alle 6 Zeiten frei wählbar. Antwortoptionen = verschiedene Personen oder Zeiten desselben Verbs (kein Ausschlussverfahren).
⚙️	Grammatik	ser/estar, gustar, Imperativ, Reflexivverben, Komparativ, Indefinido. Alle Fragen auf Spanisch.
🔄	Wiederholung	Automatisch generierte Runde aus den schwachen Wörtern des Nutzers.
⚔️	Bosse	15 thematische Bossgegner. Sieg = +50 XP und ein neuer Titel.
🏆	Hall of Fame	Alle 15 Bosse im Überblick: besiegte mit Portrait, unbesiegte als Silhouette.
🏅	Challenge	Mehrspieler-Modus über geteilten Code — alle spielen dieselbe Runde.
📊	Ranking	Lokales Bestenlisten-System mit Streak-Anzeige.

3. Fortschrittssystem
3.1 Städte-Reise (XP-basiert)
Durch das Lösen von Übungen sammeln Schülerinnen und Schüler XP-Punkte und bereisen dabei 11 spanischsprachige Städte:

Level	Stadt	XP ab	Land
1	🏛️ Madrid	0	Spanien
2	🦙 Lima	1.500	Peru
3	🌊 Barcelona	4.000	Spanien
4	🥩 Buenos Aires	7.500	Argentinien
5	🌮 México D.F.	12.000	Mexiko
6	💃 Sevilla	17.500	Spanien
7	☕ Bogotá	24.000	Kolumbien
8	🏔️ Santiago	31.500	Chile
9	🎺 La Habana	40.000	Kuba
10	⚽ Montevideo	50.000	Uruguay
11	🍊 Valencia	62.000	Spanien

3.2 Titel-System (Boss-Siege)
Durch das Besiegen von Bossen steigen Schülerinnen und Schüler in ihrem Titel auf. Der Titel ist im Topbar und im Profil sichtbar.

Siege	Titel (ES)	Titel (DE)	Icon
0	Novato/a	Anfänger/in	🐣
1	Estudiante	Schüler/in	📖
3	Aventurero/a	Entdecker/in	🗺️
6	Conocedor/a	Kenner/in	🧭
10	Experto/a	Experte/in	⭐
15	Maestro/a	Meister/in	🎓
20	Profesor/a	Lehrer/in	👑

4. Die 15 Bosse
Jeder Boss prüft einen anderen Themenbereich. Das Besiegen eines Bosses gibt +50 XP und zählt zum Titelaufstieg.

#	Boss	Thema	Stadt
1	Don Presente Presidente	Presente (Konjugation)	Valencia
2	Señora Gruñona	Begrüßung & Vorstellung	Madrid
3	Don Severo del Mar	Schule & Alltag	Lima
4	Profesora Misterio	Familie & Wohnen	Barcelona
5	El Profe Fierro	Freizeit & Hobbys	Buenos Aires
6	El Gran Chilango	Tagesablauf & Zeit	México D.F.
7	Doña Carmen la Feroz	Stadt & Orientierung	Sevilla
8	La Furia Inca	ser vs. estar	Bogotá
9	Doña Eugenia Malgenio	gustar & encantar	Santiago
10	Don Eusebio Maldonado	Imperativ	La Habana
11	Doña Matilda Mate	Reflexivverben	Montevideo
12	El Maestro Tempestivo	Presente Konjugation	Valencia
13	Doña Kira Shark-ira	Pretérito indefinido	Cartagena
14	Doña Dionisia Durango	Pretérito perfecto	Guayaquil
15	Don Campeón del Reguetón	Pretérito imperfecto	Puerto Rico

5. Konjugationsübungen
Alle 6 Zeiten sind ohne Einschränkung frei wählbar. Die Antwortmöglichkeiten sind didaktisch aufgebaut:

•	Presente: regelmäßige und unregelmäßige Verben
•	Pretérito indefinido: starke und schwache Formen
•	Pretérito perfecto: haber + Partizip — Distractoren = falsche Person oder falsches Partizip
•	Pretérito imperfecto: Zustände und Gewohnheiten
•	Futuro simple: regelmäßige Endungen
•	Condicional: Möglichkeit und Wunsch

Wichtig: Die falschen Antwortoptionen stammen immer vom selben Verb — andere Personen oder andere Zeiten. So muss man wirklich die richtige Form kennen, statt andere Verben auszuschließen.

6. Technische Details
6.1 Datei
•	Format: Einzelne HTML-Datei (ca. 200 KB)
•	Abhängigkeiten: Keine — läuft ohne Internetverbindung nach dem ersten Laden
•	Fonts: Google Fonts (Nunito, Playfair Display) — non-blocking, fallen auf System-Fonts zurück
•	Datenspeicherung: localStorage (gerätelokal, kein Server)

6.2 Navigation
5 Tabs in der Bottom-Navigation:
•	Start — Startseite mit Quick-Cards und Städte-Reise
•	Unidades — alle Lehrwerks-Einheiten mit Vokabeln
•	Ranking — lokales Bestenlisten-System
•	Bosse — Hall of Fame + Challenge-Modus
•	Profil — XP-Stand, Titel, Badges, Wochenbericht

6.3 XP-Vergabe
•	Richtige Antwort: +10 XP
•	Perfekte Runde (alle richtig): +20 % Bonus
•	Boss-Sieg: +50 XP
•	Lernmodus, 5er-Streak: +3 XP
•	Tagesziel (7 Fragen): zusätzlicher Bonus

7. Didaktischer Einsatz
Selbstständiges Üben
Schülerinnen und Schüler öffnen die HTML-Datei im Browser und üben eigenständig. Empfohlen: 7 Fragen täglich als Hausaufgabe oder Vorbereitung auf Tests.

Challenge-Modus im Unterricht
Die Lehrkraft erstellt einen Challenge-Code für ein bestimmtes Thema. Alle Schülerinnen und Schüler spielen dieselbe Runde. Anschließend werden Ergebnisse verglichen.

Boss-Kämpfe als Prüfungsvorbereitung
Jeder Boss entspricht einem grammatischen oder vokabularischen Thema. Das Bestehen eines Bosses erfordert mindestens 7–8 von 10 richtigen Antworten unter Zeitdruck.

a_tope v7 · Erstellt mit Claude (Anthropic) · Mai 2026
