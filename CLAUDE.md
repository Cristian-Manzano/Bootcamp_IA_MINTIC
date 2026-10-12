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
- Estado de las fotos en la app: "Producto" = la foto del COLLAR (24924f02-6783-41ee-a411-3177ac4b5624), la del montaje ganador; se volvió a poner para regresar a la fórmula del montaje. Caja nueva sin perro: 6596d2a6-47d4-4b16-a679-bedf9b4b6341 (usar solo si se quiere la caja). Caja vieja con perro: 4b4276af-fe8f-496b-9eea-f001ec8dcc21. "Mascota" = el perro negro (51cfc608-23e6-4b2e-be92-68163558c8c3).
- REGLA (12 oct): reacciones de las personas NATURALES. Nunca pedir "laughs out loud / laughs hard" (la IA exagera: carcajadas falsas mirando a cámara, como la abuela y el papá de `dogs15`). Pedir "soft natural smile, candid, mid-action, not looking at the camera", y nada de familias posando quietas para la foto.
  - Todo tiene que parecer una persona 100 % real grabada sin saber: expresiones, gestos y movimiento del cuerpo naturales. Ej.: "reacts like a real person caught on camera: small genuine smile, glances at the dog, relaxed shoulders, natural body movement, keeps doing what they were doing". Las personas hacen algo (caminar, acariciar, agacharse, mirar al perro), no actúan para la cámara. Al editar, quitar el audio de la IA (las risas suenan falsas) y dejar solo la canción.
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
4. Fiesta de perros (12 s generados → 10 s editados, `perros_glow_texto.mp4`, frase "When your dogs throw their own glow party 🐶"):
   1. border collie y perro café persiguiéndose en el patio al anochecer (azul);
   2. broche en un labrador chocolate (verde);
   3. boston terrier y bulldog jugando en la sala, chica riéndose (rojo);
   4. corgi en el porche con una pareja riéndose (naranja);
   5. pitbull y poodle en una cancha de noche (rosa): recortada a 1 s porque salió luz verde de más;
   6. perro dormido junto a la caja en la mesa de noche (azul).
   - Aprendido: 2 perros por toma con el MISMO color salió bien de cerca (patio, sala). En tomas de lejos de noche salen luces de otro color.
5. Husky en tienda de mascotas (Chispa, un solo prompt, 12 s, 6 cr → 9,2 s editados, `husky_texto.mp4`): husky con pañoleta roja aúlla y la dueña se ríe (SIN collar: la pañoleta que tapa el cuello funcionó) · torre de cajas · broche en un husky (rosa) · niña con shih tzu (verde) · perro que salta a los brazos del dueño (azul). Se cortó una toma por una correa roja que brillaba. A Cristian no le gustó: se perdió la esencia de recopilación de los primeros videos.
6. Súper + montaje (15 s, `super_montaje_texto.mp4`, frase "Me when I finally found THE collar 😭"). A Cristian le gustó más; volvió la esencia.
   - Inicio, 5 s generados aparte con la foto de la caja (2,5 cr): la mujer ve la torre de cajas, se tapa la boca y corre a agarrar una; el esposo se ríe. En la toma NO hay perro.
   - Montaje en Chispa con la foto del collar (6 cr):
     1. galgo corriendo en un campo (rosa);
     2. broche en un bulldog inglés (verde);
     3. chico en selfie con beagle en un mirador (azul);
     4. caniche en la terraza de un café (rojo);
     5. abuelo con un schnauzer en el porche (blanco);
     6. familia con un pug y luces de Navidad (naranja).
   - Receta: un inicio cómico SIN perro + el montaje puro.
   - Prueba de ganchos (mismo video, distinto inicio; el texto sale desde el cuadro 1, sin fundido):
     - A `super_montaje_A.mp4`: abre con el galgo, texto "POV: you found the collar everyone's asking about 😭".
     - B `super_montaje_B.mp4`: abre con la mujer gritando de sorpresa, texto "I was NOT ready for this aisle 😭".
     - C `super_montaje_C.mp4`: abre con el broche, texto "Wait for it…".
     - Comparar la retención en el segundo 3 (Analíticas de TikTok).
7. Mujer 720 + montaje 15 s (método yumekawaii, 12 oct, 20 cr → carpeta `publicar_dogs12/` (archivos numerados por orden de publicación: 1 = v2 POV, 2 = v1, 3 = v4, 4 = v3, 5 = v5, 6 = v6), 12,3 s, SIN audio de la IA: se pone la canción en la app):
   - Mujer: 5 s desde su propio cuadro como start_image (720p, 5 cr): manos en la boca → corre y abraza una caja riéndose. Salió perfecta.
   - Montaje 720p 15 s (15 cr) con la foto del collar: golden corriendo de noche (naranja) · broche en un labrador negro (verde) · frenchie lame la cara a un papá (azul) · beagle atrapa una pelota con niñas (rosa) · chico en selfie con husky (rojo) · aussie salta en un parque (blanco) · abuela con un cavalier (rosa) · familia con golden y luces de Navidad (naranja).
   - Orden editado: mujer → broche → resto. Se cortó el inicio del aussie: el frisbee salió como aro rojo brillante.
   - Re-edición: se quitó la abuela (carcajada falsa) y se acortaron el papá, la mujer y la familia. Se borraron los `dogs15` de 15 s.
   - Publicación en IG (12 oct): v2 a las 3:30 p. m. con "Total Eclipse of the Heart"; v1 y v4 en la noche (8:45–10:30 p. m.); el resto, al día siguiente. Cada versión con una canción distinta para ver cuál gana (como yumekawaii): v1 Lovely Day · v2 Total Eclipse of the Heart · v3 Walking on Sunshine · v4 Dreams (Fleetwood Mac) · v5 Here Comes the Sun · v6 Mr. Blue Sky.
   - 6 versiones, solo cambia el texto de arriba; CTA desde el s 9,8: la 1 (POV) dice "Comment GLOW if you want one ✨"; las 2–6 dicen "Comment GLOW if you NEED one" y la palabra GLOW + el corazón cambian de color cada 0,5 s (naranja 🧡 → verde 💚 → rosa 💗 → azul 💙 → rojo ❤️), como el collar. Idea de Cristian. Script: scratchpad/test/compose_cyc.py.
     1. Dog moms, this one's for you 🐶
     2. POV: you found the collar everyone's asking about 😭
     3. Golden retriever owners NEED this 😭
     4. Night walks will never be the same 🌙
     5. The perfect gift for a dog mom doesn't exis.. 😮
     6. My dog every single night now 😂
