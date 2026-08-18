# Othello / Reversi · IPET 249 Nicolás Copérnico

![Escudo del IPET 249](escudo.png) *(opcional: si tienes la imagen, colócala aquí)*

**Versión web** del clásico juego de mesa, desarrollada en **HTML5 + Canvas + JavaScript** para la asignatura **Laboratorio de Programación** del **IPET 249 Nicolás Copérnico** – Especialidad **Informática** – Año **2026**.

El proyecto es una transcripción fiel del código original en Python con Pygame, pero adaptado para ser desplegado en **GitHub Pages**. Incluye comentarios exhaustivos en el código y una interfaz personalizada con los colores institucionales del colegio (bordo, amarillo, rojo y blanco).

---

## 🎯 Objetivo del juego

**Othello** (también conocido como **Reversi**) es un juego de estrategia abstracto para dos jugadores. El objetivo es **tener la mayor cantidad de fichas del propio color** al final de la partida. Las fichas se capturan y voltean al "sándwich" entre dos fichas propias en línea recta (horizontal, vertical o diagonal).

---

## 🎮 Jugabilidad

- **Turnos**: Las negras comienzan siempre.
- **Movimiento**: Haz clic en una casilla vacía para colocar una ficha.
- **Captura**: Se voltean todas las fichas del oponente que queden atrapadas entre la ficha recién colocada y otra ficha propia, en cualquiera de las 8 direcciones.
- **Pases**: Si un jugador no tiene movimientos legales, su turno se salta automáticamente.
- **Fin de la partida**: Cuando ningún jugador puede mover (generalmente cuando el tablero está lleno). Gana quien tenga más fichas.

### Controles

| Tecla / Acción | Efecto |
|----------------|--------|
| **Clic izquierdo** | Coloca una ficha en la casilla resaltada. |
| **R** | Reinicia la partida. |
| **H** | Muestra / oculta los puntos de ayuda (movimientos legales). |
| **ESC** | Reinicia la página (cierra el juego). |

---

## 📜 Historia del Othello / Reversi

- **Reversi** fue inventado en **1888** por el inglés **Lewis Waterman** y popularizado como un juego de tablero con fichas de dos colores.
- En **1971**, el japonés **Goro Hasegawa** rediseñó las reglas y lo comercializó con el nombre **Othello**, en referencia a la obra de Shakespeare *"Otelo"*, por la constante traición y cambio de lealtades (las fichas cambian de bando).
- La marca **Othello** es propiedad de la empresa **MegaHouse** (Japón). La versión sin marca se llama genéricamente **Reversi**.

### Versiones populares

- **Othello (juego de mesa físico)** – el clásico de tablero de 8×8.
- **Reversi** – versión libre sin marca registrada.
- **Videojuegos**: apareció en consolas como NES, SNES, y actualmente en móviles (iOS/Android).
- **Versiones online**: multijugador en plataformas como Board Game Arena, o implementaciones como la presente.

### Datos interesantes

- El tablero de 8×8 tiene **10¹²** posiciones posibles (más que el ajedrez).
- El primer movimiento siempre es en una de las cuatro casillas centrales, y el segundo en las adyacentes.
- Existen torneos mundiales de Othello desde **1977**.
- La posición inicial con las cuatro fichas centrales es la única que garantiza un juego equilibrado.

---

## 🏫 IPET 249 Nicolás Copérnico

- **Nombre completo**: Instituto Provincial de Educación Técnica Nº 249 "Nicolás Copérnico".
- **Especialidad**: **Informática**.
- **Asignatura**: **Laboratorio de Programación**.
- **Año**: **2026**.
- **Ubicación**: (Córdoba, Argentina – si se desea, se puede agregar la dirección).
- **Escudo institucional**:  
  El escudo del colegio está representado en la **barra inferior del juego** con los colores:
  - **Bordo** (fondo)
  - **Amarillo** (borde y detalles)
  - **Rojo** (franja diagonal)
  - **Blanco** (estrella central y texto "IPET 249")

---

## 🚀 Cómo ejecutar este proyecto en GitHub Pages

1. **Clona o descarga** este repositorio.
2. **Asegúrate** de que el archivo principal se llame `index.html` (ya lo está).
3. **Sube** los archivos a un repositorio en GitHub.
4. Activa **GitHub Pages** desde la configuración del repositorio (branch `main` o `master`, carpeta raíz).
5. El juego estará disponible en: `https://<tu-usuario>.github.io/<nombre-repo>/`

### Ejecución local (sin servidor)

Puedes abrir el archivo `index.html` directamente en tu navegador; no necesita servidor web (funciona con `file://`).

---

## 📂 Estructura del código

El código está contenido en un **único archivo HTML** con:
- **CSS** incrustado para el estilo visual.
- **JavaScript** con comentarios detallados en español, dividido en:
  1. Constantes y colores.
  2. Variables de estado.
  3. Lógica del tablero (funciones puras).
  4. Funciones de dibujo (Canvas).
  5. Manejadores de eventos.
  6. Inicialización y bucle principal.

---

## 🙌 Créditos

- **Adaptación web**: (Tu nombre o el del equipo)
- **Docente**: (Nombre del profesor)
- **Institución**: IPET 249 Nicolás Copérnico
- **Año**: 2026

---

¡Disfruta del juego y que gane el mejor estratega! 🎲
