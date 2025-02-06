# Juego 2D con Pygame
<img src="https://www.tutorialspoint.com/pygame/images/display_window.jpg"  alt="pygame">
 
# Introduction 

## 👾 Juego 2D con Pygame 🕹️

Este proyecto es un juego 2D desarrollado con la biblioteca Pygame de Python. El objetivo principal es controlar un personaje y sobrevivir el mayor tiempo posible, evitando los obstáculos que aparecen aleatoriamente en la pantalla.

## 🚀 Características Principales

*   **Control del Personaje:** El jugador controla el personaje principal mediante las flechas del teclado (arriba, abajo, izquierda, derecha).
*   **Generación de Obstáculos Aleatorios:** Los obstáculos aparecen de forma aleatoria en diferentes posiciones, aumentando el desafío.
*   **Detección de Colisiones:** El juego detecta las colisiones entre el personaje y los obstáculos. Al ocurrir una colisión, el juego finaliza.
*   **Pantalla Principal:** El juego utiliza una ventana principal creada con Pygame para mostrar el juego.

## 🧱 Estructura del Juego

El juego se estructura de la siguiente manera:

*   **Pantalla Principal:** Inicialización de Pygame y creación de la ventana del juego.
*   **Personaje Controlable:** Definición de la clase `Personaje` y su movimiento mediante eventos de teclado.
*   **Generación de Obstáculos:** Creación aleatoria de obstáculos con diferentes posiciones y velocidades.
*   **Detección de Colisiones:** Implementación de la lógica para detectar colisiones entre el personaje y los obstáculos.
*   **Game Over:** Lógica para finalizar el juego cuando ocurre una colisión.

## 🐛 Problemas Detectados

*   **Falta de Puntuación:** No hay un sistema de puntuación para medir el rendimiento del jugador.
*   **Velocidad Constante de Obstáculos:** Los obstáculos se mueven siempre a la misma velocidad, lo que reduce la dificultad a medida que el jugador se acostumbra.
*   **Ausencia de Sonido y Efectos Visuales:** El juego carece de música de fondo, efectos de sonido y animaciones, lo que afecta la inmersión.

## ✨ Posibles Mejoras

*   **Sistema de Puntuación:** Agregar un sistema de puntuación que aumente con el tiempo de supervivencia.
*   **Dificultad Progresiva:** Aumentar gradualmente la velocidad de los obstáculos para incrementar la dificultad.
*   **Sonido y Música:** Incorporar música de fondo y efectos de sonido para mejorar la experiencia del jugador.
*   **Animaciones:** Agregar animaciones al personaje y a los obstáculos para hacer el juego más atractivo visualmente.
*   **Sistema de Niveles:** Implementar un sistema de niveles con diferentes desafíos y obstáculos.
*   **Tabla de Puntuaciones:** Guardar las puntuaciones más altas para fomentar la competencia entre jugadores.
*	**Power-Ups:** Añadir objetos que le den ventajas al jugador, como invencibilidad o aumento de velocidad.

## 🛠️ Tecnologías Utilizadas

*   **Python:** Lenguaje de programación principal.
*   **Pygame:** Biblioteca de Python para el desarrollo de videojuegos.

## ➕ Extras

*   Se podria agregar un menu de inicio para darle una mejor presentacion al juego
*   Mejorar el diseño visual del juego, tanto del personaje como de los obstaculos
*   Permitir al usuario personalizar los controles del juego

¡Espero que esto te sea útil! Puedes copiar y pegar este código Markdown en tu editor y comenzar a trabajar en él.