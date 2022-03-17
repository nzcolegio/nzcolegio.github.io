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
Formada por un cable (bus) compartido al que se unen las estaciones
- Hay finales del segmento conocidos como cargas terminales
PROS
- Bajo coste de implementación
CONTRAS
- Todas las estaciones comparten el medio. No hay repeticiones
- En caso de rotura del cable las estaciones quedan incomunicadas

## Anillo
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
Una red en malla es una topología de red en la que cada nodo está conectado a todos los nodos. De esta manera es posible llevar los mensajes de un nodo a otro por distintos caminos. Si la red de malla está completamente conectada, no puede existir absolutamente ninguna interrupción en las comunicaciones

PROS
- Todas las estaciones están interconectadas directamente
- Existen múltiples caminos para cada destino, de modo que la integridad del enlace es muy segura
- En caso de rotura del cable las estaciones no pierden la comunicación
CONTRAS
- Coste de implementación muy elevado
- Imposible de implementar cuando aumenta el número de estaciones

## Estrella
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
