# Comparador de Presupuestos de Obra

Comparador de precios de materiales de construcción para la obra en Cañuelas, Buenos Aires.

## Cómo usarlo

Abrí [la página](https://TU-USUARIO.github.io/comparador-obra) desde cualquier dispositivo — celular, tablet o compu.

## Qué incluye

- **📊 Precios** — Comparación ítem por ítem entre los 6 proveedores. Tocá cada ítem para ver todos los precios.
- **🏆 Mix óptimo** — Distribución recomendada: cada material al proveedor más barato disponible.
- **💰 Ahorro** — Cuánto ahorrás comprando a 1, 2, 3 o más proveedores vs comprarle todo a uno solo.
- **🛒 Compras realizadas** — Registro de montos ya pagados a cada proveedor.

## Proveedores cargados

| Proveedor | Descuento | Nota |
|---|---|---|
| Casa Caeiro | –10% efectivo | |
| Da Silva | precio neto | |
| LH Hnos | –10% efectivo | cobertura parcial |
| Curtoni | –10% efectivo | cobertura parcial |
| 7 Hnos | precio efectivo | ⚠️ hierros marca Bragado |
| La Esperanza | precio efectivo | actualizado 22/06/2026 |

## Cómo publicar en GitHub Pages

1. Creá un repositorio nuevo en GitHub llamado `comparador-obra`
2. Subí este archivo `index.html`
3. Andá a Settings → Pages → Source: `main` → `/root`
4. La URL va a ser: `https://TU-USUARIO.github.io/comparador-obra`

## Cómo actualizar precios

Abrí `index.html` con cualquier editor de texto y buscá el objeto `PROVEEDORES`. Cada proveedor tiene un objeto `p` con los precios unitarios (sin descuento — el descuento se aplica automáticamente con el campo `desc`).

Actualizaciones frecuentes: La Esperanza suele mandar nuevas listas. Buscar `esperanza` y actualizar los valores del objeto `p`.