## Plan de publicación (desde el 12 oct 2026)
- 2 videos al día: 12:00 p. m. y 7:00 p. m., hora de Colombia (1 p. m. y 8 p. m. hora del este de EE. UU.).
- Primero se publican los videos con los ganchos A/B/C, uno por día al mediodía.
- Versiones en 1080 listas para publicar (A = el original):
  - `fiesta_A/B/C_1080.mp4`:
    - B abre con el broche, "Wait for it…";
    - C abre con los perros en la sala, "My dogs every single night now 😂".
  - `golden_A/B/C_1080.mp4`:
    - B abre con el golden corriendo de noche, "POV: he picked his own gift at the store 😂";
    - C abre con el salto en el carrito, "He saw these and refused to leave 😭".
  - `super_montaje_A/B/C_1080.mp4`.
- Regla: nunca dos versiones del mismo video el mismo día.

## Tienda (kindear.vercel.app/glow)
- Se edita desde el chat "página de producto" de Cristian. El código no está en GitHub, así que yo no la puedo editar directo: le paso las órdenes listas para pegar.
- Estado al 11 oct 2026:
  - logo GLOW y colores de marca;
  - 6 colores;
  - paquetes 1 / 2 / 3: $21.99 / $36.99 / $49.99, eligiendo color y talla por collar;
  - "Order by Nov 28 for Christmas";
  - pago por PayPal.
- Link para responder GLOW: kindear.vercel.app/glow.
- Proveedor: ~US$6 por collar (precio sin el descuento de bienvenida). Tiene 7 colores.
  - Ganancia aproximada: ~$14.70 por 1 collar y ~$23 por el paquete de 2.
  - Meta: US$1.000 ≈ 55–65 pedidos.
  - Pendiente: confirmar el costo con envío a EE. UU.
- Calidad (11 oct): los días 1–3 se publican tal cual, en 480p generado → 1080. Si les va bien, desde el día 4 se generan en 720p (12 cr por 12 s).
  - Mejora gratis con Real-ESRGAN: mejora la imagen, pero tarda ~35 min por video sin GPU. Se canceló por ahora.
  - Script en el scratchpad: sr.py + realesr-general-x4v3.pth.

## Producto 2 en prueba: linternas de silicona con forma de animalitos (para niños)
- Proveedor elegido: LOKEY Store (AliExpress, item 3256811988317114).
  - Costo: US$14,69 con envío gratis a EE. UU., ~11 días. Máximo 1 pieza por cliente.
  - 9 modelos: cocodrilo, tortuga, ciervo, unicornio, ballena/delfín, etc.
- Respaldo: Fashion Home Life Store, US$3,97 + US$9,63 de envío, ~17 días, sin límite por cliente, sin reseñas.
- Precios sugeridos: 1 por $29.99 (~$13,8 de ganancia) · 2 por $49.99 (~$18,4) · 3 por $64.99.
- Ángulo: regalo de Navidad para niños; encaja con la marca GLOW.
- Riesgo: la forma alargada puede generar chistes de doble sentido. Mostrarlo siempre con niños, cuentos y animalitos.

## ManyChat (Instagram @kindearglow)
- Cuenta de Instagram cambiada a Creator (tiene más música que Business).
- Plan Essential en prueba gratis desde el 11 oct 2026; primer cobro de US$17 el 26 oct 2026. Recordatorio para decidir: 23 oct, 9 a. m.
- Automatización LIVE:
  - palabras clave: GLOW / glow / Glow / link / price;
  - 3 respuestas públicas;
  - mensaje inicial con el botón "Send me the link";
  - mensaje con el botón "Get my GLOW collar" → https://kindear.vercel.app/glow.
- Instagram es donde funciona: el Reel de súper + montaje A llegó a ~5.000 vistas y 70 likes, y la gente lo ve hasta el segundo 9. TikTok y Facebook siguen por debajo de 300.
  - Portada con la cara de sorpresa de la mujer, elegida por Cristian.

## Referencia de contenido viral
- Análisis de reels de @yumekawaiicompany: `investigacion/analisis-yumekawaii.md`
- Datos: `investigacion/reels-yumekawaii.csv` y `investigacion/comentarios-top5.csv`
- Úsalo siempre que trabajemos en guiones, videos, ganchos o estrategia de TikTok/Instagram.
- No inventes datos: si algo dice "no visible", no se sabe.
