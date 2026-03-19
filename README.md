# Natural Language Processing

[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jnooo-cloud/NLP/main?labpath=3-Nlp_Projekt_korrigiert.ipynb)

Dieses Repository reproduziert die Kursaufgabe "Natural Language Processing" aus dem Udemy-Kurs "Python fuer Data Science, Machine Learning & Visualization".

## Inhalt

- `3-Nlp_Projekt_korrigiert.ipynb`: Jupyter-Notebook mit der Loesung.
- `Yelp.csv`: Datensatz mit Yelp-Reviews.
- `requirements.txt`: Python-Abhaengigkeiten fuer Binder.

## Ausfuehrung

1. Klicke auf den Binder-Badge.
2. Oeffne das Notebook `3-Nlp_Projekt_korrigiert.ipynb`, falls es nicht direkt geoeffnet wird.
3. Fuehre alle Zellen in Reihenfolge aus.

## Erwartetes Ergebnis

Das Notebook verarbeitet Yelp-Review-Texte und klassifiziert diese in 1-Stern- oder 5-Sterne-Bewertungen. Dazu werden ein Bag-of-Words-Modell und anschliessend eine Pipeline mit Textvektorisierung und Naive Bayes eingesetzt. Als Ergebnis erscheinen insbesondere eine `confusion_matrix` und ein `classification_report` fuer die Vorhersagen auf den Testdaten.
