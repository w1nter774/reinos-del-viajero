# Reinos del Viajero — Modpack Forge 1.20.1

Mundo de fantasía donde eres el **Viajero Interdimensional**: despiertas en una gran capital, eliges raza, subes de nivel en mazmorras, vendes tu botín al Gremio y saltas entre mundos llenos de castillos, ruinas futuristas, NPC y monstruos.

- Minecraft **1.20.1** · Forge **47.4.29** · 109 archivos (mods, dependencias, Fresh Animations y shaders)
- **Descarga directa del modpack:** https://github.com/w1nter774/reinos-del-viajero/releases/latest/download/Reinos-del-Viajero-1.6.0.mrpack
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

## Gremio de Aventureros: encargos y rangos (1.6.0)

En cada **aldea** (junto a la campana), **castillo** y **taberna** aparece un **Tablón del Gremio** la primera vez que llegas (también en mundos ya creados). Las tabernas, castillos y capitales traen además al Maestro del Gremio. Haz clic derecho en el tablón:

- **Seis encargos al día**: dos de tu rango inferior, tres de tu rango y uno del siguiente. Cambian cada día de juego y cada tablón tiene los suyos.
- **Tipos**:
  - *Caza*: derrota N mobs de cualquier mod (Alex's Mobs, Ice and Fire, Cataclysm, Mowzie's, Legendary Monsters, Threateningly Mobs, Alex's Caves…).
  - *La cabeza de…*: un jefe.
  - *Encargo*: entrega objetos.
  - *Expedición*: encuentra una estructura de los mods o un bioma especial de Terralith o Alex's Caves.
  - *Limpieza*: derrota monstruos dentro de un bioma.
- Llevas **hasta 3 encargos** a la vez; el progreso se cuenta solo y se **entrega en cualquier tablón**. Pasa el ratón sobre un encargo para ver la pista de dónde buscar.
- **Rangos de F a S** según tu reputación: E 100 · D 300 · C 700 · B 1500 · A 3000 · S 6000. Puedes aceptar encargos de hasta un rango por encima del tuyo.
- **Recompensas**: esmeraldas, experiencia y reputación. Los jefes dan además manzanas doradas, diamantes, manzanas encantadas o lingotes de netherita según el rango.
- Fabricar un tablón: papel · esmeralda · papel / 3 tablones / palo · vacío · palo.

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
| **Inmortal de la Espada** (cultivo inmortal) | **Loto de las Diez Mil Espadas** (45 s): siete anillos de espadas de luz se abren a tu alrededor como un loto, suben al cielo y caen sobre todos los enemigos en 24 bloques con un pilar de luz (35 de daño) | Vuelo libre, +20 vida, +6 daño, +1 velocidad de ataque, +25% velocidad, +200 maná, +50% poder de hechizos, −25% recarga, sin daño por caída |
| **Heraldo de las Estrellas** | **Juicio de las Siete Estrellas** (90 s): tu cámara sube al espacio, una interfaz de enlace fija una a una las siete estrellas de la Osa Mayor y vuelves en picado: caen sobre el terreno una tras otra, cada una con su título ("IMPACTO 4 · MEGREZ"), 30 de daño en 7 bloques; al final las siete líneas de la constelación arden en el suelo (15 de daño) y la constelación queda grabada en el cielo | Vuelo libre, +16 vida, +4 daño, +20% velocidad, +250 maná, +60% poder de hechizos, −25% recarga, visión nocturna, sin daño por caída |
| **Liche Supremo** | **Caída de la Luna** (120 s): tres círculos mágicos se apilan en el cielo y una luna de 36 bloques, con cráteres y grietas al rojo, cae atravesándolos sobre el punto que miras: 45 de daño y fuego en 24 bloques | Vuelo libre, +12 vida, +6 armadura, +400 maná, +80% poder de hechizos, −35% recarga, +60% regeneración de maná, inmune al marchitamiento, respira bajo el agua, visión nocturna, sin daño por caída |
| **Slime Reencarnado** (1.6.0, réplica de Tensura) | **Depredador** (30 s): tu cuerpo se abre como una boca gigante, arrastra a los enemigos en 12 bloques y los devora (30 de daño; los débiles que no son jefes desaparecen). Te curas con lo devorado y ganas Fuerza II y Resistencia 30 s; el «Gran Sabio» te dice cuántas presas asimilaste. A los que escapan les caen los pilares de luz de **Megido** | Alas de demonio (vuelo libre), +12 vida, +4 armadura, +2 daño, +15% velocidad, inmune al veneno, al hambre y al marchitamiento, visión nocturna, sin daño por caída |

**Poderes del Viajero** (teclas en *Opciones → Controles → Origins*):

- **Salto entre mundos** (poder primario, 30 s de recarga): abre una grieta al siguiente mundo del ciclo **Superficie → Aether → Everbright → Everdawn → Undergarden → Otherside → Nether → Superficie**, con partículas de portal y sonido, y te deja en suelo seguro. **Agachado** te devuelve a la Superficie.
- **Paso del vacío** (poder secundario, 1,5 s): lanzas un fragmento de vacío y te teletransportas donde cae.
- **Pasos etéreos**: sin daño por caída.
- **Afinidad arcana**: +100 maná, +30% magia del vacío y −10% de recarga de hechizos.

Kit inicial: libro de hechizos de cobre, cuaderno de Ars Nouveau, brújulas de estructuras y biomas, pergamino de retorno, pan y el Atlas.

## Tu báculo: Arcanum del Viajero (mod propio)

**Arcanum del Viajero** es un mod hecho para este pack. Empiezas con el **Báculo del Viajero** en el kit, y también se fabrica con 2 palos, 2 fragmentos de amatista y 1 ojo de ender en diagonal.

- **Clic derecho**: lanza el hechizo elegido. **Agachado + clic derecho**: cambia de hechizo.
- Cada hechizo tiene una animación propia del cuerpo (playerAnimator), una coreografía de partículas y **efectos 3D sólidos** dibujados por el mod: zarcillos lisos que se ramifican y se mecen con cel-shading y contorno de tinta, domos de explosión de luz, ondas expansivas, rayos con hélices, relámpagos y auras; además temblor de cámara, destellos de impacto, golpe de zoom y líneas de velocidad, estilo anime. Además, cada habilidad dibuja un **círculo mágico de luz neón**, las sagradas hacen caer **pilares de luz** con **estallidos de rayos solares**, y aparece un **cartel de título** con su nombre y su lema. Los ven todos los jugadores cercanos.

| Hechizo | Animación | Efecto | Recarga |
|---|---|---|---|
| Lluvia de Meteoros | Alzas los brazos al cielo y los bajas de golpe | Círculo rúnico con pentagrama giratorio donde miras; caen 6 meteoros con estela de fuego que explotan (8 de daño, queman y empujan, sin romper bloques) | 6 s |
| Nova de Escarcha | Cruzas los brazos y los abres de golpe | 3 anillos de hielo que se expanden con picos de escarcha: 4 de daño por onda, ralentiza y congela | 3 s |
| Lanza del Vacío | Brazo atrás de la cabeza y lanzamiento con giro de torso | Rayo con doble hélice violeta de hasta 32 bloques: 10 de daño y empuje a todo lo que atraviesa, con onda sónica al impactar | 2 s |
| Grieta Dimensional | Brazos extendidos, temblando para sostenerla | Portal ovalado con espiral interior que absorbe a los enemigos 3 s y luego implosiona (10 de daño) | 8 s |
| Juicio Divino | Alzas los brazos al cielo y los bajas de golpe | Círculo dorado; caen rayos sagrados uno a uno sobre hasta 8 enemigos en 16 bloques (14 de daño, sin incendios) y te curas 3 corazones | 5 s |
| Diez Mil Espadas (萬劍天降) | Alzas los brazos al cielo | Se abre un portal en el cielo donde miras y llueven ~300 espadas de luz que se clavan en el suelo (3 de daño por golpe, ~33 en total, y ralentiza) | 7 s |
| Corte que Parte el Cielo (一劍斷天) | Brazo atrás y tajo con giro de torso | Una espada de 70 bloques se alza sobre las nubes y cae de un tajo: una grieta de luz de 80 bloques parte el terreno hacia donde miras, con un pilar de luz al final (40 de daño en la línea, sin romper bloques) | 10 s |
| Formación de Mil Hojas (千刃劍陣) | Brazos extendidos sosteniendo la formación | Una cúpula de luz de 30 bloques con 64 espadas en sus nodos atrapa a los enemigos (los ralentiza y marca) y luego todas se lanzan contra ellos (3 golpes de 9) | 12 s |
| Abanico de las Mil Espadas (千劍開屏) | Brazos extendidos sosteniendo el abanico | Tres anillos con 63 espadas se abren a tu espalda como la cola de un pavo real y disparan en ráfaga contra lo que miras: las espadas vuelan con estela de luz y se quedan clavadas en el blanco (unos 40 golpes de 0,9, ~32 de daño, y ralentiza) | 9 s |
| Reloj del Fin | Alzas los brazos al cielo y los bajas de golpe | Un reloj colosal con números romanos, runas, engranajes y tres agujas se alza delante de ti y otro de 44 bloques se dibuja en el suelo: **el tiempo se detiene 5 s** para todos los enemigos en 26 bloques (no se mueven ni atacan) y la pantalla pierde el color; todo el daño que les hagas se acumula y, cuando el reloj estalla, lo reciben de golpe ×1,5 (+12) | 30 s |
| Horizonte de Sucesos | Brazos extendidos, temblando para sostenerlo | Un agujero negro con anillo de fotones y un disco de acreción naranja que gira atrae durante 5 s todo lo que hay en 18 bloques (daño continuo); la luz del fondo se dobla a su alrededor como una lente, y colapsa con un destello (25 de daño) | 15 s |
| Campana de Oro (金鐘罩體) | Brazos extendidos sosteniendo la campana | Una campana dorada gigante con bandas de runas crece desde el suelo a tu alrededor: durante 9 s **nada de fuera puede tocar a quien está dentro** (tú, otros jugadores, aldeanos y mascotas). Las flechas y bolas de fuego rebotan con una onda dorada y un tañido, y los enemigos que la tocan salen despedidos. Al final se hace añicos | 20 s |
| Espada del Firmamento (天劍出鞘) | Alzas los brazos al cielo | Un sello con doce cuchillas se abre 44 bloques sobre el punto que miras; una espada colosal sale de él entre relámpagos y cae: se clava con una cúpula de choque, una columna de luz y grietas azules en el suelo (40 de daño en 10 bloques). Queda clavada unos segundos soltando descargas (3 de daño) | 25 s |
| Fisión del Vacío | Alzas los brazos al cielo | Circuitos de luz violeta recorren el suelo en 30 bloques, dibujan un sello con un ojo y se alzan como una jaula (los enemigos quedan ralentizados). La pantalla se vuelve negra con el nombre del hechizo y todo estalla en una cúpula violeta con una columna de luz (55 de daño en el centro, 25 en el borde) | 60 s |
| Juicio Orbital (1.6.0) | Alzas los brazos al cielo | Una mira roja marca el suelo que miras y un rayo guía baja del cielo; a los 2 s cae el disparo desde la órbita: columna roja, cúpula y onda (48 de daño en 8 bloques, 18 hasta 15, quema). Después se abren cuatro anillos de púas de azufre (7 de daño cada uno) | 30 s |
| Corte del Juicio (次元斬, 1.6.0) | Lanzas | Siete tajos dimensionales violetas rasgan el aire alrededor del punto que miras (6 de daño cada uno y frenan a los enemigos) y al final el espacio se rompe como un cristal (20 de daño en 7 bloques) | 15 s |
| Golpe Serio (1.6.0) | Lanzas | Un solo puñetazo: una onda dorada recorre 60 bloques en línea recta y barre todo lo que toca (60 de daño y los lanza lejos). Si miras al cielo, las nubes se abren | 45 s |
| Supernova (1.6.0) | Alzas los brazos al cielo | Un núcleo negro con anillos magenta flota sobre el punto que miras, arrastra a los enemigos y levanta la tierra; a los 3 s estalla como una estrella moribunda (42 de daño en el centro, 20 en 18 bloques) | 45 s |

Las **artes de la espada** tienen un cartel de caligrafía gigante con anillos dorados, un subtítulo cinematográfico arriba de la pantalla y oscurecen los bordes de la pantalla mientras duran. La **magia suprema** (Reloj del Fin, Horizonte de Sucesos, Caída de la Luna y las Siete Estrellas) también tiene su subtítulo con cuenta atrás. Además, cada vez que alguien lanza un hechizo, **su nombre aparece flotando sobre su cabeza** con el brillo de su color, para que los demás jugadores sepan qué se les viene encima.

Los golpes más fuertes (la luna, la espada del firmamento, el colapso del agujero negro y la fisión) tienen un **cuadro de impacto** al estilo manga: durante un instante la pantalla se vuelve tinta en blanco y negro. Mientras el Reloj del Fin detiene el tiempo, el mundo pierde de verdad el color (la magia sigue brillando). La Caída de la Luna deja una **luna de bloques** con grietas de magma que se desmorona a los pocos segundos (no rompe ni coloca bloques de verdad). Si usas un paquete de shaders de Oculus, estos filtros de pantalla se desactivan solos.

Los hechizos no dañan a jugadores, aldeanos, guardias, reclutas, NPC ni mascotas. Para pruebas o mapas, un operador puede usar `/execute as <entidad> at @s run arcanum lanzar <meteoro|escarcha|lanza|grieta|juicio|espadas|corte|formacion|abanico|reloj|agujero|campana|firmamento|fision|loto|luna|estrellas>`.

## Más poderes de la colección (1.6.0, también en Arcanum)

Réplicas propias de mods de la colección de TikTok que no existen para Forge 1.20.1. Todos se integran con el resto del pack: los jefes de los encargos sueltan frutas, el Sistema cuenta los monstruos de cualquier mod y Lumen es un jefe más del Gremio.

**Frutas elementales** (estilo SPMovesets). Hay cinco frutas: Magma, Glacial, Cosmos, Divina y Sombra. Al comer una ganas su poder y pierdes el de la fruta anterior; solo se tiene una a la vez. Las técnicas van en las teclas **Z** y **X**.

| Fruta | Z | X |
|---|---|---|
| Magma (炎) | **Puño Volcánico** (6 s): un chorro de lava en línea recta (14 de daño y quema) | **Erupción** (15 s): onda de fuego y anillos de roca a tu alrededor (16 en 8 bloques) |
| Glacial (氷) | **Lanza de Hielo** (6 s): rayo helado que congela y frena (12) | **Era Glacial** (18 s): anillos de cristales de hielo (14 en 10 bloques, ralentiza y congela) |
| Cosmos (星) | **Lluvia de Estrellas** (8 s): seis meteoros caen donde miras | **Gravedad Cero** (18 s): los enemigos flotan y luego caen de golpe (12) |
| Divina (聖) | **Lanza Sagrada** (8 s): un pilar de luz donde miras (16; 24 a no muertos) | **Alas del Serafín** (30 s): caída lenta, regeneración, resistencia y salto; cura a tus aliados |
| Sombra (影) | **Zarcillos de Sombra** (8 s): atrapan a seis enemigos, los marchitan y los acercan (9) | **Dominio de las Sombras** (25 s): 5 s de oscuridad que hiere, ciega y frena en 12 bloques |

Se consiguen así: los **jefes** (los de los encargos del Gremio y el Dragón del End) sueltan una al azar el 25% de las veces, y aparecen en el 3% de los **cofres** de mazmorras, fortalezas, ciudades antiguas, bastiones, mansiones, templos, castillos y torres.

**Cultivo inmortal** (estilo Renegade Immortal). Se hace con el **Sutra del Inmortal** (receta: hilo, papel y una esmeralda):

- **Mantén clic derecho** para meditar: reúnes qi (más rápido de noche) y subes por las nueve capas de la **Condensación de Qi**. Después vienen **Fundación**, **Núcleo Dorado**, **Alma Naciente** y **Transformación del Alma**, con tres etapas cada uno, y al final la **Ascensión**.
- Cada reino nuevo exige sobrevivir a la **Tribulación Celestial**: el cielo se oscurece y caen de 4 a 12 rayos sobre ti. Si mueres, pierdes la mitad del qi.
- Cada paso da vida, daño, armadura y velocidad permanentes.
- **Agachado + clic derecho**: **Lanza de Tormenta** desde la Fundación (6 s).
- **Agachado + clic derecho mirando al cielo**: **Dominio del Trueno** desde el Núcleo Dorado (30 s): durante 8 s caen rayos sobre tres enemigos de cada vez.

**Ventana del Sistema** (estilo Solo Leveling). Pulsa **N** y verás una ventana azul con:

- Tu nivel, tu rango de cazador (E, D, C, B, A, S y Monarca), tu rango del Gremio, tu reino de cultivo y tu fruta.
- **Misión diaria** «Preparación para volverse fuerte»: derrota 10 monstruos, recorre 1000 bloques y usa poderes 3 veces (cuentan el báculo, la tecla J, las frutas, el cultivo, la varita y la Mano de Dios). La recompensa son 3 puntos y la recuperación total. Se renueva cada día del juego.
- Los monstruos de cualquier mod dan experiencia del Sistema, y los jefes cinco veces más. Cada nivel da 3 puntos.
- Reparte los puntos con los botones **+**:
  - Fuerza: daño.
  - Agilidad: velocidad de movimiento y de ataque.
  - Vitalidad: vida.
  - Inteligencia: −1% de recarga de frutas y técnicas por punto, hasta −40%.
  - Percepción: suerte y armadura.

**Varita de Trazos** (estilo Drawn Magic; receta: dos palos y un fragmento de amatista). Mantén clic derecho y dibuja moviendo la vista: la estela queda flotando delante de ti. Al soltar, la forma decide el hechizo:

- **Círculo**: Égida Arcana, una cúpula de escudo.
- **Línea**: Rayo Arcano.
- **Zigzag**: Tormenta Trazada, rayos sobre cinco enemigos.
- **Triángulo**: Sello de Fuego, que explota en llamas.

**Mano de Dios** (estilo Hand of God; receta: bloques de oro, estrella del Nether y tótem). Clic derecho abre una **rueda de ocho poderes divinos**. Eliges con el ratón o con las teclas 1 a 8:

- Rayo del Juicio.
- Meteoro.
- Terremoto.
- Diluvio, que desata una tormenta o despeja el cielo.
- Sol y Luna, que trae la noche o el amanecer.
- Bendición, que cura a tus aliados.
- Génesis, que hace brotar cultivos, hierba y flores.
- Ira Divina, ocho rayos.

Los rayos de la Mano no incendian aldeas.

**Amuletos de Norine** (cadenas, lingote de oro y una gema). Se llevan en la **ranura de collar de Curios** o en la otra mano, y dejan un aura de su color:

- **Fénix**: inmune al fuego. Una vez cada 10 minutos **te salva de la muerte** con una explosión de llamas.
- **Marea**: respiras bajo el agua, nadas como un delfín y tienes el poder del conducto.
- **Vendaval**: velocidad, saltos altos y ningún daño por caída.
- **Eclipse**: visión nocturna, fuerza de noche e invisibilidad al agacharte.

**Lumen, el Sol Caído** (jefe final estilo LUMORA). Usa un **Fragmento de Sol** de día y a cielo abierto: se fabrica con piedra luminosa y una estrella del Nether. Tras un ritual de luz, un sol desciende del cielo con su barra de jefe (600 de vida).

- **Fase 1**: pilares solares bajo cada jugador, llamaradas y lluvia de fuego. Flota a nueve bloques, pero cada 12 s baja unos segundos a ras de suelo: es el momento de golpearlo cuerpo a cuerpo (el resto del tiempo, con arco o hechizos).
- **Fase 2, al 50%**: empieza el **Eclipse**. El sol se vuelve negro con una corona violeta, el cielo se oscurece y ataca más rápido. Añade la **Supernova**, una onda con anillos de púas, y la **Corona Negra**, ocho rayos.
- **Botín**: el **Báculo del Santo**, una estrella del Nether, manzanas encantadas y quizá una fruta. El Báculo lanza el **Juicio Solar** (18 de daño, 27 a no muertos) y, agachado, la **Bendición Solar**, que cura al grupo.
- Lumen también es un **encargo de jefe de rango A y S** del Gremio.

Pruebas para operadores: `/arcanum fruta <magma|glacial|cosmos|divina|sombra>`, `/arcanum poder <1|2>`, `/arcanum sistema <abrir|xp N|puntos N|mision>`, `/arcanum cultivo <paso N|qi N|tribulacion|tecnica 0|1>`, `/arcanum mano <0-7>`, `/arcanum trazo <circulo|linea|zigzag|triangulo>` y `/summon arcanum_viajero:lumen`.

## Subir de nivel

**Pufferfish's Skills** añade árboles de habilidades. Ganas experiencia de habilidad matando monstruos, explorando mazmorras y minando, y la gastas en mejoras. Incluye los árboles por defecto (combate, minería…) y **4 árboles de magia para Iron's Spells**. Busca la tecla del menú de habilidades en *Controles*.

## Qué trae

- **Magia con animaciones**: Iron's Spells 'n Spellbooks (animaciones de lanzamiento, más de 100 hechizos), Ars Nouveau (crea tus propios hechizos), Player Animator, Not Enough Animations, Fresh Animations (EMF/ETF) y los shaders Complementary Reimagined (por defecto) y Bliss (alternativo, en Opciones > Video > Shaders).
- **Combate (1.6.0)**: **Epic Fight** sustituye a Better Combat: combate estilo souls con esquivas, fijar objetivo (pulsa R para alternar entre modo minería y modo combate) y habilidades de arma. Con Weapons of Miracles, las armas de Devil May Cry y Marium's Soulslike Weaponry (armas legendarias y jefes souls).
- **Novedades de la colección de TikTok (1.6.0)**:
  - *Clima y biomas*: tormentas, viento y tornados (Weather, Storms & Tornadoes; los tornados arrancan vegetación pero no tus casas) y los biomas de Terralith.
  - *Criaturas y jefes*: dragones de Ice and Fire, Threateningly Mobs, Legendary Monsters, True Ending (nuevo Dragón del End) y Champions (monstruos élite con poderes).
  - *Rarezas*: el simbionte (Symbiote), implantes ciberpunk con ripperdoc (Project: Edgerunner), volver al punto guardado como en Re:Zero (MineZero) y aldeanos que curan a los gólems.
- **Capitales y estructuras medievales**: Luki's Grand Capitals, Towns and Towers, aldeas renovadas (CTOV), Dungeons and Taverns (tabernas, criptas y fortines), Medieval Buildings, Moog's Voyager Structures, When Dungeons Arise, todos los YUNG's, Integrated Dungeons and Structures y L_Ender's Cataclysm (jefes).
- **Futurista**: Ad Astra (cohetes, planetas y estaciones), Alex's Caves (búnkeres, robots, cuevas tóxicas y magnéticas) y Create (máquinas).
- **Otros mundos**: Aether, Blue Skies, Undergarden, Deeper and Darker y los planetas de Ad Astra.
- **Monstruos fuera de las ciudades y en los bosques**: Alex's Mobs, Mutant Monsters, Illager Invasion, Mowzie's Mobs, Friends & Foes y Cataclysm, además de los vanilla. Los **Guard Villagers** defienden las aldeas y capitales.
- **NPC**: MCA Reborn (aldeanos con diálogo, relaciones y familia), Villager Recruits (contrata soldados), Easy NPC (crea NPC con diálogos propios) y el Maestro del Gremio. Los enemigos son illagers, saqueadores, tribus y jefes de las estructuras.
- **Utilidad**: JEI, Jade, minimapa y mapa de Xaero, Waystones, Explorer's/Nature's Compass y KubeJS.

## Estado de las pruebas

**1.6.0** (cliente real con capturas):

- ✅ Arranca con los 21 mods nuevos y Epic Fight en lugar de Better Combat, sin crashes.
- ✅ Un mundo nuevo con Terralith se crea y se vuelve a abrir (antes fallaba con «Failed to read level data» por Citadel).
- ✅ El Tablón del Gremio aparece solo en la capital y la pantalla funciona: aceptar 3 encargos, ver el progreso, entregar con recompensa y ascender de rango con su cartel.
- ✅ Project Edgerunner y Villager Recruits ya no llenan el registro de errores (de más de 8000 líneas de error a ninguna de esos mods).
- ✅ Al entrar a un mundo ya no salen la configuración inicial de Edgerunner (cara ciber y nivel de sangre) ni el anuncio de Terralith.
- ✅ Los cuatro hechizos nuevos (Juicio Orbital, Corte del Juicio, Golpe Serio y Supernova) funcionan, con su cartel y su cuadro de tinta, a 96–104 FPS.
- ✅ Frutas elementales: las cinco frutas y sus diez técnicas, lanzadas con los paquetes de las teclas Z y X, con su cartel, sus efectos 3D y su daño.
- ✅ Ventana del Sistema:
  - Se abre con la tecla N.
  - El botón + reparte los puntos.
  - La misión diaria se completa: 10 monstruos, 1000 bloques y 3 poderes.
  - Subir de nivel da 3 puntos por nivel.
- ✅ Cultivo: la Tribulación Celestial (4 rayos) lleva a la Fundación, y funcionan la Lanza de Tormenta y el Dominio del Trueno.
- ✅ Mano de Dios: la rueda se dibuja y al hacer clic en un sector se lanza su poder por la red. Se probaron los ocho poderes, incluidos el diluvio y la noche.
- ✅ Varita de Trazos: las cuatro formas lanzan su hechizo. El reconocedor acierta el 100% de círculos, líneas y triángulos y el 94% de zigzags en 400 trazos de prueba con temblor.
- ✅ Amuletos: con el Fénix en la otra mano tienes resistencia al fuego, y con la Marea en la ranura de collar de Curios respiras bajo el agua.
- ✅ Lumen: tiene barra de jefe y ataques de fase 1. Al 50% pasa al Eclipse (barra violeta, cielo oscuro y cartel) y al morir sale su cartel.
- ✅ Slime Reencarnado: con la raza puesta, la tecla J lanza el Depredador (arrastra, devora 3 presas y lanza Megido).
- ✅ Ninguna de estas réplicas deja errores en el registro.
- ✅ Se probó también con entrada real, con el clic derecho mantenido y la cámara moviéndose:
  - La Varita de Trazos reconoce el círculo, la línea, el zigzag y el triángulo.
  - Meditar con el Sutra sube de capa.
  - Comer una fruta da su poder.
  - El Fragmento de Sol invoca a Lumen con su ritual.
  - El Báculo del Santo lanza el Juicio Solar.
  - La rueda de la Mano de Dios se abre desde el objeto.
- ⚠️ Réplicas sin probar todavía:
  - Que el Fénix salve de la muerte, la caída sin daño del Vendaval y la invisibilidad del Eclipse al agacharse.
  - Las técnicas del Sutra con agachado + clic: solo se probaron con su comando.
  - Las frutas que sueltan los jefes y las de los cofres.
  - Todo ello en multijugador.
- ℹ️ Los dragones de Ice and Fire atacan aldeas (en una prueba quemaron a varios aldeanos de MCA). El pack limita sus destrozos a bloques débiles para que no arrasen las aldeas ni los castillos.
- ⚠️ Sin probar todavía: cazar de verdad cada tipo de mob de los encargos (el conteo es el mismo para todos), multijugador y los mods nuevos uno por uno a fondo.

**Versiones anteriores**, probado en un servidor Forge dedicado con todos los mods de servidor:

- ✅ El servidor arranca sin crashes con los 81 mods de servidor.
- ✅ Los 23 poderes de razas y del Viajero se cargan (un ID falso da error, así que la validación es real).
- ✅ En un mundo nuevo el spawn queda **dentro de una capital** (0 bloques según `locate`) y el atlas encuentra 5 capitales.
- ✅ El Maestro del Gremio aparece con sus 26 ofertas y no desaparece.
- ✅ El salto entre mundos llega a Aether, Everbright, Everdawn, Undergarden y Nether con suelo seguro.
- ✅ Arcanum del Viajero carga en el servidor dedicado y sus 4 hechizos hacen el daño esperado contra husks de prueba (Lanza −10 al de la línea, Escarcha −12 a todos, Meteoros y Grieta matan a los 3).
- ✅ (1.5.0) Probado en un cliente real con un ensayo automático que lanza cada hechizo con `/arcanum lanzar` y saca capturas: Reloj del Fin, Horizonte de Sucesos, Caída de la Luna, Campana de Oro, Espada del Firmamento, Fisión del Vacío, Abanico y la cámara de las Siete Estrellas se ven completos, sin errores en el log y a 70–118 FPS (1280×720).
- ⚠️ Las razas Heraldo de las Estrellas y Liche Supremo no se han probado eligiéndolas en el juego (sus habilidades sí, con el comando), y los hechizos nuevos no se han probado en multijugador.
- ⚠️ Las animaciones del cuerpo del báculo están escritas a mano: puede que algún ángulo de brazo necesite ajuste.
- ⚠️ El salto al Otherside y la vuelta a la Superficie no se pudieron confirmar en la prueba sin jugador.
- ⚠️ Sin probar con cliente: animaciones, shaders, Fresh Animations, mensajes de bienvenida y kit (necesitan un jugador conectado).
- ℹ️ Errores inofensivos en el log: etiquetas de IDAS/CTOV que apuntan a mods opcionales que no están (BYG, Biomes O' Plenty) y dos errores que solo salen al apagar el servidor (MCA/Integrated API y Villager Recruits).
