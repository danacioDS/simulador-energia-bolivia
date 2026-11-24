# EnergyBalance · Simulador energético de Bolivia

Modelo anual de escenarios (2026–2040) para ver cómo el agotamiento del gas natural afecta a la generación eléctrica y al abastecimiento de combustibles en Bolivia.

**Ver el simulador:** https://danaciods.github.io/simulador-energia-bolivia/

## Qué modela

El modelo tiene cuatro partes:

1. **Gas:** los campos existentes declinan, con un límite que imponen las reservas (1P, 2P o 3P). Se pueden sumar nuevos hallazgos, exportaciones e importaciones.
2. **Electricidad:** la hidroeléctrica (ajustada por la hidrología del año) y las renovables entran primero. La térmica a gas cubre el resto. Si falta gas, esa parte queda como energía no servida.
3. **Combustibles:** la producción nacional de diésel y gasolina sigue a la producción de condensado. Lo que falta se importa.
4. **Divisas:** si la factura de importación supera los dólares disponibles, todas las importaciones se recortan en la misma proporción.

Incluye cuatro escenarios predefinidos: Inercial, Reactivación upstream, Transición eléctrica y Crisis profunda.

## Datos de partida (2025–2026)

- Producción de gas: ~25 MMm³/d a inicios de 2026 (Fundación Jubileo, Correo del Sur).
- Reservas al 31/12/2025: 1P 2,30 TCF; 2P 2,76 TCF; 3P 3,24 TCF (certificación GLJ, YPFB).
- Mercado interno: ~15 MMm³/d. Exportación a Brasil: 7–8 MMm³/d (YPFB).
- Matriz eléctrica: ~66 % térmica a gas (CNDC, CBE).
- Combustibles: ~200 M L/mes de diésel y ~140 M L/mes de gasolina. Se importa ~86–95 % del diésel y ~56 % de la gasolina (YPFB).

## Limitaciones

Es un modelo simplificado para comparar escenarios, no un pronóstico oficial. Precios, divisas y tasas de crecimiento son supuestos que se pueden editar.

## Uso

Es un solo archivo `index.html` que no necesita servidor ni instalación. Se puede abrir directamente en el navegador o publicar con GitHub Pages.

---

Stratus Dynamics · EnergyBalance · © 2026 | MSc. Daniel Canedo
4-Layer Architecture: Data → Research → Decision → Intelligence
