# Pokémon SoulGold — Castellano

Traducción no oficial al **castellano de España** de *Pokémon SoulGold*, el hack de GBA que rehace Johto y Kanto
al estilo de Oro HeartGold y Plata SoulSilver sobre Pokémon Esmeralda.

> Este repositorio **no contiene ninguna ROM**. El parche BPS está en la página de la versión: necesitas tu propia
> copia de Pokémon Esmeralda (USA). No hace falta el parche original de SoulGold.

## Estado

Versión de prueba (**v0.81**), en desarrollo, sobre la versión **1.2.1** del hack. Revisado en emulador: pantalla de inicio, intro, elección de
personaje, teclado de nombres, menú, Mochila, Opciones, Ficha de Entrenador, datos del Pokémon, equipo,
Guía, guardar y textos de combate.

Puede haber frases que no encajen bien con su contexto, textos cortados o algún resto en inglés. Si encuentras
alguno, [avísame con el formulario de fallos](../../issues/new?template=fallo.yml) y una captura.

## Qué está traducido

- Diálogos, menús, combate, objetos, movimientos, habilidades y Pokédex.
- Nombres oficiales en castellano: Pokémon, lugares de Johto y Kanto (los de Oro HeartGold y Plata SoulSilver),
  objetos, MT/MO, megapiedras y movimientos Gigamax.
- Frases según el sexo del protagonista («Estás cansado/cansada»).
- «El Pidgey salvaje», «el Pidgey rival», «tu equipo» / «el equipo rival» en combate.
- Teclado de nombres con **ñ** y vocales acentuadas, y rótulos del teclado en castellano.
- Unidades métricas en la Pokédex («1,2 m», «34,5 kg»).
- Pantalla de opciones del hack, Mochila y menú de pausa.

Lo inventado por el hack (megapiedras de tipo, hierbas, etc.) tiene un nombre propio con el estilo de los juegos
oficiales.

## Cómo aplicar el parche

1. Consigue la ROM de **Pokémon Esmeralda (USA)**:

   | Dato | Valor |
   |---|---|
   | CRC32 | `1F1C08FB` |
   | SHA-1 | `f3ae088181bf583e55daf962a92bb46f4f1d07b7` |

   Si el CRC32 no coincide (Esmeralda española, otra región o una ROM ya parcheada), el juego no funcionará bien.

