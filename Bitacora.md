# Actividad 2.

1. Una computadora trabaja con un sistema de ceros y unos. Los números se transforman en binario, las letras usan códigos como ASCII, y las imágenes se forman con píxeles que tienen valores de color. Todo, desde sonidos hasta videos, se almacena y procesa en combinaciones de estos dos dígitos.

2. El número de estados diferentes que pueden ser representados por 𝑁 variables binarias es 2𝑁.

3. ![tabla](Imágenes)

4.  Es fundamental porque permitió la creación de circuitos electrónicos y procesadores que usan estos principios para realizar cálculos y tomar decisiones en las computadoras modernas, su trabajo es la base de la lógica computacional moderna y la teoría detrás de la representación de estados en sistemas binarios.

# Actividad 3.

1. 1010101010/2=682/10

​2. 11111/2=31/10

​3. 10000000/2=128/10

​4.  100100100/2=292/10

# Actividad 4.

Los lenguajes de programación como C, Java y Python utilizan diversos tipos de datos para representar diferentes clases de información. A continuación, se presenta una tabla que resume los tipos de datos utilizados en estos lenguajes, incluyendo sus nombres, abreviaturas (cuando existen) y características principales:

| **Nombre de la variable** | **Abreviatura** | **Lenguaje(s)** | **Características principales** |
|---------------------------|-----------------|-----------------|----------------------------------|
| **Entero**               | `int`           | C, Java, Python | Representa números enteros. En C y Java, puede ser con o sin signo; en Python, es de precisión arbitraria. |
| **Entero largo**         | `long`          | C, Java         | En C, representa enteros más grandes; en Java, es un entero de 64 bits con signo. |
| **Carácter**            | `char`          | C, Java         | En C y Java, representa un solo carácter Unicode de 16 bits. |
| **Cadena de caracteres**| `string`        | Python          | En Python, es una secuencia inmutable de caracteres. En C y Java, se utilizan arreglos de caracteres o clases específicas. |
| **Flotante**            | `float`         | C, Java         | En C y Java, representa números de punto flotante de precisión simple (32 bits). |
| **Doble precisión**     | `double`        | C, Java         | En C y Java, representa números de punto flotante de doble precisión (64 bits). |
| **Booleano**           | `bool`          | C, Java, Python | Representa valores de verdad: `true` o `false`. |
| **Complejo**           | `complex`       | Python          | En Python, representa números complejos con parte real e imaginaria. |
| **Lista**               | `list`          | Python          | En Python, es una colección ordenada y mutable de elementos. |
| **Tupla**               | `tuple`         | Python          | En Python, es una colección ordenada e inmutable de elementos. |
| **Conjunto**            | `set`           | Python          | En Python, es una colección no ordenada de elementos únicos. |
| **Diccionario**         | `dict`          | Python          | En Python, es una colección de pares clave-valor. |

**Procedimiento para calcular el espacio en memoria:**

1. **Identificador numérico (`int`):**
   - **C:** Generalmente ocupa 4 bytes (32 bits).
   - **Java:** Ocupa 4 bytes (32 bits).
   - **Python:** El tamaño es dinámico, pero típicamente ocupa más de 4 bytes debido a su naturaleza de precisión arbitraria.

2. **Temperatura (`float`):**
   - **C:** Ocupa 4 bytes (32 bits).
   - **Java:** Ocupa 4 bytes (32 bits).
   - **Python:** Ocupa 4 bytes (32 bits).

3. **Valor lógico (`bool`):**
   - **C:** Generalmente ocupa 1 byte (8 bits).
   - **Java:** Ocupa 1 byte (8 bits).
   - **Python:** Ocupa 1 byte (8 bits).

4. **Texto con 10 caracteres (`string`):**
   - **C:** Cada carácter ocupa 1 byte; por lo tanto, 10 caracteres ocupan 10 bytes.
   - **Java:** Cada carácter ocupa 2 bytes (UTF-16); por lo tanto, 10 caracteres ocupan 20 bytes.
   - **Python:** Cada carácter ocupa 1 byte en codificación ASCII; por lo tanto, 10 caracteres ocupan 10 bytes. Sin embargo, si se utilizan caracteres Unicode, puede variar.

**Cálculo del espacio total requerido:**

- **C y Java:**
  - `int` (4 bytes) + `float` (4 bytes) + `bool` (1 byte) + `string` (10 bytes) = 19 bytes.
  - Redondeando a múltiplos de 4 bytes (alineación de memoria), se requieren 20 bytes.

- **Python:**
  - `int` (aproximadamente 4 bytes) + `float` (4 bytes) + `bool` (1 byte) + `string` (10 bytes) = aproximadamente 19 bytes.
  - Considerando la sobrecarga de objetos en Python, se pueden requerir alrededor de 24 bytes.

**Espacio total durante 24 horas:**

