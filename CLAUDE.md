# CLAUDE.md

Contexto para Claude Code al trabajar en este repositorio.

## Proyecto

Dropshipping para la tienda Shopify **Camila Hidalgo** (camilahidalgo.com, plan Basic, moneda EUR, España).

## Cómo trabajar aquí

- El repo empieza vacío: no asumas una estructura de carpetas existente, pregunta o propón una antes de crear muchos archivos de golpe.
- Para cualquier operación sobre la tienda (productos, pedidos, inventario, catálogo, descuentos, analíticas) usa el conector MCP de Shopify en lugar de hardcodear llamadas a la Admin API a mano, salvo que el conector no cubra esa operación.
- Si se necesita una llamada GraphQL que no tiene tool dedicada, usar `graphql_query` / `graphql_mutation` del conector de Shopify.
- Mantén los precios y textos en EUR / español, coherente con la tienda.

## Convenciones

_(añadir aquí lenguaje/framework, estilo de código y comandos de test/build en cuanto se decidan)_

## Documentos relacionados

- [README.md](./README.md) — visión general del proyecto.
- [memo.md](./memo.md) — decisiones, notas y backlog.
