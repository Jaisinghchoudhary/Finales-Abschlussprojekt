# 🎮 Abschlussprojekt – League of Legends: Gaming Analytics & Machine Learning

Dieses Projekt wurde im Rahmen der **finalen Abschlussprüfung der Data SmartPoint Academy** erstellt.  
Ziel war es, mithilfe von **Python, Datenanalyse und Machine Learning** spielbezogene Daten aus **League of Legends** zu untersuchen, zu visualisieren und prädiktive Zusammenhänge zwischen Spielern, Champions und Matchausgängen zu erkennen.
---

## 📊 Datensätze

Insgesamt wurden **vier separate Datensätze** aus dem Gaming-Bereich (ähnlich wie in League of Legends) analysiert:

- Spieler- & Matchdaten (`Datensatz 1 Games.ipynb`)  
- Champions – Set 1 (`Datensatz 2 Champion1.ipynb`)  
- Champions – Set 2 (`Datensatz 3 Champion2.ipynb`)  
- Summoner-Spells (`Datensatz 4 Summoner_Spell.ipynb`)  

Die Daten enthalten u. a.:

- Spielerstatistiken (Kills, Assists, Wins, Damage, Gold etc.)  
- Informationen zu Champions und ihren Eigenschaften  
- Verwendete Spells und deren Einfluss  
- Teamzugehörigkeit, Matchverlauf und Interaktionen  

---

## 🔧 Datenbereinigung & Vorbereitung

Im Vorfeld der Visualisierung und Modellierung wurden die Daten aufbereitet:

- Vereinheitlichung von Spaltennamen und Datentypen  
- Identifikation und Entfernung von Duplikaten  
- Umgang mit fehlenden Werten  
- Feature Engineering: Zusammenführung von Champion-Datensätzen  
- Vorbereitung der Daten für ML-Zwecke (Label-Encoding, Selektion, Scaling etc.)

Diese Schritte erfolgten über die Jupyter-Notebooks und sind vollständig nachvollziehbar dokumentiert.

---

## 📈 Visualisierung & Analyse

Für die erste explorative Analyse wurden klassische Visualisierungen eingesetzt:

- Heatmaps zur Korrelation zwischen Spielvariablen  
- Boxplots zur Verteilung von Spielerstatistiken  
- Balkendiagramme zu Teamvergleichen (Gold, Schaden, etc.)  
- Visualisierungen des Spell-Einsatzes  
- Siege vs. Niederlagen im Zusammenhang mit bestimmten Champions oder Spielweisen  

Diese Analysen finden sich gebündelt in `Standardvisualisierungen.ipynb` sowie in den jeweiligen Champion-/Spell-Notebooks.

---

## 🤖 Machine Learning

Der zweite Teil des Projekts drehte sich um **Vorhersagemodelle** auf Basis der vorbereiteten Spieldaten.  
Ziel war es, Spielausgänge (Win/Loss) oder Spielercluster basierend auf Ingame-Performance vorherzusagen.

Umgesetzt wurden:

- **K-Means Clustering** zur Gruppierung von Spielerprofilen  
- **Random Forest Classifier** zur Vorhersage von Siegen  
- Datenvorbereitung in `ML_Vorbereitungen.ipynb`  
- Visualisierungen der ML-Ergebnisse in `ML_Visualisierungen.ipynb`  
- Bewertung der Modelle mit Accuracy und Confusion-Matrix  

---

## 🧠 Erkenntnisse

- **Gold- und Schadenswerte** sind starke Prädiktoren für den Spielsieg  
- Einige Champions dominieren klar in bestimmten Spielkontexten  
- **Bestimmte Spells** sind auffällig häufig bei siegreichen Teams im Einsatz  
- Spieler lassen sich anhand ihrer Stats sinnvoll in Cluster gruppieren  
- Kombiniert man mehrere Stat-Werte, lassen sich **sehr gute Sieg-Vorhersagen** treffen  
- Machine Learning kann im Gaming-Kontext interessante Zielgruppen und Strategien aufdecken  

---

## 💾 Dateiinhalt

- `Datensatz 1 Games.ipynb` – Hauptanalyse der Spielerdaten  
- `Datensatz 2 Champion1.ipynb` – Champions Set 1  
- `Datensatz 3 Champion2.ipynb` – Champions Set 2  
- `Datensatz 4 Summoner_Spell.ipynb` – Spell-Nutzung & Auswertung  
- `Standardvisualisierungen.ipynb` – Basis-Charts & Vergleichsanalysen  
- `ML_Vorbereitungen.ipynb` – Feature Engineering & ML-Setup  
- `ML_Visualisierungen.ipynb` – ML-Ergebnisse & Visuals  
- `README.md` – Diese Dokumentation  

---

## 🎯 Ziel des Projekts

Ziel war es, **das erlernte Wissen aus allen Modulen (Python, Data Analytics, ML)** in einem praxisnahen Projekt zu bündeln.  
Dabei stand nicht nur die technische Umsetzung im Fokus, sondern auch die Fähigkeit, spielbezogene Daten zu verstehen, aufzubereiten und geschäftsrelevante oder strategische Erkenntnisse daraus zu gewinnen.

---

## 👨‍💻 Erstellt von

**Aljoscha Kropp**  
📘 Abschlussprüfung –  Für Data SmartPoint Academy  

---

## 📂 Hinweis zum Datensatz

Der verwendete Datensatz wurde im Rahmen einer Schulung zur Verfügung gestellt und basiert auf öffentlich zugänglichen Übungsdaten von [Kaggle](https://www.kaggle.com/).  
Aus lizenzrechtlichen Gründen wird der Datensatz in diesem Repository **nicht veröffentlicht**.

---

## 🧠 Daten, Skills & Gaming-Instinkt

Dieses Projekt verbindet Zahlen mit Spielgefühl – Machine Learning mit Leidenschaft.  
Ein paar kleine Ecken und Ungenauigkeiten wurden **bewusst beibehalten**, um zu zeigen:  
Datenanalyse ist kein Endzustand, sondern ein Spielfeld voller Lernmomente.  
Und genau dort liegt der wahre Highscore. 🎮✨
