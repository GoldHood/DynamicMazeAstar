# 🌟 DynamicMazeAstar: Solucionador de Laberintos Dinámicos con A\*

<p align="center">
  <img src="https://raw.githubusercontent.com/GoldHood/DynamicMazeAstar/main/DynamicMazeAstar_V1.gif" width="360" alt="DynamicMazeAstar V1"/>
</p>

<p align="center">
  <strong>Desafía los límites.</strong><br>
  Observa cómo la inteligencia artificial navega y se adapta en tiempo real a laberintos dinámicos.
</p>
---

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg?style=for-the-badge&logo=python)](https://www.python.org/)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red.svg?style=for-the-badge)](https://github.com/GoldHood/DynamicMazeAstar)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg?style=for-the-badge&logo=github)](CONTRIBUTING.md)
[![Status](https://img.shields.io/badge/Status-Active-success.svg?style=for-the-badge)]()

---

## 🚀 Bienvenido a DynamicMazeAstar

¿Te has preguntado cómo un algoritmo puede encontrar su camino en un laberinto que cambia constantemente? **DynamicMazeAstar** es más que un simple solucionador de laberintos; es una poderosa demostración de cómo la inteligencia artificial y los algoritmos de búsqueda pueden adaptarse y superar obstáculos en tiempo real.

---

## 🔥 ¿Por qué DynamicMazeAstar es especial?

- 🧠 **Adaptación en tiempo real:** Nuestro algoritmo A\* recalcula y encuentra nuevas rutas al aparecer obstáculos inesperados.
- 🎥 **Visualización interactiva:** Observa cómo el agente navega por el laberinto, ajustándose dinámicamente a los cambios.
- 📚 **Educativo y extensible:** Ideal para aprender sobre algoritmos de búsqueda y para quienes desean experimentar y mejorar el código.
- 🚀 **Próximas mejoras:** Planeamos incorporar nuevas heurísticas y el algoritmo D\* Lite en futuras versiones.

---

## 🎥 Observa el algoritmo en acción

<p align="center">
  <img src="https://raw.githubusercontent.com/GoldHood/DynamicMazeAstar/main/DynamicMazeAstar_V1.gif" width="600" alt="DynamicMazeAstar V1"/>
</p>

<p align="center">
  <em>El agente azul busca el camino más eficiente hacia la meta dorada, sorteando obstáculos que aparecen en tiempo real.</em>
</p>

---

## 📚 Tabla de Contenidos

- [🚀 Bienvenido a DynamicMazeAstar](#-bienvenido-a-dynamicmazeastar)
- [🔥 ¿Por qué DynamicMazeAstar es especial?](#-por-qué-dynamicmazeastar-es-especial)
- [🎥 Observa el algoritmo en acción](#-observa-el-algoritmo-en-acción)
- [⚙️ Instalación](#️-instalación)
- [🕹 Uso](#-uso)
- [🤔 ¿Cómo funciona el algoritmo?](#-cómo-funciona-el-algoritmo)
- [🤝 Contribuciones](#-contribuciones)
- [📬 Contacto](#-contacto)
- [📝 Licencia](#-licencia)
- [🌐 ¡Hazlo viral!](#-¡hazlo-viral)
- [🎯 Próximas versiones](#-próximas-versiones)
- [📄 Detalles del Proyecto](#-detalles-del-proyecto)

---

## ⚙️ Instalación

Asegúrate de tener **Python 3.9+** instalado. Luego, sigue estos pasos:

1. **Clona este repositorio:**

   ```bash
   git clone https://github.com/GoldHood/DynamicMazeAstar.git
   cd DynamicMazeAstar
   ```

2. **Crea un entorno virtual (opcional pero recomendado):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```

3. **Instala las dependencias necesarias:**

   ```bash
   pip install -r requirements.txt
   ```

---

## 🕹 Uso

1. **Ejecuta el script principal:**

   ```bash
   python dynamic_maze_solver.py
   ```

2. **Disfruta de la simulación:**
   
   Observa cómo el agente navega por el laberinto, adaptándose a los cambios en tiempo real.

---

## 🤔 ¿Cómo funciona el algoritmo?

El algoritmo A* es un algoritmo de búsqueda heurística que encuentra el camino más corto entre un nodo inicial y uno final. En DynamicMazeAstar, hemos implementado A* de la siguiente manera:

- **Heurística:** Utilizamos la distancia de Manhattan como función heurística.
- **Obstáculos dinámicos:** En ciertos pasos, se añaden obstáculos al laberinto, simulando cambios en tiempo real.
- **Replanificación:** Cuando aparece un nuevo obstáculo, el algoritmo recalcula la ruta desde la posición actual.

**Visualización del laberinto:**

- 🟩 **Inicio (S):** Punto de partida del agente.
- 🟨 **Meta (G):** Objetivo que el agente debe alcanzar.
- 🔵 **Agente:** Representado como un círculo azul que se mueve por el laberinto.
- 🟥 **Obstáculos:** Paredes y obstáculos dinámicos que el agente debe evitar.
- 🟫 **Camino recorrido:** Celdas que el agente ha visitado.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Sigue estos pasos:

1. **Haz un fork del repositorio.**
2. **Crea una rama nueva:**

   ```bash
   git checkout -b mi-nueva-funcionalidad
   ```

3. **Realiza tus cambios y haz commit:**

   ```bash
   git commit -m "Añadir nueva funcionalidad"
   ```

4. **Envía tus cambios al repositorio remoto:**

   ```bash
   git push origin mi-nueva-funcionalidad
   ```

5. **Abre un Pull Request.**

---

## 📬 Contacto

¿Tienes preguntas o sugerencias? ¡Contáctame!

- **Autor**: Martin Verastegui
- **Email**: martin.verastegui@gmail.com
- **GitHub**: [GoldHood](https://github.com/GoldHood)

---

## 📝 Licencia

Este proyecto está bajo la licencia MIT License.

---

## 🌐 ¡Comparte!

Tu apoyo es esencial para que más personas descubran este proyecto. Aquí tienes cómo puedes ayudar:

- Dale una estrella ⭐ al repositorio.
- Comparte en tus redes sociales:

  > "🚀 Descubre cómo DynamicMazeAstar utiliza IA para resolver laberintos dinámicos en tiempo real. ⭐ https://github.com/GoldHood/DynamicMazeAstar #Python #IA #AStar #OpenSource"

- Únete a la conversación: Comparte tus preguntas, ideas y sugerencias.

---

## 🎯 Próximas versiones

¡Esto es solo el comienzo! Estamos trabajando en:

- **Nuevas heurísticas**: Mejoraremos el algoritmo A* con heurísticas más eficientes.
- **Implementación de D* Lite**: Añadiremos este algoritmo para manejar mejor los cambios dinámicos.
- **Análisis de resultados**: Profundizaremos en cómo las diferentes heurísticas y algoritmos afectan el rendimiento.
- **Visualizaciones avanzadas**: Incluiremos gráficos y estadísticas detalladas sobre el rendimiento del algoritmo.

---

## 📄 Detalles del Proyecto

```
# -----------------------------------------------------
# Proyecto: DynamicMazeAstar
# Autor: Martin Verastegui
# Fecha: 29 de octubre de 2024
# Licencia: MIT License
# Descripción: Solucionador de laberintos dinámicos utilizando el algoritmo A* en Python.
# Repositorio: https://github.com/GoldHood/DynamicMazeAstar
# -----------------------------------------------------
```

<p align="center"> <i>¡Gracias por ser parte de DynamicMazeAstar!</i> <br> <strong>✨ Juntos, hagamos que la inteligencia artificial sea accesible para todos. ✨</strong> </p>
