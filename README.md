# Makroökonomische Zeitreihenmodellierung – Phillips-Kurve

## Projektübersicht

Dieses Projekt analysiert den Zusammenhang zwischen Inflation und Arbeitslosigkeit in den USA anhand der Phillips-Kurve.

Mithilfe makroökonomischer Zeitreihendaten der Federal Reserve (FRED) wird ein lineares OLS-Regressionsmodell verwendet, um den statistischen Zusammenhang zwischen beiden Variablen zu untersuchen.

Der Fokus des Projekts liegt auf:
- Datenaufbereitung makroökonomischer Zeitreihen
- statistischer Analyse ökonomischer Zusammenhänge
- Regressionsmodellierung mit Python
- Visualisierung und Interpretation wirtschaftlicher Entwicklungen

## Verwendete Libraries

- Python
- pandas
- statsmodels
- matplotlib
- pandas_datareader

## Nutzung

**Option 1:** [In Google Colab öffnen](https://colab.research.google.com/drive/1pGfAOI4rlVqfdYI_O4cBbXaj8Rq6cvjg?usp=sharing)

(einfach im Browser ausführen, keine Installation notwendig)

**Option 2:** Lokal ausführen
1. Repo klonen
  ```bash
  git clone https://github.com/jantschpk/portfolio-optimization.git
  cd portfolio-optimization
```

2. Libraries installieren
   ```bash
   pip install -r requirements.txt

3. Notebook starten
   ````bash
   jupyter notebook portfolio_montecarlo.ipynb

## Datenquellen

Die Daten stammen aus der FRED-Datenbank der Federal Reserve Economic Data.

Verwendete Zeitreihen:
- CPIAUCSL – Consumer Price Index
- UNRATE – US Unemployment Rate

Untersuchungszeitraum:
1950–1970


## Limitationen

- Vereinfachtes lineares Modell
- Keine Berücksichtigung externer Schocks oder geldpolitischer Effekte
- Historische Zusammenhänge sind nur eingeschränkt auf zukünftige Entwicklungen übertragbar
