# Pokémon SoulGold — Castellano

Traducción no oficial al **castellano de España** de *Pokémon SoulGold*, el hack de GBA que rehace Johto y Kanto
al estilo de Oro HeartGold y Plata SoulSilver sobre Pokémon Esmeralda.

> Este repositorio **no contiene ninguna ROM**. Solo el parche en formato BPS: necesitas tu propia copia de
> Pokémon Esmeralda (USA) y el parche original de SoulGold v1.2.

## Estado

Versión de prueba (**v0.1**), en desarrollo. Revisado en emulador: intro, elección de personaje, teclado de
nombres, menú, Mochila, Opciones, guardar y textos de combate.

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

2. Aplícale el parche original **SoulGold v1.2** (`pokemon-soulgold-v1.2.bps`). El resultado es la ROM en inglés:

   | Dato | Valor |
   |---|---|
   | Tamaño | 32 MB |
   | CRC32 | `6ABC86CF` |
   | SHA-1 | `5d6a036260fdbde96f85b5c1b92d0256d3aebafb` |

3. Aplica sobre esa ROM `Pokemon-SoulGold-Castellano.bps` con [Floating IPS](https://github.com/Alcaro/Flips),
   [RomPatcher.js](https://www.marcrobledo.com/RomPatcher.js/) o cualquier otra herramienta compatible con BPS.
4. El resultado es la ROM en castellano:

   | Dato | Valor |
   |---|---|
   | CRC32 | `0EBE7A95` |
   | SHA-1 | `904de82c23e45256fd6a75e5113d3854fb5409a1` |

Empieza partida nueva. No cargues estados guardados de la versión en inglés.

## Cambios

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
