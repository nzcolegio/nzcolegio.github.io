---
title: Guia I
published: true
---
# Redes de computadoras intruduccion.

Las redes surgen de la necesidad de compartir archivos entre computadores, esto para agilizar procesos
o tareas, en un principio los computadores solo eran diseñados para realizar calculos matematicos asi que uno
solo podia hacer la tarea sin necesidad de compartir archivos con los demas, eso hasta que llegaron los PCs.

## Aparicion de los PC.
- En 1981, IBM introduce el concepto de PC y el entorno de los ordenadores cambia radicalmente
- El PC da al usuario mucha más flexibilidad
- El software de emulación permite conectar los PC al mainframe, manteniendo así la compatibilidad con los sistemas existentes.
- Al mismo tiempo que los PC, se empezaron a desarrollar las redes de área local (LAN)
- Las LAN permiten compartir recursos (impresoras, ficheros,...) a través de un esquema de cableado único
- Las redes son conjuntos de ordenadores independientes que se comunican a través de un medio compartido. Las LAN conectan una serie de ordenadores confinados en un área geográfica, como un edificio o un campus.
- Pueden unir muchos centenares de ordenadores y pueden ser usadas por muchos miles de usuarios. El desarrollo de varias normas de protocolos de red y medios físicos han permitido la proliferación de LAN en grandes organizaciones multinacionales, aplicaciones industriales y educativas.

## Red extensa (WAN)
A menudo una red se localiza en situaciones físicas múltiples. Las redes de área extensa conectan múltiples redes LAN que están geográficamente dispersas. Esto se realiza conectando las diferentes LAN mediante servicios que incluyen líneas telefónicas alquiladas (punto a punto), líneas de teléfono normales con protocolos síncronos y asíncronos, enlaces vía satélite, y servicios portadores de paquetes de datos.

## Internet
Con el meteórico auge en demanda para la conectividad, Internet se ha convertido en la autopista de comunicaciones
para millones de usuarios. Internet fue usado inicialmente por el ejército y las instituciones académicas, pero ahora es un cauce de
información completo para cualquiera, en todas las formas de información y comercio. Los sitios World Wide Web (WWW) de Internet proporcionan ahora recursos personales, educativos, políticos y económicos a cada esquina del planeta.

# Topologias
"La topología de red se define como un mapa físico o lógico de una red para intercambiar datos. En otras palabras, es la forma en que está diseñada la red, sea en el plano físico o lógico"

## Bus

