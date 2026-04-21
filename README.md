# Rehab Tracker

Tracker de rehabilitación deportiva mobile-first. Single HTML file — React + Tailwind vía CDN, persistencia en `localStorage`.

## Demo

🔗 **https://maredbg-svg.github.io/Rehab-tracker/**

## Uso desde iPhone

1. Abre la URL en Safari
2. Botón Compartir → **Añadir a pantalla de inicio**
3. Se abre fullscreen, se siente app nativa

Los datos quedan en el `localStorage` de tu dispositivo — nada viaja a servidores.

## Stack

- React 18 + Tailwind (CDN)
- `localStorage` con shim compatible con `window.storage` de artifacts
- Dark mode automático (`prefers-color-scheme`)
- PWA meta tags para iOS "Añadir a pantalla de inicio"

## Release 1 (actual)

- [x] Plan semanal L-D con bloques AM/PM
- [x] Checkbox por ejercicio + guardar bloque
- [x] Input de dolor rodilla/lumbar (antes/después, 0-10)
- [x] KPIs: entreno cumplidos, dolor promedio
- [x] Timeline de fases
- [x] Persistencia entre sesiones

## Roadmap

- **R2** Nutrición — macros estimados por IA
- **R3** Chat IA + consulta diagnóstico
- **R4** Recálculo y cierre de día

## Privacidad

Plantilla genérica sin datos identificables. Agrega tu perfil y diagnósticos al usarla — quedan en tu dispositivo solamente.
