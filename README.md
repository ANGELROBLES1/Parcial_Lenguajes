# Parcial_Lenguajes
## Examen Parcial: Teoría de Lenguajes y Compiladores
Este repositorio contiene la resolución de los 5 puntos del examen parcial, implementando autómatas, algoritmos numéricos y analizadores sintácticos. El proyecto está organizado por carpetas, cada una funcional de manera independiente.

## Estructura del Proyecto
# Punto 1: AFD para movimientos de ajedrez (Python)
# Punto 2: AFD para identificadores de variables (Python)
# Punto 3: Calculadora de raíz cuadrada Newton-Raphson (Flex & Bison)
# Punto 4: Algoritmo de Euclides para MCD (C)
# Punto 5: Serie de Maclaurin para $e^x$ (ANTLR4 & Java)

## Requerimientos del Sistema
Para ejecutar todos los módulos, asegúrese de tener instalados los siguientes componentes en su entorno 
- Python : Para los puntos 1 y 2
- GCC (Compilador C): Para los puntos 3 y 4
- Flex y Bison: Para el punto 3
- Java JDK y ANTLR4: Para el punto 5

## Guía de Ejecución General
Todos los programas han sido estandarizados para leer datos desde un archivo externo denominado entradas.txt

1. Preparación de archivos
Cada carpeta contiene su propio archivo entradas.txt
Este archivo debe contener al menos 10 líneas de prueba para validar el comportamiento del programa bajo diferentes escenarios (casos de éxito y casos de error)

2. Navegación en la Terminal
Debe navegar hasta la carpeta específica del punto que desea evaluar
Ejemplo:
   ``cd ~/Parcial_Lenguajes/Punto1``

## Salida de los Programas
El programa procesará el archivo entradas.txt línea por línea y mostrará en la consola el resultado de la evaluación.
- Para Autómatas (Puntos 1 y 2): Imprimirá ACEPTE o NO ACEPTE según la validez de la cadena
- Para Algoritmos (Puntos 3, 4 y 5): Mostrará el resultado numérico calculado o, en su defecto, un mensaje de error técnico (Ej: Error matemático, Overflow o Error sintáctico) si la entrada intenta romper la lógica del programa.

## Documentación Individual
Cada carpeta incluye archivos adicionales para una revisión profunda
- README.md: Especificaciones técnicas y gramáticas
- PRUEBAS.md: Reporte detallado de casos de prueba con capturas de pantalla de la terminal
