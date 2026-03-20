# 🔄 Práctica de Control de Flujo: Estructuras Iterativas (Bucles)

**Tema:** Ciclos `while`, `do-while` y `for`.
**Contexto:** Módulos de gestión para el sistema académico "AppSchool".

---

## 📘 Reto 1: Captura de Calificaciones (Bucle `while`)

**Estructura a practicar:** `while` (Repetir mientras se cumpla una condición).

El módulo de evaluación de AppSchool necesita una herramienta para que los profesores ingresen las calificaciones de un grupo. Como los grupos tienen diferentes cantidades de alumnos, el sistema no sabe de antemano cuántas calificaciones se van a ingresar.

### 📝 Descripción del Problema

Desarrolla un programa en Java que solicite al profesor ingresar calificaciones (números del `0` al `100`). 
El programa debe seguir pidiendo calificaciones **mientras** el profesor no ingrese el número negativo `-1`. El `-1` funcionará como un "centinela" para avisarle al sistema que ya terminó de capturar.

Al finalizar (cuando ingrese `-1`), el sistema debe imprimir:
1. El total de calificaciones capturadas (sin contar el `-1`).
2. El promedio general del grupo.

### 📤 Salida Esperada

* **Ejemplo de Ejecución:**
```text
--- Sistema AppSchool: Captura de Calificaciones ---
Ingrese la calificación del alumno (o -1 para terminar): 85
Ingrese la calificación del alumno (o -1 para terminar): 90
Ingrese la calificación del alumno (o -1 para terminar): 75
Ingrese la calificación del alumno (o -1 para terminar): -1

-- Resumen del Grupo --
Total de alumnos evaluados: 3
Promedio general: 83.33
