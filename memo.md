# Memo

Notas, decisiones y backlog del proyecto Drop.

## 2026-08-25

- Repositorio creado en GitHub: https://github.com/mariaherdeal/Drop
- Copia/backup sincronizada en Google Drive: carpeta `Developer/Drop`
  (compartida con mariaherdeal11@gmail.com)
- Tienda Shopify conectada: Camila Hidalgo (camilahidalgo.com)

## 2026-08-26

- Se decide construir un sistema de agentes para el negocio: un **agente CEO** (el propio Claude Code trabajando en este repo, ver `CLAUDE.md`) que gestiona el negocio de forma global y delega tareas repetitivas en subagentes especializados definidos en `.claude/agents/`.
- Arrancamos solo con el CEO; los subagentes especializados se añaden uno a uno según haga falta. Roadmap propuesto (orden no definitivo, ver `.claude/agents/README.md`):
  1. Atención al cliente
  2. Búsqueda de producto
  3. Catálogo y precios
  4. Marketing y anuncios
- Se define la identidad completa del agente CEO: **Vega Duarte**. Combina 3 referencias reales investigadas a fondo — Jeff Bezos (liderazgo, 14 Leadership Principles), Nik Sharma (growth/ecommerce, framework TRACE) y Anton Kraly de Drop Ship Lifestyle (dropshipping y nicho, adaptado a moda) — y su lista de responsabilidades. Ver [.claude/agents/ceo.md](./.claude/agents/ceo.md).
  - Corrección durante la investigación: se había propuesto inicialmente "Ricky Hayes (Dropship Lifestyle)" como referencia de dropshipping, pero ese framework de nicho/alto ticket es en realidad de **Anton Kraly** (Drop Ship Lifestyle), no de Ricky Hayes (mentor real de dropshipping pero sin framework propio documentado públicamente).
- Se construye la estructura completa del repo: los 4 subagentes del roadmap (`atencion-cliente`, `busqueda-producto`, `catalogo-precios`, `marketing`) en `.claude/agents/`, cada uno con su carpeta de contenido en la raíz del repo, y `.claude/skills/` (vacía por ahora, ver su README para el criterio de cuándo añadir una skill).

## Decisiones

- _(pendiente)_

## Backlog / ideas

- [ ] Definir stack técnico (scripts en qué lenguaje, si habrá tema custom, etc.)
- [ ] Elegir proveedores de dropshipping
- [ ] Automatizar sincronización de inventario/precios
- [ ] Definir importe umbral para que `atencion-cliente` escale reembolsos al usuario
- [ ] Añadir Skills concretas a medida que se identifiquen tareas repetitivas (ver `.claude/skills/README.md`)

## Notas sueltas

- _(usa esta sección como bloc de notas rápido durante el desarrollo)_
