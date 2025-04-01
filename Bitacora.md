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
 

