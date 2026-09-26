# 🛡️ VACCheckerService

**Community Anti-Cheat Analysis** — Aufdeckung von Bannumgehungen durch systematische Steam-Profil-Analyse.

🔗 **Live-Seite:** [vaccheckerservice.github.io/vaccheckerservice-web](https://vaccheckerservice.github.io/vaccheckerservice-web/)
📊 **Busted-Datenbank:** [/busted.html](https://vaccheckerservice.github.io/vaccheckerservice-web/busted.html)
📧 **Kontakt:** vacchecker@proton.me
💬 **Discord:** [VACCheckerService](https://discord.com/users/1528840601309548715)

---

## Worum geht's?

Cheater, die einen VAC-Ban, Game-Ban oder FACEIT-Ban kassiert haben, weichen oft einfach auf einen neuen, ungesperrten Account aus. VACCheckerService deckt genau das auf — durch den Abgleich von:

- 🔍 Steam-Profilen & Kontostatus
- 👥 Freundeslisten (aktuell & historisch)
- 🏷️ Gruppenmitgliedschaften
- 🖼️ Avatar-Historien
- 📛 Namens-Verläufen (Persona-Historie)
- 🎮 FACEIT-Profilen & Ban-Historie
- 🌐 Daten von [SteamID.uk](https://steamid.uk/)

Aus diesen Spuren entsteht eine nachvollziehbare Indizienkette, mit der Community-Admin-Teams handeln können.

> ℹ️ Für eine vollständige Namens-Historie über SteamID.uk wird ein **„Silver Patreon"**-Zugang benötigt — ohne diesen werden ältere Namen teilweise nicht angezeigt.

## Ablauf

| Schritt | Was passiert |
|---|---|
| **1. Meldung** | Verdachtsfall wird über das Formular, direkt per Discord oder per Mail eingereicht |
| **2. Analyse** | Freundeslisten, Gruppen, Avatare, Namen & FACEIT-Historie werden gegen bekannte Bans abgeglichen |
| **3. Beweis** | Dokumentierte Indizienkette geht an das Admin-Team zurück |
| **4. Dokumentation** | Bestätigte Fälle werden in der [Busted-Datenbank](https://vaccheckerservice.github.io/vaccheckerservice-web/busted.html) mit vollständiger Indizienkette hinterlegt |

## Über dieses Repository

Dieses Repo enthält die statische Webseite für VACCheckerService, gehostet über **GitHub Pages**:

- `index.html` — Startseite mit Live-Scan-Demo, Ablauf-Erklärung und Melde-Formular
- `busted.html` — durchsuchbare Datenbank aller bestätigten Fälle inkl. vollständiger Indizienkette pro Fall

**Features der Seite:**
- 🌗 Dark, tech-noir Design im Analyst-Terminal-Stil
- 🖥️ Live-Scan-Simulation im Terminal-Look (spielt beim Scrollen erneut ab)
- 🌍 Sprachumschalter Deutsch / Englisch auf beiden Seiten
- 📩 Melde-Formular mit E-Mail (Pflicht), Discord & eigenem Steam-Profil (optional)
- 💬 Direkter Discord-Kontakt-Button
- 📊 Busted-Datenbank mit Suche, Filter (Avatar-/Namens-Match) und aufklappbaren Fall-Details
- 🟢🔴⚪ Status-Kennzeichnung pro Account (Neuer Account / VAC-Bann / Smurf) mit Hover-Tooltip

## Tech-Stack

- Reines HTML/CSS/JavaScript — keine Frameworks, keine Build-Schritte
- Gehostet kostenlos über [GitHub Pages](https://pages.github.com/)
- Formular-Versand via `mailto:`

## Kontakt & Meldungen

Verdachtsfall melden? Über die [Live-Seite](https://vaccheckerservice.github.io/vaccheckerservice-web/#report), direkt per [Discord](https://discord.com/users/1528840601309548715) oder per Mail an **vacchecker@proton.me**.

---

<sub>© VACCheckerService — Community Anti-Cheat Analysis</sub>
