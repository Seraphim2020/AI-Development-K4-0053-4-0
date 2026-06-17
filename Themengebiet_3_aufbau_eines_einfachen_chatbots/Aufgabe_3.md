## Aufgabe 3:

Ein Online-Buchladen möchte einen einfachen Chatbot einsetzen, der erste Nutzereingaben automatisch verarbeitet. Der Chatbot soll einfache Gesprächsabsichten erkennen, feste Informationen ausgeben und zusätzlich eine einfache Stimmung der Nutzereingabe bestimmen.

Der Chatbot soll **regelbasierte Elemente** und einfache **KI-basierte Textverarbeitung** kombinieren:

- Regelbasiert:
  - Begrüßungen erkennen
  - Verabschiedungen erkennen
  - eine feste Information zu Lieferzeiten ausgeben
- KI-basiert / NLP-basiert:
  - Eingaben mit `nltk` in Wörter zerlegen
  - Wörter mit `spaCy` lemmatisieren
  - anhand fester positiver und negativer Wörter eine einfache Stimmung erkennen

**Aufgabe**

Entwickle einen einfachen Chatbot in Python, der Nutzereingaben für einen Online-Buchladen verarbeitet.

a) Implementiere eine Klasse `BookstoreChatbot`.

b) Die Klasse soll geeignete Methoden enthalten für:

- Verarbeitung der Nutzereingabe
- Intent-Erkennung
- Sentiment-Erkennung
- Antwort-Generierung

c) Der Chatbot soll Begrüßungen wie `"Hallo"`, `"Hi"` oder `"Guten Tag"` erkennen und mit einer festen Begrüßung antworten.

d) Der Chatbot soll Verabschiedungen wie `"Tschüss"`, `"Auf Wiedersehen"` oder `"Bis bald"` erkennen und mit einer festen Verabschiedung antworten.

e) Der Chatbot soll eine Frage nach der Lieferzeit erkennen. Wenn die Eingabe Wörter wie `"Lieferzeit"`, `"Versand"` oder `"Lieferung"` enthält, soll der Chatbot eine statische Information ausgeben:

```
Unsere Standardlieferung dauert in der Regel 2 bis 4 Werktage.
```

f) Zusätzlich soll der Chatbot eine einfache Sentiment-Erkennung durchführen. Nutze dafür feste Wortlisten, zum Beispiel:

```
positive_words = ["gut", "super", "zufrieden", "schnell", "freundlich"]
negative_words = ["schlecht", "langsam", "problem", "unzufrieden", "ärgerlich"]
```

Die Eingabe soll mit `nltk` tokenisiert und mit `spaCy` lemmatisiert werden. Anschließend soll gezählt werden, ob mehr positive oder negative Wörter vorkommen.

g) Wenn keine Begrüßung, Verabschiedung oder Lieferzeitfrage erkannt wird, soll der Chatbot abhängig von der Stimmung antworten:

- positive Stimmung: `"Das freut uns. Wie können wir weiterhelfen?"`
- negative Stimmung: `"Das tut uns leid. Bitte beschreiben Sie Ihr Anliegen genauer."`
- neutrale Stimmung: `"Entschuldigung, ich habe das nicht verstanden."`

h) Teste den Chatbot mit mehreren Eingaben, sodass alle Fälle mindestens einmal geprüft werden.

