# (Transport Layer) im OSI-Modell

Die Transportschicht ist die vierte Schicht des OSI-Modells (Schicht 4). 
Sie sorgt für eine zuverlässige Ende-zu-Ende-Verbindung zwischen Anwendungen 
auf verschiedenen Geräten, unabhängig von der Netzwerkstruktur darunter.

Ihre Hauptaufgaben umfassen:

## Segmentierung und Reassemblierung: 
          Aufteilung der Daten in Segmente für die Übertragung 
          und deren Wiederzusammenfügung am Ziel, 
          um eine effiziente und fehlerfreie Datenübermittlung zu gewährleisten.

## Fehlerkorrektur: 
          Erkennung und Korrektur von Übertragungsfehlern 
          durch Mechanismen wie Sequenznummern, Bestätigungen (ACKs) 
          und Retransmission verlorener Segmente.

## Flusskontrolle: 
          Regulierung der Datenübertragungsrate 
          zwischen Sender und Empfänger, 
          um Überlastungen zu vermeiden und die Netzwerkleistung zu optimieren.

## Multiplexing von Verbindungen: 
          Verwaltung mehrerer gleichzeitiger Verbindungen 
          über denselben Netzwerkpfad, 
          indem Ports zur Identifizierung von Anwendungen verwendet werden.

## Zuverlässigkeit vs. Geschwindigkeit: 
          Bereitstellung von Optionen wie garantierter Zustellung 
          (z. B. TCP) oder schneller, aber unzuverlässiger Übertragung 
          (z. B. UDP), je nach Anforderungen der Anwendung.

## Beispiele für Technologien in dieser Schicht: 
          TCP (Transmission Control Protocol) für zuverlässige Verbindungen, 
          UDP (User Datagram Protocol) für schnelle, verbindungslose Übertragungen, 
          SCTP (Stream Control Transmission Protocol) oder DCCP. 
          Sie bietet Dienste wie garantierte Zustellung oder Echtzeitkommunikation.

Diese Schicht interagiert mit der Netzwerkschicht für die Paketweiterleitung 
und mit der Sitzungsschicht für die Verwaltung von Kommunikationssitzungen, 
während sie die Grundlage für Anwendungen wie Webbrowser oder E-Mail-Clients bildet.

Für detaillierte Spezifikationen siehe Standards wie RFC 793 (TCP) oder RFC 768 (UDP).
