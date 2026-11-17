# VOLT KICK — KAIRO FLUX (NEÓN)

**Vista interactiva actual:** https://mandelasmith704-ai.github.io/volt-kick/captains/kairo-flux.html

## Estado: V3 — Reconstrucción volumétrica a partir del arte aprobado

Se reconstruyó el volumen 3D usando las siluetas de las vistas frontal y lateral del diseño maestro y se aplicaron las tres vistas de la ilustración como textura proyectada. Esto permite ver a Kairo desde diferentes ángulos con mayor semejanza visual al concepto: rostro, rayo del pecho, uniforme 07, hombreras, guantes y espinilleras.

### Entregable principal
- **[Kairo Flux V3 texturizado (GLB, 2.58 MB)](assets/kairo-flux-v3-textured.glb)**: malla 3D continua y texturizada, altura aproximadamente 1.86 m.
- [Visor web de Kairo Flux](kairo-flux.html): giro libre, vistas ortogonales aproximadas, acercamiento al rostro y modo de malla.
- [Kairo Flux V2 anterior](assets/kairo-flux-v2.glb): conservado como respaldo.

### Verificación técnica local
- **85,232 triángulos**, alrededor de **45,462 vértices** después de separar las coordenadas de textura.
- Malla volumétrica cerrada según verificación de Trimesh (`is_watertight`).
- Textura derivada de las vistas aprobadas, no inventada para sustituir el diseño.
- GLB exportado y renderizado desde frente, perfil y espalda en una prueba local con VTK.
- Archivo GLB y actualización de visor subidos al repositorio y verificados.
- Esta prueba **no equivale** a compilar el proyecto en Unity ni a inspección visual en todos los navegadores.

### Limitaciones IMPORTANTES
Este modelo es una **aproximación volumétrica multivista**, no una escultura tridimensional artística lista para producción. Las vistas de referencia solo muestran 3 ángulos; hay costuras visibles en transiciones y detalles de la superficie que requieren reconstrucción manual. No tiene rig humanoide, texturas PBR separadas, UVs propias de producción, expresiones animadas ni optimización LOD.

**Más polígonos no significan automáticamente más calidad.** Nuestra prioridad es el parecido facial y de silueta, consistencia entre vistas, retopología correcta, texturas artísticas y animación.

### Próximo paso real de producción
1. Corregir anatomía, profundidad y cabello en una herramienta de escultura 3D (Blender o un generador especializado con revisión).
2. Retopología y UVs propias, material PBR para tela/piel/metal/energía.
3. Rig y peso de vértices para caminar, correr, girar y chutar.
4. Aplicar LOD y optimizar para iOS; pruebas de rendimiento.
5. Integrar este capitán dentro de Unity, y después continuar con los otros cuatro capitanes.

**Alcance:** solo el personaje Kairo Flux. No se ha modificado el partido, la cancha ni la afición.
