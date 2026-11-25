---
{"dg-publish":true,"permalink":"/proyecto-x/atlas/atlas-of/","dgShowLocalGraph":true,"dgEnableSearch":true,"created":"2026-11-19T14:23:10.632-03:00","ctime":"2026-11-19T14:23:10.632-03:00","mtime":"2026-11-25T18:19:51.813-03:00","dg-note-properties":{"created":"2026-11-19","type":null,"cover":null,"resumen":null,"tags":[]}}
---


Otras formas de Mirar, Ver, experimentar
Cartografías de otras formas, otros recorridos, otras lecturas 

---

```base
views:
  - type: cards
    name: últimas entradas
    filters:
      and:
        - type == "entrada"
    order:
      - file.name
      - resumen
    sort:
      - property: file.mtime
        direction: DESC
    limit: 6
    image: note.cover
    imageAspectRatio: 1.15
    cardSize: 130

```

---
[[ProyectoX/Propósito\|Propósito]] - Mapa - [[ProyectoX/Quien Soy\|Quien Soy]]