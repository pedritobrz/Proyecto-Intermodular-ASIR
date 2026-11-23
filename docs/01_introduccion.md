# 1. Introducción

## 1.1. Título del reto
Night Lounge: Diseño e implementación de la infraestructura tecnológica para un espacio de ocio nocturno privado y reservable.

## 1.2. Contexto
En los últimos años se ha incrementado la demanda de alternativas al ocio nocturno convencional. Un sector amplio de clientes busca espacios de reunión donde compartir tiempo con sus amigos de forma tranquila, confortable y privada —con ambientes amplios equipados con sofás y servicio de comida y bebida— sin la saturación ni los altos niveles de ruido de las discotecas tradicionales.

Para dar respuesta a esta necesidad, se plantea un centro de ocio de gran superficie compuesto por zonas comunes e instalaciones divididas en salas o reservables de gran capacidad (capaces de albergar confortablemente a grupos de hasta 12 personas). El concepto combina un ambiente general relajado con hilo musical suave en las zonas comunes, permitiendo al mismo tiempo que cada grupo gestione su propia experiencia multimedia y musical de forma independiente en el interior de su sala. 

Este modelo exige un soporte tecnológico integral que garantice la conectividad, la gestión de pedidos, la automatización del entretenimiento por estancia y la comunicación interna del local.

## 1.3. Problemática o necesidad
La implantación de un modelo de ocio nocturno basado en reservables privados de gran capacidad presenta retos organizativos y técnicos que deben resolverse para garantizar una experiencia fluida:

* **Gestión eficiente de reservas y estancias:** Al tratarse de salas de gran tamaño para grupos numerosos, es indispensable disponer de un control en tiempo real de la disponibilidad, horarios y estados de desinfección/preparación de cada espacio.
* **Sistema de comandas y atención en salas privadas:** Al permanecer los clientes dentro de estancias independientes, el método convencional de toma de pedidos en mesa o barra resulta ineficiente y resta privacidad. Se requiere un mecanismo ágil para solicitar comida y bebida directamente desde la sala.
* **Independencia multimedia y acústica:** Cada sala requiere aislamiento y control local del entretenimiento sin que el contenido audiovisual de un grupo afecte a las estancias colindantes ni al ambiente sonoro general del local.
* **Seguridad de la información y aislamiento de red:** Coexisten servicios de uso público (acceso a internet para clientes) con servicios críticos del negocio (TPV, cobros, videovigilancia y gestión interna). Es prioritario evitar vulnerabilidades de seguridad e interferencias entre ambos entornos.

## 1.4. Objetivos

### Objetivo general
Diseñar e implementar una infraestructura tecnológica integral, segura y escalable que dé soporte a la gestión operativa, la conectividad y la experiencia de ocio multimedia en un centro de salas privadas reservables.

### Objetivos específicos
* **Diseño de la topología de red:** Estructurar una arquitectura de red segmentada para separar el tráfico de clientes, el sistema de administración y los servicios críticos del local.
* **Despliegue de servicios centralizados:** Configurar la infraestructura de servidores necesaria para gestionar usuarios, direccionamiento de red, almacenamiento centralizado y alojamiento de aplicaciones web internas.
* **Sistema de gestión e interconexión de salas:** Habilitar los servicios informáticos que permitan la reserva de espacios, la toma de comandas digitales desde las salas y el control multimedia independiente.
* **Seguridad y alta disponibilidad:** Aplicar políticas de acceso, cortafuegos y mecanismos de copia de seguridad que garanticen la protección de los datos del negocio y la continuidad del servicio.

## 1.5. Interesados

| Interesado | Relación con el proyecto | Necesidad principal |
|---|---|---|
| **Clientes** | Usuarios finales de las instalaciones y de la red pública. | Conexión a internet rápida/estable, privacidad y facilidad para realizar pedidos y controlar el audio de la sala. |
| **Personal de sala / Camareros** | Operadores del sistema de comandas y gestión de estancias. | Recepción clara e inmediata de los pedidos por sala y visualización del estado de ocupación en tiempo real. |
| **Administrador de Sistemas (IT)** | Responsable del diseño, despliegue y mantenimiento de la infraestructura. | Facilidad de gestión, monitorización de la red, seguridad contra accesos no autorizados y respaldos de datos. |
| **Gerencia / Propietario** | Titular del negocio y promotor de la inversión tecnológica. | Fiabilidad del sistema, protección de datos de ventas/clientes y optimización de los procesos operativos. |

> Nota: Este documento se irá actualizando a medida que se concreten los requisitos técnicos del reto.
