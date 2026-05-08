# forms-ufm-madrid

Repositorio público para formularios y páginas web de UFM Madrid.
Sirve contenido en: **https://afabra-commits.github.io/forms-ufm-madrid/**

---

## Estructura

```
forms-ufm-madrid/
├── .nojekyll               ← evita que GitHub procese con Jekyll
└── verano-2026/
    ├── index.html          ← página de actividades extracurriculares
    └── img/
        └── campus_azulejo.png
```

Cada proyecto ocupa su propia subcarpeta. Las nuevas páginas siguen el mismo patrón.

---

## Flujo de trabajo

**Este repositorio es solo de publicación. El trabajo se hace en `ia_workspace`.**

1. Abrir sesión de Claude Code en `ia_workspace`
2. Leer el `CLAUDE.md` del proyecto correspondiente en `ia_workspace`
3. Preparar los datos (por ejemplo, `actividades.md`) en `ia_workspace`
4. Claude edita el HTML en este repositorio (`forms-ufm-madrid/`)
5. Commit y push desde `forms-ufm-madrid/`
6. La página queda publicada en 1-2 minutos

---

## Páginas publicadas

| Página | URL | Proyecto en ia_workspace |
|---|---|---|
| Verano 2026 — actividades extracurriculares | [/verano-2026/](https://afabra-commits.github.io/forms-ufm-madrid/verano-2026/) | `Desarrollo de proyectos/Verano 2026/Extra académicas/` |
