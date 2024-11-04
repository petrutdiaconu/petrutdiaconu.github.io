<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

![Text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[HomePage](index.md)

# Diagrame de tip _Flowchart_

```
```mermaid
flowchart LR
A[Anul I] -->|Tranzitie usoara| B[Anul II]
A(Anul I) --> B(Anul II)
A[/Anul I/] --> B[\Anul II\]
A -.->|Tranzitie grea| C[\Anul IV/]
C -->|Tranzitie medie| D[Master]
```

```mermaid
flowchart LR
A[Anul I] -->|Tranzitie usoara| B[Anul II]
A(Anul I) --> B(Anul II)
A[/Anul I/] --> B[\Anul II\]
A -.->|Tranzitie grea| C[\Anul IV/]
C -->|Tranzitie medie| D[Master]
```

**De retinut:**
- Driagramele _flowchart_ au _noduri_ si _conectori_
- Nodurile au:
  - **forma** (data de parantezele folosite la deschiderea _nodului_)
  - ID (sirul folofsit in afara descrierii _nodului_)
  - Descrierea (textului ce apare in caseta nodului si care este implementat in interiorul diferitelor tipuri de parateze - ce decit forma casetei nodului)
- Conectorii au:
  - Diferite tipuri de sageti sau chiar pot activa fara segeti
  - Diferite tipuri de linii:
  - `-->` linie continua (sageata dreapta)
  - `--` linie contiuna (fara sageti)
  - `<-->` linie continua (sageata stanga si sageata dreapta)
  - `==>` linie ingrosata cu sageata spre dreapta

## Diagrame _FLowchart_ avansate

```
A & B --> C & D & E --> F & G
```

# Diagrama de tip _TimeLine_

```mermaid
timeline
title "My Timeline"
section "Sectiunea 1"
2023-2024
        : am luat la facultate
        : am luat contact cu mediul academic
2024-2025
        : am terminat anul I
        : am facut practica

section "Sectiunea 2"

2025-2026
        : am facut practica la fotogrametrie
2026-2027 : Anul terminal IV 
         : Am terminat facultatea
```
