# Contributing Guide

Vielen Dank für dein Interesse, zu diesem Projekt beizutragen! Dieses Dokument soll dir helfen, zu verstehen, wie du effektiv mitmachen kannst. Obwohl dieses Projekt in einer Enterprise-Umgebung entwickelt wurde, folgen wir den Best Practices der Open-Source-Welt.

---

## Repository-Link

Das Repository befindet sich hier: **[Repository-Link einfügen]**

---

## Wie du beitragen kannst

### 1. Ideen und Vorschläge
- Erstelle ein Issue im Repository, um Vorschläge oder Fehler zu melden.

### 2. Code beisteuern
- Forke das Repository und erstelle einen neuen Branch für deine Änderungen.
- Führe Tests lokal aus, bevor du einen Pull-Request (PR) erstellst.
- Stelle sicher, dass dein PR sauber dokumentiert ist und beschreibe, was geändert wurde und warum.

### 3. Dokumentation verbessern
- Auch Verbesserungen der Dokumentation sind willkommen! Hilf uns, die Inhalte klar und zugänglich zu gestalten.

---

## Arbeiten mit `metrics.py` und `predicates.py`

### `metrics.py`
- Neue Metriken können durch Hinzufügen einer Funktion in `metrics.py` erstellt werden.
- Nutze den `@metrics`-Dekorator, um die Funktion als Metrik zu markieren.
- Beispiel:
    ```python     
    @metrics     
    def example_metric(data):    
        # Deine Logik hier    
        return result    
    ```
### `predicates.py`
- Prädikate liefern boolesche Antworten zu spezifischen Eigenschaften des Repositories.
- Neue Prädikate können durch Hinzufügen einer Funktion in predicates.py erstellt werden.
- Beispiel:
    ```python
    @predicates
    def example_predicate(repo_data):
        # Überprüft, ob Branch-Schutz aktiviert ist
        return repo_data.get("branch_protection", False) is True
    ```