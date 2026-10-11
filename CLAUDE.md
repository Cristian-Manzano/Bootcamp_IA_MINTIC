# Memoria de Chispa Studio (collar LED para perros)

## La fórmula de los videos que funcionan
La saqué de 3 videos de referencia de TikTok que subió Cristian:
- una máscara de miedo para el asiento del carro;
- una bandana con cara de viejo para pescadores;
- una lagartija de resorte para la moto.

Con esta fórmula salió el video ganador (`montaje_editado.mp4`).

1. **Sorpresa en los primeros 1–2 s.** Abre con la toma más llamativa: una revelación, una acción inesperada o algo en movimiento que brille.
2. **Un corte cada 1,5–2,5 s.** Cada toma pasa en otro lugar, con otra gente, otro perro y otro ambiente.
3. **Cámara en mano y con movimiento:** seguir al perro, acercarse, selfie, POV desde el carro, plano bajo.
4. **El producto sale en TODAS las tomas, en uso.** Que parezca una recopilación de clientes ("todo el mundo lo tiene").
5. **Nadie vende hablando a cámara.** La emoción la ponen las risas y las reacciones. Sin voz y sin texto generado por la IA, porque lo escribe mal y mete emojis al azar.
6. **En TikTok se agregan tres cosas:**
   - una sola frase de identificación arriba durante todo el video, no de venta (ej. "Dog moms, this one's for you 🐶");
   - al final, una palabra para comentar (ej. "Comment 'GLOW' if you want one");
   - un sonido de moda.
7. **Duración de 10–15 s.** 12 s = 6 tomas de 2 s, en este orden:
   1. toma llamativa;
   2. el botón del broche (cómo funciona);
   3. tres tomas variadas;
   4. cierre emotivo.

## Cómo dar prompts
Cada vez que Cristian pida un prompt:
- Usa la estructura de arriba y **varía todo**: lugares, razas, personas, colores, cámara, gancho y frase de TikTok.
- No repitas las combinaciones de la lista "Ya usados".
- Escríbelo en español; lo hablado o escrito para el público, en inglés.
- Como se pega con el Modo Agente apagado, el prompt debe llevar dentro las reglas del collar.
- En la app: UGC Try-On, estructura "Montaje rápido (corte cada 2 s)", 12 s y "Prueba · 480p" para probar.

## Reglas del collar (van en cada prompt)
- **Quién lo lleva:** solo los perros, nunca las personas.
- **Cómo se enciende:** solo con el botón del broche blanco en la nuca, nunca desde la correa.
- **Nada más brilla:** las correas son normales y no brillan; no inventar otros accesorios que brillen.
- **Lo que sí tiene:** 6 colores (naranja, verde, rosa, rojo, azul, blanco), 3 modos de luz, se corta a la medida y carga por USB.
- **NO afirmar** distancia exacta, que es resistente al agua ni horas de batería. Sin perros metidos al agua.
- **Visibilidad:** en las tomas de lejos el perro tiene que verse claro.
- **Ojo al revisar:** en 2 de 3 montajes la IA puso una correa o tira extra que brilla (playa, dachshund). Revisar siempre y cortar esa toma.

