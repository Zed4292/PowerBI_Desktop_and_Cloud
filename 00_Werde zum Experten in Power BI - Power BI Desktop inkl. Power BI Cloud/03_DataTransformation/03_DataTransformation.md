# Daten Transformieren

## Daten verbinden

- Klicken auf "Get data" und dann Files, Datenbanken oder andere Datenquellen auswählen.

![alt text](image.png)

- Gewünschtes Excel File bzw. Mappe auswählen und im Navigator auf "Transform Data" klicken.

### Zeilen bearbeiten

![alt text](image-1.png)

![alt text](image-2.png)

### Tabellenüberschriften auswählen

![alt text](image-3.png)

### Leere Zeilen / Fehler entfernen

- Fehler werden mit einem roten Symbol am Kopf der Spalte angezeigt.
- Spalte auswählen und auf "Remove Errors" klicken.

![alt text](image-4.png)

### Duplikate entfernen

- Spalte auswählen in der Duplikate entfernt werden sollen
- Remove Rows auswählen und Remove Duplicates auswählen

![alt text](image-5.png)

### Datentypen der Spalten

- Datentypen anzeigen indem man auf Symbol neben dem Spaltennamen klickt
- Auch Mehrfachauswahl der einzelnen Spalten notwendig

### Werte ersetzen in Spalten

- z.B. bei Dezimalzahlen die mit entweder mit "." oder mit "," getrennt werden
- um Daten korrekt zu verarbeiten müssen Punkte mit Komma ersetzt werden

![alt text](image-6.png)

### Daten extrahieren

- Dazu wird eine weitere zusätzliche Datenquelle angebunden (.csv Datei)
- Import und Tranformation kann genau so gemacht werden wie bei Excel (beim Laden muss jedoch der Seperator ausgewählt werden)

Link für Datenabruf aus dem Internet: [Liste der Länder und Territorien nach Fläche](https://de.wikipedia.org/wiki/Liste_der_L%C3%A4nder_und_Territorien_nach_Fl%C3%A4che)
Url in zweites Fenster eintragen

![alt text](image-7.png)

![alt text](image-8.png)

![alt text](image-9.png)

Power Bi parsed automatisch die Webseite und gibt Datenquellen zurück, diese können ausgewählt werden

![alt text](image-10.png)

Um die Spalte "Staat" bzw. die Kürzel am Ende jeder Zeile zu extrahieren auf "Extract"-> "Text after Delimiter" klicken

![alt text](image-12.png)

### Daten in neue Spalte verschieben

Spalte auswählen -> Split Column -> "By Delimiter" auswählen

![alt text](image-13.png)

### Spalten hinzufügen

![alt text](image-14.png)

### Neue Spalten aus Beispielen erstellen

![alt text](image-15.png)

![alt text](image-16.png)

### Zusammenführen von mehreren Arbeitsmappen mit gleichen / ähnlichen Daten

![alt text](image-17.png)

- Beide Tabellen werden anschließend gejoined
- Spalte über die gejoind werden soll muss jeweils angeklickt werden

![alt text](image-18.png)

- Für den Join können durch halten der Shift Taste auch mehrere Spalten ausgewählt werden
- Nach dem Merge können die Daten angezeigt werden indem man auf das kleine Symbol der gejointen Tabelle klickt und die Daten filtert die man anzeigen möchte

![alt text](image-19.png)
![alt text](image-20.png)

### Pivotisieren / Entpivotisieren

- Damit PowerBI Daten besser verarbeiten kann müssen die Daten manchmal besser vorbereitet werden
- Um Spalten zu Entpivotisieren alle Spalten markieren und "Unpivot Columns" auswählen

![alt text](image-21.png)

![alt text](image-22.png)

### Abfragen hinzufügen

![alt text](image-23.png)

![alt text](image-24.png)

