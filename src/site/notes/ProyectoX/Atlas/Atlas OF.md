---
{"dg-publish":true,"permalink":"/proyecto-x/atlas/atlas-of/","dgEnableSearch":true,"created":"2026-11-19T14:23:10.632-03:00","ctime":"2026-11-19T14:23:10.632-03:00","mtime":"2026-11-24T16:34:09.034-03:00","dg-note-properties":{"created":"2026-11-19","tags":[]}}
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