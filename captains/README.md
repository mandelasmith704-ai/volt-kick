# VOLT KICK — Kairo Flux (NEÓN)

## Modelo actual: V4.1 — Pase de detalle y limpieza

**Visor interactivo:** https://mandelasmith704-ai.github.io/volt-kick/captains/kairo-flux.html?v=41

### Entregable actual

- [Kairo V4.1 · GLB (2.17 MB)](assets/kairo-flux-v4-1-cleanup.glb) — modelo tridimensional estático, con la reconstrucción texturizada de V3 y piezas nuevas de detalle
- [Visor 3D](kairo-flux.html) — comparador V4.1 y V3, giro libre, acercamiento de rostro y modo alambre
- [V4 inicial (conservada)](assets/kairo-flux-v4-detail-pass.glb)
- [V3 texturizada (conservada)](assets/kairo-flux-v3-textured.glb)
- [V2 anterior (conservada)](assets/kairo-flux-v2.glb)

### Cambios realizados respecto a V3

1. Geometría independiente de cabello angular, con mechones cortos y acentos azules
2. Trazo eléctrico ligeramente volumétrico sobre la mejilla izquierda
3. Capas de protección en hombros y guanteletes, con líneas luminosas
4. Elementos adicionales en espinilleras y botas
5. Limpieza de **890 triángulos** de pequeños fragmentos desconectados de la proyección original
6. Materiales diferenciados (azules, titanio, piel, cabello y emisivos), manteniendo la textura aprobada en el cuerpo

### Verificaciones técnicas realizadas

- **100,872 triángulos** en **56 mallas** (una malla base + 55 piezas)
- **53,085 vértices** después de las operaciones de geometría y UV
- GLB de **2.17 MB**, generado y reimportado satisfactoriamente con Trimesh
- Render real de frente, perfil y espalda en VTK
- JavaScript del visor verificado sintácticamente
- Archivo y visor subidos a GitHub
- El modelo base **no es completamente hermético** (`is_watertight = false`): quedan aberturas y transiciones que necesitan reconstrucción; el modelo **no está listo para rigging**

### Limitaciones que siguen pendientes

La reconstrucción fototexturizada sigue teniendo costuras y errores de profundidad entre las distintas vistas, especialmente en perfil. Las piezas de detalle V4.1 son adiciones independientes y no reemplazan la necesidad de modelado orgánico supervisado. El rostro no es una escultura manual de alta fidelidad, no hay materiales PBR pintados con UV propias, y tampoco hay esqueleto, pesos, animaciones, LOD ni validación de rendimiento iOS.

**Más polígonos no equivalen a calidad AAA.** La ruta de producción de Kairo pasa por reconstruir una malla limpia en Blender u otra herramienta 3D especializada, mejorar rostro/cabello, retopología, UV y materiales, rig y animaciones, y probar en Unity.

### Alcance

Solo Kairo Flux. No se modificaron los demás capitanes, la cancha, el partido ni la afición. Evitar mezclar esta maqueta con el personaje comercial definitivo.
