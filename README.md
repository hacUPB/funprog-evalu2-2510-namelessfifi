[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/IYE4ssuc)
# Unidad No. 2
## Información del estudiante  
Nombre del estudiante:  Estefanía Santos 
ID: 572003
---
## Bitácora
# 🖥️. ¿Qué es un computador?
Un computador es una máquina electrónica que está diseñada para realizar tareas específicas. Con esta máquina se pueden desarrollar tareas que ahora hacen parte de nuestra vida cotidiana, como elaborar cartas o una hoja de vida, hablar con personas de otros países, hacer presupuestos, jugar y hasta navegar en internet.

Referencia: https://edu.gcfglobal.org/es/informatica-basica/que-es-un-computador/1/

# 🏗️. Arquitectura de computadoras
 la arquitectura de computadoras constituye la base conceptual y técnica que admite la creación de ordenadores y sistemas informáticos funcionales. Incluye la forma en que los componentes se comunican entre sí, la manera en que se gestionan los recursos, cómo se ejecutan las instrucciones, así como el procedimiento de almacenar y acceder a los datos.

 **Arquitectura de Von Neumann**

Fue propuesto por el matemático John Von Neumann en la década de 1940. Es una de las arquitecturas fundamentales en el campo, sirvió para la creación de la computadora EDVAC, que ha servido como fundamento para el diseño de ordenadores actuales. Se basa en la idea de tener una unidad central de procesamiento (CPU) que accede a una memoria compartida para almacenar tanto datos como programas. Las instrucciones y datos se guardan en la misma memoria y se recuperan a través de un bus (o canal) común.

**Arquitectura Harvard**

Es un modelo similar a la arquitectura de Von Neumann, pero este se caracteriza por utilizar memorias físicamente separadas para almacenar las instrucciones del programa y los datos de manera independiente. Esto permite que la CPU acceda simultáneamente a ambos, mejorando el rendimiento en ciertas aplicaciones específicas. Se ha usado principalmente en aplicaciones donde se requiere un alto rendimiento en el procesamiento de señales o en tareas específicas donde el acceso simultáneo a instrucciones y datos es ventajoso.

**Arquitectura RISC (Reduced Instruction Set Computer)**

Es un enfoque de diseño de procesadores y computadoras que se caracteriza por utilizar un conjunto de instrucciones reducido y altamente optimizado. Los procesadores RISC ejecutan instrucciones en un solo ciclo de reloj, lo que los hace más eficientes en operaciones simples y repetitivas. Además, pueden alcanzar altos niveles de rendimiento, siendo particularmente útiles en aplicaciones que requieren un procesamiento intensivo, como servidores y supercomputadoras. Su efectividad la ha convertido en la base para muchos procesadores modernos.

 **Arquitectura CISC (Complex Instruction Set Computer)**

A diferencia de RISC, los procesadores CISC utilizan un conjunto de instrucciones más amplio y diverso. Estas instrucciones pueden realizar tareas más complejas en un solo ciclo de reloj, lo que facilita la programación, pero puede afectar el rendimiento en ciertos escenarios. Por esta razón, a lo largo del tiempo, se han desarrollado técnicas para mejorar la ejecución de instrucciones CISC, como la segmentación (pipeline) y la ejecución fuera de orden (out-of-order execution).

# 👩🏾‍💻 ¿Qué es el Hardware?

Son el conjunto de los componentes materiales, tangibles, de un computador o un sistema informático. Incluye todas las partes mecánicas, eléctricas y electrónicas, sin considerar los programas y otros elementos digitales que  forman parte del software.

**Fuente:** https://concepto.de/hardware/#ixzz8zIbdapO1



### 1. **CPU (Unidad Central de Procesamiento)**

La **CPU** es el "cerebro" de la computadora, encargado de realizar los cálculos, las operaciones lógicas y el control del flujo de datos. La CPU ejecuta las instrucciones de los programas, realizando tareas fundamentales para que el sistema operativo y las aplicaciones funcionen correctamente.


- **ALU (Unidad Aritmético Lógica):**
    - **Definición:** Es una de las partes más importantes de la CPU. Se encarga de realizar operaciones aritméticas (como sumas y restas) y lógicas (como comparaciones).
    - **Función:** La ALU ejecuta operaciones matemáticas (como la suma, la multiplicación o la división) y operaciones lógicas (como las comparaciones de "mayor que" o "igual a"). También maneja las operaciones bit a bit en algunos casos.
  
- **Unidad de Control:**
    - **Definición:** La unidad de control es responsable de coordinar todas las actividades dentro de la CPU. Se encarga de interpretar las instrucciones de los programas y controlar el flujo de datos entre los diferentes componentes de la computadora.
    - **Función:** Su principal función es dirigir el flujo de datos entre la ALU, los registros y la memoria, asegurándose de que las operaciones se ejecuten de manera ordenada y eficiente.

