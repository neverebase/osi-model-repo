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

# Repository-Struktur
## osi-model-repo/
## main/                    
└── README.md
└── [COMMIT_HISTORY.md](COMMIT_HISTORY.md)
## 1. Physische Schicht (Bitübertragung)
01physical-layer/          
└── [physical.txt](physical.txt)
## 2. Datenverbindungsschicht 
02data-link-layer/        
└── [data-link.txt](data-link.txt)
## 3. Netzwerkschicht
03network-layer/          
└── [network.txt](network.txt)
## 4. Transportschicht
04transport-layer/        
└── [transport.txt](transport.txt)
## 5. Sitzungsschicht
05session-layer/          
└── [session.txt](session.txt)
## 6. Präsentationsschicht
06presentation-layer/     
└── [presentation.txt](presentation.txt)
## 7. Anwendungsschicht
07application-layer/      
└── [application.txt](application.txt)
