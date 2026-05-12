# CHAOS_CORE: Visualización de Atractores Extraños

Una estación de observación de sistemas dinámicos no lineales. Este laboratorio visualiza la belleza matemática del caos, donde pequeñas variaciones en las condiciones iniciales conducen a resultados divergentes, pero siempre confinados dentro de una estructura geométrica compleja llamada **Atractor**.

## 🌀 Conceptos Fundamentales

### ¿Qué es un Atractor Extraño?
En el estudio de sistemas dinámicos, un atractor es un conjunto de valores numéricos hacia los cuales un sistema tiende a evolucionar. Un atractor se llama "extraño" si tiene una estructura **fractal**. Esto suele ocurrir en sistemas que son caóticos pero deterministas.

### Efecto Mariposa
Técnicamente conocido como *dependencia sensible a las condiciones iniciales*. Es la razón por la cual el clima es difícil de predecir a largo plazo: un cambio minúsculo hoy puede resultar en un estado completamente diferente en el futuro.

## 🧪 Sistemas Simulados

### 1. Atractor de Lorenz (El Vuelo de la Mariposa)
Originalmente derivado de un modelo simplificado de convección atmosférica por Edward Lorenz en 1963.
- **Ecuaciones:**
  - `dx/dt = σ(y - x)`
  - `dy/dt = x(ρ - z) - y`
  - `dz/dt = xy - βz`
- **Visualización:** Dos "alas" o lóbulos por los que la trayectoria orbita de forma impredecible pero nunca se cruza a sí misma.

### 2. Atractor de Rössler
Diseñado por Otto Rössler en 1976 con la intención de crear el atractor caótico más simple posible, con solo un término no lineal.
- **Visualización:** Se asemeja a una cinta de Möbius o un espiral que se dobla sobre sí mismo, representando un flujo caótico más suave y continuo que el de Lorenz.

## 💻 Detalles Técnicos

### Integración Numérica (RK4)
Para resolver las ecuaciones diferenciales en tiempo real, se utiliza el método de **Runge-Kutta de 4º orden**. Este algoritmo proporciona un equilibrio excelente entre precisión matemática y rendimiento computacional para simulaciones interactivas.

### Renderizado Estético
- **Proyección Isométrica:** Visualización 3D proyectada en un plano 2D.
- **Efecto Fósforo:** Simulación de la persistencia lumínica de los antiguos monitores CRT.
- **Glitch UI:** Interfaz reactiva con animaciones de "corrupción" de datos controlada.

## 🚀 Instalación y Uso

Abre `index.html` en tu navegador o accede a la [Demo en vivo](https://narquileerrado.github.io/atractores/).

---
*"El caos no es una falta de orden, sino un orden de una complejidad superior."*
