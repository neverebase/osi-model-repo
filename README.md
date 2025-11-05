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

#osi-model-repo/
## main/                    
└──README.md
└──[COMMIT_HISTORY.md](COMMIT_HISTORY.md)
## Physische Schicht 
|physical-layer/          
└── [physical.txt](physical.txt)
## Datenverbindungsschicht 
|data-link-layer/        
└── [data-link.txt](data-link.txt)
## Netzwerkschicht
|network-layer/          
└── [network.txt](network.txt)
## Transport Layer
|transport-layer/        
└── [transport.txt](transport.txt)
## Sessionschicht
|session-layer/          
└── [session.txt](session.txt)
## Präsentationsschicht
|presentation-layer/     
└── [presentation txt](presentation.Txt)
## Anwendungsschicht
|application-layer/      
└── [application.Txt](application.Txt) 
