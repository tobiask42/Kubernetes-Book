# Kubernetes – Technische Übersicht und Best Practices

**Sprache / Language**: Deutsch 🇩🇪  
**Lizenz / License**: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)  
**PDF**: [Download hier](./main.pdf)  

---

## Projektbeschreibung

Dies ist ein umfassendes, auf Deutsch verfasstes Nachschlagewerk zu Kubernetes, das sich an Administratoren, Entwickler, Studierende und alle richtet, die sich technisch fundiert mit Kubernetes beschäftigen möchten.

Entstanden ist das Dokument im Rahmen meiner eigenen vertieften Einarbeitung. Ziel war es, das Thema systematisch, praxisorientiert und mit einem klaren Fokus auf Best Practices aufzubereiten.

Das Dokument behandelt u.a.:

- Grundlagen und Architektur
- Konfiguration, Secrets und Probes
- Skalierung, Sicherheit und Netzwerk
- CI/CD, Debugging und Operatoren
- Backup & Recovery
- ...und über 150 Codebeispiele (YAML, Bash, Go, Python)

Der Fokus liegt auf Klarheit, Best Practices und praktischer Anwendbarkeit.

Feedback, Fragen und Verbesserungsvorschläge sind willkommen. Ich bin über mein Kontaktformular unter [https://tobias-koch.dev/de/contact](https://tobias-koch.dev/de/contact) erreichbar.

---
Komplette Kapitelliste:
1. Grundlagen
2. Konfiguration und Geheimnisse
3. Skalierung und Autoscaling
4. Speicherverwaltung
5. Workloads und Ressourcen
6. Probes
7. Sicherheit und Zugriffskontrolle
8. Ressourcenverwaltung
9. Erweiterungen und Anpassungen
10. Überwachung und Debugging
11. Taints und Affinitäten
12. Bereitstellungsstrategien
13. Backup und Wiederherstellung
14. CI/CD Integration
15. Kompendium

---

Das Titelbild wurde von Growtika kreiert, von mir zugeschnitten und unter der Unsplash-Lizenz lizensiert. Es kann unter https://unsplash.com/photos/GSiEeoHcNTQ heruntergeladen werden.

---

## Inhalt und Build

Die Gliederung erfolgt modular in Kapiteldateien (`chapters/`) sowie Beispielcode (`minted/`). Das finale PDF wird mit LaTeX (explizit **XeLaTeX**) generiert (empfohlen: `latexmk` mit `-shell-escape`).

## Technisches

- Formatierung mit `latexmk`, `minted`, `xelatex`
- Schriftarten: `Fira Code` (Monospace)
- Quellcode-Snippets liegen in separaten Dateien im Ordner `minted/`
- Temporäre Dateien wie `_minted/` und `*.aux`, `*.log` sind via `.gitignore` ausgeschlossen



## English Summary

This project is a **comprehensive German-language guide** to Kubernetes. It provides a detailed walkthrough of common tools, patterns, and best practices, including real-world configurations and command-line examples.

Although the primary audience is German-speaking, readers with technical Kubernetes knowledge may benefit from the examples and structure.


Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
