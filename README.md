# (Session Layer) im OSI-Modell

Die Sitzungsschicht ist die fünfte Schicht des OSI-Modells (Schicht 5). 
Sie verwaltet die Kommunikationssitzungen zwischen Anwendungen 
auf verschiedenen Geräten, um einen strukturierten Datenaustausch zu ermöglichen.

Ihre Hauptaufgaben umfassen:

## Aufbau, Verwaltung und Abbau von Sitzungen: 
          Etablierung von Verbindungen zwischen Anwendungen, 
          Überwachung des Sitzungsstatus und ordnungsgemäße Beendigung 
          der Kommunikation, um Ressourcen freizugeben.

## Synchronisation von Datenströmen: 
          Sicherstellung der korrekten Reihenfolge und Synchronisation 
          von Datenübertragungen, z. B. durch Checkpoints 
          zur Wiederherstellung nach Unterbrechungen.

## Token-Management: 
          Verwaltung von Zugriffsrechten und Token-Systemen 
          zur Koordination des Datenaustauschs, 
          um Konflikte in Mehrbenutzerumgebungen zu vermeiden.

## Dialogsteuerung: 
          Bestimmung des Kommunikationsmodus, 
          z. B. Simplex (einseitig), Half-Duplex (abwechselnd) 
          oder Full-Duplex (bidirektional), 
          je nach Anforderungen der Anwendung.

## Fehlerbehandlung auf Sitzungsebene: 
          Erkennung und Behandlung von Sitzungsfehlern, 
          wie Verbindungsabbrüche, 
          und Initiierung von Wiederherstellungsprozessen.

## Beispiele für Technologien in dieser Schicht: 
          NetBIOS (Network Basic Input/Output System), 
          RPC (Remote Procedure Call), PPTP (Point-to-Point Tunneling Protocol) 
          oder ISO 8326. 
          Sie stellt sicher, dass Sitzungen effizient und sicher ablaufen.

Diese Schicht interagiert mit der Transportschicht für die zuverlässige Datenübertragung 
und mit der Präsentationsschicht für die Datenformatierung, 
während sie die Grundlage für Anwendungen wie Videokonferenzen oder Dateitransfers bildet.

Für detaillierte Spezifikationen siehe Standards wie ITU-T X.225 oder ISO 8326.
