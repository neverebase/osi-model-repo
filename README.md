# OSI-Modell als Git-Repository

Dies ist eine Darstellung des OSI-Modells als Git-Repository, wobei jede Schicht als eigenes Feature-Branch implementiert wurde.

## Branch-Struktur
- Hauptbranch: main
- Feature-Branches für jede OSI-Schicht
- Dokumentation der Kommunikationsprozesse

## Commit-Historie
Siehe [COMMIT_HISTORY.md](COMMIT_HISTORY.md)

## Installation
```bash
git clone https://github.com/neverebase/osi-model-repo.git
```

## Kontributionen
Öffnen Sie einen Pull-Request pro OSI-Schicht.

## Repository-Struktur
#osi-model-repo/
## main/                    
└── README.md
└── [COMMIT_HISTORY.md](COMMIT_HISTORY.md)
## 1. Physische Schicht (Bitübertragung)
physical-layer/          
└── [physical.txt](physical.txt)
## 2. Datenverbindungsschicht 
data-link-layer/        
└── [data-link.txt](data-link.txt)
## 3. Netzwerkschicht
network-layer/          
└── [network.txt](network.txt)
## 4. Transportschicht
transport-layer/        
└── [transport.txt](transport.txt)
## 5. Sitzungsschicht
session-layer/          
└── [session.txt](session.txt)
## 6. Präsentationsschicht
presentation-layer/     
└── [presentation.txt](presentation.txt)
## 7. Anwendungsschicht
application-layer/      
└── [application.txt](application.txt)
