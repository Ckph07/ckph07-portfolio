# Contexto de las capturas

Las seis imágenes de esta ficha se generaron el 4 de octubre de 2026 desde
la implementación Flutter Web de Family Finance OS, en un navegador de
prueba con viewport de 1440 × 1100 píxeles.

Se utilizaron respuestas API ficticias interceptadas por Playwright. No se
consultaron bases de datos familiares, no se utilizaron credenciales reales
y no se enviaron escrituras al backend operativo. La solicitud de vista
previa CSV también recibió una respuesta simulada.

| Imagen | Contexto |
|---|---|
| `dashboard-demo.png` | Vista Todos, acciones rápidas, indicadores y gasto por categoría |
| `accounts-demo.png` | Cuentas y efectivo de Alex y Ana, junto con una cuenta compartida |
| `budget-demo.png` | Presupuesto mensual, seis categorías y luz bimestral |
| `bimonthly-demo.png` | Edición de la línea Luz: pago de $2,000 y planeación mensual de $1,000 |
| `wealth-demo.png` | Activos manuales, tandas y snapshots ficticios |
| `csv-preview-demo.png` | Dos filas válidas y una fecha inválida, sin confirmar la importación |

## Datos de demostración

- Cuentas y efectivo: $39,000; el efectivo de $2,000 ya está incluido en ese total.
- Activos manuales: $48,000.
- Tandas: $8,000.
- Deudas: $14,500.
- Patrimonio neto: $39,000 + $48,000 + $8,000 - $14,500 = $80,500.
- Presupuesto mensual planeado: $9,900; gasto mostrado: $5,650; uso: 57.07%.

Los IDs con prefijo `demo-`, los nombres, las cuentas, los importes y el
histórico son ficticios. Las imágenes documentan la presentación y los
componentes implementados; no demuestran conciliación bancaria, rendimientos
de inversión ni validación de los contratos del backend.
