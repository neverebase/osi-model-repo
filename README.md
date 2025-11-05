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

osi-model-repo/
├── main/                    
│   ├── README.md
│   └── [COMMIT_HISTORY.md](COMMIT_HISTORY.md)
├── physical-layer/          
# Physische Schicht
│   └── [physical.txt](physical.txt) 
├── data-link-layer/        # Datenverbindungsschicht
│   └── data-link.txt
├── network-layer/          # Netzwerkschicht
│   └── network.txt
├── transport-layer/        # Transport Layer
│   └── transport.txt
├── session-layer/          # Sessionschicht
│   └── session.txt
├── presentation-layer/     # Präsentationsschicht
│   └── presentation.txt
└── application-layer/      # Anwendungsschicht
    └── application.txt
