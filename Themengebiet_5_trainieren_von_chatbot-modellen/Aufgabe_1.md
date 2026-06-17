## Aufgabe 1:

Eine Online-Buchhandlung möchte Kundenanfragen automatisch einer passenden Kategorie zuordnen. Der Chatbot soll erkennen, ob eine Nachricht eine Frage zu einem Buch, zum Versand oder zur Rücksendung ist.

Entwickle ein Python-Skript, das folgende Anforderungen erfüllt:

a) Trainingsdaten erzeugen

Erzeuge mindestens **100 eindeutige Kundennachrichten** für die drei Kategorien:

- `Buchanfrage`
- `Versandanfrage`
- `Rücksendeanfrage`

Nutze dafür ein einfaches Template-System mit Platzhaltern, zum Beispiel für Buchtitel, Autorennamen oder Bestelldaten.

b) Datenqualität prüfen

Implementiere eine Funktion, die prüft:

- ob alle Nachrichten vollständig sind,
- wie die Kategorien verteilt sind,
- wie viele eindeutige Formulierungen vorhanden sind.

c) Modell trainieren

Trainiere ein einfaches Chatbot-Modell mit den gesammelten Daten. Verwende dafür eine gängige Python-Bibliothek für maschinelles Lernen oder natürliche Sprachverarbeitung (z. B. TensorFlow, PyTorch, spaCy). Experimentiere mit mindestens zwei verschiedenen Sets von Hyperparametern, um die Auswirkungen auf Overfitting und Modellgenauigkeit zu untersuchen.

d) Transfer Learning nutzen

Implementiere Transfer Learning, indem du ein vortrainiertes Modell als Ausgangspunkt nimmst und es mit deinen Daten feinabstimmst. Vergleiche die Leistung des feinabgestimmten Modells mit dem in Schritt c) trainierten Modell.

