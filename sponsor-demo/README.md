# Sponsor-Banner Demo Version

Diese Demo-Version der Website zeigt verschiedene Möglichkeiten, wie Sponsor-Banner integriert werden können.

## Was ist neu in dieser Demo?

Diese Version enthält **4 verschiedene Sponsor-Banner-Optionen**:

### 1. **Horizontaler Banner-Strip (unter Navigation)**
- Position: Direkt unter der Hauptnavigation
- Stil: Gelb-goldener Gradient mit Sponsor-Logos nebeneinander
- Vorteil: Sehr prominent, sofort sichtbar
- Nachteil: Nimmt wertvollen Platz über dem Hero-Bereich ein

### 2. **Dedizierte Sponsoren-Sektion**
- Position: Zwischen "Über uns" und "CTA Strip"
- Stil: Große Karten für Hauptsponsoren, kleinere Logo-Reihe für Partner
- Vorteil: Professionelle Präsentation, zeigt Wertschätzung
- Nachteil: Nimmt eine ganze Sektion ein

### 3. **Sidebar-Banner**
- Position: Als dritte Kachel neben den Produktionen
- Stil: Rotes Sparkasse-Banner mit gleicher Größe wie Produktionskacheln
- Vorteil: Integriert sich nahtlos, wirkt nicht aufdringlich
- Nachteil: Nimmt Platz einer Produktionskachel ein

### 4. **Footer-Anerkennung**
- Position: Im Footer über dem Copyright
- Stil: Dezente Logo-Reihe
- Vorteil: Dezent, stört nicht
- Nachteil: Weniger prominent

## Verwendete Technologien

- Alle Banner verwenden **Tailwind CSS** (bereits im Projekt vorhanden)
- **Custom SVG-Logos** mit professionellem Design:
  - Sparkasse Unna: Rotes "S" Logo im Sparkassen-Stil
  - Stadt Holzwickede: Wappen mit Schild in Blau/Gold
  - Kulturförderung NRW: Grünes Logo mit kulturellen Elementen
  - Partner-Logos: Individuelle Business-Designs
- **Responsive Design** für Mobile und Desktop
- **Hover-Effekte** und Animationen für bessere Interaktivität

## Anpassungen für Produktiveinsatz

Für den echten Einsatz sollten:

1. SVG-Platzhalter durch echte Sponsor-Logos ersetzt werden
2. Die `#`-Links durch echte Sponsor-URLs ersetzt werden
3. Die Beispielnamen durch echte Sponsoren ersetzt werden
4. Entscheidung getroffen werden, welche Variante(n) verwendet werden sollen
5. Optional: Animation/Rotation für mehrere Sponsoren hinzufügen

## Dateien

Alle HTML-Dateien aus dem Hauptverzeichnis wurden in diesen Ordner kopiert. Sponsor-Banner wurden hinzugefügt zu:

- **index.html** - Alle 4 Banner-Optionen demonstriert
- **production_detail.html** (John & Jen) - Produktions-spezifische Banner mit Sparkasse Unna als Hauptsponsor
- **production_detail_kleiner_tag.html** (Der kleine Tag) - Produktions-spezifische Banner mit Kulturförderung NRW als Hauptförderer

### Produktionsseiten-Banner:

Auf den Produktionsdetailseiten wurden 2 zusätzliche Integrationen demonstriert:

1. **Banner direkt unter Navigation**: Zeigt den Hauptsponsor der jeweiligen Produktion
   - John & Jen: Sparkasse Unna (rotes Banner)
   - Der kleine Tag: Kulturförderung NRW (grünes Banner)

2. **Sponsor-Sektion vor dem CTA**: Zeigt alle unterstützenden Partner der Produktion mit verschiedenen Größen (Haupt- und Nebensponsor)

## Demo ansehen

Öffnen Sie einfach `sponsor-demo/index.html` in einem Browser, um die verschiedenen Banner-Optionen zu sehen.
