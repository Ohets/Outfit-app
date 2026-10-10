# Outfit Studio 3D

Eine mobilefreundliche 3D-Outfit-Vorschau direkt im Browser. Die App läuft als statische Website und benötigt keinen Build-Schritt.

## Funktionen

- Interaktive 3D-Ansicht mit Touch-Drehung und Zoom
- Weibliches 3D-Charaktermodell im GLB-Format (smooth casual look, CC0)
- Vier Outfit-Stile und Farbauswahl für die integrierte Fallback-Figur
- Zufällige Outfit-Kombination und Zurücksetzen
- Responsive Oberfläche für Smartphones und Desktop
- Integrierte einfache 3D-Figur als Fallback, falls das externe GLB nicht geladen werden kann

## Starten

Öffne `index.html` in einem Browser mit Internetverbindung. Three.js und OrbitControls werden über jsDelivr geladen. Das weibliche GLB-Modell wird direkt über die Raw-Datei des öffentlichen GitHub-Repositories `Papyszoo/CC0-Public-Domain-Models` geladen.

## Modelllizenz

Das verwendete Modell `smooth_female_casual.glb` stammt aus dem Repository [Papyszoo/CC0-Public-Domain-Models](https://github.com/Papyszoo/CC0-Public-Domain-Models), das die enthaltenen Assets als CC0 1.0/Public Domain ausweist. Modellpfad: https://github.com/Papyszoo/CC0-Public-Domain-Models/tree/main/packs/quaternius-animatedwomen/models/smooth_female_casual. Die GLB-Datei wird aktuell von GitHub geladen und noch nicht als Datei in dieses Outfit-app-Repository kopiert.

## GitHub Pages aktivieren

1. Öffne **Settings → Pages** im Repository.
2. Wähle **Deploy from a branch**.
3. Wähle Branch **main** und Ordner **/(root)**.
4. Speichere die Einstellung. Nach dem Deployment ist die App üblicherweise unter `https://ohets.github.io/Outfit-app/` erreichbar.

## Hinweis

Die 3D-Bibliothek und das GLB-Modell werden online geladen. Für das Modell wird eine Raw-URL von GitHub verwendet. Für den Start ist deshalb eine Internetverbindung erforderlich. Die App speichert keine persönlichen Daten und benötigt kein Konto.
