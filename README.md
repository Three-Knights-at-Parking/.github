# Three Knights at Parking 

**Parkhaus-Simulation "Rauenegg" – Programmieren 1 (TSATSL25)**

Willkommen beim Repository von **Three Knights at Parking**! Wir sind ein Team von Studierenden der DHBW Ravensburg (Studiengang Embedded Systems) und entwickeln im Rahmen des Kurses *Programmieren 1* eine diskrete Parkhaus-Simulation in der Programmiersprache C.

---

## Projektbeschreibung

Dieses Projekt simuliert das **Parkhaus Rauenegg** – eine zeitbasierte Simulation, die den Betrieb eines Parkhauses mit konfigurierbaren Parametern nachbildet. Unser Ziel ist es, ein strukturiertes, wartbares und gut dokumentiertes C-Programm zu entwickeln, das die Anforderungen der Aufgabenstellung erfüllt und die Prinzipien sauberer Softwareentwicklung umsetzt.

### Kernfunktionen

Die Simulation umfasst folgende zentrale Funktionalitäten:

- **Konfigurierbare Simulationsparameter**: Eingabe über das Terminal (Anzahl Stellplätze, maximale Warteschlangenlänge, Simulationsdauer, Random-Seed, etc.)
- **Stellplätze und Warteschlange**: Dynamische Verwaltung von parkenden Fahrzeugen und wartenden Fahrzeugen in einer Warteschlange mit dynamischer Speicherverwaltung
- **Fahrzeugankunft und -abfahrt**: Zufällige Ankunftszeiten und Parkdauern basierend auf konfigurierbarer Zufallsverteilung
- **Diskrete Zeitschritte**: Die Simulation läuft in diskreten Zeitschritten und aktualisiert den Zustand des Parkhauses schrittweise
- **Statistiken**: Ausgabe aussagekräftiger Statistiken pro Zeitschritt und am Ende der Simulation (z. B. Auslastung, durchschnittliche Wartezeit, Anzahl abgewiesener Fahrzeuge)
- **Ausgabe**: Konsolenausgabe und optionale Ausgabe in Datei

---

## Projektziele

Dieses Projekt dient als **Programmentwurf (Teil I)** und fokussiert sich auf:

1. **Entwurf und Strukturierung**: Entwicklung einer klaren Modulstruktur mit sinnvoller Aufteilung in Header- und Quelldateien
2. **Datenstrukturen**: Definition geeigneter `struct`-Typen für Fahrzeuge, Parkhaus, Warteschlange und Statistiken
3. **Funktionsprototypen**: Spezifikation aller benötigten Funktionen mit klaren Schnittstellen
4. **Pseudocode**: Dokumentation der Algorithmen in strukturiertem Pseudocode
5. **Flussdiagramme**: Grafische Darstellung der wichtigsten Programmabläufe
6. **Dokumentation**: Umfassende Dokumentation von Designentscheidungen, Datenstrukturen und Algorithmen

---

## Technische Anforderungen

- **Programmiersprache**: C (Standard: C99 oder höher)
- **Dynamische Speicherverwaltung**: Die Warteschlange muss mit dynamischer Speicherverwaltung (`malloc`, `free`) realisiert werden
- **Modularisierung**: Klare Trennung in Module (`.c`/`.h`-Dateien) gemäß Best Practices
- **Coding-Standards**: Einhaltung der im Space definierten C-Coding-Conventions für Embedded Systems
- **Versionskontrolle**: Git/GitHub mit sinnvollen, atomaren Commits und aussagekräftigen Commit-Messages
- **Dokumentation**: Alle Funktionen werden mit Header-Kommentaren versehen (kurze Beschreibung, Parameter, Rückgabewerte)

---

## Repository-Struktur

