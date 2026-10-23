# Pokémon SoulGold — Castellano

Traducción no oficial al **castellano de España** de *Pokémon SoulGold*, el hack de GBA que rehace Johto y Kanto
al estilo de Oro HeartGold y Plata SoulSilver sobre Pokémon Esmeralda.

> Este repositorio **no contiene ninguna ROM**. El parche BPS está en la página de la versión: necesitas tu propia
> copia de Pokémon Esmeralda (USA). No hace falta el parche original de SoulGold.

## Estado

Versión de prueba (**v0.5**), en desarrollo. Revisado en emulador: pantalla de inicio, intro, elección de
personaje, teclado de nombres, menú, Mochila, Opciones, Ficha de Entrenador, Guía, guardar y textos de combate.

Puede haber frases que no encajen bien con su contexto, textos cortados o algún resto en inglés. Si encuentras
alguno, abre un *issue* con una captura.

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

2. Descarga `Pokemon-SoulGold-Castellano.bps` de la [última versión](../../releases/latest) y aplícalo
   **directamente** sobre esa ROM con [Floating IPS](https://github.com/Alcaro/Flips),
   [RomPatcher.js](https://www.marcrobledo.com/RomPatcher.js/) o cualquier otra herramienta compatible con BPS.
   No apliques antes el parche de SoulGold en inglés.
3. El resultado es la ROM en castellano:

   | Dato | Valor |
   |---|---|
   | Tamaño | 32 MB |
   | CRC32 | `DD7410C8` |
   | SHA-1 | `ef64ff6cfa33cd377c211cdc07cd97ab3e9aada7` |

Empieza partida nueva. No cargues estados guardados de la versión en inglés.

## Cambios

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
