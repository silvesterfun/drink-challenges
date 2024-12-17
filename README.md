
# 🎉 Drink Challenges - Silvester Fun

**Drink Challenges** ist ein Partyspiel, das zufällige Aufgaben anzeigt. Perfekt für deine nächste Feier, sei es Silvester oder jede andere Gelegenheit, bei der Spaß und gute Stimmung nicht fehlen dürfen! 🥳

📢 **Live Demo**: [Drink Challenges](https://silvesterfun.github.io/drink-challenges/)

---


## 🚀 Features

- 🎲 **Zufällige Aufgaben**: Lasse dir spannende Aufgaben zufällig anzeigen.
- ⏱ **Timer für Herausforderungen**: Einige Aufgaben haben einen Timer – schaffst du es rechtzeitig?
- 🎨 **Modernes Design**: Ein ansprechendes, modernes Design mit klaren Buttons und Animationen.
- 🌐 **Einfacher Zugang**: Keine Installation erforderlich, direkt über den Browser spielbar.

---

## 📂 Projektstruktur

```plaintext
drink-challenges/
│
├── index.html       # Hauptdatei mit dem Spiel-Interface und der Logik
├── tasks.json       # JSON-Datei mit der Liste aller Aufgaben und Timern
└── README.md        # Dokumentation des Projekts
```

---

## 🔧 Installation & Lokales Testen

Falls du das Projekt lokal starten möchtest:

1. **Repository klonen**:
   ```bash
   git clone https://github.com/silvesterfun/drink-challenges.git
   cd drink-challenges
   ```

2. **Spiel starten**:
   Öffne die Datei `index.html` direkt in einem Browser.

3. **JSON-Datei bearbeiten**:
   Die Aufgaben befinden sich in der Datei `tasks.json`. Jede Aufgabe folgt diesem Format:
   ```json
   {
       "title": "Aufgabentitel",
       "task": "Beschreibung der Aufgabe",
       "timer": 60
   }
   ```

   - **`title`**: Titel der Aufgabe.
   - **`task`**: Beschreibung der Aufgabe.
   - **`timer`** *(optional)*: Zeitlimit in **Sekunden**. Wenn das Feld nicht vorhanden ist, wird kein Timer angezeigt.


🎉 Viel Spaß mit **Drink Challenges**! Prost und gute Unterhaltung! 🍻

```


