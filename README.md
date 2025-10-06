# template_2ahit_file_input_output

Some examples to read input from files

---

### **Aufgabenstellung: „Werkzeuge für einen Daten-Workflow“**

Es sollen **fünf eigenständige Programme** entwickelt werden, die jeweils über **Kommandozeilenparameter** gesteuert werden. Die Programme müssen ausschließlich über die Kommandozeile (ohne grafische Oberfläche) bedient werden.

Alle Programme sollen unabhängig voneinander lauffähig sein, können aber inhaltlich aufeinander aufbauen.

---

#### **Programm 1: Textstatistik**

Schreibe ein Programm, das eine Textdatei einliest und folgende Informationen berechnet:

* Anzahl der Zeilen
* Anzahl der Wörter
* Anzahl der Zeichen

**Kommandozeilenparameter:**

1. Pfad zur Eingabedatei
2. Optional: Schalter `-w`, um nur die Wortanzahl auszugeben

---

#### **Programm 2: Zahlenanalyse**

Ein Programm liest eine Datei mit Ganzzahlen (eine Zahl pro Zeile) und berechnet:

* Summe
* Durchschnitt
* Minimum und Maximum

**Kommandozeilenparameter:**

1. Pfad zur Eingabedatei
2. Optional: Schalter `-o <Datei>`, um die Ergebnisse in eine Ausgabedatei zu schreiben

---

#### **Programm 3: Dateifilter**

Ein Programm, das eine Textdatei Zeile für Zeile durchgeht und nur jene Zeilen ausgibt, die ein bestimmtes Suchwort enthalten.

**Kommandozeilenparameter:**

1. Pfad zur Eingabedatei
2. Suchbegriff
3. Optional: Schalter `-i` für Groß-/Kleinschreibungs-Unabhängigkeit

---

#### **Programm 4: Datumsrechner**

Ein Programm, das ein Datum (Format `JJJJ-MM-TT`) entgegennimmt und ein neues Datum berechnet, das eine bestimmte Anzahl von Tagen später liegt.

**Kommandozeilenparameter:**

1. Startdatum
2. Anzahl der Tage (positiv oder negativ)

Beispiel:
`programm4 2025-10-06 30` → Ausgabe: `2025-11-05`

---

#### **Programm 5: Mini-Berichtsgenerator**

Ein Programm, das die Ergebnisse aus mehreren Dateien (z. B. aus den vorherigen Programmen) zusammenfasst und in einer neuen Textdatei speichert.

**Kommandozeilenparameter:**

1. Liste von Eingabedateien
2. Pfad zur Ausgabedatei

Beispiel:
`programm5 stats.txt zahlen.txt filter.txt bericht.txt`

Das Programm soll alle Inhalte der Eingabedateien mit Überschriften versehen in die Ausgabedatei schreiben.

---

### **Bewertungskriterien**

* Korrekte Verarbeitung und Validierung der Kommandozeilenparameter
* Sinnvolle und klare Konsolenausgaben
* Robuste Fehlerbehandlung (z. B. fehlende Datei, falsches Datum)
* Lesbare und strukturierte Quelltexte
