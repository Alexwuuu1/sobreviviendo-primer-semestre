# Guía para la defensa oral individual

## Sobre el videojuego

**¿Cuál es la idea del videojuego?**  
Es una simulación de vida universitaria en 2D. El jugador controla a un estudiante nuevo que aprende a orientarse por el campus y, en etapas posteriores, equilibrará estudio, energía y vida social.

**¿Cuál es el género?**  
Simulación de vida con aventura RPG ligera.

**¿Cuál es la plataforma objetivo?**  
PC con Windows; posteriormente podría publicarse también en WebGL.

**¿Qué parte del videojuego trabajaste?**  
Responder con la tarea real de cada integrante y mencionar el archivo o elemento concreto modificado.

## Sobre Unity

**¿Dónde está almacenada la escena?**  
En `Assets/Scenes/Nivel01.unity`.

**¿Dónde están los assets?**  
En `Assets/Art/`, separados en Backgrounds, Characters, Decorations, Tiles y UI.

**¿Dónde están los tiles?**  
Los sprites están en `Assets/Art/Tiles/` y los objetos Tile están en `Assets/Art/Tiles/GeneratedTiles/`.

**¿Qué función cumple el Tilemap?**  
Permite construir el escenario sobre una cuadrícula reutilizando piezas gráficas. En la escena se usa para el suelo, los senderos y el edificio.

**¿Qué elementos incorpora la escena?**  
Cámara ortográfica, fondo, Grid, Tilemaps de terreno y edificio, césped, senderos, árboles, banco, señal y un estudiante provisional.

## Sobre Git

**¿Qué es main?**  
Es la rama estable que representa la versión preparada para entregar.

**¿Qué es develop?**  
Es la rama donde se integra progresivamente el trabajo del equipo.

**¿Para qué utilizaron feature/*?**  
Para desarrollar tareas específicas sin modificar directamente la versión estable ni interferir con otros cambios.

**¿Por qué utilizaron ramas?**  
Para aislar tareas, revisar cambios y mantener un historial claro de quién hizo cada aporte.

**¿Qué ocurrió durante el merge?**  
Los cambios comprobados de una rama feature se incorporaron a develop. Al finalizar, develop se integró en main.

## Sobre GitHub

**¿Cuál es tu usuario?**  
Cada integrante debe memorizar y responder su propio usuario.

**¿Cuál es tu commit?**  
Cada integrante debe identificar el mensaje y el hash corto de su commit en GitHub.

**¿Qué modificación realizaste?**  
Explicar el cambio real, por ejemplo agregar un árbol, ampliar el sendero con tiles o completar una sección del README.

**¿Cómo comprobaste que llegó al repositorio?**  
Revisando la rama y el historial de commits en GitHub, y después verificando que el cambio estuviera presente tras el merge.

## Sobre el proyecto

**¿Qué assets utilizaron?**  
Assets originales creados para la escena: fondo, césped, sendero, pared, techo, árboles, banco, señal y estudiante provisional.

**¿De dónde obtuvieron los assets?**  
Se generaron dentro del proyecto con la herramienta `Assets/Editor/Hito2Setup.cs`; no se usaron paquetes gráficos externos.

**¿Qué licencia tienen?**  
Uso académico del Grupo 64 para este proyecto.

**¿Qué falta desarrollar?**  
Movimiento, colisiones, diálogos, NPC, misiones, gestión de estadísticas, interfaz, audio, guardado y minijuegos. Esos elementos corresponden a hitos posteriores.

