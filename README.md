## Das **OSI-Modell** (Open Systems Interconnection) 
ist ein Referenzmodell für Netzwerkprotokolle, 
das die Kommunikation in sieben Schichten unterteilt. 

Jede Schicht hat spezifische Aufgaben 
und baut auf der darunterliegenden auf. 

Hier eine Übersicht mit englischen 
und deutschen Bezeichnungen sowie kurzen Beschreibungen.

| Schicht | Englisch | Deutsch | Beschreibung |
|---------|----------|---------|-------------|
| 7 | Application Layer | Anwendungsschicht | Schnittstelle für Anwendungen; z.B. HTTP, FTP. |
| 6 | Presentation Layer | Darstellungsschicht | Datenformatierung, Verschlüsselung und Komprimierung. |
| 5 | Session Layer | Sitzungsschicht | Verwaltung von Sitzungen und Verbindungen. |
| 4 | Transport Layer | Transportschicht | Zuverlässige Datenübertragung; z.B. TCP, UDP. |
| 3 | Network Layer | Vermittlungsschicht | Routing und Adressierung; z.B. IP. |
| 2 | Data Link Layer | Sicherungsschicht | Fehlerkorrektur und Zugriff auf das Medium; z.B. Ethernet. |
| 1 | Physical Layer | Bitübertragungsschicht | Übertragung von Bits über physische Medien; z.B. Kabel, WLAN. |

Dieses Modell hilft beim Verständnis von Netzwerkarchitekturen und der Fehlerbehebung. 
Für detaillierte Informationen siehe die offizielle OSI-Spezifikation.

# STRUKTUGRAMM

          jede in den Branches liegende README.md beinhaltet 
          eine Beschreibung der jeweiligen Schicht/ des jeweiligen Layer.

main
--> [README.md](README.md)
--> [COMMIT_HISTORY.md](COMMIT_HISTORY.md)
/01physical-layer
--> README.md
/02data-link-layer
--> README.md
/03network-layer
--> README.md
/04transport-layer
--> README.md
/05session-layer
--> README.md
/06presentation-layer
--> README.md
/07application-layer
--> README.md