![Red en bus - Wikipedia, la enciclopedia libre](https://upload.wikimedia.org/wikipedia/commons/thumb/d/dd/Topologia_magistrali.svg/200px-Topologia_magistrali.svg.png)

Formada por un cable (bus) compartido al que se unen las estaciones
- Hay finales del segmento conocidos como cargas terminales
PROS
- Bajo coste de implementación
CONTRAS
- Todas las estaciones comparten el medio. No hay repeticiones
- En caso de rotura del cable las estaciones quedan incomunicadas

## Anillo

![Doble Anillo - Topologías de Red](http://3.bp.blogspot.com/_aHHzRbOm2qU/SUmXa7AYL5I/AAAAAAAAAAs/D2WBNuVR7Fk/s320/Imagen3.png)

Una red en anillo es una topología de red en la que cada nodo se conecta exactamente a otros dos nodos, formando una única ruta continua, para las señales a través de cada nodo
PROS
- Todas las estaciones se consideran repetidoras, ya que la información pasa
por todas las estaciones que se encuentrern en el camino desde el origen
hasta el destino.
- Todas las estaciones pueden repetir la señal aunque esta no vaya destinada a ellas
- La señal se repite bit a bit sin almacenarla
CONTRAS
- Si una estación cae puede provocar la
- caída de la red entera

## Malla

![Red en malla - Wikipedia, la enciclopedia libre](data:image/png;base64,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)

Una red en malla es una topología de red en la que cada nodo está conectado a todos los nodos. De esta manera es posible llevar los mensajes de un nodo a otro por distintos caminos. Si la red de malla está completamente conectada, no puede existir absolutamente ninguna interrupción en las comunicaciones

PROS
- Todas las estaciones están interconectadas directamente
- Existen múltiples caminos para cada destino, de modo que la integridad del enlace es muy segura
- En caso de rotura del cable las estaciones no pierden la comunicación
CONTRAS
- Coste de implementación muy elevado
- Imposible de implementar cuando aumenta el número de estaciones

## Estrella

![Red en estrella - Wikipedia, la enciclopedia libre](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAM0AAADICAMAAAB8r5XoAAAAY1BMVEX///8AAADAwMCgoKBAQEBhYWGAgIDy8vK9vb0jIyNqamoX7gD19fUEBATm5uYKCgrNzc2urq4RERHd3d0yMjKWlpYaGhqKiopRUVF1dXUGnhjUhwLdNQFZWVmmpqY8PDwmJiYnczaZAAAET0lEQVR4nO2d6XLiMAyAE5I0QIFwFtoux/s/ZZ1AlqNOfMmxrOqb2R/byUT6kGPLLYYkYRiGYZSkPYTOzRxqNqMO2CY0tY1slEVsk4jE04SKDbHaJE15Eho21Grza92J2IZWbdgGJWyDF7bBC9vghZ4Nrd0aBRvZ+JIROk89qNl0jbEYx1ttk915+s/1B9HZ5C21zdsjjc1bXDa0avP11WTelCKbZ9/fN5Vbbd7jsiFVGxX/SNnQqk1MNrR6AUo2Eoq0CJ0CIGyDF7bBC9vghW3wwjZ4YRu8sA1e2AYvbIMXtsEL2+CFbfDCNngZ3sbnL8DdbUyzo2bj7w9HEDZm2dGzkdURj41Jdj6PmADZGGRHsTZ+jphA1UY/O5K18XLEBKw22tkRrA3baMA2btn9HZuFYy6ONrPlHtJmUqychJxsNrt8nULazNO5k5C9zSY7fKTpOoe0WRUTJyFLm8WqECrVdr+cwc4CCychG5tyNK0jbj9HpTI7uU3vfshByNhmNvrcVk2sUjM7U5tHoXHp0UZMYfVz/3E43V82fRtZBWU8CFW3AeDBZpPVKutDtrHIzuL6xerYPJz6Qto2i9N1ChPPvW12Fm/5vU6c2kJ6Nv/LflexyM7urfImQho25ejzUj+S09fbmWZnfcREW0hlI557MYXJWw7T7FyOMegJ9du0U1gmnfmtamN/xKQV2j8Nd12btnXZbTouMM3O/YhJm1KXUJfNbXY897wQVrVRoTxicu10O4SkNuVYa+UyzQ7oUMZtCZcJ/bYp29ZF2VXYzNAANj1CLzbisrOYwj6OOh2fuY3ZaqsU0rtd1vXcv9qY9gKANrUQ6O2gszMmTfP8/b3/Xzznb+jZqGCbMLANXtgGL4GXO2Bo2TwwnsynbZe8Wle7oMm48iiTJLsqap1nmUYnC5aMK68ytc5kHCgZV37LJLPpPFIdiYzYQUeqI5VpdC7L4bNxpENG6BRprreHxkOnTJJs8th0emTi0+mVaXSOZn+cC4lCRuhsFRcgQimjdQkStDKtL+r+TToeNF92cVkEHaj2GDpF0FAbPBD49wdGT7fQOflMxhXDqWqHugM1nXdR7w/MFxHE+wObFVHobFG2bHbLe3lE2YHa9iooG2r7xguhjksXKXQKVB2oW0u8vKBqqF37e1T7A/dkEO0PIF7Z8QRJBwozTDIcDTXUmEexP4B7gHfVegVyI3sgZ6N96A4UdGoN3VADrxO1zgjudoaAL3pC5xyqZfOwgpeHUB2ol3YkVEPtqbeqdVzP/JnjrVEUOh470KHfjeE3HjUblzdIY4tHz0ZWdZ82/uL5/CiV4eNRrM1w39brNx7J2nj5KJXh4xGsDdugjMc2eOOxDd54bIM3Hj0bWrs1CjayesuA8/AZj5pNV839jDe/8dw/EgJTPOuPUnGx8RaPYG0G/LZev/Ho1UYF5Lf1+o1Hb4amZEOrF6BkwzAMwzDMH+AH+4BQfgahtpkAAAAASUVORK5CYII=)

Todas las estaciones se conectan a un punto común (concentrador)
PROS:
– No hay un punto de fallo que pueda afectar a la red entera
– Permite una mejor gestión de la red
- Con la aparición de los sistemas decableado estructurado es la topología más común hoy en día

# Redes en general
Las redes en general es una manera de compartir información entre dos o más dispositivos, eso con el fin de ahorrar recursos
o tiempo de ejecucion de una tarea, un ejemplo de red es los datos, cuando usted recarga el celular usted obtiene conexion a
otros recursos como Google, pero eso pasa debido a que la empresa proveedora de esos datos le brinda un espacio en su servidor
y le comparte toda esa información necesaria como para poder meterse a Google o a cualquier cosa que requiera internet, otro ejemplo
puede ser cuando le presta datos a su compañero/a, ahi usted sería el que serviria de servidor, proveedor de la informacion necesaria
para que el otro dispositivo sea capaz de llegar a otro servidores más grandes.

[Mapa conceptual](https://lucid.app/lucidchart/1ef03b56-3620-4ac1-b4cd-928200c9533e/edit?page=0_0&invitationId=inv_5a856284-3ac8-4d3e-936a-aa5347d48afb#)
Jhossimar Herrera 1101.
