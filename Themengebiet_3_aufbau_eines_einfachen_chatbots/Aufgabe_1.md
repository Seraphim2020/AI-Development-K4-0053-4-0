## Aufgabe 1:

Entwickle einen einfachen, regelbasierten Chatbot in Python, der auf bestimmte Schlüsselwörter in Nutzereingaben reagiert. Der Chatbot soll einfache Fragen zu den Öffnungszeiten einer fiktiven Bibliothek und zur Ausleihe beantworten.

a) Definiere eine Python-Klasse namens `SimpleLibraryBot`.

b) Implementiere in dieser Klasse eine Methode `respond_to_user_input`, die eine Nutzereingabe als Argument erhält.

c) Die Methode soll prüfen, ob die Nutzereingabe eines der folgenden Schlüsselwörter enthält:

- `öffnungszeiten`
- `ausleihe`

Wenn nach den Öffnungszeiten gefragt wird, soll der Bot antworten:

```
Unsere Bibliothek ist Montag bis Freitag von 09:00 bis 18:00 Uhr geöffnet.
```

Wenn nach der Ausleihe gefragt wird, soll der Bot antworten:

```
Bücher können für 14 Tage ausgeliehen werden.
```

Wenn keines der Schlüsselwörter enthalten ist, soll der Bot eine allgemeine Fehlermeldung zurückgeben.

d) Teste deine Implementierung mit mehreren Nutzereingaben.

