# Daten transformieren - fortgeschritten

## Erweiterter Editor

- Im erweiterten Editor kann der Code, der generiert wird für die verschiedenen Abfragen, bearbeitet werden

![alt text](image.png)

## Unterschied Verweis / Duplizieren

- Eine neue Tabelle die mit "Verweis"/"Reference" erzeugt wurde übernimmt automatisch auch alle Änderungen der Ausgangstabelle
- Ein Duplikat wird zum Zeitpunk x von einer Ausgangstabelle erzeugt und ist danach völlig unabhängig davon

![alt text](image-1.png)

- Die Beziehungen der einzelnen Tabellen zueinander können unter View->Querry Dependencies überprüft werden

![alt text](image-2.png)

## Laden aktivieren / deaktivieren

- Aus Performance-Gründen können nicht benötigte Hilfstabellen deaktiviert werden und verbessern so die Performance des Berichts da PowerBI diese nicht extra in das Datenmodell laden muss
- Zusätzlich kann, bei Tabellen die sich nicht ändern, die Einstellung "Include in report refresh" deaktiviert werden
- Dadurch werden die Ladezeiten bei Berichtsaktualisierungen verbessert

![alt text](image-3.png)

## Gruppierungen erstellen

- Unter "Transform->Group by" können die Daten gruppiert werden

![alt text](image-4.png)

- Es gibt aber auch die Möglichkeit mehrer Gruppierungen zu erstellen, dazu auf "Advanced" klicken

![alt text](image-5.png)

## Mathematische Operationen

- Math. Operationen sind nur bei Spalten mit einem Zahlenwert möglich
- Dafür einfach Spalte auswählen und im Menüband die gewünschte mathematische Operation auswählen

![alt text](image-6.png)

## R-Scripte in PowerBI ausführen

- Dies dient zur Erstellung von komplexen Berechnungen innerhalb von PowerBI

![alt text](image-7.png)

## Parameter zur dynamischen Transformierung

- Um einen Parameter zu erstellen unter Home->Manage Parameters auf New Parameter oder Manage Parameter klicken

![alt text](image-8.png)

## M-Formelsprache

- Die Formelsprache kann in dem erweiterten Editor aufgerufen werden

![alt text](image-9.png)

