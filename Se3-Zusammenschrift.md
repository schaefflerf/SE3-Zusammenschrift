# Software Engineering

## Qualität
Software-bezogene Qualität:  
- **Prozessqualität:** Qualität des Projekts, bzw. des **Prozesses** indem/mit dessen Hilfe die Software entwickelt wird.
- **Produktqualität:** Qualität des **Ergebnisses** der Herstellung , d.h. die **Software** selber.

### Produktqualität:
- Brauchbarkeit
    - Bedienbarkeit (wie gut die Software in der Lage ist, Aufgaben zu erfüllen)
        - Einfachheit (hoch, wenn SW dem Benutzer konzeptionell einfach erscheint)
        - Verständlichkeit (Benutzer versteht rasch, wie er mit SW umgehen muss)
        - Konsistenz (SW verhält sich ähnlich in ähnlichen Situation)
        - Handbuchvollständigkeit (Alle Fragen des Benutzers können beantwortet werden)
    - Nützlichkeit
        - Leistungsvollständigkeit (SW erbringt alle geforderten Leistungen)
        - Sparsamkeit (SW benötigt kaum Speicherplatz und andere Betriebsmittel)
        - Effizienz (SW benötigt kaum Rechenzeit, als minimal erforderlich wäre)
    - Zuverlässigkeit
        - Genauigkeit (Resultate vom mathematisch korrekten Resultat nur wenig Abweichungen)
        - Ausfallsicherheit
        - Korrektheit (Spezifikation zutreffend, SW korrekt)
- Wartbarkeit (Fähigkeit der Software, in Zukunft geändert/gewartet zu werden, ohne großen Aufwand und Kosten zu verursachen)
    - Portabilität
        - Abgeschlossenheit
        - Geräteunabhängigkeit
    - Änderbarkeit
        - Lesbarkeit
        - Knappheit
        - Simplizität (hoch, wenn nur wenige schwer verst. Konstruktionen enthalten sind)
        - Strukturiertheit (hoch, wenn SW logisch abgeschlossen und in hohem Zusammenhalt und geringer Kopplung gegliedert ist)
    - Prüfbarkeit
        - Testbarkeit (Ausführung ist reproduziertbar. Vollständiges Erfassen der Resultate)
        - Lokalität (hoch, wenn Fernwirkungen in SW vermieden sind.)
        - Spezifikationsvollständigkeit

---
## Architektur
- Architekturmuster
    - sind Muster, die für die Organisation und Strukturierung von Software-Systemen verwendet werden.
    - beschreiben, wie die Komponenten eines Systems miteinander verbunden sind und wie Steuerungsfluss und Datenfluss gestaltet sind.
    - sind auf höherer Ebene als Desing-Patterns.
    - sind normalerweise unabhängig von einer Programmiersprache.
    - Beispiele: Model-View-Controller(MVC), Event-Driven Architecture(EDA), Microservices Architecture
    - **Zusammenfassend: Architekturmuster beziehen sich auf die große Struktur des Systems.**

### Architekturmuster - Aufteilung
- Strukturierende Architekturmuster
    - Pipes und Filter
        - **Kontext:** System mit vielfältigen Aufgaben
        - **Probleme:**
            - Aufgaben sind fast immer unterschiedlich
            - System muss flexibel bleiben
        - **Lösung:**
            - Nacheinanderschalten verschiedener (unabhängiger) Komponenten für einzelne Teilaufgaben
        - **Vorteile:**
            - Einfacher Aufbau
            - Gute Wiederverwendbarkeit
            - Unabhängigkeit der Einzelschritte erleichtert Wartung
            - Parallelisierung der Einzelschritte möglich
        - **Nachteile:**
            - Datenformate meist rudimentär
            - Geschwindigkeit und Latenzzeiten abh. vom langsamsten Teil
        - **Beispiele:**
            - Compiler, Konsolenbefehle der Unix-Shell, Funktionale Programmierung, Verteilte Systeme
    - Schichten
- Architekturmuster für interaktive Systeme
    - MVC
- Architekturmuster für verteilte Systeme
    - Vermittler-Prinzip
    - Client-Server
    - Dienstorientierte Architektur
    - Peer-to-Peer

- Design-Patterns
    - sind Muster, die auf der Implementierung von einzelnen Komponenten eines Systems auf Basis von bestimmten Problemen aufbauen.
    - beschreiben, wie bestimmte Probleme in einer bestimmten Programmiersprache gelöst werden können.
    - sind auf tieferer Ebene als Architekturmuster.
    - sind für bestimmte Programmiersprachen gültig.
    - Design Pattern mit "globalem" Einfluss auf SW werden oft auch als Architekturmuster angesehen.
    - Beispiele: Singleton, Factory Method, Observer
    - **Zusammenfassend: Design-Patterns beziehen sich auf kleinere Strukturen und die Implementation von einzelnen Komponenten.**
