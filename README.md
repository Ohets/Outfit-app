# Outfit Studio 3D

Eine mobilefreundliche 3D-Outfit-Vorschau direkt im Browser. Die App läuft als statische Website und benötigt keinen Build-Schritt.

## Funktionen

- Interaktive 3D-Ansicht mit Touch-Drehung und Zoom
- Weibliches 3D-Charaktermodell im GLB-Format (Priya, sportlicher Look)
- Vier Outfit-Stile und Farbauswahl für die integrierte Fallback-Figur
- Zufällige Outfit-Kombination und Zurücksetzen
- Responsive Oberfläche für Smartphones und Desktop
- Integrierte einfache 3D-Figur als Fallback, falls das externe GLB nicht geladen werden kann

## Starten

Öffne `index.html` in einem Browser mit Internetverbindung. Three.js und OrbitControls werden über jsDelivr geladen. Das weibliche GLB-Modell wird von Innerscene geladen.

## Modelllizenz

Das verwendete Modell „Priya - 3D Person, Woman Athletic walking“ ist laut Innerscene unter CC0/Public Domain veröffentlicht und darf auch kommerziell genutzt werden. Modellquelle: https://www.innerscene.com/tools/library/3d-parts/priya-3d-person-woman-athletic-walking-bf61042b

## GitHub Pages aktivieren

1. Öffne **Settings → Pages** im Repository.
2. Wähle **Deploy from a branch**.
3. Wähle Branch **main** und Ordner **/(root)**.
4. Speichere die Einstellung. Nach dem Deployment ist die App üblicherweise unter `https://ohets.github.io/Outfit-app/` erreichbar.

## Hinweis

Die 3D-Bibliothek und das GLB-Modell werden online geladen. Für den Start ist deshalb eine Internetverbindung erforderlich. Die App speichert keine persönlichen Daten und benötigt kein Konto.
