# Ventas de autos — entrevista

Dataset de 100 ventas de una red de automotoras ficticia (2025).

## Datos

Archivo: `ventas_autos.json` (array de objetos).

| Campo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador de la venta |
| fecha_venta | string (YYYY-MM-DD) | Fecha de la venta |
| vendedor | string | Vendedor que cerró la venta |
| sucursal | string | Sucursal |
| marca / modelo / anio | string / string / int | Vehículo |
| kilometraje | int | Km al momento de la venta |
| precio_lista | int (CLP) | Precio sin descuento |
| descuento_pct | int | Descuento aplicado (%) |
| precio_venta | int (CLP) | Precio final pagado |
| medio_pago | string | contado, crédito bancario, leasing, financiamiento automotriz |
| canal | string | Por dónde llegó el cliente |
| cliente_edad / cliente_ciudad | int / string | Datos del cliente |
| dias_en_inventario | int | Días que el auto estuvo en stock antes de venderse |
| entregado | bool | Si el auto ya fue entregado |

## Acceso

Leer el JSON desde el link de la entrega (raw) y trabajar con él en el lenguaje que prefieras.
