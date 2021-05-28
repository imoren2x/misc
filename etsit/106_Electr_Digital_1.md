Electrónica Digital 1
======

Curso 1.999/2.000.

Capítulo 1. Introducción (pág. 4)
------

    1.1 Introducción
        1.1.1 Telecomunicaciones
        1.1.2 Tecnologías óptimas
        1.1.3 Información y señales

    1.2 Electrónica
        1.2.1 Electrónica Analógica y Digital
        1.2.2 Sistemas Electrónicos

    1.3 Entorno de las asignaturas
        1.3.1 Electrónica Digital 1
        1.3.2 Electrónica Digital 2
        1.3.3 Laboratorios

    1.4 Enfoque de las asignaturas


Capítulo 2. Sistemas y códigos de numeración (pág. 15)
------

    2.1 Sistemas de numeración
        2.1.1 Sistema decimal

    2.2 Sistemas ponderados
        2.2.1 Código binario
        2.2.2 Números complementarios
        2.2.3 Ejemplos de operaciones en complemento
        2.2.4 Sistemas octal y hexadecimal
        2.2.5 Unidades binarias

    2.3 Conversión de formatos
        2.3.1 Ejemplos
        2.3.2 Ejemplo de conversión hexadecimal

    2.4 Códigos BCD
        2.4.1 Otros códigos BCD
        2.4.2 Ejemplos de BCD

    2.5 Códigos de bytes

    2.6 Códigos y errores
        2.6.1 Paridad
            2.6.1.1 Otros sistemas de paridad
            2.6.1.2 Ejemplos de paridad
        2.6.2 Códigos de Gray y de Johnson
        2.6.3 Códigos de bloque
        2.6.4 Códigos correctores


Capítulo 3. Álgebra de Boole (pág. 38)
------

George Boole (1815--1864)

    3.1 Álgebra de Boole
        3.1.1 Álgebra binaria

    3.2 Funciones binarias
        3.2.1 Símbolos gráficos
        3.2.2 Propiedades de las funciones lógicas
        3.2.3 Funciones exclusivas
        3.2.4 Ejemplo. Sumador de 1 bit
        3.2.5 Más ejemplos

    3.3 Formas canónicas
        3.3.1 Diseño con funciones canónicas

    3.4 Simplificación
        3.4.1 Métodos de simplificación
        3.4.2 Métodos de Karnaugh
        3.4.3 Simetrías y excepciones
        3.4.4 Inespecificaciones
        3.4.5 Funciones múltiples


Capítulo 4. Circuitos Combinacionales (pág. 63)
------

    4.1 Concepto de diseño
        4.1.1 Señales
        4.1.2 Etiquetas
        4.1.3 Puertas
            4.1.3.1 Ejemplo: multiplexor de dos entradas
        4.1.4 Señales de dato y control
        4.1.5 Etiquetas y sentido físico
            4.1.5.1 Señales complementarias. ‘Lógica positiva’.
            4.1.5.2 Datos múltiples: números en etiquetas

    4.2 Funciones combinacionales
        4.2.1 Multiplexores
        4.2.2 Demultiplexores
        4.2.3 Bloques funcionales. Símbolos lógicos.
            4.2.3.1 Funciones inversas
            4.2.3.2 Ejemplo de diseño con funciones inversas
            4.2.3.3 Información significativa. Precauciones
        4.2.4 Codificaciones y decodificaciones
        4.2.5 Comparadores
        4.2.6 Paridad
        4.2.7 Sumadores
            4.2.7.1 Acarreo
            4.2.7.2 Resta binaria
        4.2.8 Multiplicación. División
        4.2.9 ALU


