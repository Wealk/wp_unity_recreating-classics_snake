# 🎮 Recreando clásicos: Snake - Unity

Este proyecto es una recreación del clásico *Snake* de 1997 usando Unity. Se ha diseñado para ser fiel al juego original, manteniendo su jugabilidad simple pero desafiante.
Este proyecto forma parte de una serie de recreaciones de videojuegos clásicos, diseñados para aprender, experimentar y mejorar habilidades en desarrollo de juegos con Unity.

> **Objetivo**: Reproducir la experiencia del *Snake* original con mecánicas fieles y código optimizado.

---

## 🎥 Referencias al juego original

Estos videos ayudan a comprender los detalles del diseño y la jugabilidad original para lograr una recreación fiel.
Para entender mejor la jugabilidad y el diseño original, puedes revisar los siguientes videos:

1. [Nokia 3310 Snake game complete](https://www.youtube.com/shorts/ymV93I6fQKY)  
3. [Wikipedia](https://es.wikipedia.org/wiki/Snake_(videojuego))

---

## 📌 Game design

Entorno:
- Pantalla fija con bordes que pueden ser letales o permitir movimiento cíclico.

Entidades:
- **Serpiente**: controlada por el jugador, se mueve en direcciones fijas y crece al comer alimento.
- **Alimento**: aparece aleatoriamente en la pantalla y al ser consumido aumenta el tamaño de la serpiente.

Comportamientos:
- La serpiente se mueve en una dirección fija hasta que el jugador cambia su trayectoria.
- Al comer alimento, la serpiente crece y aumenta la dificultad.
- El juego termina si la serpiente choca contra su propio cuerpo o los bordes (según la configuración).

Interfaz:
- Se muestra la puntuación en la parte superior.
- Opción de reiniciar el juego al perder.
- Configuración para elegir entre colisiones letales o movimiento cíclico en los bordes.

---

## 🛠️ Requisitos

- **Unity**: Versión **60000.0.32f1** o superior (recomendado).  
- **.NET 6** o superior.  
- **Editor de código** compatible con Unity (Visual Studio o VS Code).  
- **Git** (opcional, para clonar el repositorio).  

---

## 🎮 Controles del juego

| Acción         | Tecla |
|---------------|----|
| Mover arriba  | `W` o `↑` |
| Mover abajo   | `S` o `↓` |
| Mover izquierda | `A` o `←` |
| Mover derecha  | `D` o `→` |
| Iniciar / Reiniciar | `Espacio` |

---

## 🐟 Licencia

Este proyecto se distribuye bajo la licencia **MIT**.  
Puedes usarlo, modificarlo y distribuirlo libremente.

---

¡Diviértete desarrollando *Snake* y recreando clásicos! 🌐

