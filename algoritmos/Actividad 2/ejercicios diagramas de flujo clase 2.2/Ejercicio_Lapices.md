# Cálculo del Costo de Lápices por Volumen

En este ejercicio determinamos el costo total a pagar por la compra de una cantidad determinada de lápices, aplicando un descuento por escala de volumen.

## Enunciado
![Enunciado del problema](img2/enunciado-ejercicio-lapices.png)

# Diagrama

![diagrama ejercicio](img2/diagrama-lapices.drawio.png)

## ¿Qué se hizo?

Se estructuró una solución basada en una condicional simple:
1. **Lectura:** Se solicita la cantidad de lápices que el usuario desea comprar.
2. **Evaluación de condición:** Se verifica si la cantidad es mayor o igual a 1,000 unidades.
   - Si **sí**, se calcula el total multiplicando la cantidad por $85.
   - Si **no**, se calcula multiplicando la cantidad por el precio base de $90.
3. **Salida:** Se despliega en pantalla el costo total a pagar.
