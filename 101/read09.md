# Introducción a Javascript

**¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?**

- Booleano. true y false.
- null. Una palabra clave especial que denota un valor nulo. (Dado que JavaScript distingue entre mayúsculas y minúsculas, null no es lo mismo que Null, NULL o cualquier otra variante).
- undefined. Una propiedad de alto nivel cuyo valor no está definido.
- Number. Un número entero o un número con coma flotante. Por ejemplo: 42 o 3.14159.
- BigInt. Un número entero con precisión arbitraria. Por ejemplo: 9007199254740992n.
- String. Una secuencia de caracteres que representan un valor de texto. Por ejemplo: "Hola"
- Symbol (nuevo en ECMAScript 2015). Un tipo de dato cuyas instancias son únicas e inmutables


**¿Cómo se utilizan las estructuras condicionales *if y else* en JavaScript, y qué propósito cumplen dentro de un programa?**

- Se utiliza ifpara especificar un bloque de código que se ejecutará, si una condición especificada es verdadera
+ Se utiliza elsepara especificar un bloque de código que se ejecutará, si la misma condición es falsa

¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?

Existen diferentes tipos de operadores de JavaScript:

- Operadores aritméticos
+ Operadores de asignación
+ Operadores de comparación
+ Operadores de cadena
+ Operadores lógicos
+ Operadores bit a bit
+ Operadores ternarios
+ Operadores de tipo

### Operadores Arimeticos:
|Operador|Descripcion|
|--------|-----------|
|+  |Adición|
|-  |Sustracción|
|**  |Exponentiation |
|/  |División|
|%  |Residuo|
|++  |Incremento|
|--  |Decremento|

**¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?**

Se puede declarar variables usando:

+ const: siempre que el valor no deba cambiar.
+ let: cuando necesites reasignar valores dentro de un bloque.
+ var: ya que su alcance amplio y su hoisting pueden generar errores inesperados.

