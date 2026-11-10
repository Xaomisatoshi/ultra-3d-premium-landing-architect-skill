# Build-Pfade: No-Code und Code
## Entscheidung
1. Bestehender Builder oder verbundener Dienst? Vorhandene Werkzeuge und Berechtigungen prüfen.
2. Wenn geeigneter No-Code-Builder verfügbar: Komponenten, Layout, Zustände, Breakpoints, Interaktionen und Veröffentlichungscheck dort umsetzen.
3. Wenn Builder keine echte 3D-Szene unterstützt: gehostete Spline-/WebGL-Einbettung nur mit geprüfter Verfügbarkeit und Consent-/Performance-Bewertung; sonst CSS-/Video-/Poster-Fallback.
4. Ohne verbundenen Builder: Builder-neutralen, ausführbaren Schrittplan liefern; wenn Code-Ausführung verfügbar, zusätzlich lauffähiges Projekt generieren.
## No-Code Blueprint
- Seitenbaum mit Sektionen und IDs
- Design-Tokens und Komponentenbibliothek
- Layout pro Breakpoint (mobile/tablet/desktop)
- Animationstrigger, Dauer, Easing, Fallback
- Formularfelder, Validierung, Zielintegration
- SEO-Metadaten, OG-Bild, Analytics-Ereignisse, Consent-Handling
- Test- und Veröffentlichungs-Checkliste
## Code-Fallback
- React/Vite oder Next.js passend zur Laufzeit; Tailwind optional
- Three.js/React Three Fiber nur wenn erforderlich; GSAP optional
- Dateien und Start-/Build-Befehle nennen; Abhängigkeiten versionieren
- Buttons, Links, Formulare müssen tatsächlich funktionieren oder sichtbar als Demo markiert sein
## Tool-Ehrlichkeit
- Tool fehlt: nicht behaupten, im Builder gearbeitet zu haben.
- Deployment und Browser-QA nur als abgeschlossen ausweisen, wenn tatsächlich durchgeführt.
