# Three.js Water Drops & Octree Physics

Este proyecto es una simulación interactiva en 3D construida con **Three.js**. Implementa un sistema de colisiones basado en **Octree** para permitir que el jugador explore un mapa complejo y lance proyectiles de agua con propiedades físicas visuales realistas.

## 🚀 Características

- **Agua Realista:** Proyectiles con `MeshPhysicalMaterial` que incluyen transparencia (transmisión), refracción y reflejos.
- **Octree Physics:** Colisiones optimizadas de alto rendimiento entre el jugador, los proyectiles y el entorno.
- **Cámara en Primera Persona:** Control total mediante `Pointer Lock API`.
- **Lanzamiento Dinámico:** La fuerza del proyectil depende del tiempo de carga al mantener presionado el ratón.

## 📁 Estructura del Proyecto

- `index.html`: Configuración de la escena y carga de módulos.
- `style.css`: Estilos visuales de la interfaz.
- `script.js`: Lógica del juego, físicas y renderizado.

## 🛠️ Instalación

1. Copia los archivos a tu servidor local.
2. Asegúrate de tener los assets en la ruta:
   `./assets/models/gltf/collision-world.glb`
3. Ejecuta un servidor local (ej. Live Server en VS Code) para evitar problemas de CORS.

## 🎮 Controles

- **Moverse:** `W` `A` `S` `D`
- **Saltar:** `Espacio`
- **Mirar:** Movimiento del ratón
- **Lanzar Agua:** Mantener clic izquierdo y soltar.

---
*Desarrollado con Three.js*
