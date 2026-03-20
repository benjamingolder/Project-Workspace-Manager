# Project-Workspace-Manager

M365 Self-Service-Anwendung zur automatisierten Verwaltung von SharePoint-Projektarbeitsbereichen.

## Projektbeschreibung

Der Project-Workspace-Manager ermöglicht Projektmanagern die eigenständige Erstellung standardisierter SharePoint-Projektarbeitsbereiche ohne IT-Eingriff. Die Lösung basiert auf Microsoft Power Platform (Power Apps + Power Automate) und ist vollständig in Microsoft 365 integriert.

## Ordnerstruktur

```
Project-Workspace-Manager/
│
├── docs/                          # Dokumentation
│   ├── anforderungen/             # Funktionale & nicht-funktionale Anforderungen
│   ├── architektur/               # Systemarchitektur & Diagramme
│   ├── besprechungen/             # Besprechungsprotokolle
│   └── projektumgebung/           # Projektumgebung (Aufgabe 2)
│
├── src/                           # Quellcode & Entwicklungsartefakte
│   ├── power-apps/                # Power Apps Canvas App Exporte (.msapp)
│   ├── power-automate/            # Power Automate Flow Exporte (.zip)
│   └── sharepoint/                # SharePoint Templates & Skripte
│       ├── templates/             # Site Templates (.xml)
│       ├── scripts/               # PowerShell-Skripte
│       └── listen/                # Listen-Schemas (JSON)
│
├── installation/                  # Installation & Setup
│   ├── checklisten/               # Schritt-für-Schritt Installationschecklisten
│   └── konfiguration/             # Konfigurationsvorlagen
│
├── tests/                         # Tests & Qualitätssicherung
│   ├── uat/                       # User Acceptance Test Protokolle
│   └── testfaelle/                # Testfallbeschreibungen je Anforderung
│
└── Projekt-Workspace-Manager_Projektdokumentation.md   # Hauptprojektdokument
```

## Technologie-Stack

| Komponente | Technologie |
|---|---|
| Frontend / UI | Microsoft Power Apps (Canvas App) |
| Automatisierung | Microsoft Power Automate |
| Backend / Storage | SharePoint Online |
| API | Microsoft Graph API |
| Authentifizierung | Microsoft Entra ID (Azure AD) |
| Versionskontrolle | GitHub |

## Projektdokumentation

Die vollständige Projektdokumentation befindet sich in [`Projekt-Workspace-Manager_Projektdokumentation.md`](./Projekt-Workspace-Manager_Projektdokumentation.md).
