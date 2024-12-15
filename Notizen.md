# Notizen: Repository Metriken

## **Aktivität**
- **Lebendigkeit und Engagement**:
  - Zeigt, ob das Repository aktiv weiterentwickelt wird.
- **Nutzen**:
  - Identifikation veralteter oder vernachlässigter Repositories.

## **Qualität**
- **Technische Integrität**:
  - Langfristig wartbarer und effizienter Code.
- **Nutzen**:
  - Reduktion von zukünftigen Fehlern.
  - Frühes Erkennen problematischer Bereiche.

## **Workflow**
- **Effizienz der Prozesse**:
  - Sicherstellung stabiler Workflows.
- **Nutzen**:
  - Schnelleres und zuverlässigeres Bereitstellen von Features und Fixes.

---
# Beschriftung der Diagramme erklären

## **Merges to Main**
- **Ziel**: Höhere Werte bedeuten **Stabilität** und **Aktualität**.
- **Einfluss kleinerer Projekte**:
  - Vereinfachte Workflows reduzieren die Merge-Häufigkeit.

---

## **Rating per Python File**
- **Public Repositories**:
  - **Größere Spanne** zwischen den besten und schlechtesten Bewertungen.
  - Mehr Entwickler tragen zur **Code-Optimierung** bei.
- **Private Repositories**:
  - **Gleichgewicht** zwischen hoher Qualität und Effizienz.
- **Einfluss kleiner Dateien**:
  - Oft nicht so dokumentiert, wie es Pylint erwartet, was die Bewertungen beeinflusst.

---

## **GitHub Actions Success Rate (GHA SR)**
- **Ziel**: Eine **hohe Erfolgsrate** (nahe 1) zeigt stabile Pipelines.
- **Wichtigkeit der Workflows**: Nicht vollständig berücksichtigt.
- **Public Repositories**:
  - **Geringere Erfolgsrate** durch komplexere Workflows und mehr Tests.
  - Höhere **Variabilität** in der Workflow-Struktur.
- **Private Repositories**:
  - Höhere Erfolgsrate durch **weniger komplexe und standardisierte Pipelines**.
