# E-Commerce Kunden: Vorhersage des Jahresumsatzes (Lineare Regression)
Kurzes Projekt zur Vorhersage des jährlichen Umsatzes von E-Commerce-Kunden auf Basis ihres Nutzungsverhaltens 
(Zeit auf der Website, Zeit in der App, Mitgliedschaftsdauer, u. a.) mittels linearer Regression.
# Inhalt
- regression.ipynb
- data/costumer.csv
# Vorgehen
1. Datenprüfung: Duplikate und fehlende Werte prüfen
2. EDA: Visualisierung der Zusammenhänge zwischen Nutzungsmerkmalen und Jahresumsatz
3. Modell: LinearRegression (scikit-learn), Train-Test-Split 70/30
4. Evaluierung: MAE, MSE, RMSE
5. Residuenanalyse: Histogramm und Q-Q-Plot zur Prüfung der Modellannahmen
# Set up
```bash
pip install -r requirements.txt
jupyter notebook regression.ipynb
```
# Limitationen
- Kein Vergleich mit alternativen Modellen (z. B. Ridge/Lasso)
- Keine Cross-Validation