## Texto en los videos (estilo aprobado por Cristian)
- Solo texto, SIN fondo ni cuadro blanco. Letra Montserrat 800, blanca, 34 px en un video de 720×1280, con sombra suave negra para que se lea.
- Va arriba (desde ~150 px del borde superior), centrado y en máximo 2 líneas equilibradas, sin tapar caras ni perros. El emoji va pegado a la última palabra.
- Durante casi todo el video sale la frase de identificación. En los últimos 2,5 s se cambia por el llamado a comentar, con la palabra clave en naranja (#FF8A3D), con aparición suave.
- Cómo se hace: se generan imágenes transparentes con Chromium/Playwright y se ponen encima con ffmpeg (overlay).

## Prueba en curso: con texto vs. sin texto
- Publicar unos videos con este texto y otros sin texto, y comparar en "Resultados" las vistas y el % que ve el video completo.
- Día 1: Montaje con texto (`montaje_texto.mp4`), a las 7 p. m.
- Videos 4–6 ya tienen el texto nuevo y GLOW: `antes_despues_texto.mp4` (12,6 s), `max_texto.mp4`, `reto_texto.mp4`. El texto viejo de la IA se borró con delogo.

## Descripción de las publicaciones (formato aprobado)
- REGLA: la palabra para comentar es SIEMPRE una sola y la misma: GLOW. En la descripción y en el texto final del video. Nunca otra (ni "color" ni frases).
- Primero, una sola frase con la palabra para comentar: Comment "GLOW" and I'll send you the link 🐶✨
- Al final, 3–5 hashtags (#dogmom #ledcollar #dogsoftiktok #nightwalk…).
- Referencias: Rain Coded ("Comment GREEN if you would buy this") y Novax ("Comenta moto para info", 39,7 k likes, ángulo de regalo).
- El texto en pantalla puede dejar la frase a medias para dar curiosidad: "The perfect gift for a dog mom doesn't exis.. 😮". El ángulo de regalo sirve para Halloween y Navidad.
- Siempre responder los comentarios con el link por mensaje (ManyChat en Instagram y Facebook; a mano en TikTok).

## Marca
- Nombre: **KINDEAR GLOW** (LED Dog Collar). Logo: "KINDEAR" en blanco, espaciado, sobre "GLOW" en letras de neón (G verde, L azul, O rosa en forma de collar con broche blanco, W amarilla) en fondo azul oscuro / morado.
- Caja: azul marino, perro negro con collar verde, íconos "360° GLOW", "USB RECHARGEABLE", "3 LIGHT MODES". Usar la foto de la caja como referencia en Higgsfield para que la IA la copie igual.
- La W amarilla es solo diseño: en los videos los collares van en los 6 colores reales, nunca amarillo.
- Próximo video (idea de Cristian, esperando sus referencias): pareja con su perro en el supermercado; el perro ve la caja KINDEAR GLOW y se emociona; la mujer se desmaya (comedia); transición al perro de noche con el collar; montaje de varios perros jugando con el collar; cierre con la caja y GLOW.

- Primer intento del supermercado (7,5 cr, editado gratis → `super_texto.mp4`). Errores a evitar en el próximo:
  - el perro ya llevaba collar antes de ver la caja → en el supermercado debe llevar SOLO arnés, nada en el cuello;
  - salía una sola caja → pedir un estante lleno de decenas de cajas KINDEAR GLOW;
  - la mujer no se desmayó → describir el desmayo paso a paso;
  - la toma de varios perros jugando en el parque salió con correas brillantes por el piso → nada de grupos de perros con correas; un perro por toma.
- Estado de las fotos en la app: "Producto" = la CAJA (4b4276af-fe8f-496b-9eea-f001ec8dcc21), de forma temporal. La foto del collar es 24924f02-6783-41ee-a411-3177ac4b5624; devolverla cuando se termine el video de la caja. "Mascota" = el perro negro otra vez (51cfc608-23e6-4b2e-be92-68163558c8c3). Con "Montaje rápido" se manda una sola foto (Producto).
- Receta que funciona: 1 sola foto de referencia; collar siempre puesto; tomas de 2 s simples; un solo cambio (el broche que se enciende); todo en positivo (ej. pañoleta roja en vez de "sin collar"); acciones fáciles (reír, taparse la boca; no desmayos); un perro por toma.

## Método para no perder créditos (acordado después del supermercado)
- Por qué los primeros salieron bien: en los montajes el collar sale puesto y encendido en todas las tomas. A la IA le es fácil, porque solo copia la foto del collar. Los errores se cortaban en edición.
- Por qué falló el supermercado: pedía "sin collar" al principio y "con collar" después. La IA falla con las negaciones y con los cambios de estado, y además la app le manda la foto del collar y la caja (que también trae un perro con collar), así que lo copia. Los desmayos y la comedia física también le salen mal.
- Regla 1: el formato principal es el montaje con el collar siempre puesto.
- Regla 2: si una toma necesita que el collar NO aparezca (o un momento exacto), se hace por partes:
  1. primero una imagen fija (Nano Banana 2: 1,5 cr por la app/MCP, o gratis en la web de Higgsfield con el ilimitado);
  2. Cristian aprueba la imagen;
  3. se anima esa imagen como start_image, 5 s a 480p = 2,5 cr, mandando solo las fotos que deben salir (en "antes del collar", nunca la foto del collar).
- Regla 3: probar las ideas nuevas en piezas de ≤6 s, nunca el video completo. Yo armo y edito el video gratis.
- Comprobado (supermercado final → `super2_texto.mp4`): la toma "antes del collar" se generó SIN ninguna foto (solo texto, 5 s, 2,5 cr) y salió limpia: golden con arnés negro y pañoleta roja dentro del carrito. El resto se pegó gratis con tomas ya generadas.
- Regla 4: antes de que Cristian envíe, revisar el prompt contra la lista de fallas conocidas: negaciones, desmayos o comedia física, grupos de perros con correas, texto en pantalla, cambios de estado.

## Preferencias de Cristian
- Preguntar antes de gastar créditos de Higgsfield.
- No agregar funciones nuevas a la app si no las pide.
- Respuestas cortas: cuidar su uso semanal de Claude.

## Ya usados
1. Montaje ganador:
   1. golden retriever con el botón del broche (naranja);
   2. husky corriendo en un parque (azul);
   3. chica en selfie en la ciudad (rosa);
   4. perro visto desde el carro (verde);
   5. niñas en el patio con un perro negro (rojo);
   6. pareja en la playa: se quitó en la edición porque salió una correa brillante.
2. Aventura de noche (10 s): perro corriendo en un sendero del bosque (verde) · botón del broche junto a una carpa (naranja) · chico subiendo una montaña (rojo) · perro saltando de una camioneta (blanco) · perro junto a la fogata (azul).
3. Razas y colores (10 s): chihuahua (rosa) · botón del broche en un golden (naranja) · dachshund en la acera (verde) · pastor alemán en un parque (azul) · pomerania en brazos de su dueña (rojo).
