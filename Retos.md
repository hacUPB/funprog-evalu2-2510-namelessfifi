# Retos. 😵‍💫
A continuación, se presenta un análisis detallado de cada uno de los problemas planteados, incluyendo la clasificación de variables, ecuaciones involucradas y un enfoque analítico para la solución.

### Reto 1: Distancia entre dos puntos en el plano cartesiano.

**Variables:**
- **Entrada:** 
  - \( x_1, y_1 \) (coordenadas del primer punto)
  - \( x_2, y_2 \) (coordenadas del segundo punto)
- **Salida:** 
  - \( d \) (distancia entre los dos puntos)
- **Constantes:** 
  - Ninguna

**Ecuación:**
√( x₂ − x₁ ) ₂ + ( y₂ − y₁ ) ₂ 

**Pseudocódigo**
Inicio
    Leer x1, y1, x2, y2
    dx = x2 - x1
    dy = y2 - y1
    distancia = sqrt(dx^2 + dy^2)
    Imprimir distancia
Fin


**Enfoque analítico:**
1. Leer las coordenadas de los dos puntos.
2. Aplicar la fórmula de distancia.
3. Mostrar el resultado.

### Reto 2: Conversión de metros a pulgadas

**Variables:**
- **Entrada:** 
  - \( m \) (medida en metros)
- **Salida:** 
  - \( p \) (medida en pulgadas)
- **Constantes:** 
  - \( 1 \text{ pulgada} = 0.0254 \text{ m} \)

**Ecuación:**
Multiplicar el valor de longitud por 39.37

**Pseudocódigo**
Inicio
    Leer metros
    pulgadas = metros / 0.0254
    Imprimir pulgadas
Fin


**Enfoque analítico:**
1. Leer la medida en metros.
2. Convertir a pulgadas usando la constante.
3. Mostrar el resultado.

### Reto 3: Determinación de la edad y cumpleaños

**Variables:**
- **Entrada:** 
  - Fecha de nacimiento
  - Fecha actual
- **Salida:** 
  - Edad actual
  
- **Constantes:** 
  - Ninguna

**Ecuaciones:**
1. Edad = año actual - año de nacimiento.
2. Ajustar la edad si el cumpleaños no ha ocurrido.

**Pseudocódigo**
Inicio
    Leer dia_nacimiento, mes_nacimiento, año_nacimiento
    Leer dia_actual, mes_actual, año_actual

    edad = año_actual - año_nacimiento
    Si (mes_actual < mes_nacimiento) o (mes_actual == mes_nacimiento y dia_actual < dia_nacimiento)
        edad = edad - 1
    FinSi

    Si (dia_actual == dia_nacimiento y mes_actual == mes_nacimiento)
        Imprimir "Feliz Cumpleaños"
    FinSi

    Imprimir "Edad: ", edad
Fin



**Enfoque analítico:**
1. Leer las fechas de nacimiento y actual.
2. Calcular la edad.
3. Determinar si el cumpleaños ya ocurrió o es hoy.
4. Mostrar el resultado.

### Reto 4: Cálculo del sueldo semanal

**Variables:**
- **Entrada:** 
  - Horas trabajadas en la semana
  - Pago por hora
- **Salida:** 
  - Sueldo semanal
- **Constantes:** 
  - Ninguna

**Ecuaciones:**
1. Sueldo base hasta 40 horas.
2. Sueldo con recargos para horas extras.

**Pseudocódigo**
Inicio
    Leer horas_trabajadas, pago_por_hora

    Si (horas_trabajadas <= 40)
        sueldo = horas_trabajadas * pago_por_hora
    SinoSi (horas_trabajadas <= 45)
        sueldo = (40 * pago_por_hora) + ((horas_trabajadas - 40) * 2 * pago_por_hora)
    SinoSi (horas_trabajadas <= 50)
        sueldo = (40 * pago_por_hora) + (5 * 2 * pago_por_hora) + ((horas_trabajadas - 45) * 3 * pago_por_hora)
    FinSi

    Imprimir sueldo
Fin



**Enfoque analítico:**
1. Leer horas trabajadas y pago por hora.
2. Calcular el sueldo según las reglas de pago.
3. Mostrar el resultado.

### Reto 5: Conteo de números

**Variables:**
- **Entrada:** 
  - Cantidad de números a evaluar
