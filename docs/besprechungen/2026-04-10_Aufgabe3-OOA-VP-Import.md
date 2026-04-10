# Besprechung – 2026-04-10 Aufgabe 3 OOA / VP Import

**Datum:** 2026-04-10
**Teilnehmer:** Benjamin Golder, Dennis Eberhard
**Dauer:** 1h 5min
**Format:** Remote (Teams-Anruf)

---

## Traktanden
1. Aufgabe 3 OOA – Stand und Vorgehen
2. UML-Diagramme in Visual Paradigm importieren
3. Arbeitsaufteilung für Diagramme
4. Diverses (Semesterprüfung, GNS3-Auftrag, nächste Lektion)

---

## Besprochenes

### Aufgabe 3 OOA – Stand
Claude hat das Fachklassenmodell, das Zustandsmodell und das Glossar vollständig erarbeitet und in GitHub unter `docs/analyse/` abgelegt (MD-Dateien, PNG-Exporte). Benjamin hat den Stand via Bildschirmfreigabe gezeigt. Dennis hat die Dokumentation als Grundlage für die VP-Diagramme verwendet.

### UML-Diagramme in Visual Paradigm importieren
Es wurde intensiv versucht, die generierten Diagramme in Visual Paradigm Community Edition zu importieren:

- **PlantUML-Import:** Nicht verfügbar in der Community Edition (Feature hinter Paywall)
- **XMI-Import:** Technisch vorhanden, aber 0 Elemente importiert – Format nicht kompatibel
- **XML-Import (umbenannte XMI):** Ebenfalls 0 Elemente importiert
- **draw.io / diagrams.net:** PlantUML-Import versucht, hat nicht wie erwartet funktioniert

**Fazit:** Import in VP Community ist mit den generierten Dateien nicht möglich. Die Diagramme müssen manuell in VP nachgebaut werden.

### Arbeitsaufteilung für Diagramme
Da der Import nicht funktioniert, zeichnet jeder ein Diagramm manuell in Visual Paradigm nach. Als Referenz dienen die PNG-Vorschau und die MD-Beschreibungen auf GitHub.

### Diverses
- **Claude Sonnet vs. Opus:** Empfehlung, Sonnet für die meisten Aufgaben zu nutzen (günstiger, schneller, ausreichend). Opus nur für sehr komplexe Tasks.
- **Semesterprüfung SE1:** Dienstag im Juni (zweitletzter Unterrichtstag) – schriftlich mit Stift/Papier, Programmieraufgaben.
- **GNS3-Auftrag (Dani):** Abgabetermin unklar – Dennis fragt nach. Dennis: Firewall & VPN. Benjamin: Cloud.
- **Nächste Lektion:** Morgen (2026-04-11) remote/online.

---

## Beschlüsse
- Diagramme werden manuell in Visual Paradigm nachgebaut (kein Import)
- Arbeitsaufteilung: Benjamin → Fachklassenmodell, Dennis → Zustandsmodell
- Finale VP-Diagramme werden anschliessend in `docs/analyse/` hochgeladen
- Morgen in der Lektion: Diagramme vorzeigen und Feedback vom Dozenten einholen

---

## Offene Punkte / Folgeaufgaben

| Aufgabe | Verantwortlich | Fällig bis |
|---|---|---|
| Fachklassenmodell in VP nachzeichnen | Benjamin | 2026-04-11 |
| Zustandsmodell in VP nachzeichnen | Dennis | 2026-04-11 |
| VP-Diagramme in `docs/analyse/` hochladen | Benjamin & Dennis | 2026-04-11 |
| Abgabetermin GNS3-Auftrag klären | Dennis | 2026-04-11 |
