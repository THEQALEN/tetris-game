🎮 Tetris Game - JavaScript Puro
Un juego de Tetris completamente funcional y jugable desarrollado con HTML5, CSS3 y JavaScript vanilla.

Tetris JavaScript HTML5

🚀 Características
✅ Tablero clásico 10×20
✅ 7 piezas oficiales (I, O, T, S, Z, J, L)
✅ Rotación completa de piezas
✅ Sistema de colisiones preciso
✅ Detección y eliminación de líneas
✅ Sistema de puntuación progresivo
✅ Niveles dinámicos que aumentan la dificultad
✅ Game Over con reinicio
✅ Interfaz visual moderna y atractiva

🎮 Controles


Tecla	Acción
←	Mover a la izquierda
→	Mover a la derecha
↓	Caída rápida
↑	Rotar pieza
ESPACIO	Caída instantánea
📊 Sistema de Puntuación
1 línea = 100 puntos × nivel
2 líneas = 300 puntos × nivel
3 líneas = 500 puntos × nivel
4 líneas = 800 puntos × nivel (¡Tetris!)
Bonus por caída rápida
🎯 Cómo Jugar
Abre tetris.html en tu navegador web
El juego inicia automáticamente
Usa las teclas de flechas para mover y rotar las piezas
Completa líneas horizontales para eliminarlas y ganar puntos
El juego termina cuando no hay espacio para una nueva pieza
💻 Instalación
bash


# Clonar el repositorio
git clone https://github.com/THEQALEN/tetris-game.git

# Entrar al directorio
cd tetris-game

# Abrir el juego (opción 1: doble clic en tetris.html)
# Opción 2: usar un servidor local
python -m http.server 8000
# Luego abre http://localhost:8000/tetris.html
🛠️ Tecnologías Utilizadas
HTML5 Canvas - Renderizado gráfico
CSS3 - Estilos y animaciones
JavaScript ES6 - Lógica del juego
Sin dependencias externas - 100% vanilla
📝 Estructura del Código


tetris.html
├── Estilos CSS (interfaz moderna)
├── Canvas (área de juego)
└── JavaScript
    ├── Configuración y constantes
    ├── Definición de piezas (7 tetrominos)
    ├── Motor del juego (colisiones, rotación)
    ├── Sistema de puntuación
    ├── Renderizado (Canvas API)
    └── Controles de teclado
🎨 Características Técnicas
Sin frameworks - Código limpio y educativo
Completamente comentado - Fácil de entender
Responsive - Se adapta a diferentes pantallas
Optimizado - Usa requestAnimationFrame para rendering fluido
Autocontenido - Un solo archivo HTML
🤝 Contribuciones
Las contribuciones son bienvenidas. Por favor:

Fork el proyecto
Crea una rama (git checkout -b feature/nueva-caracteristica)
Commit tus cambios (git commit -am 'Agrega nueva característica')
Push a la rama (git push origin feature/nueva-caracteristica)
Abre un Pull Request
📄 Licencia
Este proyecto es de código abierto y está disponible bajo la licencia MIT.

👨‍💻 Autor
Desarrollado con ❤️ por un desarrollador profesional de videojuegos

¡Disfruta del juego! 🎮
