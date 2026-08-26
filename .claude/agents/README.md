# Subagentes del negocio Drop

El **agente CEO** (Claude Code trabajando en este repo, ver [../../CLAUDE.md](../../CLAUDE.md)) orquesta el negocio y delega tareas repetitivas y especializadas en subagentes definidos aquí.

## Cómo añadir un subagente

Cada subagente es un archivo `.md` en esta carpeta con frontmatter (nombre, descripción, tools permitidas) e instrucciones específicas de su área. El CEO los invoca según la tarea lo requiera.

## Roster

_(vacío por ahora — se añaden a medida que el CEO detecta tareas repetitivas que conviene delegar)_

## Roadmap propuesto

Orden no definitivo, priorizar según lo que más tiempo consuma en cada momento:

1. **Atención al cliente** — responder emails/mensajes de clientes (devoluciones, dudas de pedidos, seguimiento) vía Gmail/Shopify.
2. **Búsqueda de producto** — investigar y evaluar productos ganadores (tendencias, proveedores, márgenes).
3. **Catálogo y precios** — sincronizar inventario, precios y estado de productos entre proveedor y Shopify.
4. **Marketing y anuncios** — generar copys, analizar campañas y sugerir escalado.

Ver decisión en [../../memo.md](../../memo.md) (2026-08-26).
