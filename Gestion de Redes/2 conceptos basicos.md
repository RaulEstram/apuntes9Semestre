# Conceptos 

hay varios conceptos que tenemos que utilizar a partir de ahora los cuales se veran a continuacion

## Nube del carrier

Es el conjunto de routers o switches que se encargan de transportar todos los paquetes de las aplicaciones de los clientes, por la infraestructura del carrier ( Telmex, Avantel, Alestra, MetroRed, etc.).

> **Note** por ejemplo en nuestro proyecto serian los 3 estados de México.

## Equipos del ISP

Son los routers, switches, servidores, equipos de acceso, etc. que son propiedad de un ISP ( Internet Service Provider) y que normalmente residen dentro de la central publica. Pueden ser propiedad o NO del carrier.

> **Note** en el proyecto seremos los dueños de los equipos del ISP. Y  serian los equipos que estan dentro de una central como de telmex.

## Medio de Transmisión

Consta de toda la infraestructura capaz de soportar la transmisión de información sobre cobre, fibra óptica, microondas, etc., permitiendo que el servicio llegue a las oficinas del cliente desde la central pública y que puede pasar por varios puntos de interconexión para llegar a su destino final.

> **Note** en el proyecto lo vamos a arrendar esto, y seria en pocas palabras toda la infraestructura cableada o no que tiene el fin de transmitir toda la informacion.

## PE

Es el router que esta en la frontera de la nube y sirve como punto de acceso a los servicios del carrier contratados por el cliente.

> **Note** serian las cajas grandes de la calle de Telmex, creo

## CPE

Es el router que esta en el sitio del cliente y se utiliza como punto de acceso a la red del cliente desde la nube del carrier.

> **Note** Nuestro Modem de casa practicamente.

## NOC

Network Operation Center, es el centro de operaciones desde donde se gestionan los equipos que conforman la nube y son los encargados de mantenerla en operación las 24 horas del día, los 365 días del año.

## Puerto Extendido

Se refiere a que el cliente delega la responsabilidad de parte de su red en manos del carrier ya que su nicho de negocio no son las telecomunicaciones.

## Administrador IT

Se refiere a una o más personas encargadas de gestionar y mantener la red del cliente en producción y guarda una estrecha relación con el NOC, mesa de ayuda y el carrier.

## Cliente

Hace referencia a aquellas personas que esperan recibir un servicio para realizar su trabajo, pueden ubicarse en la oficina, en el NOC, en el carrier, y en otras entidades que conforman el soporte de la red.

## Mesa de ayuda

Es el grupo de personas encargadas de recibir los reportes de falla del cliente, tiene gestión del CPE y la red del cliente, apoya al administrador IT, además puede interactuar con el NOC para la solución de fallas.

> **Note** es un externo de la empreza.

## Ejecutivo de cuenta 

Ss aquella persona que se encarga de poner al alcance del cliente todo el portafolio de productos que ofrece el carrier, el ISP, el NOC o la mesa de ayuda; es el único capaz de brindar una solución comercial al cliente, aprobada técnicamente por la gente de Ingeniería, por los diseñadores de la red, así como el fabricante del producto.

## CRM

software administrativo que utilizan algunas entidades dentro de la red para la gestión de las fallas el cuál permite que todos los involucrados estén actualizados durante el proceso de atención de una falla ( por ejemplo Clarify, Remedy, Help Desk, etc. )