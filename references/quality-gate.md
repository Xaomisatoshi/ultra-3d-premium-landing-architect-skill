# Release Quality Gate
## Prüffelder
| Bereich | Akzeptanzkriterium |
|---|---|
| Ziel | Ein primäres Conversion-Ziel und klare CTA |
| Inhalt | Keine erfundenen Claims, Quellen für kritische Behauptungen |
| Visuell | Eigenständige Art Direction, saubere Hierarchie, responsive Layouts |
| Funktion | CTA, Navigation, Formulare, Zustände und Links getestet |
| 3D | Nutzenbezug, stabiler Fallback, keine Blockade der Bedienung |
| Accessibility | Tastatur, Fokus, Labels, Alt-Texte, Kontrast, Reduced Motion |
| Performance | Bild-/Asset-Optimierung, Lazy Loading, mobile Budgetprüfung |
| SEO | Title, Description, semantische Überschriften, Social Preview |
| Datenschutz | Keine unerlaubten Tracker; Consent falls erforderlich |
| Betrieb | Fehlermeldungen, Browser-Kompatibilität, Deploymentstatus |
## Befundformat
Schweregrad (BLOCKER/HOCH/MITTEL/NIEDRIG) | Befund | Evidenz | Auswirkung | minimale Korrektur | Status.
Status: BESTANDEN, FEHLER, NICHT PRÜFBAR.
Freigabe: STOP bei Blockern; MIT AUFLAGEN bei nichtkritischen Lücken; RELEASE nur wenn kritische Kriterien tatsächlich getestet wurden.
## Zielwerte
Lighthouse/Core Web Vitals nicht als bestanden melden, solange keine echte Messung vorliegt. Dokumentiere Messumgebung, Gerät, Netzwerk und Zeitpunkt.
## Stressfälle
Nur ein Satz Input; widersprüchliche Markenwünsche; fehlende Bilder; WebGL deaktiviert; langsames Mobilgerät; Tastaturnutzung; reduzierte Bewegung; Formularfehler; fehlender Builder-Zugang.
