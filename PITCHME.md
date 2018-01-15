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

Note:
- Docker ist mächtig und sinnvoll in einigen Anwendungsfällen
- Zu Docker erscheinen jedes Jahr 4000-5000 wissenschaftliche Arbeiten
- Docker ist auf jeden Fall relevant

- NVIDIA CUDA für parallelisierbare Aufgaben
- Speicher, Rechenleistung und Architektur von Grafikkarten nutzen

- Kombination von beidem in nicht sehr vielen Arbeiten zu finden
- In der Presse wird die Kombination auch nicht erwähnt
- Kein Beispiel in der Arbeit genannt, wofür man die Kombination nutzen könnte

- Vorteil von Kombination nicht sichtbar
- Wenn jemand genau diese Kombination braucht, sicher sinnvoll

---

## Herangehensweise und Methodik

- Gute Erläuterung der Technologien
  + Wichtige Komponente fehlen jedoch
  
- Unklar worum es sich bei ConVGPU handelt

- Logischer Aufbau

- Wissen über Docker und NVIDIA CUDA vorrausgesetzt

Note:
- Verwendeten Technologien werden gut und ausführlich beschrieben
- Einige wichtige Erklärungen fehlen
  + z.B. IOMMU (I/O memory management unit)

- nicht klar, was ConVGPU genau ist
  + selbst erstellt?
  + aus verschiedenen Teilen zusammengesetzt?
  + ist das Programm überhaupt lauffähig?
  
- Arbeit verständlich aufgebaut
  + erst Erklärungen, dann Zusammenhang und dann Versuch mit Ergebnissen

- Man muss Wissen über Docker und NVIDIA CUDA haben um das Thema durchdringen zu können

---

## Ergebnisse und Schlussfolgerungen

- Ergebniszusammenfassung ist Verständnishilfe

- Ergebnisse stecken noch in den Anfängen

- Eher ein "Proof-of-Concept"

Note:
- Letzer Absatz, etwas 1/3 des Schlusses, spricht über nötige Verbesserungen

---

## Beurteilung

---

- Eignet sich durchauch für ein Kongress

- Spricht aber gezielte Gruppe an

- Umgesetzte Lösung ist recht speziell
  + Idee dahinter recht offen
  
- Noch keine fundierte Schlussfolgerung möglich

Note:
- Selbst im Team unschlüssig
- Unklar, ob es weitere Arbeiten in diesem Gebiet gibt
