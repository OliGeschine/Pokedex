# 🎮 Pokédex

Ein interaktiver Pokédex, der die [PokéAPI](https://pokeapi.co/) nutzt, um Informationen über alle 1025 Pokémon anzuzeigen.

![Pokédex Preview](assets/img/favicon.png)

## ✨ Features

- **Vollständige Pokémon-Datenbank**: Alle 1025 Pokémon aus allen Generationen
- **Intelligentes Caching**: Daten werden im LocalStorage gespeichert für schnellere Ladezeiten
- **Live-Suche**: Suche Pokémon nach Namen in Echtzeit
- **Detaillierte Informationen**:
  - Base Stats mit visuellen Balken
  - Größe und Gewicht
  - Fähigkeiten
  - Shiny-Varianten
- **Pokemon Cries**: Klicke auf ein Pokémon im Modal, um seinen Ruf zu hören
- **Farbcodierung**: Jede Karte hat die Farbe des Primär-Typs
- **Navigation**: Wechsle zwischen Pokémon mit Pfeiltasten im Modal
- **Lazy Loading**: Lade mehr Pokémon nach Bedarf
- **Responsive Design**: Funktioniert auf Desktop und Mobile

## 🚀 Live Demo

[Hier Link zu deiner GitHub Pages einfügen]

## 📸 Screenshots

### Hauptansicht
Die Pokémon-Karten zeigen Name, ID, Sprite und Typen.

### Detail-Modal
Detaillierte Statistiken, Informationen und Shiny-Sprites für jedes Pokémon.

## 🛠️ Technologien

- **HTML5**: Semantisches Markup
- **CSS3**: Modernes Styling mit Flexbox
- **Vanilla JavaScript**: Keine Frameworks, nur reines JS
- **PokéAPI**: REST API für Pokémon-Daten
- **LocalStorage**: Client-seitiges Caching

## 📁 Projektstruktur

```
pokedex/
├── index.html              # Haupt-HTML-Datei
├── script.js               # Kernlogik & API-Calls
├── modal.js                # Modal-Funktionalität
├── colors.js               # Typ-Farben-Mapping
├── style.css               # Basis-Styling
├── pokecard.css            # Pokémon-Karten-Styles
├── overlay.css             # Modal-Styles
├── spinner.css             # Loading-Animation
├── media.css               # Responsive Breakpoints
└── assets/
    ├── img/                # Bilder & Icons
    └── gif/                # Animationen
```

## 🎯 Installation & Nutzung

### Voraussetzungen
- Ein moderner Webbrowser
- Internetverbindung (für API-Aufrufe beim ersten Laden)

### Lokale Einrichtung

1. **Repository klonen**
   ```bash
   git clone https://github.com/DEIN-USERNAME/pokedex.git
   cd pokedex
   ```

2. **Öffnen**
   - Öffne `index.html` direkt im Browser
   - Oder nutze einen lokalen Server:
   ```bash
   # Mit Python
   python -m http.server 8000
   
   # Mit Node.js (http-server)
   npx http-server
   ```

3. **Besuchen**
   - Öffne `http://localhost:8000` im Browser

## 💡 Verwendung

1. **Laden**: Beim ersten Besuch werden alle Pokémon von der API geladen (ca. 4 Sekunden)
2. **Durchsuchen**: Scrolle durch die Pokémon-Karten
3. **Suchen**: Gib mindestens 2 Zeichen in die Suchleiste ein
4. **Details ansehen**: Klicke auf eine Karte, um das Detail-Modal zu öffnen
5. **Ruf abspielen**: Klicke auf das Pokémon-Bild im Modal
6. **Navigation**: Nutze die Pfeile im Modal, um zwischen Pokémon zu wechseln
7. **Mehr laden**: Klicke auf "Load More" für weitere Pokémon

## ⚡ Performance-Optimierungen

- **Batch-Loading**: Pokémon werden in Batches von 50 geladen
- **LocalStorage-Cache**: Nach dem ersten Laden werden Daten lokal gespeichert
- **Lazy Loading**: Nur 20 Pokémon werden initial angezeigt
- **Optimierte Datenstruktur**: Nur benötigte Daten werden gecacht

## 🎨 Features im Detail

### Typ-Farben
Jedes Pokémon wird mit der Farbe seines Primär-Typs dargestellt:
- Feuer 🔥: Rot
- Wasser 💧: Blau
- Pflanze 🌿: Grün
- usw.

### Statistik-Balken
Base Stats werden visuell dargestellt mit farbcodierten Balken:
- Rot: Sehr niedrig
- Orange: Niedrig
- Gelb: Durchschnittlich
- Hellgrün: Gut
- Hellblau: Exzellent

## 🤝 Mitwirken

Contributions sind willkommen! Fühle dich frei, Issues zu öffnen oder Pull Requests zu erstellen.

1. Fork das Projekt
2. Erstelle einen Feature-Branch (`git checkout -b feature/AmazingFeature`)
3. Committe deine Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen Pull Request

## 📝 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert.

## 🙏 Danksagungen

- [PokéAPI](https://pokeapi.co/) für die umfassende Pokémon-Datenbank
- Pokémon und alle verwandten Namen sind Marken von Nintendo/Game Freak/Creatures Inc.
- Type-Icons aus der Community

## 📧 Kontakt

Dein Name - [@dein-twitter](https://twitter.com/dein-twitter)

Projekt Link: [https://github.com/DEIN-USERNAME/pokedex](https://github.com/DEIN-USERNAME/pokedex)

---

⭐ Wenn dir dieses Projekt gefällt, gib ihm einen Stern auf GitHub!