Capítulo 5. Diseño con funciones lógicas integradas (pág. 91)
------

    5.1 Fases de la vida de un producto
        5.1.1 Fases de un diseño
    
    5.2 Descomposición en bloques
        5.2.1 Bloques funcionales integrados
        5.2.2 Clasificación de bloques funcionales
    
    5.3 Representación gráfica de bloques funcionales
        5.3.1 Representación estándar
        5.3.2 Norma ANSI
    
    5.4 Dispositivos comerciales
        5.4.1 Hojas de características (‘Datasheets’)
        5.4.2 Tipos disponibles y configuraciones
    
    5.5 Recomendaciones de diseño lógicos
        5.5.1 Estructuración
        5.5.2 Documentación
        5.5.3 Señales no utilizadas
        5.5.4 Pruebas lógicas. Simulación
    
    5.6. Ejemplos
        5.6.1 Extensión de una función: multiplexor de 16 a 1
            5.6.1.1 Funciones inversas. Información significativa
            5.6.1.2 Doble funcionalidad: decodificador-codificador
            5.6.1.3 Doble funcionalidad: generación y detección de paridad
        5.6.2 Resta de dos números
            5.6.2.1 Comparador
            5.6.2.2 Inversores programables y sumador
            5.6.2.3 Simulación


Capítulo 6. Circuitos secuenciales (pág. 129)
------

    6.1 Introducción: el tiempo en el diseño
    
    6.2 El tiempo en el diseño
        6.2.1 Sincronización
            6.2.1.1 Señales síncronas y asíncronas
            6.2.1.2 Características de las señales de sincronismo
        6.2.2 Diagramas de tiempos
    
    6.3 Biestables
        6.3.1 Latch tipo D
        6.3.2 Biestables controladas por flanco
        6.3.3 Biestable S-R
        6.3.4 Biestables J-K
            6.3.4.1 Biestables J-K por flanco. Salida post-puesta
        6.3.5 Biestable tipo T
        6.3.6 Biestables complejos. Entradas síncronas y asíncronas
        6.3.7 Entradas síncronas y asíncronas
        6.3.8 Biestables comerciales
    
    6.4 Ejemplos sencillos
        6.4.1 Divisor de frecuencia
        6.4.2 Ejemplo. Reloj de cuatro fases
        6.4.3 Ejemplo. Reloj simétrico de tres fases
    
    6.5 Registros
        6.5.1 Registro pararelo
        6.5.2 Registro serie
        6.5.3 Registros universales
            6.5.3.1 Registro de desplazamiento universal de 4 bits
            6.5.3.2 Ejemplo. Conversión serie-paralelo
        6.5.4 Otros registros
    
    6.6 Contadores
        6.6.1 Contador de décadas
        6.6.2 Contadores asíncronos
        6.6.3 Contadores síncronos
            6.6.3.1 Tipos de contadores síncronos
            6.6.3.2 Contador síncrono universal
        6.6.4 Contadores Integrados
            6.6.4.1 Grupos de contadores integrados
        6.6.5 Ejemplos de diseño con contadores
            6.6.5.1 Ejemplo. Divisor por 6
            6.6.5.2 Ejemplo. Convertir segundos en minutos
            6.6.5.3 Ejemplo. Contador grande


Capítulo 7. Máquinas de estado (pág. 187)
------

    7.1 Sistemas combinacionales y secuenciales
        7.1.1 Máquinas de estado
        7.1.2 Especificación
            7.1.2.1 Tablas de transición
        7.1.3 Diagramas de transición
        7.1.4 Máquinas de Moore y Mealey
        7.1.5 Simplificación de estados
            7.1.5.1 Tablas de implicación
            7.1.5.2 Ejemplo
        7.1.6 Codificación
        7.1.7 Indefiniciones
        7.1.8 Implementación
            7.1.8.1 Ejemplo
    
    7.2 Diseño asíncrono
        7.2.1 Tabla de fases
        7.2.2 Ejemplo. Máquina asíncrona I
        7.2.3 Problemática de los sistemas secuenciales asíncronos
            7.2.3.1 Ejemplo: máquina asíncrona II
        7.2.4 Máquinas de pulsos
    
    7.3 Metodologías del diseño secuencial síncrono
        7.3.1 Estructuras de máquinas de estado síncronas
        7.3.2 Desarrollo de una máquina síncrona
        7.3.3 Sumador serie
        7.3.4 Ejemplo II. Detección de secuencia
        7.3.5 Limitaciones de las máquinas finitas


