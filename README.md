# Red Team

Arsenal ofensivo organizado por categorías. Cada proyecto incluye la herramienta y, cuando aplica, la evidencia de su ejecución real en laboratorio.

## Estructura

```
Red-Team/
├── Exploits/   Exploits funcionales, con evidencia de ejecución
├── PoCs/       Pruebas de concepto y research de vulnerabilidades
├── Recon/      Enumeración, descubrimiento y fingerprinting
└── Tooling/    Utilidades y automatización
```

## Índice

### Exploits

| Proyecto | Vector | Evidencia |
|---|---|---|
| [php2shell](Exploits/php2shell-cve-2026-109618/) | CVE-2026-109618 / CVE-2026-109619 — PHP `session.upload_progress` → session file injection + LFI → RCE | GIF + MP4 |

### PoCs

_Pendiente._

### Recon

_Pendiente._

### Tooling

_Pendiente._

## Convenciones

Cada proyecto vive en su propia carpeta dentro de su categoría y contiene:

- `README.md` — vector, condiciones de explotabilidad, uso y parámetros.
- La herramienta o PoC, autocontenida y ejecutable.
- Evidencia de la ejecución (GIF/MP4) cuando aplica.
