# VOLT KICK — Biblia de los cinco capitanes (concepto v1)

**Estado:** dirección artística aprobada como referencia visual; todavía **NO** hay modelos 3D definitivos, rig ni integración en la partida. El arte conceptual no se debe presentar como captura del juego.

## Pilares de producción
- Cinco equipos originales, un capitán protagonista por equipo; sus acompañantes se harán después a partir de modelos genéricos con colores y equipamiento del equipo.
- Estilo: fútbol arcade futurista, semi-estilizado, siluetas distintivas, materiales creíbles, toques de energía, lectura visual nítida desde cámara lejana.
- La energía elemental debe notarse en cabello, emblema, guantes, botas y animaciones, sin depender de partículas excesivas.
- Diseños y nombres de trabajo originales; revisar disponibilidad de marcas antes de publicar comercialmente.
- Prioridad: capitanes, no cambiar estadio ni afición durante esta fase.

## 1. NEÓN — «EL RELÁMPAGO» (capitán rápido)
- **Nombre provisional:** Kairo Flux
- **Identidad:** poder de rayo, aceleración explosiva.
- **Silueta:** delantero atlético de torso en V, armadura aerodinámica, cabello con puntas angulares, guantes ligeros.
- **Colores:** cian eléctrico, azul noche, plata.
- **Detalles de firma:** surcos en zigzag en hombreras, botas con aletas luminosas, emblema del rayo.
- **Rasgo de animación:** salida de velocista, zancadas largas, estela eléctrica breve.
- **Poder conceptual:** *Arranque Relámpago* (aceleración especial); pendiente balancear.

## 2. BLAZE — «EL TITÁN» (capitán fuerte)
- **Nombre provisional:** Kael Magma
- **Identidad:** roca volcánica y lava, potencia de choque.
- **Silueta:** muy ancho y macizo, hombros masivos, brazos como basalto agrietado, botas pesadas.
- **Colores:** obsidiana, naranja magma, rojo incandescente.
- **Detalles de firma:** grietas luminosas bajo placas de piedra, vapor discreto, emblema de llama.
- **Rasgo de animación:** pisadas pesadas, impacto del suelo, preparación del cañonazo.
- **Poder conceptual:** *Martillo Magmático* (remate de gran fuerza); pendiente balancear.

## 3. AERIS — «LA ZÉFIRA» (capitana ágil)
- **Nombre provisional:** Lyra Zéfira
- **Identidad:** viento, agilidad, regates y cambios de dirección.
- **Silueta:** mujer atlética y liviana, cabello largo en movimiento, protecciones pequeñas, bufanda/cinta aerodinámica segura para animación.
- **Colores:** turquesa, plata, blanco nacarado.
- **Detalles de firma:** espirales en tela y armadura, aletas flexibles, emblema de remolino.
- **Rasgo de animación:** giros, pasos laterales, fintas fluidas y remolinos moderados.
- **Poder conceptual:** *Danza del Ciclón* (regate/evitación temporal); pendiente balancear.

## 4. FROST — «EL GLACIAL» (capitán resistente)
- **Nombre provisional:** Boreal
- **Identidad:** hielo y control defensivo del espacio.
- **Silueta:** alto, ancho, protector de cuello, guanteletes geométricos, hombros con cristal de hielo.
- **Colores:** azul glaciar, blanco, acero frío.
- **Detalles de firma:** fractales discretos, placas translúcidas y emblema de copo.
- **Rasgo de animación:** guardia firme, pasos medidos, ráfaga de cristales al defender.
- **Poder conceptual:** *Muro Boreal* (bloqueo/contención breve); pendiente balancear.

## 5. VORTEX — «EL ESTRATEGA» (capitán técnico)
- **Nombre provisional:** Veyr Nexus
- **Identidad:** gravedad, anticipación y precisión.
- **Silueta:** complexión media, gesto seguro, peinado en trenzas, visor violeta, armadura asimétrica.
- **Colores:** violeta, negro grafito, magenta.
- **Detalles de firma:** anillos concéntricos, orbes suspendidos y emblema espiral.
- **Rasgo de animación:** gestos controlados, energía orbital alrededor del balón durante el especial.
- **Poder conceptual:** *Órbita Cero* (alteración breve de la trayectoria del balón); pendiente balancear.

## Plan de modelado e integración

1. **Hojas de personaje (turnaround)**: frente, perfil y espalda de cada capitán, más primer plano de rostro, uniforme, botas y accesorios. Corregir cualquier detalle inconsistente antes de modelar.
2. **Modelo 3D maestro**: comenzar con NEÓN como piloto; topología adecuada para animación, materiales PBR, UVs, LODs.
3. **Rig + animación**: esqueleto humanoide, idle, carrera, giro, sprint, pase, tiro, barrida, celebración y especial propio; comprobar clipping.
4. **Prueba en Unity**: cámara y tamaño reales del partido, iluminación de prueba, sombras y rendimiento móvil. No asumir que la demo WebGL actual representa el aspecto final.
5. **Repetir para BLAZE, AERIS, FROST y VORTEX**, reutilizando un rig base cuando tenga sentido.
6. **Después:** diseñar acompañantes genéricos por equipo; recién entonces avanzar a campo, porterías y afición.

## Criterios de aceptación visual
- Reconocer cada capitán por silueta aun sin colores.
- Rostro, traje y accesorios coherentes entre frente/perfil/espalda.
- Materiales de tela, goma, metal y energía diferenciados sin exceso de brillo.
- Las poses/animaciones no atraviesan la geometría del cuerpo.
- Buen aspecto en planos cercanos y desde la cámara normal del partido.
- Rendimiento confirmado en dispositivo iOS objetivo; objetivos de polígonos/texturas se fijarán mediante pruebas, no promesas.

**Nota:** Las cinco identidades y habilidades son propuestas creativas, no habilidades ya programadas.
