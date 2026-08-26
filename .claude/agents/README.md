# Subagentes del negocio Drop

El **agente CEO** (Claude Code trabajando en este repo, ver [../../CLAUDE.md](../../CLAUDE.md)) orquesta el negocio y delega tareas repetitivas y especializadas en subagentes definidos aquí.

## Cómo añadir un subagente

Cada subagente es un archivo `.md` en esta carpeta con frontmatter (nombre, descripción, tools permitidas) e instrucciones específicas de su área. El CEO los invoca según la tarea lo requiera.

## Roster

| Agente | Área | Carpeta de contenido |
|---|---|---|
| [ceo.md](./ceo.md) — Vega Duarte | Dirección general del negocio | — |
| [atencion-cliente.md](./atencion-cliente.md) | Atención al cliente | [/atencion-cliente](../../atencion-cliente/) |
| [busqueda-producto.md](./busqueda-producto.md) | Búsqueda de producto | [/busqueda-producto](../../busqueda-producto/) |
| [catalogo-precios.md](./catalogo-precios.md) | Catálogo y precios | [/catalogo-precios](../../catalogo-precios/) |
| [marketing.md](./marketing.md) | Marketing y anuncios | [/marketing](../../marketing/) |

Ver Skills (procedimientos puntuales, distintos de los agentes de área) en [../skills/README.md](../skills/README.md).

Ver decisión original en [../../memo.md](../../memo.md) (2026-08-26).
