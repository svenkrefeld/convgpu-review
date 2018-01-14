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
- Es wird in der Arbeit angeführt, dass Docker ein beliebtes Framework ist. Ich denke diese Behauptung können wir alle bestätigen, nachdem wir gehört haben wie mächtig Docker ist. Aufgrund der Behauptung haben wir in unserem Review eine kleine Suche gestartet und festgestellt, dass sich die Anzahl an wissenschaftlichen Arbeiten, die sich auf Docker beziehen in den letzten Jahren fast linear steigt (ca. 4000-5000 pro Jahr). Das bedeutet, dass das Thema zwar nicht an Relevanz gewinnt, allerdings auch nicht abnimmt.

- NVIDIA CUDA wird häufig benutzt um parallelisierbare Aufgaben auszuführen, hiermit kann man die Architektur, den Speicher und die Rechenleistung einer Grafikkarte benutzen. Viele Grafikkarten unterstützen NVIDIA CUDA.

- Die Kombination von Docker und NVIDIA CUDA wird unseres Ermessens nach nicht sehr häufig gebraucht. Grund dafür ist vielleicht auch, dass im Text keine Beispiele angegeben werden, wofür man diese Kombination benutzen könnte.

- Der Vorteil, den die Autoren in dem von ihnen behandelten Thema sehen, wird durch die Arbeit nicht dargestellt. Für jemanden, der genau diese Kombination braucht, kann die Arbeit aber durchaus von Relevanz sein.

---

## Herangehensweise und Methodik

- Gute Erläuterung der Technologien
  + Wichtige Komponente fehlen jedoch
  
- Unklar worum es sich bei ConVGPU handelt

- Logischer Aufbau

- Wissen über Docker und NVIDIA CUDA vorrausgesetzt

Note:
- Die verwendeten Technologien und der geschilderte Aufbau werden deutlich gemacht und sind gut zu verstehen. Einige wichtige Erklärungen fehlen jedoch, wären ganz hilfreich. Oder weiß jeder von euch worum es sich bei IOMMU (I/O memory management unit) handelt?

- Es wird durch den Aufbau nicht ganz klar worum es sich bei dem beschriebenen ConVGPU handelt. Es wird nicht deutlich, ob es komplett selbst geschrieben ist, aus verschiedenen Teilen zusammengesetzt wird. Ebenfalls ist nicht klar, ob das Programm, so wie es beschrieben wird komplett lauffähig ist.

- Die Arbeit ist verständlich aufgebaut, erst mit Erklärungen, dann mit Komponentenzusammenbau und danach mit den Versuchsergebnissen

- Wenn man die Arbeit schnell verstehen will, muss man sich im Voraus mit NVIDIA CUDA und Docker auseinandergesetzt haben, da sonst Zeit benötigt wird um sich zu informieren.

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
