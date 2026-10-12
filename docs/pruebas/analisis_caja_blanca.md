# Pruebas: análisis de caja blanca

## Objetivo

El análisis de caja blanca comprueba la lógica interna de una aplicación, sus condiciones y sus caminos de ejecución.

## Función de cálculo del pedido

La función debe recorrer los productos, multiplicar cada precio por las unidades solicitadas y sumar los importes.

## Casos de prueba

| Caso | Entrada | Resultado esperado |
|---|---|---|
| P01 | Un producto y dos unidades | Precio multiplicado por dos |
| P02 | Varios productos | Suma de los importes |
| P03 | Pedido vacío | Total igual a cero |
| P04 | Cantidad negativa | Rechazo de la entrada |
| P05 | Precio negativo | Rechazo de la entrada |

## Criterios de aceptación

La función debe calcular los importes válidos y rechazar los valores que incumplan las reglas.

Los resultados deberán verificarse ejecutando las pruebas sobre la implementación real.
