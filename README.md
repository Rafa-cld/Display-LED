# 🔢 7-Segment Display Simulator (Python)

Este proyecto simula un **display digital de 7 segmentos** utilizando caracteres en la consola. Puedes visualizar cualquier número como si estuviera en una pantalla LED, usando el carácter `#`.

---

## 🎯 ¿Qué hace este proyecto?

Toma un número entero ingresado en el código y lo representa visualmente usando una simulación de 7 segmentos, como los utilizados en calculadoras o relojes digitales.

---

## 💡 ¿Cómo funciona?

Cada dígito (0–9) se representa mediante una cadena de 7 bits que indican qué segmentos están encendidos (`1`) o apagados (`0`).

Ejemplo:  
`"1111110"` representa el número **0**, donde están encendidos todos los segmentos excepto el del medio.

El programa:
- Convierte cada dígito del número en su equivalente binario de 7 segmentos.
- Crea una representación de 5 filas por 3 columnas para cada dígito.
- Combina todos los dígitos horizontalmente y los imprime como líneas.

---
📦 Requisitos
Python 3.x

No se usan librerías externas

## 🖥️ Ejemplo de salida

```python
print_numbers(1234567890)

  # ### ### # # ### ### ### ### ### ### 
  #   #   # # # #   #     # # # # # # # 
  # ### ### ### ### ###   # ### ### # # 
  # #     #   #   # # #   # # #   # # # 
  # ### ###   # ### ###   # ### ### ### 
