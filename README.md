# Versuch animierte Banner

Dieses Repository enthält einen interaktiven Banner mit animierten Elementen, die mithilfe von [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/) erstellt wurden. Ziel des Projekts ist es, verschiedene Animationstechniken auszuprobieren, wie sie für Web-Interfaces, Werbebanner oder interaktive Designs verwendet werden können.

## Banner 01 Link

[https://banner-01.netlify.app]

## 🚀 Funktionen

- **Sequenzielle Animationen**: Die Elemente animieren sich nacheinander automatisch beim Laden der Seite.
- **Dynamische Wiederholungen**: Animationen werden alle 5 Sekunden wiederholt.
- **Individuelle Animationen pro Element**:
  - **Element 1**: Animiert sich mit dem Effekt [easeInSine](https://easings.net/#easeInSine).
  - **Element 2**: Vergrößert sich und verschiebt sich mit [easeInOutBack](https://easings.net/#easeInOutBack).
  - **Element 3**: Springt mit [easeOutBounce](https://easings.net/#easeOutBounce).
- **Responsive Bilder oder Hintergrundbilder**: Elemente können durch PNG-Bilder ersetzt werden.

## 🛠️ Technologien

- **HTML5**: Struktur des Banners.
- **CSS3**: Styling und Layout der Elemente.
- **GSAP**: Hochperformante Animationsbibliothek.

## 📂 Dateien im Repository

- `index.html`: Hauptdatei, die die Animationen und das Layout enthält.
- `style.css`: Enthält das Styling für die Banner-Elemente.
- `script.js`: GSAP-Animationen und deren Sequenzen.
- **Bilder**: Platzhalter für die PNG-Dateien, die in den animierten Containern verwendet werden können.

## 📖 Ressourcen

Um mehr über die verwendeten Animationstechniken und Easing-Funktionen zu erfahren, empfehlen wir folgende Ressourcen:

- [Jonas.io Resources](https://jonas.io/resources/): Eine umfangreiche Sammlung von Ressourcen für Entwickler, darunter Animationstools und Design-Tutorials.
- [Easings.net](https://easings.net/): Eine visuelle Darstellung verschiedener Easing-Funktionen, die Animationen natürlicher und dynamischer gestalten.

## 🖼️ Vorschau

Eine Vorschau der animierten Banner findest du direkt im Browser, indem du die Datei `index.html` öffnest.

## 🔧 Anpassung

### Bilder einfügen

Ersetze die Platzhalter-Bilder durch deine eigenen PNG-Dateien:

```html
<img src="dein-bild.png" alt="Beschreibung des Bildes" />
```
