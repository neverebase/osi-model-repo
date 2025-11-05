# Das **OSI-Modell** (Open Systems Interconnection) 

## STRUKTOGRAMM

jede in den Branches liegende README.md beinhaltet 
eine Beschreibung der jeweiligen Schicht/ des jeweiligen Layer.

|/main||
|---|----------------|
|          👉|[README.md](README.md)|
|          👉|[COMMIT_HISTORY.md](COMMIT_HISTORY.md)|
| /01physical-layer |
|          👉| [README.md](https://github.com/neverebase/osi-model-repo/blob/d7f70012f9eae98493d9cd1ed4add99795dcde7d/README.md) |
| /02data-link-layer |
|          👉| [README.md](https://github.com/neverebase/osi-model-repo/blob/4fe67b71e258995414b728f24b78c6e03b290a56/README.md) |
| /03network-layer |
|          👉| [README.md](https://github.com/neverebase/osi-model-repo/blob/b1a3d8dde7490694e535a94ce16d77229fc2b17f/README.md) |
| /04transport-layer |
|          👉| [README.md] |
| /05session-layer |
|          👉| [README.md] |
| /06presentation-layer |
|          👉| [README.md] |
| /07application-layer | 
|          👉| [README.md] |

# Übersicht 
mit englischen und deutschen Bezeichnungen sowie kurzen Beschreibungen.

| Schicht | Englisch | Deutsch | Beschreibung |
|---------|----------|---------|-------------|
| 7 | Application Layer | Anwendungsschicht | Schnittstelle für Anwendungen; z.B. HTTP, FTP. |
| 6 | Presentation Layer | Darstellungsschicht | Datenformatierung, Verschlüsselung und Komprimierung. |
| 5 | Session Layer | Sitzungsschicht | Verwaltung von Sitzungen und Verbindungen. |
| 4 | Transport Layer | Transportschicht | Zuverlässige Datenübertragung; z.B. TCP, UDP. |
| 3 | Network Layer | Vermittlungsschicht | Routing und Adressierung; z.B. IP. |
| 2 | Data Link Layer | Sicherungsschicht | Fehlerkorrektur und Zugriff auf das Medium; z.B. Ethernet. |
| 1 | Physical Layer | Bitübertragungsschicht | Übertragung von Bits über physische Medien; z.B. Kabel, WLAN. |

## Zusammenfassung aller OSI-Schichten

Das OSI-Modell (Open Systems Interconnection) besteht aus 7 Schichten, 
die die Kommunikation in Netzwerken standardisieren. 
Jede Schicht baut auf der darunterliegenden auf und übernimmt spezifische Aufgaben. 
Nachfolgend eine kurze Zusammenfassung jeder Schicht mit deutscher und englischer Bezeichnung, 
Hauptaufgaben, Beispielen und Standards.

## 1. Physische Schicht (Physical Layer)
Die Physische Schicht ist die unterste Schicht des OSI-Modells (Schicht 1). 
Sie befasst sich mit der physischen Übertragung von Rohdaten (Bits) 
über ein Kommunikationsmedium, ohne Rücksicht auf die Bedeutung der Daten. 

- **Hauptaufgaben**:
          - Signalübertragung, Kodierung und Modulation,
            Hardware-Schnittstellen, Synchronisation
            und grundlegende Fehlererkennung.  
- **Beispiele**:
          - Ethernet-Kabel (Cat5/Cat6), Glasfaserkabel, WLAN (Wi-Fi), Bluetooth.  
- **Standards**:
          - IEEE 802.3 (Ethernet), ITU-T G-Serie.  

Sie bildet die Grundlage für alle höheren Schichten, 
indem sie eine zuverlässige Bit-Übertragung ermöglicht.

## 2. Datenverbindungsschicht (Data Link Layer)
Die Datenverbindungsschicht, auch Sicherungsschicht genannt, 
ist die zweite Schicht (Schicht 2). 
Sie stellt eine zuverlässige Verbindung zwischen direkt verbundenen Geräten her.  

- **Hauptaufgaben**:
          - Framing (Rahmenbildung), Adressierung mit MAC-Adressen,
  Fehlererkennung und -korrektur, Zugriffskontrolle auf das Medium.  
- **Beispiele**:
          - Ethernet (IEEE 802.3), Wi-Fi (IEEE 802.11), PPP, HDLC.  
- **Standards**:
          - IEEE 802.x, ITU-T X.25.  

Sie sorgt für fehlerarme Übertragung 
in lokalen Netzwerken und liefert Daten an die Netzwerkschicht.

## 3. Netzwerkschicht (Network Layer)
Die Netzwerkschicht ist die dritte Schicht (Schicht 3). 
Sie kümmert sich um die logische Adressierung 
und den Weg der Datenpakete durch das Netzwerk.  

- **Hauptaufgaben**:
          - Routing (Wegfindung), Paketweiterleitung,
            Fragmentierung und Reassemblierung,
            logische Adressierung (z. B. IP-Adressen).  
- **Beispiele**:
          - IP (Internet Protocol), ICMP, OSPF, BGP.  
- **Standards**:
          - RFC 791 (IPv4), RFC 2460 (IPv6).  

Sie ermöglicht die Kommunikation über mehrere Netzwerke hinweg 
und stellt die Verbindung zur Transportschicht her.

## 4. Transportschicht (Transport Layer)
Die Transportschicht ist die vierte Schicht (Schicht 4). 
Sie sorgt für eine zuverlässige Ende-zu-Ende-Verbindung 
zwischen Anwendungen auf verschiedenen Geräten.  

- **Hauptaufgaben**:
          - Segmentierung und Reassemblierung von Daten,
            Fehlerkorrektur, Flusskontrolle, Multiplexing von Verbindungen.  
- **Beispiele**:
          - TCP (Transmission Control Protocol), UDP (User Datagram Protocol).  
- **Standards**:
          - RFC 793 (TCP), RFC 768 (UDP).  

Sie bietet Dienste wie garantierte Zustellung (TCP) 
oder schnelle, aber unzuverlässige Übertragung (UDP).

## 5. Sitzungsschicht (Session Layer)
Die Sitzungsschicht ist die fünfte Schicht (Schicht 5). 
Sie verwaltet die Kommunikationssitzungen zwischen Anwendungen.  

- **Hauptaufgaben**:
          - Aufbau, Verwaltung und Abbau von Sitzungen,
            Synchronisation von Datenströmen,
            Token-Management für den Zugriff.  
- **Beispiele**:
          - NetBIOS, RPC (Remote Procedure Call), PPTP.  
- **Standards**:
          - ITU-T X.225, ISO 8326.  

Sie stellt sicher, dass Sitzungen effizient und sicher ablaufen, 
und koordiniert den Datenaustausch.

## 6. Präsentationsschicht (Presentation Layer)
Die Präsentationsschicht ist die sechste Schicht (Schicht 6). 
Sie übersetzt Datenformate und stellt sicher, 
dass Daten korrekt interpretiert werden.  

- **Hauptaufgaben**:
          - Datenformatierung und -übersetzung,
            Verschlüsselung und Komprimierung,
            Code-Konvertierung (z. B. ASCII zu EBCDIC).  
- **Beispiele**:
          - MIME (Multipurpose Internet Mail Extensions), SSL/TLS, JPEG, ASCII.  
- **Standards**:
          - ISO 8822, ITU-T X.226.  

Sie macht Daten für die Anwendungsschicht lesbar 
und handhabt Sicherheitsaspekte wie Verschlüsselung.

## 7. Anwendungsschicht (Application Layer)
Die Anwendungsschicht ist die oberste Schicht (Schicht 7). 
Sie stellt Schnittstellen für Benutzeranwendungen und Netzwerkdienste bereit.  

- **Hauptaufgaben**:
          - Zugriff auf Netzwerkdienste, Datenübertragung für Anwendungen,
            Authentifizierung und Autorisierung.  
- **Beispiele**:
          - HTTP/HTTPS, FTP, SMTP, DNS, Telnet.  
- **Standards**:
          - RFC 2616 (HTTP), RFC 1035 (DNS).  

Sie ist die einzige Schicht, mit der Endbenutzer direkt interagieren, 
und ermöglicht den Zugriff auf Ressourcen wie Webseiten oder E-Mails.

Diese Schichten arbeiten zusammen, um eine standardisierte, 
skalierbare Netzwerkkommunikation zu gewährleisten. 

Jede Schicht kapselt Daten der höheren Schicht und fügt eigene Header hinzu. 
Für detaillierte Informationen siehe die ISO/IEC 7498-1 Norm.