- **Registros:**
    - **Definición:** Los registros son pequeñas ubicaciones de almacenamiento dentro de la CPU. Son muy rápidas y se utilizan para almacenar temporalmente datos e instrucciones que están siendo procesadas.
    - **Función:** Los registros se utilizan para almacenar resultados intermedios de cálculos, direcciones de memoria, o instrucciones que la CPU necesita procesar. Existen diferentes tipos de registros, como los registros de datos, los registros de direcciones y los registros de estado.

- **Buses:**
    - **Definición:** Un bus es un conjunto de líneas o circuitos que transportan datos entre diferentes componentes de la computadora.
    - **Función:** Los buses permiten la comunicación entre la CPU, la memoria y otros dispositivos de entrada/salida. Existen varios tipos de buses, como el bus de datos, el bus de direcciones y el bus de control.

### 2. **Memoria**

La memoria es una parte esencial del hardware que permite almacenar datos e instrucciones para su procesamiento. Existen diferentes tipos de memoria, cada una con distintas características de velocidad y capacidad.

#### Tipos de memoria:

- **Registros:**
    - **Definición:** Son pequeñas ubicaciones dentro de la CPU que almacenan información temporalmente.
    - **Función:** Los registros permiten a la CPU acceder rápidamente a los datos y realizar operaciones sin tener que acceder a la memoria principal. Son muy rápidos, pero tienen una capacidad limitada.

- **Caché:**
    - **Definición:** La caché es una memoria de acceso ultrarrápido que se encuentra entre la CPU y la memoria principal (RAM).
    - **Función:** Su función es almacenar temporalmente los datos más frecuentemente utilizados, para que la CPU pueda acceder a ellos rápidamente sin tener que acceder a la memoria RAM, que es más lenta. La caché reduce significativamente el tiempo de acceso a los datos y mejora el rendimiento del sistema.

- **Memoria Principal (RAM - Memoria de Acceso Aleatorio):**
    - **Definición:** La RAM es la memoria principal de la computadora, que almacena datos e instrucciones que están en uso activo por los programas.
    - **Función:** La RAM permite a la CPU acceder rápidamente a los datos que están siendo procesados. Es volátil, lo que significa que pierde los datos cuando se apaga el sistema.

- **Memoria Secundaria (Disco Duro y Unidades Externas de Almacenamiento):**
    - **Definición:** Son dispositivos de almacenamiento a largo plazo, como los discos duros (HDD), las unidades de estado sólido (SSD) y las unidades externas (pendrives, discos duros externos).
    - **Función:** La memoria secundaria se utiliza para almacenar datos de manera permanente, incluso cuando el equipo está apagado. Los discos duros y las SSDs ofrecen un gran almacenamiento de datos, aunque son más lentos que la memoria RAM.

### 3. **Dispositivos de Entrada / Salida**

Los dispositivos de entrada y salida permiten la interacción entre el usuario y la computadora. Los dispositivos de **entrada** permiten que el usuario envíe información al sistema, mientras que los dispositivos de **salida** permiten que el sistema envíe información al usuario.

#### Dispositivos de Entrada:
- **Teclado:** Permite al usuario introducir texto y comandos.
- **Ratón (Mouse):** Permite al usuario interactuar con la interfaz gráfica de la computadora.
- **Escáner:** Convierte imágenes físicas en formatos digitales.
- **Micrófono:** Permite la entrada de sonido o voz al sistema.

#### Dispositivos de Salida:
- **Monitor:** Muestra información visual al usuario.
- **Impresora:** Permite que el usuario imprima documentos en papel.
- **Altavoces:** Permiten emitir sonidos al usuario.



# 🎮 ¿Qué es el Software?

Conjunto de programas que permiten el funcionamiento del hardware.

**— Software de sistema:** Gestiona recursos del hardware (SO, drivers, BIOS).

**— Software de aplicación:** Programas para el usuario (navegadores, editores de texto).

**— Software de desarrollo:** Herramientas para programadores (compiladores, IDEs).

**Fuente:** https://concepto.de/software/

# 📲 Funcionamiento del computador.
**Procesos al encender la computadora:**

— BIOS/UEFI: Realiza el POST (Power-On Self Test).

— Carga del SO: Se busca el sistema operativo en el almacenamiento.

— Inicialización: Se configuran drivers y procesos.

**Procesamiento de datos (ejemplo: teclado a pantalla)**

— Entrada por teclado.

— CPU interpreta y procesa la entrada.

— Resultado enviado a la GPU.

— La pantalla muestra la salida.

**Codificación interna de datos**

— Datos representados en binario (0 y 1).

— Uso de sistemas como ASCII, Unicode para caracteres.

**Unidades de medida de datos**

— Bit: Unidad mínima (0 o 1).

— Byte: 8 bits.

— Kilobyte (KB): 1024 bytes.

— Megabyte (MB): 1024 KB.

— Gigabyte (GB): 1024 MB.

— Terabyte (TB): 1024 GB.