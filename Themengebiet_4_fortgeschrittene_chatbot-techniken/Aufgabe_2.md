## Aufgabe 2:

Entwickle einen einfachen AI-basierten Chatbot für eine fiktive Buchhandlung, der Kundinnen und Kunden bei der Buchauswahl unterstützt. Der Chatbot soll in der Lage sein, auf Basis der eingegebenen Nutzerdaten und Anfragen, wie Buchtitel, Genre oder Autor, passende Bücher vorzuschlagen.

Zusätzlich soll der Chatbot prüfen, ob ein gewünschtes Buch aktuell verfügbar ist. Falls kein Exemplar verfügbar ist, soll der Chatbot eine passende Alternative oder einen Hinweis geben, wann das Buch voraussichtlich wieder verfügbar ist.

Der Chatbot soll außerdem Kontextinformationen, wie vorherige Nutzeranfragen, berücksichtigen können, um mehrstufige Dialoge zu führen. Nutze Python und einfache Techniken aus Natural Language Processing (NLP), zum Beispiel reguläre Ausdrücke und Schlüsselworterkennung, um diese Aufgabe zu lösen.

**Aufgabenstellung**

a) Entwickle eine Python-Klasse `BookSelectionChatbot`, die grundlegende Funktionen wie Intent-Erkennung für Buchsuche, Verfügbarkeitsprüfung und Empfehlung sowie eine einfache Entity-Erkennung für Buchtitel, Genres und Autorennamen enthält.

b) Implementiere eine Methode `handle_message`, die eine Nutzereingabe entgegennimmt, den Intent und relevante Entities erkennt und basierend auf dem aktuellen Kontext eine passende Antwort generiert.

c) Erweitere den Chatbot um die Fähigkeit, mehrstufige Dialoge zu führen. Der Chatbot soll sich merken können, wonach ein Nutzer zuvor gefragt hat, zum Beispiel ein Genre oder einen bestimmten Autor.

d) Füge eine Funktion hinzu, die prüft, ob ein gewünschtes Buch aktuell verfügbar ist.

e) Falls ein Buch verfügbar ist, soll der Chatbot dieses Buch vorschlagen. Falls kein Exemplar verfügbar ist, soll der Chatbot mitteilen, wann das Buch voraussichtlich wieder verfügbar ist, oder ein ähnliches verfügbares Buch empfehlen.

f) Teste den Chatbot mit verschiedenen Eingaben, zum Beispiel:

- Anfrage nach einem bestimmten Buch
- Anfrage nach einem Genre
- Anfrage nach einem nicht verfügbaren Buch
- mehrstufige Anfrage, bei der der Nutzer erst ein Genre nennt und danach nach einer Empfehlung fragt

