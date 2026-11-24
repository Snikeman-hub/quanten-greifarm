# 🕹️ Quanten-Greifarm Arcade

Ein physikbasiertes Sci-Fi-Arcade-Greifarmspiel für den Browser mit **3 Quanten-Fähigkeiten**, **Kombo-Multiplikator**, **Spezial-Kernen & Gefahren**, **Shop-Upgrades** und **Web Audio API Soundeffekten**.

## 🌐 Live spielen
* https://greifarm.thetimo.de
* https://greifarm.der-timoo.de

---

## ✨ Features & Spielmechanik (Aktueller Stand: Phase 2)

### ⚡ 3 Quanten-Fähigkeiten („Der Kniff“)
Jede Aktivierung kostet **35 Quanten-Energie** (von max. 100):
* **🧲 Magnet-Impuls (`[1]`):** Sendet eine elektromagnetische Impulswelle aus, die metallische und schwere Objekte (wie Gold-Krone, Quanten-Kristall, Energie-Zellen oder Stör-Minen) zur Kralle zieht.
* **🔬 Schrumpf-Strahl (`[2]`):** Projiziert einen Laser-Kegel unter den Greifer und reduziert Radius ($\times 0.65$) sowie Gewicht ($\times 0.5$) aller getroffenen Objekte.
* **⏱️ Zeit-Stasis (`[3]`):** Friert alle Objekte im Automaten für exakt **5 Sekunden** in der Luft ein – ideal für schwebende Helium-Ballons oder rutschige Quanten-Kapseln.

### 🔥 Kombo-System & Spezial-Objekte
* **Kombo-Multiplikator (`x1.0` bis `x2.5`):** Jeder erfolgreiche Fang in Folge steigert den Münz-Multiplikator um `+0.2x`. Greifst du ins Leere, rutscht ein Objekt ab oder triffst du eine Stör-Mine, wird die Serie zurückgesetzt.
* **⚡ Energie-Zelle:** Ein magnetischer Energiekern. Beim Greifen lädt er die Quanten-Energie sofort wieder auf **100 %** auf (`+40 🪙`).
* **💣 Stör-Mine (Hazard):** Vorsicht vor dem pulsierenden Gefahrenring! Beim Greifen detoniert ein EMP, der deine Energie auf `0 %` setzt und die Steuerung für **4 Sekunden invertiert**. Räume sie stattdessen gezielt mit dem *Magnet-Impuls* beiseite.
* **🎁 Mysteriöse Quanten-Kapsel:** Sehr leicht, aber extrem glatt (hohes Abrutsch-Risiko ohne *Zeit-Stasis* oder *Schrumpf-Strahl*). Enthält zufälligen Bonus-Loot (Münz-Jackpot, volle Energie oder fehlende Sammlungs-Baupläne).

### 🎨 Arcade-UI & Physik-Simulation
* **2D-Kreisphysik:** Gewicht, Reibung, Auftrieb (Helium-Ballon), gegenseitige Kollisionsabstoßung und interaktiver Auswurf-Schacht.
* **Diegetic UI:** Ziel-Laser unter der Kralle, integrierter Energie-Ladebogen auf der Greifer-Nabe sowie dynamische Spannungs-Farben (Grün → Gelb → blinkendes Rot mit Funkenflug bei Überlastung).
* **🛠️ Quanten-Werkstatt (Shop):** Verbessere *Greifkraft*, *Motor-Tempo* und *Kniff-Batterie* dauerhaft mit verdienten Münzen.
* **🔊 Web Audio Synthesizer:** Dynamisch generierte Retro-Soundeffekte komplett ohne externe Audiodateien.

---

## 🎮 Steuerung
* **Bewegen:** `◄` / `►` oder `A` / `D` (bzw. Touch-Buttons gedrückt halten)
* **Greifarm absenken:** `Leertaste` oder `▼`
* **Aktiven Kniff auslösen:** `E` oder `Shift`
* **Fähigkeit wechseln:** `1` (Magnet), `2` (Schrumpfen), `3` (Stasis)

---

## 🗺️ Entwicklungs-Roadmap (Nächste Phasen)

* [x] **Phase 1 – Visual & UI Polish:** Arcade-Kabinett-Design, schwebendes Glas-HUD, Diegetic Greifer-Anzeigen, Partikel- & Laser-Effekte sowie Hotkey-Steuerung.
* [x] **Phase 2 – Neue Objekte & Kombo-System:** Serien-Multiplikator (`x1.0`–`x2.5`), *⚡ Energie-Zelle*, *💣 Stör-Mine* (EMP-Hazard) und *🎁 Quanten-Kapsel* mit Zufalls-Loot.
* [ ] **Phase 3 – Werkstatt-Erweiterung, Aufträge & Sammlungs-Sets:**
  * Neue Upgrades im Shop (*📡 Ziel-Laser-Visier* mit Wirkungsradius-Anzeige und *🧲 Krallen-Reibung* gegen Abrutschen).
  * Dynamische Runden-Aufträge (z. B. *„Fange 2 Helium-Ballons während einer Zeit-Stasis“*) für Bonus-Münzen.
  * Passive Set-Boni beim Vervollständigen bestimmter Preis-Kategorien und freischaltbare Greifarm-Skins.
* [ ] **Phase 4 – Puzzle- & Herausforderungs-Modus:**
  * Eigenständiger Spielmodus mit **10 handgebauten Taktik-Levels**, begrenzten Greifversuchen und kniffligen Physik-Rätseln (z. B. vergrabene Quanten-Kristalle unter Stör-Minen freilegen).