2. Descarga `Pokemon-SoulGold-Castellano.bps` de la [última versión](../../releases/latest) y aplícalo
   **directamente** sobre esa ROM con [Floating IPS](https://github.com/Alcaro/Flips),
   [RomPatcher.js](https://www.marcrobledo.com/RomPatcher.js/) o cualquier otra herramienta compatible con BPS.
   No apliques antes el parche de SoulGold en inglés.
3. El resultado es la ROM en castellano:

   | Dato | Valor |
   |---|---|
   | Tamaño | 32 MB |
   | CRC32 | `53D31104` |
   | SHA-1 | `d58bb903746b38dc07627e71b69c5dc286f8f60b` |

Empieza partida nueva. No cargues estados guardados de la versión en inglés.

## Cambios

**13-nov-2026 (v0.81)**
- Pokédex, página de evoluciones: ya no sale texto basura detrás de «Macho» (Espurr) ni en otras condiciones
  (Girar, Intercambio, NO de día/mañana/atardecer, Naturaleza, belleza), y sin el punto doble de «Descon.» y «Hada mov.».

**13-nov-2026 (v0.8)**
- El estuche de MT de la Mochila sale en castellano: TIPO, POTENC., PRECIS. y PP, y los tipos (AGUA, VOLAD., ACERO…),
  redibujados con la letra del hack.

**13-nov-2026 (v0.79)**
- Unas 600 frases que en inglés son idénticas a las de HeartGold y SoulSilver usan ahora el texto oficial en castellano de esos juegos,
  con los nombres del hack (Mochila, Caramelo Raro, Repelente Máximo, Zona Safari, Cascabel Oleaje).
- Se mantiene la traducción propia donde la oficial perdía chistes, la forma de hablar de algún personaje o hablaba de «vosotros» a una sola persona.

**12-nov-2026 (v0.78)**
- Atenea, del Team Rocket, ya habla en castellano en el combate doble de la Torre Radio.
- Traducidos los últimos textos sueltos en inglés: el compañero de Magno en el Centro Espacial, un Entrenador que te pregunta si eres de Johto,
  dos nadadores de la Ruta 41, «Aliado» en combate y el aviso de emulador poco preciso.

**10-nov-2026 (v0.77)**
- Nombres unificados en todo el juego: «Torre Campana», «Cascabel Claro» y «Cascabel Oleaje» (como en la Mochila), «Campo Abrasado»,
  «Ases del Frente», «Monte Cimanieve» y «Pueblo Caoba» en el letrero de la Ruta 44.
- Las frases de los entrenadores del Frente Batalla (Charla Fácil) vuelven a tener sentido: antes eran una ensalada de palabras.
- Palabras que se partían con guion al saltar de línea en descripciones de objetos («paraliza-/dos», «Zigza-/Goon», «Smoo-/Chum»): ahora enteras.
- Las llamadas del guardián Baoba por el Pokégear (apertura y ampliaciones de la Zona Safari) ya salen en castellano.
- Máscaras (Fuente, Horno y Cimiento) y «Energía Potenciadora» con su nombre oficial en las descripciones, que seguían en inglés.
- Erratas corregidas («asestan golpes críticos», «estimulado», «resplandeciente», «aumentar», «eléctrico», «estos», «del Claro Oculto»).
- Más de 150 nombres de lugar en las listas, el mapa y el Pokénav con su mayúscula («Cueva Diglett», «Guarida Rocket», «Cámaras Sete», «Ciudad Portual»…) y «Dodrio a por bayas».

**9-nov-2026 (v0.76)**
- La descripción del Polvo Brillo ya cabe entera en la Mochila.
- Traducido el grito del Wooper del laboratorio del Prof. Elm.

**9-nov-2026 (v0.75)**
- Siglas cortas en las estadísticas de la Pokédex (Atq, Def, AtE, DfE, Vel): ya no tapan los números.
- Fondos de caja del PC traducidos (CORAZÓN, ALMA, DISTORSIÓN, GALAXIA…), «Pokécubo Dorado», «Llamar» en el teléfono y «Chat» en el Club Unión.
- Textos que aún salían en inglés: «¡Todo ordenado!», «Anónimo» y «Han rechazado tu oferta».
- Una descripción de la Pokédex que se salía de la caja, reajustada.

**3-nov-2026 (v0.74)**
- Nombres del clima en castellano en la Pokédex («Nv↑50, clima lluvia»).
- Salto Pokémon con los rótulos oficiales de Esmeralda («EXCELENTE +500», «MUY BIEN +200»…).
- Cartel del Santuario Dragón y una frase del mezclador de Pokécubos traducidos.
- Rótulos en minúsculas como en el hack («Polvo de bayas», «Bofetón Lodo», «Bajo el agua») y frase oficial «El 2.º equipo está preparado».

**29-oct-2026 (v0.73)**
- Casino traducido: rótulos de la Lotería, el Derby de Trigal, el Pachinko, Beautifly, el Blackjack, Giravoltorb y
  Block Builder, tienda de fichas y ventana de saldo («Fichas»).
- Descripciones de habilidad de la pestaña RASGOS acortadas para que no se corten, y aviso de innata bloqueada en
  castellano («Se desbloquea al nivel…»).
- Símbolo de número «N.º» como en los juegos oficiales (Pokédex, ficha, MT).
- «Los Claros Ocultos» y otros textos corregidos.

**27-oct-2026 (v0.72)**
- Unos 80 textos de Esmeralda con la frase oficial en castellano.
- Ficha de bayas: sabores en castellano y fila de dureza sin basura («DUR. / Blanda»).
- Mapa del Pase del Frente, carteles «PULSA A», «META» y «PELIGRO» en castellano.
- Decoraciones (muñecos) con sus nombres oficiales, y arreglados los datos de las decoraciones, los intercambios con
  entrenadores y un minijuego, que leían de un sitio equivocado.
- Arreglada la basura detrás de algunos efectos del combate, de condiciones de evolución de la Pokédex y de
  «¿Cuántos…?».

**27-oct-2026 (v0.71)**
- Arreglado el nombre por defecto «Amigo», que podía romper el juego al ser demasiado largo.
- Nombres oficiales: Treto (Scott) y Maya (Dawn).

**26-oct-2026 (v0.7)**
- Actualizada a la versión 1.2.1 de SoulGold: textos nuevos traducidos (efectos activos del combate, búsqueda en
  las Cajas, innatas nuevas, llamadas de Elm…).
- Arreglado el cuelgue al poner mote a un Pokémon recién capturado.
- Botones del teclado de nombres en castellano («otros», «BORRA / BOTÓN B», «FIN / START», «MAYÚS», «minús»).
- Menús de Esmeralda que seguían en inglés: PC, Pokénav, marcas de los Pokémon, Pase del Frente, tragaperras,
  concursos, Ficha de Kanto, chat de la Sala Unión y otros.
- Derby: los motes de los corredores se traducen y ya no salen con basura.
- Entrada de la Pokédex de Meganium, rival en Ciudad Olivo, Pirámide y Sierpe Batalla, Tactio y otros textos
  que seguían en inglés.
- Menú tras una captura («Unir al equipo») y ayuda de «Salir» en Ajustes, que se salían del cuadro.
- Nombres de zona demasiado largos para el mapa acortados (p. ej. «Lab. Abandonado»).
- Radio del Pokégear traducida entera (antes había frases en inglés o cortadas), blackjack, gritos de Pokémon y otros textos que seguían en inglés.
- Signos «¡ !» en la radio (contraseña de Buena) y en los gritos de los Pokémon («¡Rat!», «¡Zig!»).
- Iconos de estado en castellano en combate, en el equipo y en la ficha (ENV, PAR, DOR, CON, QUE, DEB).
- Mochila: icono «MO» en las máquinas ocultas.
- Pokédex: «PS» en los datos y el número de la MT ya no se sale del cuadro.
- Combate: «…se han registrado en la Pokédex», «Velocidad de X bajó mucho», «Ataque y At. Esp.», y frases
  largas como «quiere aprender el movimiento…» que se cortaban.
- Pokédex: grupos huevo, condiciones de evolución y buscador (SELECT) en castellano.
- DexNav y radio («SINTONÍA») traducidos.
- Trofeos: arreglada la basura que salía junto a los trofeos conseguidos.
- Pokédex: categorías en orden castellano («Pokémon Semilla»).
- Ficha: información de habilidad sin basura y con las descripciones enteras; «EV»/«IV»; recordador de movimientos.
- Combate: el cartel de habilidad ya no pone «Pidgeotto’s».

**24-oct-2026 (v0.6.1)**
- Combate: «PS» en las barras de vida y botón «INFO MOV.» (antes «HP» y «MOVE INFO»).
- Nombres oficiales: «Nao Abandonada», «Malvalanova» y «Vía Subterránea».

**24-oct-2026 (v0.6)**
- Arreglado el bloqueo con sonidos raros al recibir un objeto en algunas casas (la de la Miltank tras Ciudad
  Cerezo y otras): el juego mostraba «Obtuvo ????????» sin parar.
- Arreglados los fallos gráficos del Pokégear.
- Datos del Pokémon en castellano: rótulos (PERFIL, HABILIDAD, NOTAS DEL EO, OBJETO, AMISTAD, DATOS, RASGOS,
  INNATA, MOVIM., DESCRIPCIÓN), «Naturaleza Afable. Visto con Nv 5, en…», «Rasgos», «Ver IV/EV» y «Mote».
- Iconos de tipo en castellano (PLA, NOR, LUC, VOL, FUE, AGU…) y de estado (ENV, DOR, CON, QUE, DEB).
- «Nv» en lugar de «Lv» en todo el juego, «PS» en combate y «Objeto» en el equipo.
- Información del movimiento en combate (CAT., POT., PRE.), «¡Nuevo trofeo!» y pantalla de trofeos.
- Ficha de Entrenador: «Nombre:» y «N.º ID».
- «Cristal» en lugar de «Crystal», también en los entrenadores del modo Difícil, que seguían en inglés.
- Frase de Cristal al salir del laboratorio y cartel «Laboratorio del Prof. Elm».
- La «p» y la «q» de las descripciones de habilidad ya no se salen del cuadro.

**24-oct-2026 (v0.5)**
- Cabecera del teclado de motes corregida: ahora pone «¿Mote de Sprigatito?».

**23-oct-2026 (v0.4)**
- Pantalla de inicio traducida: aviso del arranque y «PULSA START».
- Ficha de Entrenador y medallas redibujadas en castellano, y «Mapa» en el Pokégear.
- Traducidos los textos que seguían en inglés: unos 110 diálogos de scripts (Plata en el laboratorio de Elm…),
  descripciones de movimientos, entradas de la Pokédex, habilidades, mensajes del Pokémon compañero y de combate.
- Palabras del Easy Chat con la lista oficial de Pokémon Esmeralda.
- Pantalla de opciones: valores alineados en todas las filas, «Compañero» en lugar de «Seguidores» y ayudas que ya
  no se salen de la ventana.
- Los dos puntos («:») quedan a la altura correcta en todas las fuentes.
- Siglas (GBA, S.S. Anne, K.O.), mayúsculas y frases que no cabían en su cuadro.

**23-oct-2026 (v0.3)**
- El parche se aplica directamente sobre Pokémon Esmeralda (USA), sin el parche de SoulGold en inglés.

**22-oct-2026 (v0.2)**
- Traducidos diálogos que seguían en inglés (Eusine, Lance, Plata, Giovanni, Pokégear, aviso de medallas…),
  llamadas del Pokégear, menús de listas y la pantalla Guía (códigos QR).
- Plurales correctos de todos los objetos y clase «Entrenadora» para las entrenadoras.
- Nombres oficiales más recientes de movimientos en tablas y diálogos (sin restos de Gen 3) y nombres de
  entrenador de Oro HeartGold y Plata SoulSilver.
- Descripciones de objetos y habilidades que se salían del cuadro, mayúsculas, signos ¡¿ y tildes actuales
  («solo», «ese»).

**22-oct-2026 (v0.1)**
- Primera versión de prueba.

## Créditos

- Traducción al castellano y herramientas: SeCaVa.
- *Pokémon SoulGold*: su autor y colaboradores (ver los créditos del propio juego).
- Textos oficiales de referencia: Pokémon Edición Oro HeartGold / Plata SoulSilver y Pokémon Edición Esmeralda.
- Pokémon es una marca de Nintendo, Creatures Inc. y GAME FREAK inc. Proyecto sin ánimo de lucro, no afiliado.

## Apoya el proyecto

Si te gusta esta traducción, puedes apoyarme en:

- Ko-fi: https://ko-fi.com/secava
- Patreon: https://www.patreon.com/secava
- GitHub Sponsors: https://github.com/sponsors/SeCaVa
