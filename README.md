# PEI 1 — Dinámica de Actitud Satelital

Proyecto grupal de  **Ampliación de Matemáticas 1 (MUSE - ETSIAE)** .

Creado por: Rubén Nuñez, Ignacio Pérez y Mario Penin

El objetivo es estudiar la dinámica de rotación de un satélite y comparar distintos métodos numéricos usando  **Python** .

## Objetivos del proyecto

Durante esta primera fase trabajaremos hasta el  **Milestone 4** :

* Implementar métodos de integración numérica.
* Comparar su precisión y estabilidad.
* Estudiar cómo afecta el paso temporal `<span>Δt</span>`.
* Aplicar los métodos a problemas de dinámica y actitud satelital.
* Representar y analizar los resultados mediante gráficas.

## Milestones

### Milestone 1

Implementación básica de:

* Euler.
* Crank-Nicolson.
* RK4.

Comparación de resultados usando distintos pasos de tiempo.

### Milestone 2

Crear funciones reutilizables para:

* Euler.
* Euler inverso.
* Crank-Nicolson.
* RK4.

También se creará una función general para integrar problemas del tipo:

```
dU/dt = F(U, t)
```

### Milestone 3

Estudio del  **error numérico y la convergencia** :

* Extrapolación de Richardson.
* Comparación de errores.
* Cálculo del orden de convergencia de cada método.

### Milestone 4

Estudio de la **estabilidad numérica** de:

* Euler.
* Euler inverso.
* Leap-Frog.
* Crank-Nicolson.
* RK4.

Se calcularán sus regiones de estabilidad y se compararán con los resultados de las simulaciones.

## Organización

El proyecto se desarrollará de forma modular, separando:

* Métodos numéricos.
* Problemas físicos.
* Análisis de errores y estabilidad.
* Gráficas y visualización.

## Tecnologías

* Python
* NumPy
* SciPy
* Matplotlib

## Estado

* [ ] Milestone 1
* [ ] Milestone 2
* [ ] Milestone 3
* [ ] Milestone 4
