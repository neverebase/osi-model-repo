# (Network Layer) im OSI-Modell

Die Netzwerkschicht ist die dritte Schicht des OSI-Modells (Schicht 3). 
Sie kümmert sich um die logische Adressierung und den Weg der Datenpakete 
durch das Netzwerk, unabhängig von der physischen Übertragung.

Ihre Hauptaufgaben umfassen:

## Routing (Wegfindung): 
          Bestimmung des optimalen Pfads für Datenpakete 
          von der Quelle zum Ziel über verschiedene Netzwerke hinweg, 
          unter Verwendung von Routing-Tabellen und Algorithmen.

## Paketweiterleitung: 
          Weiterleitung von Paketen an den nächsten Knoten 
          basierend auf logischen Adressen, 
          um eine effiziente Datenübertragung zu gewährleisten.

## Fragmentierung und Reassemblierung: 
          Aufteilung großer Datenpakete in kleinere Fragmente 
          für die Übertragung über Medien mit begrenzter Größe 
          und deren Wiederzusammenfügung am Ziel.

## Logische Adressierung: 
          Zuweisung und Verwaltung von logischen Adressen 
          (z. B. IP-Adressen) zur Identifizierung von Geräten 
          und Netzwerken im Internet oder lokalen Netzen.

## Fehlerbehandlung und Diagnose: 
          Grundlegende Fehlererkennung und -meldung, 
          z. B. durch ICMP (Internet Control Message Protocol), 
          zur Unterstützung der Netzwerkdiagnose.

## Beispiele für Technologien in dieser Schicht: 
          IP (Internet Protocol), ICMP, OSPF (Open Shortest Path First), 
          BGP (Border Gateway Protocol) oder RIP (Routing Information Protocol). 
          Sie ermöglicht die Kommunikation über mehrere Netzwerke hinweg 
          und stellt die Verbindung zur Transportschicht her.

Diese Schicht interagiert mit der Datenverbindungsschicht für die lokale Übertragung 
und mit der Transportschicht für Ende-zu-Ende-Kommunikation, 
während sie die Grundlage für das Routing im Internet bildet.

Für detaillierte Spezifikationen siehe Standards wie RFC 791 (IPv4) oder RFC 2460 (IPv6).
