# ConVGPU

### GPU Management Middleware in Container Based Virtualized Environment

---

## Inhaltliche Zusammenfassung

---

## Themenbereich und Problemstellung

- Virtualisierung von GPU-Rechenleistung

- Docker Containerbasierte Virtualisierung

- Keine zufriedenstellende Lösung

- Mehrfache und geteilte Verwenden einer Grafikkarte 

- Probleme beim Speichermanagement

---

## Umsetzung

- Angepasster NVIDIA-Docker

- Augenmerk auf drei Faktoren:
  + Isolation
  + Konsistenz
  + Austauschbarkeit

- Zwei Hauptbestandteile:
  + CUDA wrapper API module
  + GPU memory scheduler

---?image=assets/image/convgpu.png&opacity=100&size=auto 90%

@title[ConVGPU - Schaubild]

---

## Analyse

---

## Relevanz

- Docker sehr beliebtes Framework

- NVIDIA CUDA Grafikkarten viel verwendet

- Kombination wiederrum weniger

- Vorteil wird nicht deutlich

---

## Herangehensweise und Methodik

- Gute Erläuterung der Technologien
  + Wichtige Komponente fehlen jedoch
  
- Unklar worum es sich bei ConVGPU handelt

- Logischer Aufbau

- Wissen über Docker und NVIDIA CUDA vorrausgesetzt

---

## Ergebnisse und Schlussfolgerungen

- Ergebniszusammenfassung ist Verständnishilfe

- Ergebnisse stecken noch in den Anfängen

- Eher ein "Proof-of-Concept"

---

## Beurteilung

---

- Eignet sich durchauch für ein Kongress

- Spricht aber gezielte Gruppe an

- Umgesetzte Lösung ist recht speziell
  + Idee dahinter recht offen
  
- Noch keine fundierte Schlussfolgerung möglich
