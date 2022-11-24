# BOFHers Mastodon

«The Bastard Operator From Hell (BOFH) is a fictional rogue computer operator, who takes out their anger on users (who are "lusers" to them).» Bienvenidos a la comunidad `bofher`. En este repo/documento encontrarás más información sobre cómo se maneja y organiza todo este chiringuito.

## Bienvenido a bordo

El registro en [mastodon.bofhers.es](https://mastodon.bofhers.es) está abierto con previa aprobación, todos los días el equipo de moderación (*team Mike*) da un ojo a las solicitudes pendientes y comprueba que no se traten bots ni de cuentas fake antes de dar el OK.

Para entrar puedes crear una cuenta nueva, asegúrate de rellenar el motivo por el que quieres unirte, y si eres miembro activo de cualquiera de los canales [#bofhers](https://bofhers.es) de Telegram irá directamente al lado positivo de la balanza.

En cualquier caso, no es complicado ponerse en contacto con cualquiera de nosotros, mismamente puedes usar este repo y sus issues para ello.

## Metas

La meta principal por la que se escribe este documento es el "automantenimiento" del servidor. De momento todos los gastos de instalación, mantenimiento e infraestructura del servidor los lleva [@oscarmlage](https://mastodon.bofhers.es/@oscarmlage), pero como nos encanta el fediverso y la descentralización, la idea es llegar a una situación en la que no se dependa únicamente de una persona.

Además de la instancia de Mastodon, se han previsto otras acciones como la instalación y uso de un [gitea](https://gitea.com) propio, la generación de una base documental en cada una de estas acciones/instalaciones de forma que cualquiera pueda consultar cómo, dónde y en qué manera se gestiona cada una de las instancias y datos que conforman este pequeño mundo. Enseñar y aprender.

## Problemas

El principal problema con el que nos estamos encontrando es la comunicación con todos los usuarios del nodo. Hemos creado un canal #BOFHverse donde intentamos hablar de todo esto, pero no se ha alcanzado ni el 25% de los usuarios activos de la instancia.

## Ideas

### 1. Equipos

Diferentes perfiles que hagan diferentes cosas, porque no a todos nos gusta lo mismo,        los equipos parecen una buena opción para dividir responsabilidades. Todo suma.

- *Team Alpha* (administración de la instancia, actualizaciones, migraciones...)
- *Team Bravo* (burocracia, federación, interacción con otras instancias...)
- *Team Mike* (moderación de usuarios en la instancia)
- *Team Papa* (recaudación de fondos y gestión del  hosting y otros recursos, cuentas paypal-ko-fi...)

Para apuntarte a alguno de los equipos o sumar de cualquier otra forma puedes ponerte en contacto con nosotros, entrar en el canal de Telegram o hacernos llegar cualquier tipo de sugerencia.

### 2. Donaciones

Un sistema de donaciones (*Patreon*, *Paypal*, *Ko-Fi*...) podría recaudar para que los gastos del servidor no sean problema. El *Team Papa* se encargaría de gestionar tanto las membresías de los miembros como los pagos a proveedor de hosting u otras tareas burocráticas que se requieran.

Para cubrir un gasto mensual aproximado de 30€ podría haber dos niveles de suscripción:

1. *luser*: El privilegio de este nivel sería el honor de una mención y el compromiso de colaboración con el mantenimiento del servidor. Además, si lo deseas, ¡serás mencionado como mecenas por nuestra mascota [@tifu](https://mastodon.bofhers.es/@tifu) en un toot!
2. *bofher*: Además del compromiso de colaboración y el honor de una mención, tendrás tu avatar disponible como emoji personalizado para poder usar en la instancia `:username:`.

## Reglas

- Antes de darte de alta consulta [las reglas de esta instancia](https://mastodon.bofhers.es/about) y asegúrate de cumplirlas para no llevarte ningún desengaño.

## Infraestructura

Especificaciones *actuales* de la "infraestructura". La *infra* consta de un servidor alojado en OVH Francia.

- Empezó siendo un VPS básico (4Gb RAM y 60Gb SSD) de 7€/mes pero con todo el tema de Twitter ha llegado más gente y se ha migrado.
- Actualmente se trata de un servidor más grande, que además realiza otras funciones, no está 100% dedicado a la instancia de Mastodon (y eso también es un problema).

Las especificaciones del servidor:

-   8 cores (Intel(R) Xeon(R) CPU E3-1245 V2 @ 3.40GHz)
-   32Gb RAM
-   2Tb disk


## Estado

Por el momento no tenemos ningún recurso para controlar el estado de el/los servicio(s), llegado el momento se valorará.

## Recursos

- [GitHub - hachyderm/community: Hachyderm Community Resources](https://github.com/hachyderm/community)
- [About - Mastodon.green](https://mastodon.green/about)
- [Riseup Pad](https://pad.riseup.net/p/NmQ6UX0BjVLsuJ0j3OxN-keep)
