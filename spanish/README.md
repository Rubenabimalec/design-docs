# Design Doc: Chatbot de Telegram para Manejo de QR Secure
Link: [https://github.com/netrix4/CarLogBot](#)

Author(s): Mario, Ruben

Status: [In Review]

Ultima actualización: 2025-03-31

## Contenido
- Goals
- Non-Goals
- Background
- Overview


## Links
- [Un link](#)
- [Otro link](#)

## Objetivo
Estamos desarrollando un chatbot de Telegram que utiliza códigos QR como identificadores únicos de objetos pertenecientes a estudiantes y docentes. El objetivo principal es facilitar la recuperación de objetos perdidos y permitir la notificación de incidentes dentro de la comunidad universitaria, contribuyendo a un entorno más seguro y organizado.

Por ejemplo, en caso de que un vehículo esté averiado, cualquier miembro de la comunidad podrá reportarlo a través del bot, permitiendo que el propietario tome precauciones de manera rápida.

Los estudiantes podrán registrarse en el chatbot y asociar sus objetos a un código QR único. Una opción será pegar stickers con el QR en un lugar visible, de modo que otros estudiantes puedan escanearlo y contactar al propietario en caso de extravío.

Además, el bot contará con un sistema de moderación basado en reportes comunitarios. Si un usuario envía mensajes inapropiados o hace un mal uso de la plataforma, podrá ser eliminado tras recibir múltiples reportes de la comunidad.

## Goals
- Permitir la notificación de incidentes dentro de la comunidad universitaria (ej., vehículo llanta sin aire, mochila perdida).
- Ofrecer un registro en el chatbot para que los usuarios asocien objetos a un código QR único.
- Posibilitar la comunicación entre usuarios a través del escaneo de códigos QR para reportar objetos encontrados.
- Implementar una función que permita a los usuarios listar los objetos asociados a su cuenta.
- reportes comunitarios para moderar y eliminar usuarios que hagan mal uso de la plataforma.

## Non-Goals
- No se busca reemplazar sistemas de seguridad o vigilancia de la institución.
- No se pretende manejar pagos o información financiera en la plataforma.

## Background
La pérdida de objetos en el campus es un problema recurrente, y actualmente no existe un medio organizado para que los estudiantes y docentes reporten y recuperen sus pertenencias de manera eficiente.

Además, existen situaciones dentro de la comunidad universitaria donde una notificación temprana podría evitar inconvenientes mayores. Por ejemplo, muchos estudiantes terminan sus clases a altas horas de la noche y pueden encontrarse con problemas como una llanta ponchada o una luz del auto no encendida. A esas horas, encontrar ayuda mecánica puede ser complicado, pero si otro estudiante nota el problema, podría notificar al propietario antes de que sea demasiado tarde.

Dado que Telegram es una plataforma ampliamente utilizada y accesible para la mayoría de los estudiantes y docentes, se presenta como una solución ideal para implementar un bot con estas funcionalidades.


