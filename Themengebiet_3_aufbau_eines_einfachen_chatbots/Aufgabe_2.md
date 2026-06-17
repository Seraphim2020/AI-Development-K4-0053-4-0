## Aufgabe 2:

Ein kleines Fitnessstudio möchte auf seiner Website einfache Standardfragen automatisch beantworten lassen. Häufig fragen Besucher nach den Trainingszeiten oder nach einem Probetraining. Dafür soll ein sehr einfacher Chatbot entwickelt werden.

Der Chatbot soll auf passende Begriffe in einer Nutzereingabe reagieren und jeweils eine feste Antwort zurückgeben.

Der Bot soll folgende Informationen beantworten können:

- Bei einer Frage zu den Trainingszeiten soll er antworten:

```
Unser Fitnessstudio ist täglich von 06:00 bis 22:00 Uhr geöffnet.
```

- Bei einer Frage zu einem Probetraining soll er antworten:

```
Ein kostenloses Probetraining kann telefonisch oder direkt vor Ort vereinbart werden.
```

Wenn keine passende Frage erkannt wird, soll eine allgemeine Antwort zurückgegeben werden.

**Anforderung**

a) Erstelle eine Python-Klasse namens `SimpleGymBot`.

b) Speichere die festen Antworten in einer geeigneten Datenstruktur.

c) Implementiere eine Methode `respond_to_user_input`, die eine Nutzereingabe verarbeitet und eine passende Antwort zurückgibt.

d) Teste die Methode mit mehreren Beispiel-Eingaben.

e) Begründe kurz:

- warum die gewählte Datenstruktur für die Antworten sinnvoll ist,
- warum die Eingabe in Kleinbuchstaben umgewandelt wird,
- warum die Prüfung mit Schlüsselwörtern zur Aufgabe passt.

