# KAIRO FLUX — Capitán NEÓN

## Modelo 3D: iteración 02

**Visor web:** https://mandelasmith704-ai.github.io/volt-kick/captains/kairo-flux.html

Se regeneró la malla geométrica inicial de Kairo, buscando una silueta más orgánica con rostro, anatomía, cabello en mechones 3D, calzado deportivo y armadura por capas. Se mejoraron materiales, iluminación y controles del visor, con un modo **ROSTRO**.

### Entregables subidos a GitHub

- **[Kairo Flux GLB v2 para Unity / Blender](assets/kairo-flux-v2.glb)** — archivo 3D binario con geometría, normales y 12 materiales. 647 KB aprox.; escala corregida a una estatura aproximada de 1.86 m. **Sin rig ni animación.**
- [Modelo actualizado OBJ](assets/kairo-flux.obj)
- [Materiales MTL](assets/kairo-flux.mtl)
- [Visor interactivo](kairo-flux.html)
- [Versión OBJ anterior, respaldo](archive/kairo-flux-v01.obj)
- [Materiales anteriores, respaldo](archive/kairo-flux-v01.mtl)

### Verificaciones geométricas realizadas

- 18,763 vértices y 18,763 normales
- 31,868 triángulos
- 138 objetos/piezas con 12 materiales
- 0 índices de vértice o normal fuera de rango
- JavaScript del visor verificado sintácticamente; visor actualizado para cargar el mismo GLB, sin prueba visual en dispositivo real

### Lo que falta — sin maquillar el estado

Este **no** es todavía un personaje 3D profesional terminado ni una conversión fiel del concepto ilustrado. Las formas se han generado de manera procedural y carecen de retopología artística, UVs, texturas pintadas, esqueleto, pesos de deformación y animaciones de personaje. Aún no se ha comprobado visualmente en todos los dispositivos.

Para acercarlo al concepto hay que utilizar un flujo profesional con **Blender** o una plataforma de generación de modelos 3D con revisión humana. Recomiendo comparar frontal, lateral, espalda y primer plano del rostro con el arte conceptual de referencia, y corregir hasta obtener una silueta convincente antes de añadir animaciones o producir más capitanes.

### Siguiente nivel de calidad

1. Escultura anatómica supervisada y diseño facial fiel a la hoja conceptual.
2. Vestuario y armaduras con UV, PBR y texturas.
3. Retopología y rig humanoide.
4. Animaciones de carrera, tiro y especial del rayo.
5. LODs y pruebas de rendimiento en iPhone; luego importar en Unity.

**Alcance:** solo Kairo Flux. Aún no modifica el estadio, la afición, el partido ni los otros capitanes.
