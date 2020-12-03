---
theme: 'night'
transition: 'slide'
highlightTheme: 'monokai'
logoImg: './img/logo-prodv.png'
slideNumber: false
title: 'Crossplattform GUI Entwicklung mit Webtechnologien'
---

### CyberArk Data Tool

Entwicklung einer nativen, crossplattform GUI mit Web Technologien

<small>von [Achim Hilker](https://github.com/achimwork) / [PRO DV AG](https://prodv.de)</small>

---

## Übersicht

1.  Hintergrund
2.  Anforderungen
3.  Technolgische Auswahl
4.  Demo: Entwicklungsumgebung
5.  Demo: Das Ergebniss
6.  Zusammenfassung

---

### Problemstellung

![Benutzeroberfäche](./drawing/workflow-overview-before2.png)

--

### Lösung

![Benutzeroberfäche](./drawing/workflow-overview2.png)

---

### Anforderungen

--

### Anwender

intuitive Oberfläche
intuitive Bedienung
Hilfetexte

--

### Administrator

anpassbar und konfigurierbar
Eingabevalidierung

--

### Entwickler

Doumentation
Entwicklungsumgebung
automatisierte Kompilation

--

### Technologisch

zukunfstsichere Technologien
Plattformübergreifend
Open Source

---

## technolgische Auswahl

--

### Programiersprachen

|                                                                 |            |
| --------------------------------------------------------------- | ---------- |
| ![HTML5](./img/logo-html.png){ height=150px}{.fragment .grow}   | HTML5      |
| ![CSS3](./img/logo-css.png){ height=150px}{.fragment .grow}     | CSS3       |
| ![JavaScript](./img/logo-js.png){ width=150px}{.fragment .grow} | JavaScript |

--

### Bibliotheken

|                                                         |                                                  |
| ------------------------------------------------------- | ------------------------------------------------ |
| ![node.js](./img/logo-nodejs.png){ width=150px}         | [node.js](https://nodejs.org/)                   |
| ![electron.js](./img/logo-electron.png){ width=150px}   | [electron.js](https://www.electronjs.org/)       |
| ![formio.js](./img/logo-formio.png){ width=150px}       | [formio.js](https://formio.github.io/formio.js/) |
| ![Semantic UI](./img/logo-semanticui.png){ width=150px} | [Semantic UI](https://semantic-ui.com/)          |

---

### Entwicklungsumgebung

Editor: Visual Studio Code (VSCode)

Source Controll System: Git

Paketmanager: NPM (Node.js)

--

### Datenverarbeitung

- CSV von Export
- Eingabe durch User
- REST Webservice

---

<div class="mermaid">
graph LR;
  A(AAAA)==> B(B node);
  B==> C(SEE SEE);

class A diag-a-styles;
class B diag-b-styles
class C diag-c-styles;

</div>
