# Die Datenverbindungsschicht, auch Sicherungsschicht oder Data Link Layer genannt, 
ist die zweite Schicht des OSI-Modells (Schicht 2). 

Sie baut auf der Physischen Schicht auf 
und stellt eine zuverlässige Punkt-zu-Punkt- 
oder Punkt-zu-Mehrpunkt-Verbindung zwischen direkt verbundenen Geräten her. 

# Ihre Hauptaufgaben umfassen:

## Framing (Rahmenbildung): 
          Unterteilung der Datenströme in Rahmen (Frames) mit Header und Trailer, 
          um die Daten zu strukturieren und zu übertragen.
## Adressierung: 
          Verwendung von MAC-Adressen (Media Access Control) 
          zur Identifizierung von Geräten im lokalen Netzwerk (z. B. 48-Bit-Adressen in Ethernet).

## Fehlererkennung und -korrektur Überprüfung auf Übertragungsfehler 
durch Mechanismen wie CRC (Cyclic Redundancy Check) und ggf. Retransmission fehlerhafter Frames.

## Zugriffskontrolle auf das Medium: 
          Verwaltung des Zugriffs auf das Übertragungsmedium, 
          z. B. durch CSMA/CD (Carrier Sense Multiple Access with Collision Detection) 
          in Ethernet oder CSMA/CA in WLAN.

## Unterschichten: 
          Oft unterteilt in LLC (Logical Link Control) für logische Verbindungen 
          und MAC (Media Access Control) für den physischen Zugriff.

## Beispiele für Technologien und Protokolle in dieser Schicht: 
          Ethernet (IEEE 802.3), Wi-Fi (IEEE 802.11), 
          PPP (Point-to-Point Protocol) für Wählverbindungen 
          oder HDLC (High-Level Data Link Control) für serielle Verbindungen. 
          
## Sie sorgt für eine fehlerarme Übertragung 
          innerhalb eines lokalen Netzwerks und liefert Daten 
          an die Netzwerkschicht (Schicht 3), 
          während sie die physische Übertragung von der Schicht 1 nutzt.

Für detaillierte Spezifikationen siehe Standards wie IEEE 802.x oder ITU-T X.25. Diese Schicht ist entscheidend für die Zuverlässigkeit in LANs (Local Area Networks).
