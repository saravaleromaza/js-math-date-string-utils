# 🛠️ UTILIDADES Y OBJETOS NATIVOS EN JAVASCRIPT

Este repositorio contiene un script en JavaScript que demuestra el uso práctico de objetos nativos del lenguaje y métodos estándar para la manipulación de números aleatorios, fechas y cadenas de texto.

---

## 📌 CONTENIDO DEL CÓDIGO

El script se divide en tres partes principales:

1. **Generador de Identificador (`Objeto Math`):** 
   * Genera un número aleatorio entre 1000 y 9999 utilizando `Math.random()` y `Math.floor()` para crear un código de usuario único (`USR-XXXX`).
   * Muestra el valor de `Math.PI` formateado con dos decimales.

2. **Cálculo Temporal (`Objeto Date`):** 
   * Obtiene la fecha actual del sistema.
   * Define una fecha de referencia fija y calcula de forma precisa los días transcurridos mediante la diferencia en milisegundos.

3. **Formateo de Texto (`Métodos de Strings`):** 
   * Limpia espacios en blanco sobrantes utilizando `.trim()`.
   * Transforma el texto completo a mayúsculas con `.toUpperCase()`.
   * Cuenta el número total de caracteres de la cadena resultante usando `.length`.