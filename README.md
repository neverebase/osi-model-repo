# OSI-Modell als Git-Repository

Dies ist eine Darstellung des OSI-Modells als Git-Repository, wobei jede Schicht als eigenes Feature-Branch fungiert.

## Schichtenstruktur

1. [Physische Schicht](docs/physical-layer.md)
2. [Datenverbindungsschicht](docs/data-link-layer.md)
3. [Netzwerkschicht](docs/network-layer.md)
4. [Transport Layer](docs/transport-layer.md)
5. [Sessionschicht](docs/session-layer.md)
6. [Präsentationsschicht](docs/presentation-layer.md)
7. [Anwendungsschicht](docs/application-layer.md)

## Branch-Strategie
- Hauptbranch: `main`
- Feature-Branches: Eine pro OSI-Schicht
- Commit-Nachrichten enthalten die spezifischen Funktionen jeder Sch icht
