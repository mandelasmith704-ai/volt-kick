# KAIRO FLUX — Capitán NEÓN

## V5 — Corrección de apariencia oscura (17 de noviembre de 2026)

**Visor interactivo:** https://mandelasmith704-ai.github.io/volt-kick/captains/kairo-flux.html?v=5

**Modelo actual:** [Kairo Flux V5 · GLB](assets/kairo-flux-v5-colorfix.glb), un modelo 3D estático de referencia para VOLT KICK.

### Qué se corrigió

- La textura original ya contenía sombras y luces pintadas; el visor aplicaba sombreado físico y sombras propias sobre ella, duplicando el oscurecimiento.
- La iluminación frontal insuficiente hacía que el rostro y el uniforme perdieran detalle.
- Las superficies del cabello y la armadura eran excesivamente oscuras incluso sin el visor.

En V5, los tonos medios del mapa de textura se elevaron con una transformación conservando contraste, se aclaró la paleta del cabello, metálicos y piel, y se agregaron nueve trazos 3D decorativos de energía en hombros, botas, cintura y espinilleras.

El visor ahora:
- Carga V5 por defecto.
- Aplica por defecto **TEXTURA CLARA** (material sin doble sombreado) solo a las texturas fotoproyectadas.
- Conserva iluminación física en las piezas sin proyección.
- Añade relleno frontal y desactiva el autosombreado problemático de la malla provisional.
- Permite alternar modo claro/PBR, comparar V5/V4.1/V3, activar energía, malla, giro y primer plano de rostro.

### Verificaciones técnicas

- 65 mallas, **101,272 triángulos**, archivo de **2,856,228 bytes**.
- El GLB se reimportó con Trimesh.
- Se renderizaron vistas frontal, perfil y posterior con VTK.
- El JavaScript del visor pasó comprobación sintáctica.
- GitHub Actions publicó el cambio con estado *success*.

### Versiones guardadas

- [V5 claro](assets/kairo-flux-v5-colorfix.glb)
- [V4.1](assets/kairo-flux-v4-1-cleanup.glb)
- [V4](assets/kairo-flux-v4-detail-pass.glb)
- [V3](assets/kairo-flux-v3-textured.glb)
- [V2](assets/kairo-flux-v2.glb)

### Limitaciones reales

Aunque V5 mejora visibilidad y algunos detalles, **no es una escultura profesional terminada**. La geometría base y parte de la apariencia fueron reconstruidas a partir de imágenes, por lo que persisten errores anatómicos, costuras, superposiciones, proyección lateral imperfecta y partes separadas. No tiene rig, animaciones, UVs de producción ni LODs, y tampoco está validada su ejecución a rendimiento objetivo en iPhone.

Siguiente hito de calidad: reconstruir cabeza y cuerpo con modelado 3D supervisado y topología continua, mapear textiles y metal mediante texturas PBR, preparar esqueleto/skin y verificar las animaciones en Unity.

**Alcance:** Solo Kairo Flux. El partido, el estadio, la afición y los otros cuatro capitanes siguen sin cambios.
