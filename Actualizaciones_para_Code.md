# Actualizaciones para Code — corrida 18/11/2026 (termómetro noviembre, provisorio)

## Cambio estructural: MAURO SALIÓ (ya pagado)
- Descontado en el Maestro general. Fondo activo (4) = **$412.191.683**. %: Francisco 80,67 · Gastón 9,10 · Gerard 7,87 · Turco 2,35.

## Maestro general (1ChNa..., gid 1962812297) — EDITADO
- **Agregadas 5 filas de stock:** 1331, 1333, 1334, 1335, 1336 (Saldo inv = −costo). Total asignado $79.790.000.
- **Reclasificados a liquidez (cobrado>costo):** 1301 (fila 92), 1308 (fila 94), 1326 (fila 106) → de "senado (NO cuenta liq)" a "vendido noviembre". 1308 quedó margen levemente negativo (−$95.334).
- **Total recalculado (hardcode):** Saldo inv $26.306.550 · Ingreso $1.623.370.315 · Egreso $1.497.375.644 · Valor ref $1.404.324.583 · Comisión ag $99.317.837 · Egreso total $1.596.693.481 · Ganancia inv $66.211.889 · Gan bruta $165.529.726.
- Tabs de cierre: Octubre cerrado y cierre mauro ya hechos. Noviembre: tab de cierre = paso manual de diciembre.

## data.json (dashboard) — ACTUALIZADO (push pendiente de Gastón)
- Noviembre: cajaLiquida 26.306.550 · capitalAutos 384.774.999 · fondoTotal 411.081.549 · autosStock 22 · autosSenados 4 · autosVendidos 5
- Vendidos que cuentan: 1213, 1315, 1301, 1308, 1326 (margen inv $1.499.015). Señas: 1229, 1278, 1283, 1307.
- 5 autos nuevos en autosEnStock. `index.html` no se toca. Backup: data.json.bak_1118.

## Para administración / Gastón
1. **1308**: definir si queda como venta (margen ~0 negativo) o vuelve a seña.
2. **Señas (1229, 1283, 1307)**: confirmar completamiento y precio final.
3. **Comisiones de noviembre**: para el cierre formal.
