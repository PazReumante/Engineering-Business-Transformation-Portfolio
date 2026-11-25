# Ejemplo reproducible de flujo de caja

Ejercicio didáctico con **datos sintéticos en unidades monetarias** y flujos netos al final de cada año. La tasa anual es 10 %. Se mantiene la inversión inicial y se reduce el flujo anual en el escenario adverso.

| Escenario | Año 0 | Año 1 | Año 2 | VAN esperado |
| --- | ---: | ---: | ---: | ---: |
| Base | −100 | 60 | 60 | 4,13 |
| Adverso | −100 | 50 | 50 | −13,22 |

Calcula el valor actual neto (VAN) con la fórmula `flujo_0 + flujo_1 / 1.10 + flujo_2 / 1.10^2`. En una hoja de cálculo con los flujos en B2:D2, usa `=B2+C2/(1+10%) + D2/(1+10%)^2` y redondea a dos decimales. El cambio de signo muestra por qué conviene probar los supuestos de ingresos y costos.

Los valores se eligieron para ilustrar el método. Los resultados históricos del caso se describen en la [nota técnica](../docs/technical-analysis.md).
