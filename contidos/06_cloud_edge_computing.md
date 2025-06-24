# Ferramentas para a impartición do módulo de Dixitalización aplicada aos sectores produtivos

## Cloud e Edge Computing: a nova fronteira da dixitalización industrial

## 1. Introducción: del centro de datos a la computación distribuida

La digitalización de procesos ha provocado un cambio radical en la manera en que las empresas almacenan, procesan y acceden a sus datos. El modelo tradicional basado en centros de datos locales ha dado paso a arquitecturas más flexibles, escalables y distribuidas, como la computación en la nube (cloud computing) y la computación en el borde (edge computing).

### ¿A qué le llamamos "nube"?

La "nube" se refiere a un conjunto de servicios digitales accesibles a través de Internet, que permiten almacenar y procesar datos sin necesidad de infraestructura física propia. Estos servicios pueden ser públicos, privados o híbridos, y ofrecen ventajas como la escalabilidad, la reducción de costes y la flexibilidad.

## Cloud Computing

### Definición

Modelo de prestación de servicios digitales (almacenamiento, procesamiento, redes, aplicaciones, etc.) a través de Internet, bajo demanda y con pago por uso.

### Tipos de servicios en la nube

- **IaaS (Infraestructura como servicio):** acceso a servidores, almacenamiento, redes.
  Ej: Amazon EC2, Google Compute Engine.
- **PaaS (Plataforma como servicio):** entornos de desarrollo y despliegue.
  Ej: Heroku, Google App Engine.
- **SaaS (Software como servicio):** aplicaciones listas para usar.
  Ej: Google Workspace, Office 365, Notion.

### Tipos de nube

| Tipo    | Descripción                                                               | Ejemplos                     |
| ------- | ------------------------------------------------------------------------- | ---------------------------- |
| Pública | Gestionada por un proveedor externo. Uso compartido.                      | AWS, Azure, Google Cloud     |
| Privada | Infraestructura de uso exclusivo, gestionada internamente o por terceros. | Nube propia de una empresa   |
| Híbrida | Combinación de ambas, con interconexión y portabilidad entre sistemas.    | Empresas con datos sensibles |

### Ventajas y desventajas

| Ventajas                               | Desventajas                                 |
| -------------------------------------- | ------------------------------------------- |
| Escalabilidad                          | Dependencia de la conectividad              |
| Reducción de costes de infraestructura | Posibles problemas de privacidad y control  |
| Flexibilidad y movilidad               | Riesgos de seguridad si no se gestiona bien |
| Mantenimiento delegado                 | Costes variables y difíciles de prever      |

## Centros de datos

- **Qué son:** instalaciones físicas que albergan servidores, almacenamiento y sistemas de red.
- **Elementos clave:** climatización, redundancia eléctrica, seguridad física y lógica, monitorización.
- **Rol actual:** aunque muchas empresas migran a la nube, los centros de datos siguen siendo cruciales como infraestructura base, sobre todo en nube privada o híbrida.

## Edge Computing, Fog Computing e Mist Computing

### ¿Qué es el edge computing?

Proceso de tratamiento de datos **cerca del lugar donde se generan**, sin necesidad de enviar todo a la nube.

- **Ejemplo:** en una planta química, sensores que detectan fugas o temperatura anómala procesan la información en un microcontrolador local, generando alertas inmediatas.

### ¿Y el fog y mist computing?

- **Fog computing:** arquitectura intermedia entre dispositivos de borde y la nube. Se usan gateways o nodos locales de procesamiento.
- **Mist computing:** procesamiento ultra-local, casi en el dispositivo sensor (nivel más bajo del borde).

| Nivel | Procesamiento           | Latencia | Ejemplo                               |
| ----- | ----------------------- | -------- | ------------------------------------- |
| Mist  | En el propio sensor     | Muy baja | Sensor de presión con microprocesador |
| Edge  | En la red local/gateway | Baja     | Controlador local de maquinaria       |
| Fog   | Nodo intermedio/local   | Media    | Mini centro de datos in situ          |
| Cloud | Centro de datos externo | Alta     | Almacenamiento e IA centralizada      |

![edge vs mist vs fog](/imagenes/edge_vs_mist_vs_fog.png)

## Casos de aplicación

| Sector     | Cloud computing                                   | Edge/Fog/Mist computing                           |
| ---------- | ------------------------------------------------- | ------------------------------------------------- |
| Químico    | Simulación de procesos, almacenamiento de ensayos | Control de procesos en tiempo real                |
| Agrícola   | Plataforma de gestión de cultivos en la nube      | Estaciones meteorológicas locales                 |
| Industrial | ERP y CRM en la nube                              | Monitorización de máquinas con alertas inmediatas |
| Saúde      | Historia clínica electrónica                      | Wearables que monitorizan pacientes               |
| Educación  | Plataformas LMS (Moodle, Classroom, etc.)         | Dispositivos IoT para experimentación             |

## Herramientas e exemplos útiles para FP

### Nube

- **Google Cloud Platform (GCP)**: entorno completo para explorar IaaS, PaaS e incluso modelos de IA.
- **Microsoft Azure for Education**: recursos específicos para FP, con créditos gratuitos.
- **AWS Educate**: plataforma de formación y laboratorio cloud.
- **Nextcloud**: nube privada autoalojada, útil para mostrar alternativas open source.

### Edge/fog

- **Raspberry Pi / Arduino**: plataformas de desarrollo que permiten simular entornos de computación en el borde.
- **Node-RED**: herramienta de programación visual que permite crear flujos de automatización con sensores y dispositivos IoT.
- **Simuladores IoT**: como **Cisco Packet Tracer**, **Tinkercad Circuits**, o **ThingsBoard** para crear dashboards.

## Actividades posibles para alumnado de FP

| Tipo de actividade                     | Descrición                                                                                     |
| -------------------------------------- | ---------------------------------------------------------------------------------------------- |
| **Comparativa de servizos cloud**      | Investigación guiada sobre características, prezos e casos de uso de AWS, Azure e Google Cloud |
| **Montaxe de mini-nube privada**       | Crear un Nextcloud en local ou nunha Raspberry Pi                                              |
| **Simulación de procesos Edge**        | Usar sensores simulados (Tinkercad/Node-RED) para actuar segundo os datos                      |
| **Análise dun caso real de migración** | Estudo de empresas que pasaron de sistemas locais a híbridos ou cloud                          |
| **Taller de arquitectura distribuída** | Construír un diagrama representando cloud, fog, edge e dispositivos conectados                 |

## Recomendacións para docentes

- Propor tarefas que combinen **teoría e análise de casos reais**, non só montaxes técnicas.
- Traballar con linguaxe visual (diagramas, mapas mentais) para explicar arquitecturas complexas.
- Aplicar o **modelo de capas**: desde a infraestrutura ata o servizo final.
- Empregar **rúbricas claras** para avaliar tanto a comprensión conceptual como a capacidade de explicar procesos tecnolóxicos.
