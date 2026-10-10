# Outfit Studio 3D

Eine mobilefreundliche 3D-Outfit-Vorschau direkt im Browser. Die App läuft als statische Website und benötigt keinen Build-Schritt.

## Funktionen

- Interaktive 3D-Ansicht mit Touch-Drehung und Zoom
- Vier lokal gespeicherte weibliche 3D-Charaktermodelle im GLB-Format: Casual, Kleid, Alternative und Tanktop (CC0)
- Umschalten zwischen vier weiblichen Modellen und vier Outfit-Stilen
- Farbauswahl für die integrierte Fallback-Figur
- Zufällige Outfit-Kombination und Zurücksetzen
- Responsive Oberfläche für Smartphones und Desktop
- Integrierte einfache 3D-Figur als Fallback, falls das lokale GLB nicht geladen werden kann

## Starten

Öffne die Website über GitHub Pages oder einen lokalen Webserver. Three.js und OrbitControls werden über jsDelivr geladen. Die vier weiblichen GLB-Modelle liegen im Ordner `models/` (`smooth_female_casual.glb`, `female_dress.glb`, `female_alternative.glb` und `female_tank_top.glb`). Du kannst sie über die Modellauswahl in der App wechseln.

## Modelllizenz

Das verwendete Modell `smooth_female_casual.glb` stammt aus dem Repository [Papyszoo/CC0-Public-Domain-Models](https://github.com/Papyszoo/CC0-Public-Domain-Models), das die enthaltenen Assets als CC0 1.0/Public Domain ausweist. Modellpfad: https://github.com/Papyszoo/CC0-Public-Domain-Models/tree/main/packs/quaternius-animatedwomen/models/smooth_female_casual. Die GLB-Dateien liegen in diesem Projekt im Ordner `models/`.

## GitHub Pages aktivieren

1. Öffne **Settings → Pages** im Repository.
2. Wähle **Deploy from a branch**.
3. Wähle Branch **main** und Ordner **/(root)**.
4. Speichere die Einstellung. Nach dem Deployment ist die App üblicherweise unter `https://ohets.github.io/Outfit-app/` erreichbar.

## Hinweis

Die 3D-Bibliothek wird online über jsDelivr geladen. Alle vier GLB-Dateien sind im Repository enthalten; für Three.js und OrbitControls wird weiterhin eine Internetverbindung benötigt. Die App speichert keine persönlichen Daten und benötigt kein Konto.