- **Salida:** 
  - Contadores
- **Constantes:** 
  - Ninguna

**Pseudocódigo**

Inicio
    Leer N
    cero = 0
    negativo = 0
    positivo = 0

    Para i = 1 hasta N
        Leer numero
        Si numero == 0
            cero = cero + 1
        SinoSi numero < 0
            negativo = negativo + 1
        Sino
            positivo = positivo + 1
        FinSi
    FinPara

    Imprimir "Ceros: ", cero
    Imprimir "Negativos: ", negativo
    Imprimir "Positivos: ", positivo
Fin


**Enfoque analítico:**
1. Leer ( N ) números.
2. Contar cuántos son cero, menores y mayores que cero.
3. Mostrar los resultados.

### Reto 6: Ahorro diario

**Variables:**
- **Entrada:** 
  - Ninguna (se inicia con 3¢)
- **Salida:** 
  - Ahorro diario
  - Total ahorrado en un año
- **Constantes:** 
  - Ninguna
**Pseudocódigo**

Inicio
    ahorro_total = 0
    Para dia = 1 hasta 365
        ahorro = 3 * (3^(dia-1))
        ahorro_total = ahorro_total + ahorro
    FinPara
    Imprimir "Ahorro total en el año: ", ahorro_total
Fin

**Enfoque analítico:**
1. Iniciar el ahorro en 3¢.
2. Duplicar el ahorro cada día.
3. Sumar el ahorro diario durante 365 días.
4. Mostrar el total.

### Reto 7: Cálculo de costo con descuentos

**Variables:**
- **Entrada:** 
  - Número de artículos
  - Precio de cada artículo
- **Salida:** 
  - Costo total después de descuentos
- **Constantes:** 
  - Descuentos según rangos de precios.

  **Pseudocódigo**
  Inicio
    Leer N
    total_pago = 0

    Para i = 1 hasta N
        Leer precio
        Si precio >= 200
            descuento = precio * 0.15
        SinoSi precio > 100
            descuento = precio * 0.12
        Sino
            descuento = precio * 0.10
        FinSi
        precio_con_descuento = precio - descuento
        total_pago = total_pago + precio_con_descuento
        Imprimir "Costo del artículo ", i, ": ", precio_con_descuento, " Descuento: ", descuento
    FinPara

    Imprimir "Total a pagar: ", total_pago
Fin


**Enfoque analítico:**
1. Leer el número de artículos y sus precios.
2. Aplicar descuentos según las reglas.
3. Calcular el costo total.
4. Mostrar el resultado.

### Reto 8: Función exponencial

**Variables:**
- **Entrada:** 
  - Valor para la función
- **Salida:** 
  - Resultado de la función
- **Constantes:** 
  - Ninguna

**Ecuación:**

 y = a × bx
- La base de la función es a, y debe ser mayor que 0.
- x es la variable.
- y es la solución.
- b es la base.

**Pseudocódigo**
Inicio
    Leer x
    resultado = 1
    factorial = 1
    potencia = x
    i = 1

    Mientras (i <= 10)
        resultado = resultado + (potencia / factorial)
        i = i + 1
        potencia = potencia * x
        factorial = factorial * i
    FinMientras

    Imprimir "Valor aproximado de e^x: ", resultado
Fin



**Enfoque analítico:**
1. Leer el valor de \( x \).
2. Calcular la serie hasta un número de términos definido.
3. Mostrar el resultado.

### Reto 9:  Cálculo del seno

**Variables:**
- **Entrada:** 
  - Angulo en radianes
- **Salida:** 
  - Resultado del seno
- **Constantes:** 
  - Ninguna

**Ecuación:**
 sen(α) = y r = PQ r

 **Pseudocódigo**
 
 Inicio
    Leer x
    seno = 0
    potencia = x
    signo = 1
    factorial = 1
    i = 1

    Mientras (i <= 10)
        seno = seno + signo * (potencia / factorial)
        signo = -signo
        potencia = potencia * x^2
        factorial = factorial * (i * (i+1))
        i = i + 2
    FinMientras

    Imprimir "Valor aproximado de sin(x): ", seno
Fin


**Enfoque analítico:**
1. Leer el valor de \( x \).
2. Calcular la serie hasta un número de términos definido.
3. Mostrar el resultado.

