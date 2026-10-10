# Outfit Studio 3D

Eine mobilefreundliche 3D-Outfit-Vorschau direkt im Browser. Die App läuft als statische Website und benötigt keinen Build-Schritt.

## Funktionen

- Interaktive 3D-Ansicht mit Touch-Drehung und Zoom
- Vier Outfit-Stile: Sport, Casual, Elegant und Streetwear
- Separate Farbauswahl für Oberteil und Hose
- Zufällige Outfit-Kombination und Zurücksetzen
- Responsive Oberfläche für Smartphones und Desktop
- Prozedural erzeugte 3D-Figur; keine externe Modelldatei erforderlich

## Starten

Öffne `index.html` in einem Browser mit Internetverbindung. Three.js und OrbitControls werden über jsDelivr geladen.

## GitHub Pages aktivieren

1. Öffne **Settings → Pages** im Repository.
2. Wähle **Deploy from a branch**.
3. Wähle Branch **main** und Ordner **/(root)**.
4. Speichere die Einstellung. Nach dem Deployment ist die App üblicherweise unter `https://ohets.github.io/Outfit-app/` erreichbar.

## Hinweis

Die 3D-Bibliothek wird von einem CDN geladen. Für den ersten Start ist deshalb eine Internetverbindung erforderlich. Die App speichert keine persönlichen Daten und benötigt kein Konto.
