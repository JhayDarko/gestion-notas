# Sistema de Gestión de Notas

Este proyecto es un programa de gestión de notas de estudiantes desarrollado en equipo. El objetivo principal es calcular promedios de calificaciones y determinar si los estudiantes han aprobado o reprobado, con base en ciertos criterios predefinidos.

## Miembros del equipo

- **Andreina Arevalo Bencardino**
- **Tatiana Arengas**
- **Jhojander**

## Descripción del proyecto

El programa permite ingresar las calificaciones de los estudiantes y calcula su promedio, determinando si han aprobado o no en base a un umbral de evaluación predefinido.

### Estructura del programa

1. **Parte 1: Inicialización y estructura del programa**
   - Definición de variables y constantes.
   - Uso de `ArrayList` y arrays para almacenar las notas.
   - Entrada y salida de datos.
   - Diseño de las estructuras de control para gestionar las decisiones dentro del sistema.

2. **Parte 2: Cálculo de promedios y determinación del estado**
   - Implementación de la lógica para calcular el promedio de calificaciones.
   - Determinación de si un estudiante ha aprobado o reprobado, basándose en el límite mínimo de aprobación (3.0).
   - Las notas se almacenan en una matriz de estudiantes.

3. **Parte 3: Generación de informe y pruebas**
   - Generación de un informe final con los resultados de cada estudiante.
   - Pruebas del programa para garantizar su correcto funcionamiento.
   - Validación del código para asegurar que se cumplen los requisitos establecidos.

## Funcionamiento del sistema

- El sistema solicita la cantidad de notas por estudiante (definido por la constante `NUMBER_OF_SUBJECTS`).
- Se ingresan las calificaciones mediante un bucle `for`, validando que estén dentro del rango permitido (0.0 a 5.0).
- Se calcula el promedio sumando todas las notas y dividiéndolas por el número de materias.
- Se determina si el estudiante aprueba o reprueba utilizando un operador ternario, comparando el promedio con el límite de aprobación (`APROVAL_LIMIT`).
  
## Criterios de aprobación

- El promedio mínimo para aprobar es **3.0**.
