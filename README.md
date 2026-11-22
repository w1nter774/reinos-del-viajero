# Reinos del Viajero — Modpack Forge 1.20.1

Mundo de fantasía donde eres el **Viajero Interdimensional**: despiertas en una gran capital, eliges raza, subes de nivel en mazmorras, vendes tu botín al Gremio y saltas entre mundos llenos de castillos, ruinas futuristas, NPC y monstruos.

- Minecraft **1.20.1** · Forge **47.4.29** · 89 archivos (mods, dependencias, Fresh Animations y shader)
- **Descarga directa del modpack:** https://github.com/w1nter774/reinos-del-viajero/releases/latest/download/Reinos-del-Viajero-1.1.0.mrpack
- **Launcher:** https://prismlauncher.org/download/windows/

## Cómo instalarlo

El `.mrpack` no contiene los mods: tu launcher los descarga de Modrinth (con hashes verificados) al importarlo.

1. Instala **Prism Launcher** (https://prismlauncher.org) o la **Modrinth App** (https://modrinth.com/app).
2. Prism: *Añadir instancia → Importar* → elige el `.mrpack`. Modrinth App: arrastra el archivo a la ventana.
3. Asigna **8 GB de RAM** (Prism: *Editar instancia → Ajustes → Memoria*). Con menos de 6 GB irá mal.
4. Usa Java 17 o 21. Si usas Java 21, en *Configuración → Java* de la instancia marca **"Omitir las comprobaciones de compatibilidad de Java"**.
5. Crea un mundo nuevo. La primera carga tarda un poco, porque se busca tu capital.

> El launcher de CurseForge no importa `.mrpack`; usa Prism o Modrinth App.

### Shaders y OptiFine

Los shaders ya vienen activados con **Oculus + Embeddium** y el shader **Complementary Reimagined**. Puedes cambiarlos o desactivarlos en *Opciones → Vídeo → Shader Packs* (tecla **O**).
**No instales OptiFine:** es incompatible con Embeddium y Oculus y rompe Fresh Animations y Create. Su licencia, además, no permite incluirlo en un modpack. Oculus carga los mismos shaders que OptiFine.

## Empiezas en una capital

Al crear el mundo, el pack busca la **capital más cercana** (las aldeas vanilla que Luki's Grand Capitals convierte en grandes ciudades medievales) y te hace aparecer en ella. También cartografía hasta **5 capitales** (Valdoria, Eldenmar, Kharzul, Aurelia y Drakmoor) en distintas direcciones.

- Recibes el libro **Atlas de los Reinos** con las coordenadas de cada capital. Ábrelo, pulsa **M** (mapa del mundo de Xaero) y crea un punto de ruta.
- Junto a ti aparece el **Maestro del Gremio**: un comerciante fijo e invulnerable.

## El Gremio: vende tu botín

El Maestro del Gremio paga **esmeraldas** por:

| Botín de monstruos | Minería |
|---|---|
| 24 carne podrida, 12 huesos, 12 hilos, 8 ojos de araña, 6 pólvora, 6 slime, 6 cuero, 2 membranas, 2 varas de blaze → 1 esmeralda | 16 carbón, 16 cobre, 6 hierro, 4 oro (en bruto), 16 redstone, 12 lapislázuli, 12 cuarzo, 8 amatista → 1 esmeralda |
| Perla de ender → 1 · Lágrima de ghast → 2 | Diamante → 3 · Escombros ancestrales → 8 |

Y vende: frascos de experiencia, manzanas doradas, comida, ojos de ender y tótems.
Un operador puede poner más gremios (por ejemplo en otras capitales) con `/reinos gremio`.

## Tu personaje

Al entrar eliges **raza** y después tu **destino** (tu clase de protagonista). Hay 5 destinos, todos muy poderosos:

| Destino | Poder primario | Poder secundario | Pasivas |
|---|---|---|---|
| **Viajero Interdimensional** | Salto entre mundos (15 s) | Paso del vacío (1,5 s) | +250 maná, +20% hechizos, +50% magia del vacío, −20% recarga, sin daño por caída |
| **Archimago del Caos** | Lluvia de Meteoros (12 s) | Grieta del Caos (16 s) | +300 maná, +60% poder de hechizos, −30% recarga, +50% regeneración de maná, escudo de absorción cada 10 s |
| **Señor de los Dragones** | Ráfaga de 6 bolas de fuego (3 s) | Impulso al cielo (5 s) | Vuela como con élitros, +10 vida, +6 armadura, +4 dureza, inmune al fuego, +50% magia de fuego |
| **Paladín Celestial** | Juicio Divino: rayos sobre 8 enemigos y te cura (10 s) | Escudo Sagrado: resistencia III, absorción IV y regeneración II (40 s) | +20 vida, +6 armadura, +4 daño, regeneración constante, +50% magia sagrada |
| **Asesino de las Sombras** | Manto de Sombras: invisible, velocidad II y fuerza III (30 s) | Paso sombrío (0,75 s) | +30% velocidad, +6 daño, +1 velocidad de ataque, visión nocturna, sin daño por caída |

> En un mundo creado **antes** de esta actualización ya tienes asignado el Viajero. Para elegir otro destino, activa los trucos y usa `/origin gui @s fantasia:destino`, o crea un mundo nuevo.

Detalle del Viajero Interdimensional:

| Raza | Ventajas | Desventaja |
|---|---|---|
| Humano | +50 maná, +1 suerte | — |
| Elfo | +12% velocidad, +20% magia de naturaleza y regeneración de maná, visión nocturna | −2 de vida |
| Enano | +4 vida, +2 armadura, resiste empuje, pica 25% más rápido, inmune al veneno | −8% velocidad |
| Orco | +2 daño, +2 vida, +20% magia de sangre | −30 maná |
| Dracónido | Inmune al fuego y la lava, +30% magia de fuego, +2 armadura | — (raza fuerte) |
| Celestial | Cae lento y sin daño, +25% magia sagrada | −2 de vida |

**Razas legendarias.** Tienen una **habilidad racial** en la tecla **J** (se cambia en *Opciones → Controles → Arcanum del Viajero*), con animación del cuerpo y efectos 3D:

| Raza | Habilidad racial (J) | Pasivas |
|---|---|---|
| **Deidad Primordial** (tipo dios) | **Apoteosis** (60 s): te elevas envuelto en un aura dorada y desatas zarcillos de oro, una onda gigante y rayos sobre todos los enemigos en 20 bloques (30 de daño) | Vuelo libre, +40 vida, +10 armadura, +6 dureza, +8 daño, +40% velocidad, inamovible, +500 maná, +100% poder de hechizos, −50% recarga, inmune a fuego y caídas, regeneración II y saciedad constantes |
| **Vampiro Ancestral** | **Festín de Sangre** (20 s): zarcillos de sangre en 3D se clavan en los enemigos a 12 bloques, los desangran y te curan | Cada golpe te cura 1 corazón, +8 vida, +5 daño, +20% velocidad, visión nocturna, +50% magia de sangre |
| **Titán** | **Pisotón Sísmico** (12 s): onda sísmica de roca que lanza por los aires a los enemigos (12 de daño) | +30 vida, +8 armadura, +4 dureza, +6 daño, inamovible, −10% velocidad |
| **Elemental de Tormenta** | **Ira de la Tormenta** (25 s): 3 s de relámpagos ramificados sobre los enemigos (10 de daño cada uno) | +40% velocidad, +2 velocidad de ataque, +50% magia de rayo, inmune a rayos y caídas |

**Poderes del Viajero** (teclas en *Opciones → Controles → Origins*):

- **Salto entre mundos** (poder primario, 30 s de recarga): abre una grieta al siguiente mundo del ciclo **Superficie → Aether → Everbright → Everdawn → Undergarden → Otherside → Nether → Superficie**, con partículas de portal y sonido, y te deja en suelo seguro. **Agachado** te devuelve a la Superficie.
- **Paso del vacío** (poder secundario, 1,5 s): lanzas un fragmento de vacío y te teletransportas donde cae.
- **Pasos etéreos**: sin daño por caída.
- **Afinidad arcana**: +100 maná, +30% magia del vacío y −10% de recarga de hechizos.

Kit inicial: libro de hechizos de cobre, cuaderno de Ars Nouveau, brújulas de estructuras y biomas, pergamino de retorno, pan y el Atlas.

## Tu báculo: Arcanum del Viajero (mod propio)

**Arcanum del Viajero** es un mod hecho para este pack. Empiezas con el **Báculo del Viajero** en el kit, y también se fabrica con 2 palos, 2 fragmentos de amatista y 1 ojo de ender en diagonal.

- **Clic derecho**: lanza el hechizo elegido. **Agachado + clic derecho**: cambia de hechizo.
- Cada hechizo tiene una animación propia del cuerpo (playerAnimator), una coreografía de partículas y **efectos 3D sólidos** dibujados por el mod: zarcillos lisos que se ramifican y se mecen con cel-shading y contorno de tinta, domos de explosión de luz, ondas expansivas, rayos con hélices, relámpagos y auras; además temblor de cámara, destellos de impacto, golpe de zoom y líneas de velocidad, estilo anime. Los ven todos los jugadores cercanos.

| Hechizo | Animación | Efecto | Recarga |
|---|---|---|---|
| Lluvia de Meteoros | Alzas los brazos al cielo y los bajas de golpe | Círculo rúnico con pentagrama giratorio donde miras; caen 6 meteoros con estela de fuego que explotan (8 de daño, queman y empujan, sin romper bloques) | 6 s |
| Nova de Escarcha | Cruzas los brazos y los abres de golpe | 3 anillos de hielo que se expanden con picos de escarcha: 4 de daño por onda, ralentiza y congela | 3 s |
| Lanza del Vacío | Brazo atrás de la cabeza y lanzamiento con giro de torso | Rayo con doble hélice violeta de hasta 32 bloques: 10 de daño y empuje a todo lo que atraviesa, con onda sónica al impactar | 2 s |
| Grieta Dimensional | Brazos extendidos, temblando para sostenerla | Portal ovalado con espiral interior que absorbe a los enemigos 3 s y luego implosiona (10 de daño) | 8 s |
| Juicio Divino | Alzas los brazos al cielo y los bajas de golpe | Círculo dorado; caen rayos sagrados uno a uno sobre hasta 8 enemigos en 16 bloques (14 de daño, sin incendios) y te curas 3 corazones | 5 s |

Los hechizos no dañan a jugadores, aldeanos, guardias, reclutas, NPC ni mascotas. Para pruebas o mapas, un operador puede usar `/execute as <entidad> at @s run arcanum lanzar <meteoro|escarcha|lanza|grieta>`.

## Subir de nivel

**Pufferfish's Skills** añade árboles de habilidades. Ganas experiencia de habilidad matando monstruos, explorando mazmorras y minando, y la gastas en mejoras. Incluye los árboles por defecto (combate, minería…) y **4 árboles de magia para Iron's Spells**. Busca la tecla del menú de habilidades en *Controles*.

## Qué trae

- **Magia con animaciones**: Iron's Spells 'n Spellbooks (animaciones de lanzamiento, más de 100 hechizos), Ars Nouveau (crea tus propios hechizos), Player Animator, Better Combat, Not Enough Animations, Fresh Animations (EMF/ETF) y el shader Complementary Reimagined.
- **Capitales y estructuras medievales**: Luki's Grand Capitals, Towns and Towers, aldeas renovadas (CTOV), Dungeons and Taverns (tabernas, criptas y fortines), Medieval Buildings, Moog's Voyager Structures, When Dungeons Arise, todos los YUNG's, Integrated Dungeons and Structures y L_Ender's Cataclysm (jefes).
- **Futurista**: Ad Astra (cohetes, planetas y estaciones), Alex's Caves (búnkeres, robots, cuevas tóxicas y magnéticas) y Create (máquinas).
- **Otros mundos**: Aether, Blue Skies, Undergarden, Deeper and Darker y los planetas de Ad Astra.
- **Monstruos fuera de las ciudades y en los bosques**: Alex's Mobs, Mutant Monsters, Illager Invasion, Mowzie's Mobs, Friends & Foes y Cataclysm, además de los vanilla. Los **Guard Villagers** defienden las aldeas y capitales.
- **NPC**: MCA Reborn (aldeanos con diálogo, relaciones y familia), Villager Recruits (contrata soldados), Easy NPC (crea NPC con diálogos propios) y el Maestro del Gremio. Los enemigos son illagers, saqueadores, tribus y jefes de las estructuras.
- **Utilidad**: JEI, Jade, minimapa y mapa de Xaero, Waystones, Explorer's/Nature's Compass y KubeJS.

## Estado de las pruebas

Probado en un servidor Forge dedicado con todos los mods de servidor:

- ✅ El servidor arranca sin crashes con los 81 mods de servidor.
- ✅ Los 23 poderes de razas y del Viajero se cargan (un ID falso da error, así que la validación es real).
- ✅ En un mundo nuevo el spawn queda **dentro de una capital** (0 bloques según `locate`) y el atlas encuentra 5 capitales.
- ✅ El Maestro del Gremio aparece con sus 26 ofertas y no desaparece.
- ✅ El salto entre mundos llega a Aether, Everbright, Everdawn, Undergarden y Nether con suelo seguro.
- ✅ Arcanum del Viajero carga en el servidor dedicado y sus 4 hechizos hacen el daño esperado contra husks de prueba (Lanza −10 al de la línea, Escarcha −12 a todos, Meteoros y Grieta matan a los 3).
- ⚠️ Las animaciones del cuerpo del báculo están escritas a mano y no se han visto en un cliente: puede que algún ángulo de brazo necesite ajuste.
- ⚠️ El salto al Otherside y la vuelta a la Superficie no se pudieron confirmar en la prueba sin jugador.
- ⚠️ Sin probar con cliente: animaciones, shaders, Fresh Animations, mensajes de bienvenida y kit (necesitan un jugador conectado).
- ℹ️ Errores inofensivos en el log: etiquetas de IDAS/CTOV que apuntan a mods opcionales que no están (BYG, Biomes O' Plenty) y dos errores que solo salen al apagar el servidor (MCA/Integrated API y Villager Recruits).
