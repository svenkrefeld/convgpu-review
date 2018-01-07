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

## Beurteilung