- **Frecuencia de almacenamiento:** Cada 10 segundos durante 24 horas.
  - 24 horas = 86,400 segundos.
  - Número de registros = 86,400 / 10 = 8,640 registros.

- **Espacio total requerido:**
  - **C y Java:** 8,640 registros × 20 bytes = 172,800 bytes (aproximadamente 168.75 KB).
  - **Python:** 8,640 registros × 24 bytes = 207,360 bytes (aproximadamente 202.5 KB).


La representación de datos en las computadoras varía según el lenguaje de programación utilizado, afectando el espacio de memoria requerido. Lenguajes como C y Java, con tipado estático, permiten un control más preciso sobre el uso de memoria. Python, al ser de tipado dinámico, ofrece mayor flexibilidad pero con un mayor consumo de memoria debido a su manejo interno de objetos. Comprender estas diferencias es crucial para optimizar el rendimiento y el uso de recursos en el desarrollo de software. 

# Actividad 5.

Los diagramas de flujo utilizan símbolos específicos para representar diferentes operaciones y pasos de un proceso. Cada símbolo tiene un propósito específico y se usa de manera estándar para hacer los diagramas más fáciles de leer y entender. Aquí te dejo un resumen de los símbolos más comunes:

1. **Inicio/Fin**: Este símbolo se usa para marcar el inicio y el final de un proceso. Es un óvalo o elipse.
   
2. **Proceso**: Representa una acción o una operación que se realiza. Este símbolo es un rectángulo.

3. **Decisión**: Se utiliza cuando en el flujo se debe tomar una decisión (sí/no, verdadero/falso). Este símbolo es un rombo.

4. **Entrada/Salida**: Indica la entrada o salida de datos del sistema. Este símbolo es un paralelogramo.

5. **Conector**: Es un círculo pequeño que se usa cuando el diagrama tiene que saltar a otra parte del diagrama o página. Sirve para conectar distintas secciones.

6. **Documento**: Se utiliza para representar un documento generado o utilizado durante el proceso. Se dibuja como un rectángulo con una línea ondulada en la parte inferior.

7. **Preparación**: Este símbolo indica que se están preparando datos o valores antes de realizar una operación. Se dibuja como un rectángulo con bordes inclinados.

8. **Almacenamiento de datos**: Representa cuando se guarda información en una base de datos o en algún lugar de almacenamiento. Se dibuja con un paralelogramo con líneas horizontales.

9. **Línea de flujo**: Es simplemente una flecha que muestra la dirección en la que sigue el proceso en el diagrama.

10. **Subproceso**: Este símbolo se usa cuando hay un proceso predefinido o que se ha definido en otro lugar. Se representa con un rectángulo con bordes dobles.

# Actividad 6.

 
###  Identificar Algoritmos

1. **Una página web.**
   - **No es un algoritmo.**
   - **Por qué:** Aunque una página web tiene contenido e interactividad, no describe un conjunto de pasos claros para resolver un problema, que es lo que define a un algoritmo.

2. **Una receta para hacer un pastel, donde se indican ingredientes y pasos a seguir.**
   - **Sí es un algoritmo.**
   - **Por qué:** Una receta tiene pasos ordenados que debes seguir para obtener un resultado específico, en este caso, el pastel. Esto es exactamente lo que hace un algoritmo.

3. **"Piensa en un número y multiplícalo por otro".**
   - **No es un algoritmo completo.**
   - **Por qué:** Aunque es una operación matemática, no está bien definida ni tiene el conjunto completo de instrucciones para que se pueda considerar un algoritmo.

4. **Un manual de instrucciones para armar un mueble, con pasos detallados y un orden claro.**
   - **Sí es un algoritmo.**
   - **Por qué:** Un manual de instrucciones tiene pasos ordenados y específicos que te llevan a un resultado (un mueble armado), lo que cumple con la definición de algoritmo.

5. **Una lista de compras organizada en orden alfabético.**
   - **No es un algoritmo.**
   - **Por qué:** Aunque es una lista organizada, no describe un proceso para resolver un problema o hacer algo paso a paso, por lo que no se considera un algoritmo.


###  Variables y Constantes

1. **El valor de la gravedad en la Tierra, 9.8 m/s².**
   - **Es una constante.**
   - **Por qué:** La gravedad en la Tierra es un valor fijo que no cambia, así que es una constante.

2. **La edad de una persona calculada en base al año actual y su año de nacimiento.**
   - **Es una variable.**
   - **Por qué:** La edad cambia con el tiempo, así que es una variable, ya que depende del año actual.

3. **La cantidad de dinero en una cuenta bancaria.**
   - **Es una variable.**
   - **Por qué:** El dinero en una cuenta bancaria cambia constantemente dependiendo de las transacciones, por lo que es una variable.

