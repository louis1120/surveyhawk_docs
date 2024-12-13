### **FAQ - Häufig gestellte Fragen**

---

#### **Frage 1: Wie ist die Struktur der Datenbank?**

![Datenbankstrukur](../assets/RepoDB.png)

---

#### **Frage 2: Wieso wurde DuckDB als Datenbank verwendet?**

1. **Einfach einzurichten** ist: Keine separate Serverinstallation erforderlich.  
2. **Schnell arbeitet**: Hohe Abfragegeschwindigkeit für effiziente Analysen.  
3. **API-Ratenbeschränkungen umgeht**: Lokale Speicherung reduziert Abhängigkeiten von API-Anfragen.  
4. **Stabile Metriken ermöglicht**: Eine robuste Grundlage für die Datenverarbeitung bietet.

---

#### **Frage 3: Wieso wurde Pylint zur Bewertung der Codequalität verwendet?**

1. **Statische Codeanalyse** ermöglicht: Es identifiziert Fehler ohne Codeausführung.  
2. **PEP8-konform** ist: Sorgt für klare, wartbare Code-Struktur.  
3. **Flexibel bewertbar** ist: Skala von 0 bis 10, anpassbar an Projektspezifika.  
4. **Effizient integriert** ist: Automatische Bewertung relevanter Python-Dateien.

#### **Frage 4: Warum wurden bestimmte Metriken priorisiert?**
Die Priorisierung der Metriken erfolgte auf Basis ihrer Relevanz für die Repository-Gesundheit:  
1. **Messbarkeit**: Metriken wie Commit-Häufigkeit und PR-Status sind einfach zu erfassen und aussagekräftig für Aktivität und Fortschritt.  
2. **Qualitätsbewertung**: Metriken wie Review-Zeiten und Branch-Protection unterstützen die Bewertung der Codequalität und der Entwicklungseffizienz.  
3. **Relevanz für Teamprozesse**: Workflow-bezogene Metriken wie CI/CD-Status und Merge-Zeiten zeigen direkt Optimierungspotenziale in Entwicklungsprozessen auf.  
4. **Verfügbarkeit der Daten**: Die Auswahl beschränkte sich auf Metriken, deren Daten über die GitHub-API und vorhandene Tools wie Pylint verfügbar waren.

---

#### **Frage 5: Wieso wurde Pandas verwendet?**
Pandas wurde aufgrund seiner vielseitigen Funktionen und Effizienz verwendet:
1. **Flexible Datenmanipulation**: Es ermöglicht die einfache Filterung, Transformation und Aggregation von großen Datenmengen.  
2. **Kompatibilität**: Die Integration mit anderen Python-Bibliotheken wie NumPy und Matplotlib macht es zu einer idealen Wahl für analytische Workflows.  
3. **Performance**: Pandas bietet optimierte Datenrahmenstrukturen, die ideal für die Verarbeitung der Repository-Metriken geeignet sind.  
4. **Einfachheit**: Es reduziert den Implementierungsaufwand durch seine umfangreiche API und Dokumentation.

---

#### **Frage 6: Wieso habe ich bestimmte Visualisierungsmöglichkeiten gewählt?**
Die Visualisierungen wurden gezielt auf Basis ihrer Aussagekraft gewählt:  
1. **Balkendiagramme**: Sie ermöglichen einen klaren Vergleich von Aktivitätsmetriken wie Commit- und PR-Zahlen.  
2. **Liniendiagramme**: Zeigen Trends und Entwicklungen über Zeiträume, z. B. bei Merge-Zeiten.  
3. **Heatmaps**: Kompakt und prägnant für den Vergleich von Repositories oder Metrikrelationen, z. B. „Open vs. Closed Issues“.  
4. **Boxplots**: Zur Analyse der Verteilung von Review-Zeiten und Identifikation von Ausreißern.

---

#### **Frage 7: Welche Herausforderungen traten auf?**
Im Projekt wurden mehrere Herausforderungen bewältigt:  
1. **Datenzugang**: Ratenbeschränkungen der GitHub-API verlangsamten die Datenerhebung.  
2. **Datenkonsistenz**: Unterschiedliche Formate und Quellen erforderten eine standardisierte Datenaufbereitung.  
3. **Metrikvalidierung**: Die Bedeutung und Aussagekraft einzelner Metriken variiert je nach Repository-Typ.  
4. **Erweiterbarkeit**: Die Architektur musste modular sein, um neue Metriken flexibel integrieren zu können.

---

#### **Frage 8: Welche kritischen Metriken wurden vernachlässigt?**
Einige wichtige Metriken konnten nicht vollständig abgedeckt werden:  
1. **Testabdeckung**: Eine Schlüsselmetrik für Codequalität, die aufgrund fehlender Datenquellen nicht integriert wurde.  
2. **Langzeittrends**: Historische Entwicklungen wurden eingeschränkt berücksichtigt, da umfassende Daten nicht verfügbar waren.  
3. **Teamdynamik**: Qualitative Aspekte wie Kommunikation und Wissensaustausch konnten nicht durch Metriken erfasst werden.  
4. **Fehleranalysen**: Die detaillierte Verfolgung von Fehlerursachen blieb außerhalb des Projektumfangs.

---
##### Quellen:
<!-- ![surveyhawk_art](../assets/char_art.png){ width=9.4% }
![surveyhawk_art](../assets/char_art.png){ width=9.4% }
![surveyhawk_art](../assets/char_art.png){ width=9.4% }
![surveyhawk_art](../assets/char_art.png){ width=9.4% }
![surveyhawk_art](../assets/char_art.png){ width=9.4% }
![surveyhawk_art](../assets/char_art.png){ width=9.4% }
![surveyhawk_art](../assets/char_art.png){ width=9.4% }
![surveyhawk_art](../assets/char_art.png){ width=9.4% }
![surveyhawk_art](../assets/char_art.png){ width=9.4% }
![surveyhawk_art](../assets/char_art.png){ width=9.4% } -->
