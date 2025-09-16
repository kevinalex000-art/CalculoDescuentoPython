# CalculoDescuentoPython

Este proyecto fue desarrollado como parte de una tarea de programación para practicar el uso de funciones en Python. El objetivo es calcular el descuento aplicado a una compra según el monto total y un porcentaje de descuento.

## Objetivo

- Practicar funciones con parámetros y valores predeterminados.
- Calcular descuentos en compras.
- Mostrar el monto final a pagar.
- Utilizar Git y GitHub para control de versiones.

## Funcionalidad

La función principal `calcular_descuento` recibe:

- `monto_total`: el total de la compra.
- `porcentaje_descuento`: el porcentaje de descuento (por defecto 10%).

Retorna el monto del descuento y permite calcular el total a pagar.

## Ejemplo de uso

```python
descuento = calcular_descuento(200.0, 15)
print(f"Descuento: ${descuento}")