4. **La velocidad de la luz en el vacío, 299,792,458 m/s.**
   - **Es una constante.**
   - **Por qué:** La velocidad de la luz es un valor fijo que no cambia, así que es una constante.

5. **El radio de un círculo.**
   - **Es una variable.**
   - **Por qué:** El radio de un círculo puede variar dependiendo del círculo, por lo que es una variable.

   ###  Características de los Algoritmos

1. **Para elegir la ruta más corta entre varias ciudades, el algoritmo examina rutas candidatas, deteniéndose cuando los cambios en la distancia parecen lo suficientemente pequeños.**
   - **No cumple con las características de un algoritmo.**
   - **Justificación:** Este enunciado no describe un algoritmo de manera completa. Aunque habla de examinar rutas, no especifica claramente los pasos a seguir, ni qué condiciones exactas detendrían el proceso de forma precisa y definitiva. Un algoritmo debe ser finito y debe tener un conjunto claro de pasos que garanticen que se llegue a un resultado.

2. **Suma los números ingresados y muestra el resultado.**
   - **Sí cumple con las características de un algoritmo.**
   - **Justificación:** Este enunciado describe un proceso claro y finito con pasos definidos: tomar dos números, sumarlos y mostrar el resultado. Es un algoritmo simple y directo.

3. **Un conjunto de pasos para calcular el área de un rectángulo dado su base y altura.**
   - **Sí cumple con las características de un algoritmo.**
   - **Justificación:** Este enunciado describe de manera clara un conjunto de pasos (obtener la base, obtener la altura, multiplicarlas y dar el resultado). Es un proceso definido y finito.

4. **El algoritmo cuenta el número de votos obtenidos por cada uno de los candidatos de una elección para presidente. Empieza solicitando el nombre del candidato y finaliza cuando se ingresa el valor -1.**
   - **Sí cumple con las características de un algoritmo.**
   - **Justificación:** Este enunciado describe claramente un proceso secuencial con un inicio (solicitar el nombre del candidato) y un final (cuando se ingresa -1). Los pasos están definidos, y el algoritmo terminaría después de contar los votos de los candidatos.

---

###  Comprensión de Herramientas

1. **El pseudocódigo utiliza símbolos estándar para representar las operaciones lógicas.**
   - **Falso.**
   - **Justificación:** El pseudocódigo es una forma de describir un algoritmo usando un lenguaje más cercano al humano que a un lenguaje de programación formal. No utiliza símbolos estándar como los diagramas de flujo, sino más bien palabras y estructuras que son comprensibles para las personas.

2. **Los diagramas de flujo son una representación gráfica de un algoritmo.**
   - **Cierto.**
   - **Justificación:** Los diagramas de flujo son una representación gráfica que muestra cómo se ejecutan los pasos de un algoritmo. Usan símbolos específicos (como rectángulos, rombos, flechas) para representar las operaciones y decisiones dentro del algoritmo.

3. **El pseudocódigo debe estar escrito en un lenguaje de programación específico.**
   - **Falso.**
   - **Justificación:** El pseudocódigo no se escribe en un lenguaje de programación específico. Es una forma abstracta de escribir un algoritmo utilizando un lenguaje que se asemeja al lenguaje natural y a la vez a las estructuras de programación, pero no está atado a un lenguaje concreto.

4. **Un diagrama de flujo siempre debe tener un inicio y un fin claramente definidos.**
   - **Cierto.**
   - **Justificación:** Un diagrama de flujo siempre debe tener un punto de inicio y de fin para que sea claro y comprensible. Esto asegura que el proceso sea finito y que haya una estructura clara para seguir el flujo del algoritmo.

---

###  Estructuras de Control

Las **estructuras de control** son fundamentales en los algoritmos y programas, ya que permiten tomar decisiones o repetir acciones según ciertas condiciones. Existen principalmente tres tipos de estructuras de control: secuenciales, de selección (condicionales) y de repetición (bucles).

#### Ejemplo 1
- **Situación:** Imagina que estás decidiendo si salir a correr o no dependiendo del clima.
  - **Decisión (Selección):** Si está lloviendo, no salgo a correr. Si no está lloviendo, entonces salgo a correr.
  - **Estructura de control:** **Condicional (if)**: Si se cumple la condición (que esté lloviendo), entonces no realizas la acción de correr. Si no se cumple, haces la acción de salir a correr.

#### Ejemplo 2
- **Situación:** Supongamos que quieres calcular si puedes comprar un producto basado en el dinero que tienes disponible y el precio del producto.
  - **Cálculo y decisión:** Si el dinero que tienes es mayor o igual al precio del producto, entonces puedes comprarlo. Si no, no puedes comprarlo.
  - **Estructura de control:** **Condicional (if)**, con una operación matemática para comparar el dinero disponible con el precio. Si el resultado de la comparación es verdadero, compras el producto; si es falso, no compras.





