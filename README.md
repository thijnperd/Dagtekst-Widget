# 📖 Dagelijkse Tekst — Scriptable Widget Builder

Een visuele widget-builder waarmee je een prachtige **Dagelijkse Tekst**-widget voor je iPhone kunt maken, volledig gepersonaliseerd met eigen kleuren, lettertype en ornamenten.

> Gebouwd voor gebruik met de [Scriptable](https://scriptable.app)-app op iOS/iPadOS.

---

## ✨ Functies

- 🎨 **Preset thema's** — kies uit meerdere kant-en-klare stijlen
- 🌈 **Volledige kleurcontrole** — licht- én donkermodus apart instelbaar
- 🔤 **Lettertypekeuze** — meer dan 20 iOS-lettertypen
- ✦ **Ornamentpicker** — decoratieve tekens voor boven en bij de datum
- 📐 **Maat & padding** — instelbaar voor kleine, middelgrote en grote widgets
- 📱 **Live preview** — bekijk het resultaat direct, ook in een telefoonsimulatie
- 💾 **Exporteer als .js-bestand** — klaar om in Scriptable te plakken
- 📲 **Mobiel-vriendelijk** — werkt op telefoon én desktop

---

## 🚀 Aan de slag

### Stap 1 — Download Scriptable

Installeer de gratis **Scriptable**-app op je iPhone of iPad:

[![Download in App Store](https://img.shields.io/badge/App_Store-Scriptable-0a84ff?style=flat&logo=apple&logoColor=white)](https://apps.apple.com/app/scriptable/id1405459188)

> Scriptable is een gratis app waarmee je JavaScript-scripts kunt uitvoeren als iOS-widget.

---

### Stap 2 — Open de Widget Builder

Open het bestand `widget-builder.html` in je browser (Safari, Chrome of Firefox).  
Geen installatie of server nodig — het werkt volledig lokaal.

---

### Stap 3 — Pas het thema aan

Gebruik de tabbladen in het linkerpaneel om je widget in te stellen:

| Tabblad | Wat je kunt instellen |
|---|---|
| **Thema's** | Kies een kant-en-klaar kleurthema |
| **Kleuren** | Stel achtergrond, tekst en ornamentkleur in voor licht en donker |
| **Tekst** | Lettertype, -grootte en regelafstand |
| **Ornament** | Decoratief teken bovenaan en bij de datum |
| **Overig** | Taal (wtLocale), rsconf, padding, Scriptable-icon |

Rechts zie je een **live preview**. Schakel tussen:
- **Widget** — de widget op ware grootte
- **Telefoon** — simulatie van hoe de widget eruitziet op je beginscherm

---

### Stap 4 — Exporteer het script

Klik op de knop **Exporteer Script** rechtsboven.  
Je browser downloadt automatisch een bestand genaamd `DagelijkseTekst.js`.

Of: ga naar het tabblad **Script** (op mobiel) of de codebalk (op desktop) en klik op **Kopieer** om de code naar je klembord te kopiëren.

---

### Stap 5 — Plak in Scriptable

1. Open **Scriptable** op je iPhone
2. Tik op **+** rechtsboven om een nieuw script te maken
3. Plak de gekopieerde code (of importeer het `.js`-bestand via de Bestanden-app)
4. Geef het script een naam, bijv. `DagelijkseTekst`
5. Tik op **Done** / sla op

---

### Stap 6 — Voeg de widget toe aan je beginscherm

1. Houd je beginscherm ingedrukt totdat de icoontjes beginnen te wiebelen
2. Tik op **+** (linksboven op iOS 14+)
3. Zoek naar **Scriptable**
4. Kies de gewenste widgetgrootte (klein, medium of groot)
5. Tik op **Widget toevoegen**
6. Tik op de widget → selecteer jouw script (`DagelijkseTekst`)
7. Tik op **Gereed**

De widget toont nu elke dag automatisch de dagelijkse tekst van [JW.org](https://www.jw.org).

---

## ⚙️ Geavanceerde instellingen

### Taal wijzigen

In het tabblad **Overig** kun je de `wtLocale`-code instellen:

| Taal | Code |
|---|---|
| Nederlands | `o` |
| Engels | `e` |
| Duits | `g` |
| Frans | `f` |
| Spaans | `s` |
| Portugees | `p` |

### rsconf

De `rsconf`-waarde bepaalt van welke JW.org-regio de tekst wordt opgehaald. De standaardwaarde `18` werkt voor de meeste gebruikers. Pas dit alleen aan als je teksten niet laden.

---

## 📁 Bestanden

```
widget-builder.html   ← Open dit in je browser
README.md             ← Dit bestand
```

---

## 🛠️ Technische details

- Het gegenereerde script haalt de dagelijkse tekst op via de [WOL API van JW.org](https://wol.jw.org)
- Geen externe afhankelijkheden — puur Scriptable JS
- Werkt met alle drie widgetformaten: klein (small), medium en groot (large)
- Ondersteunt automatisch licht- en donkermodus op basis van iOS-instellingen

---

## 🙏 Credits

Gebouwd met de [Scriptable](https://scriptable.app)-app van Simon Støvring.  
Dagelijkse teksten afkomstig van [JW.org](https://www.jw.org).

---

## 📄 Licentie

Vrij te gebruiken voor persoonlijk gebruik.
