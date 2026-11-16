# KAIRO FLUX — Capitán del equipo NEÓN

## Estado del personaje · Iteración 01

La dirección artística está fijada mediante una **lámina conceptual de frente, perfil y espalda** generada para VOLT KICK. Esta primera versión geométrica es una **maqueta 3D** para comenzar a validar volumen, silueta, paleta, equipo y proporciones; todavía no reproduce el nivel de detalle del concepto.

### Ver en el navegador

https://mandelasmith704-ai.github.io/volt-kick/captains/kairo-flux.html

La página del visor usa Three.js, carga la malla OBJ y el archivo de materiales desde `assets/`, y ofrece vistas de frente, perfil y espalda, rotación, zoom e iluminación elemental.

### Archivos editables

- [Malla OBJ](assets/kairo-flux.obj)
- [Materiales MTL](assets/kairo-flux.mtl)
- [Visor del modelo real](kairo-flux.html)

Detalles de la malla generada:
- **4,858 vértices**
- **7,895 triángulos**
- **106 piezas** geométricas nombradas
- **10 materiales** con paleta azul oscuro, cian eléctrico, plata y piel
- Orientación: eje **Y vertical**, frente hacia **+Z**.
- Sin esqueleto, pesos de skinning, morph targets, texturas UV ni animaciones de huesos.

### Pasos para importar a Unity

1. Importar `kairo-flux.obj` y `kairo-flux.mtl` juntos dentro de `Assets/Characters/Kairo/`.
2. Inspeccionar orientación y escala en una escena vacía, y usar materiales compatibles con URP.
3. Convertir la maqueta en un modelo definitivo con topología y materiales adecuados, retopología y UV mapping.
4. Construir el rig humanoide y producir idle, carrera, sprint, pase, tiro, barrida, celebración y especial eléctrico.
5. Crear versiones LOD, probar sombras y FPS en iPhone real.

### Criterios de calidad para dar por aprobado al personaje

- La silueta debe reconocerse a distancia sin depender exclusivamente del azul eléctrico.
- Rostro expresivo, cabello angular y proporciones coherentes entre vistas.
- Telas, metal, goma y emisivos deben distinguirse mediante PBR y texturas optimizadas.
- Guardar la referencia conceptual y compararla con capturas de la malla en frente, perfil y espalda.
- El modelo final debe deformarse bien al correr y patear, sin cruces entre hombros, rodillas y botas.

### Equipo y especial

- Equipo: **NEÓN**
- Nombre: **Kairo Flux**
- Poder: **rayo**
- Rasgo: **velocidad / aceleración**
- Especial previsto: **Arranque Relámpago** (aún no implementado)

**Importante:** La demo 3D web actual de VOLT KICK sigue siendo una prealfa; este estudio no añade automáticamente a Kairo al partido, ni se presenta como personaje AAA terminado.
