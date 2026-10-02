# Simple Rockets (Vanilla+)

<img src="media/thumbnail.png" width="256" alt="Simple Rockets (Vanilla+)">

**[Descárgalo en el portal de mods de Factorio](https://mods.factorio.com/mod/simple-rockets)** · [English](README.md)

Cohetes pequeños, potentes y de sólo ida que llevan tus pedidos logísticos **directamente de un
planeta a otro**, sin plataforma espacial. Construye un silo en el planeta que tiene los objetos y
una plataforma de aterrizaje en el que los necesita: la plataforma pide, el silo lo reúne de su red
logística, despega, y el cohete aterriza en la plataforma unos minutos después.

No sustituyen a las plataformas espaciales: son una forma rápida y directa de mandar cargas
urgentes (hasta 1 tonelada por cohete) entre planetas.

Necesita **Space Age**. Gráficos renderizados con el aspecto del juego y sonidos vanilla.

---

## Silo de cohetes simples (6×6)

- Monta un cohete con **5 partes de cohete simple** (cada una: 1 escudo térmico, 1 ordenador de
  guía, 1 fuselaje criogénico y 1 combustible criogénico).
- **Destino:** *Automático* (por defecto) o una plataforma. En automático las plataformas se
  atienden por orden de espera; a cada una le toca el silo cuya red logística ya tiene lo que le
  falta, luego el más cercano, luego el que lleva más tiempo sin lanzar.
- El silo pide a su red logística lo que le falta a la plataforma (como el silo vanilla para las
  plataformas espaciales) y despega cuando el cohete está lleno o lo lleva todo.
- **Nunca despega sin ruta**: si no tiene adónde ir, el cohete espera en el pozo.
- **Receta:** 500 hormigón reforzado, 100 placas de tungsteno, 100 unidades de procesamiento,
  50 superconductores, 50 estructuras de baja densidad, 5 procesadores cuánticos.

## Plataforma de aterrizaje (6×6)

- Su propio panel bajo su ventana: sus **peticiones para los cohetes** (objeto, calidad y
  cantidad) son lo que envían los silos.
- En una red logística funciona como un **cofre proveedor pasivo**: los robots pueden sacar lo que
  tiene, pero nunca traerle nada.
- **Nombre** editable, que sale en la lista de destinos del silo.
- **"Recibir solo lo que pide"**: la plataforma sólo recibe lo que pide.
- El cohete baja frenando con el chorro, abre las patas y se posa. El **brazo umbilical** de la
  torre de servicio se engancha y lo descarga en la plataforma; luego el **elevador** lo baja por el
  pozo, donde se desmonta en **chatarra de cohete**, y vuelve a subir vacío.
- Si llegan varios cohetes a la vez, aterrizan uno tras otro.
- **Receta:** 500 hormigón reforzado, 100 placas de tungsteno, 50 unidades de procesamiento,
  20 superconductores, 5 procesadores cuánticos.

## Vuelos

- Velocidad fija: **450 km/s**, **+15 km/s por nivel** de la investigación infinita *Velocidad de
  cohetes simples*. Nauvis → Aquilo tarda alrededor de 1:40.
- Los cohetes en vuelo salen en las ventanas del silo y de la plataforma de aterrizaje, con su destino y el tiempo que les falta.

## Materiales del cohete

Cada uno se fabrica en su planeta, en la máquina de ese planeta:

| Material | Dónde | Ingredientes |
|---|---|---|
| Escudo térmico de tungsteno | Vulcanus, fundición | carburo de tungsteno, placa de tungsteno, cobre fundido |
| Ordenador de guía | Fulgora, planta electromagnética | supercondensador, superconductor, unidad de procesamiento |
| Fuselaje criogénico | Aquilo, planta criogénica | placa de litio, fibra de carbono, fluorocetona fría |
| Combustible criogénico | Aquilo, planta criogénica | combustible de cohete, amoníaco, fluorocetona fría |

La **chatarra de cohete** va a la recicladora y devuelve los **materiales** del cohete: **de 1 a 3 de cada uno** (escudo térmico, ordenador de guiado, fuselaje y combustible).

## Calidad

- **Silo:** cohetes más rápidos, +30 % de velocidad de vuelo por nivel de calidad (legendario: ×2,5, además de la investigación) y, como cualquier máquina, fabrica las partes del cohete más rápido.
- **Plataforma de aterrizaje:** una segunda chatarra de cohete al 20 % por nivel de calidad (legendaria: siempre 2), así que vuelven más materiales; y, como cualquier cofre, más casillas (legendaria: 200).

## Investigación

- **Cohetes simples:** tras el paquete de ciencia criogénica (y las tecnologías de los ingredientes).
- **Velocidad de cohetes simples:** infinita, +15 km/s por nivel.

---

Gráficos en resolución estándar (32 px por casilla). Comentarios y fallos, en la pestaña de
discusión.

---

☕ **Apoya mi trabajo**

Hacer mods es un hobby que hago en mi tiempo libre, por puro gusto, y mis mods son y serán
siempre gratuitos. Si te gustan y te apetece, puedes invitarme a un café:
[buymeacoffee.com/wolfenstain](https://buymeacoffee.com/wolfenstain)

Sin ningún compromiso: que los juegues y me dejes tus comentarios ya significa mucho. ¡Gracias!