Capítulo 8. Dispositivos programables (pág. 235)
------

    8.1 Suma de productos
    
    8.2 Circuito PLD
    
    8.3 Circuito SPLD
        8.3.1 Arquitectura general de un dispositivo SPLD
        8.3.2 Representación gráfica
        8.3.3 Tipos de circuitos SPLD
            8.3.3.1 PLA (Programmable Logic Array)
            8.3.3.2 PROM (Programmable Read-Only Memory)
            8.3.3.3 PAL (Programmable Array Logic)
        8.3.4 Ejemplos de circuitos SPLD
            8.3.4.1 PAL tipo H
            8.3.4.2 PAL tipo L
            8.3.4.3 PAL 16R6
            8.3.4.4 PAL 20X4
            8.3.4.5 PAL 22V10
            8.3.4.6 PLA 153
            8.3.4.7 PLA 105
    
    8.4 Circuitos CPLD
        8.4.1 Introducción
        8.4.2 Arquitectura de los CPLD de la serie MAX 7000 de Altera
        8.4.3 Otros fabricantes
        8.4.4 Aplicaciones de los CPLD
    
    8.5 Diseño con circuitos PLD
        8.5.1 Compiladores de PLD
        8.5.2 Declaraciones
    
    8.6 Ejemplos de diseño con PLD
        8.6.1 Codificador
        8.6.2 Biestable
        8.6.3 Contador
        8.6.4 Ejemplo completo


Capítulo 9. Organización de datos (pág. 276)
------

    9.1 Buses
        9.1.1 Interconexión de agentes
        9.1.2 Buses síncronos y asíncronos
        9.1.3 Protocolos
            9.1.3.1 Protocolos de control de bus
            9.1.3.2 Otros protocolos de control
        9.1.4 Dispositivos lógicos para la interconexión
            9.1.4.1 Circuitos de interconexión
        9.1.5 Ejemplo. Circuito de control de acceso

    9.2 Memorias
        9.2.1 Circuitos integrados de memoria
        9.2.2 Acceso secuencial
        9.2.3 Memoria asociativa

    9.3 Ejemplos
        9.3.1 Ejemplo 1. Codificador con PROM
        9.3.2 Ejemplo. Memoria de 128 KiB
            9.3.2.1 Bloque de memoria
            9.3.2.2 Bloque de control


Capítulo 10. Diseño algorítmico (pág. 320)
------

    10.1 Estructura general de un sistema
        10.1.1 Secuencial Vs. combinacionales
    
    10.2 Paralelismo
    
    10.3 Pipeline
    
    10.4 Lenguajes de descripción lógica: VHDL


Apéndice A. Norma ANSI
------

    A.1 Introducción
    
    A.2 Composición de los símbolos
    
    A.3 Símbolos cualificadores
        A.3.1 Símbolos generales
        A.3.2 Símbolos para E/S (i/o)
        A.3.3 Símbolos dentro del perfil
    
    A.4 Notación Dependencial
        A.4.1 Explicación general
        A.4.2 Reglas de aplicación
        A.4.3 And
        A.4.4 Or
        A.4.5 Negación
        A.4.6 Interconexión
        A.4.7 Control
        A.4.8 Set y reset
        A.4.9 Enable
        A.4.10 Modo
        A.4.11 Dirección
    
    A.5 Biestables
    
    A.6 Codificadores
    
    A.7 Uso de un codificador para generar entradas afectantes
    
    A.8 Uso de agrupaciones binarias para generar entradas afectantes
    
    A.9 Secuencia de etiquetas de entradas
    
    A.10 Secuencia de etiquetas de salida

Table I. General Qualifying Symbols

Table II. Qualifying Symbols for inputs and outputs

Table III. Symbols inside the outline
