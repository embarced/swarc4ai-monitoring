# Übung: AI-Monitoring & Observability

In dieser Übung analysiert ihr reale Momentaufnahmen (Snapshots) unseres Monitoring-Dashboards. Zwei KI-Komponenten laufen bei arca.shop in Produktion:
1. **PreisPilot** (Klassisches ML – Preisbewertung für Einzelstücke im Ankaufsportal und nächtlicher Repricing-Batch)
2. **Kompatibilitäts-Assistent** (GenAI / RAG – Beantwortung von Kundenfragen auf Produktseiten aus redaktionellen Inhalten)

In jedem Snapshot hat sich ein konkretes Problem eingeschlichen. Eure Aufgabe ist es, als Entwicklungs- und Architekturteam die Ursachen zu identifizieren und passende Maßnahmen abzuleiten.

---

## 🚀 Dashboard starten

Ihr benötigt keine Server-Installation oder zusätzliche Software.

Öffnet einfach die Datei **[`Uebung_AI-Monitoring_arca_Dashboard.html`](./Uebung_AI-Monitoring_arca_Dashboard.html)** direkt in einem Webbrowser eurer Wahl (per Doppelklick oder Drag & Drop).

---

## 👥 Teamaufteilung

Jedes Team untersucht eine andere Momentaufnahme des Dashboards:

| Team | Dashboard-Tab |
| :--- | :--- |
| **Team 1** | **Snapshot 1** |
| **Team 2** | **Snapshot 2** |
| **Team 3** | **Snapshot 3** |
| **Team 4** | **Snapshot 4** |

*(Der Tab **„Start · Szenario & Aufgabe“** bietet euch zusätzlich eine kurze Übersicht über die beiden Systeme und Rahmenbedingungen.)*

---

## 🎯 Aufgabenstellung

1. **Welche Probleme zeigt Euer Dashboard?**
   - Wo im Dashboard stimmt etwas nicht?
   - Welche Panels zeigen Anomalien und welche zeigen kein Problem?
2. **Welche Sofortmaßnahmen würdet Ihr ergreifen?**
   - Was tut ihr als Erstes, um den akuten Schaden abzuwenden oder zu begrenzen?
3. **Welche langfristigen Architekturmaßnahmen ergreift Ihr, um derartige Probleme in Zukunft zu verhindern?**
   - Welche architektonischen Schutzmechanismen, Pipelines, Fallbacks oder Quality Gates sollten etabliert werden?
4. **Gibt es weitere Dinge, die Ihr monitoren würdet, um solche Probleme besser oder früher zu erkennen?**
   - Welche Metriken, Checks oder Alerts hätten euch schon vor den Auswirkungen gewarnt?
