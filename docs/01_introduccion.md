# 1. Introducción

## 1.1. Título del reto
Night Lounge: Diseño e implementación de la infraestructura tecnológica para un espacio de ocio nocturno privado y reservable.

## 1.2. Contexto
En los últimos años se ha incrementado la demanda de alternativas al ocio nocturno convencional. Un sector amplio de clientes busca espacios de reunión donde compartir tiempo con sus amigos de forma tranquila, confortable y privada —con ambientes amplios equipados con sofás y servicio de comida y bebida— sin la saturación ni los altos niveles de ruido de las discotecas tradicionales.

Para dar respuesta a esta necesidad, se plantea un centro de ocio de gran superficie compuesto por zonas comunes e instalaciones divididas en salas o reservables de gran capacidad (capaces de albergar confortablemente a grupos de hasta 12 personas). El concepto combina un ambiente general relajado con hilo musical suave en las zonas comunes, permitiendo al mismo tiempo que cada grupo gestione su propia experiencia multimedia y ambiental de forma independiente en el interior de su sala. 

Este modelo exige un soporte tecnológico integral que garantice la conectividad, la gestión de pedidos, la automatización del entretenimiento por estancia y la comunicación interna del local.

## 1.3. Problemática o necesidad
La implantación de un modelo de ocio nocturno basado en reservables privados de gran capacidad presenta retos organizativos y técnicos que deben resolverse para garantizar una experiencia fluida:

* **Gestión eficiente de reservas y control de aforo:** Al tratarse de salas de gran tamaño para grupos numerosos, es indispensable disponer de un sistema centralizado para controlar en tiempo real el aforo, la disponibilidad, los horarios y los estados de preparación de cada estancia.
* **Sistema de comandas y gestión de pedidos:** Al permanecer los clientes dentro de estancias independientes, el método convencional de toma de pedidos resulta ineficiente. Se requiere una plataforma web con base de datos en tiempo real que permita solicitar comida y bebida directamente desde cada sala.
* **Control multimedia y ambiental por estancia:** Cada sala requiere independencia para gestionar su hilo musical, reproducción de contenidos y control de iluminación/domótica local sin interferir en las estancias colindantes ni en las zonas comunes.
* **Acceso Wi-Fi seguro mediante portal interactivo (LoungePass):** Es necesario proporcionar conectividad inalámbrica a los clientes separada de la red administrativa, validando accesos y ofreciendo un punto de interacción inicial seguro.
* **Seguridad de la información y aislamiento de red:** Coexisten servicios de uso público con datos críticos del negocio (TPV, cobros, videovigilancia y servidores internos). Es prioritario evitar vulnerabilidades de seguridad e interferencias entre ambos entornos.

## 1.4. Objetivos

### Objetivo general
Diseñar e implementar una infraestructura tecnológica integral, segura y escalable que dé soporte a la gestión operativa, la conectividad, el control domótico/multimedia y el sistema informático de comandas en un centro de salas privadas reservables.

### Objetivos específicos
* **Diseño de la topología de red y Portal Cautivo (LoungePass):** Estructurar una arquitectura de red segmentada mediante VLANs para aislar el tráfico de clientes, el sistema de administración y los servicios críticos, desplegando un portal de acceso Wi-Fi seguro.
* **Despliegue de servicios centralizados de aforo y base de datos:** Configurar servidores para la gestión de usuarios, direccionamiento de red, base de datos relacional para comandas y almacenamiento centralizado del negocio.
* **Plataforma web de comandas e interconexión de salas:** Habilitar una aplicación web interna alojada en contenedores que gestione los pedidos en tiempo real desde las salas hacia el personal de barra/cocina.
* **Sistema de control multimedia e IoT en sala:** Desplegar los servicios locales encargados de la gestión audiovisual independiente y el control de iluminación por estancia.
* **Seguridad y alta disponibilidad:** Aplicar políticas de acceso en cortafuegos, monitorización de red y copias de seguridad automáticas que garanticen la continuidad del servicio.

## 1.5. Interesados

| Interesado | Relación con el proyecto | Necesidad principal |
|---|---|---|
| **Clientes** | Usuarios finales de las instalaciones, de la Wi-Fi LoungePass y de la app de sala. | Conexión a internet rápida/estable, privacidad, control ambiental/multimedia y facilidad para realizar pedidos. |
| **Personal de sala / Camareros** | Operadores del sistema de comandas y gestión de estancias. | Recepción clara e inmediata de pedidos en cocina/barra y visualización del aforo y estado de salas en tiempo real. |
| **Administrador de Sistemas (IT)** | Responsable del diseño, despliegue y mantenimiento de la infraestructura. | Facilidad de gestión, monitorización de la red, gestión de contenedores/BD, seguridad de la red Wi-Fi y respaldos. |
| **Gerencia / Propietario** | Titular del negocio y promotor de la inversión tecnológica. | Fiabilidad del sistema de comandas/aforo, protección de datos y optimización de los procesos operativos. |

> Nota: Este documento se irá actualizando a medida que se concreten los requisitos técnicos del reto.
