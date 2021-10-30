<h1>Introducción a la Nube con Azure</h1>

<h3>Héctor Vega</h3>

<h1>Tabla de Contenido</h1>

- [1. Introducción al cómputo en la nube](#1-introducción-al-cómputo-en-la-nube)
  - [Aprender sobre la nube](#aprender-sobre-la-nube)
  - [Qué es la nube: ventajas y características](#qué-es-la-nube-ventajas-y-características)
  - [Modelos de servicio: IaaS, PaaS, SaaS y serverless](#modelos-de-servicio-iaas-paas-saas-y-serverless)
  - [Tipos de nube: pública, privada e híbrida](#tipos-de-nube-pública-privada-e-híbrida)
- [2. Componentes de Azure](#2-componentes-de-azure)
  - [Qué es Azure](#qué-es-azure)
  - [Cuentas de Azure](#cuentas-de-azure)
  - [Suscripciones y grupos de administración](#suscripciones-y-grupos-de-administración)
  - [Recursos y grupos de recursos](#recursos-y-grupos-de-recursos)
  - [Regiones](#regiones)
  - [Laboratorio: crear un sitio en WordPress](#laboratorio-crear-un-sitio-en-wordpress)
- [3. Servicios de Azure](#3-servicios-de-azure)
  - [Análisis y bases de datos](#análisis-y-bases-de-datos)
  - [Servicios de cómputo en la nube](#servicios-de-cómputo-en-la-nube)
  - [Almacenamiento](#almacenamiento)
  - [Red](#red)
  - [Inteligencia artificial](#inteligencia-artificial)
  - [DevOps](#devops)
  - [Monitoreo y supervisión](#monitoreo-y-supervisión)
  - [Administración y configuración de entorno](#administración-y-configuración-de-entorno)
  - [Serverless](#serverless)
  - [IoT](#iot)
  - [Seguridad](#seguridad)
- [4. Protección de datos](#4-protección-de-datos)
  - [Privacidad, cumplimiento y protección de datos](#privacidad-cumplimiento-y-protección-de-datos)
- [5. Acuerdos de nivel de servicio (SLA)](#5-acuerdos-de-nivel-de-servicio-sla)
  - [Administración de costos de servicio](#administración-de-costos-de-servicio)
  - [Acuerdos de nivel de servicio y ciclo de vida](#acuerdos-de-nivel-de-servicio-y-ciclo-de-vida)
- [6. Bonus: Laboratorios para aprender más de Azure](#6-bonus-laboratorios-para-aprender-más-de-azure)
  - [Conociendo los servicios básicos de Azure](#conociendo-los-servicios-básicos-de-azure)
  - [Conoce los servicios especializados de Azure](#conoce-los-servicios-especializados-de-azure)
  - [Introducción a SQL Server en Linux](#introducción-a-sql-server-en-linux)
  - [Hospedaje de una aplicación web](#hospedaje-de-una-aplicación-web)
  - [Creación de lógica serverless con Azure Functions](#creación-de-lógica-serverless-con-azure-functions)
- [7. Seguir aprendiendo sobre la nube](#7-seguir-aprendiendo-sobre-la-nube)
  - [Certifícate en Azure](#certifícate-en-azure)

# 1. Introducción al cómputo en la nube

## Aprender sobre la nube

### **Conociendo Azure**

- Qué es
- Azure Portal
- Marketplace
- Servicios

### **Servicios:**

- Cómputo
- Web
- Almacenamiento
- BBDD
- Red
- IA
- DevOps
- Entornos
- Serverless
- IoT
- Seguridad

### **Componentes de Azure**

- Suscripciones
- Grupos de administración
- Recursos
- Grupos de recursos
- Regiones

### **Seguridad y privacidad**

- Protección de la información.
- Red segura.
- Servicios de identidad.
- Gobernanza de la nube.
- Estándares de privacidad.

### **Acuerdo de nivel de servicio**

- Acuerdos.
- Ciclo de vida del servicio.
- Administración de costos de servicio.

### Certificaciones Microsoft

**Developer:** Diseñan, construyen, prueban y mantienen soluciones para la nube:

- Azure Developer
- Developer Associate
- Dynamics 365
- Power Platform Developer
- IoT Developer

**Solutions Architect:** Expertos en cómputo, redes, almacenamiento y seguridad:

- Azure Solutions
- Power Platform
- Finance and Operations Apps

**Administrator:** Implementan, monitorean y mantienen soluciones.

- Azure Administrator
- Windows Virtual Desktop
- Teams Administrator
- Security Administrator

**Data Engineer:** Diseñan e implementan la administración, monitoreo, seguridad y privacidad de datos

- Azure Data Engineer Associate

**Data Scientist:** Aplican técnicas de machine learning para entrenar, evaluar y desplegar modelos que resuelven problemas de negocio:

- Azure Data Scientist Associate

**AI Engineer:** Usan servicios cognitivos, machine learning y knowledge mining para diseñar e implementar soluciones:

- Azure AI Engineer Associate.

**DevOps Engineer:** Combinan personas, procesos y tecnologías para entregar productos de valor y servicios de forma continua:

- Azure DevOps Engineer Expert

**Security Engineer:** Implementan controles de seguridad y protección de amenazas para accesos, datos, aplicaciones y redes:

- Azure Security Engineer
- Security Operations
- Indentity and Access

> Para los interesados en certificarse con Microsoft, pueden estudiar con las [siguientes rutas](https://docs.microsoft.com/es-es/learn/certifications/exams/az-900) Luego de terminar el curso de Platzi, al leer la documentacion de Microsoft sera mas facil la comprension.

 Más de informacion sobre ese[ certificado ](https://docs.microsoft.com/en-us/learn/certifications/azure-data-scientist/)tambien pueden ver sobre el de [AI Engineer](https://docs.microsoft.com/en-us/learn/certifications/azure-ai-engineer/)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Microsoft Certifications | Microsoft Docs](https://docs.microsoft.com/en-us/learn/certifications/)

## Qué es la nube: ventajas y características

### ¿Qué es la nube?

La nube son instalaciones en las cuales cada una tiene de forma independiente energia electrica, refrigeración y seguridad, son llamados Centro de Datos. Dentro de ellos se encuentran cientos de equipos conectados a Internet para consumir los servicios ofrecidos en la Nube.

Los Centros de Datos se encuentran distribuidos a lo largo del mundo. Azure es el servicio Cloud que tiene mas DataCenters desplegados a nivel mundial.

Azure (Microsoft) busca que sus DataCenters sean 100% sustentables utilizando Energias Limpias

### ¿Para qué o Por qué?

- Cómputo
- Servidores
- Almacenamiento y bases de datos
- Redes
- Inteligencia Artificial
- Software y mas

> "Todo lo que puedes hacer en una computadora se puede hacer en la nube pero más: **barato, ágil y seguro**"

### Modelo basado en consumo

Pago por servicios usados:

- Reduce costos operativos
- Optimiza la infraestructura
- Escala según las necesidades

### CapEx vs OpEx

- **Gastos de capital (CapEx):** Inversión en infraestructura física, deducible a largo plazo
- **Gastos operativos (OpEx):** Inversión en servicios o productos facturados al momento

### Ventajas

**Confiabilidad y Alta Disponibilidad**

- Experiencia de usuario sin tiempo de inactividad perceptible, aunque haya errores

**Escalable**

- Vertical: aumentando RAM | CPU a una VM
- Horizontal: aumentado instancias de recursos

**Elasticidad**

- Las aplicaciones siempre tendrán los recursos necesarios

**Agilidad**

- Instanciar recursos en la nube es muy rápido de implementar y configurar

**Distribución geográfica**

- DataCenter en todo el mundo ofreciendo el mejor rendimiento a cada región

**Recuperación ante desastres**

- Los datos se protegen con copias de seguridad, replicación de datos y distribución geográfica

## Modelos de servicio: IaaS, PaaS, SaaS y serverless

![](https://ftrasvent.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fcae40e67-4f26-4f17-a9c9-5f2555194f3d%2FUntitled.png?table=block&id=a2adbfcc-c78f-4239-999e-12e75d0f0f2d&spaceId=a1d40c1f-847c-4e6e-a021-b93b7f5ebb7b&width=1890&userId=&cache=v2)

### On-Premise (Local)

Todo corre por tu cuente:

- Equipos
- Adecuación
- Mantenimiento
- Configuración
- Actualización

### IaaS

**Ventajas**

Parecedo a on-premise ofreciendo mayor flexibilidad y control sobre el hardware:

- Sin CapEx
- Ágil
- Administración compartida

**Desventajas**

- Complicado al inicio según el grado de detalle que se requiere en aspectos de conocimiento y tiempo

### PaaS

**Ventajas**

Entorno administrado por el proveedor: VMs, red, infraestructura.

- Solo te preocupas por el desarrollo.
- Configuración más ágil que IaaS.
- Enfocado al despliegue de aplicaciones.

**Desventajas**

- Puede ser más caro que IaaS.
- Compatibilidad con algunos elementos.
- Dependencias con el proveedor.
- Riesgos de seguridad.
- Limitantes de idioma, interfaz o recursos.

### SaaS

**Ventajas**

El proveedor administra el 100% del entorno y los usuarios solo utilizan la aplicación que se ejecuta en la nube:

- Office Online.
- Outlook.
- CRM.
- ERP.

**Desventajas**

- Se necesita conexión a internet.
- Poco control.
- Baja personalización.
- Desempeño limitado.

### Serveless

- Sí usa servidores.
- El proveedor aprovisiona, escala y administra la infraestructura.
- Ejecuta funciones o fracciones de código.
- Es dirigida por eventos.

**Ventajas**

- Altamente escalable.
- Enfocada a la lógica de negocio.
- Ahorro de tiempo.
- Desarrollo ágil.
- Pago por uso.

**Desventajas**

- No están diseñada para procesos extensos.
- Detalles de desempeño.
- Retos de testing y debugging.

## Tipos de nube: pública, privada e híbrida

### Nube Pública

- Accesible a todo el mundo.
- Son propiedad de un proveedor.
- Se distribuye a través de internet.

### Nube Privada

- Accesible para miembros de una organización
- Puede estar on-premise u hospedada.

### Nube Híbrida

- Combinación de on-premise, nube pública y privada.

![img](https://ftrasvent.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F167d0edf-a416-4114-960b-51f86fff0977%2FUntitled.png?table=block&id=d7264907-c5b1-4c03-a781-7a0556300014&spaceId=a1d40c1f-847c-4e6e-a021-b93b7f5ebb7b&width=1890&userId=&cache=v2)

# 2. Componentes de Azure

## Qué es Azure 🦄 ✨

Azure es un proveedor de servicios en la nube.

### Ventajas de Azure

- Preparado para el futuro.
- Crea a tu ritmo.
- Listo para cualquier tipo de nube.
- Confiable.

### ¿Cómo funciona Azure?

- Virtualización

### Herramientas

- Azure Portal
- Azure MarketPlace

[![img](https://www.google.com/s2/favicons?domain=//azurecomcdn.azureedge.net/cvt-233147754f3cbba3c733e98527f90b7173b78e5c437a095e31cb4f5ec7d35283/images/icon/favicon.ico)Soluciones de Azure | Microsoft Azure](https://azure.microsoft.com/es-es/solutions/)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Microsoft Azure](https://portal.azure.com/)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Examinar todo - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/browse/?products=azure&resource_type=learning path)

## Cuentas de Azure

![img](https://ftrasvent.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F70995e31-cbc0-46c6-a9cc-a0df055b0c11%2FUntitled.png?table=block&id=a82b4f38-8d16-4674-ab15-ecf5bd8ff6b5&spaceId=a1d40c1f-847c-4e6e-a021-b93b7f5ebb7b&width=1150&userId=&cache=v2)

**Recursos:** Instancias de los servicios disponibles como máquinas virtuales, discos duros y bases de datos.

**Grupos de recursos:** Contenedor lógico donde se implementan y administran recursos de Azure. Un recurso puede pertenecer a un solo GR pero puede comunicarse con recursos de otro GR.

- Aplicaciones web.

**Suscripciones:** Agrupación de cuentas de usuario y recursos creados por estas cuentas. 

- Puede tener límites o cuotas definidas.

**Grupos de administración:** Administran el acceso, las directivas y cumplimiento de las suscripciones. 

- Las suscripciones heredan las condiciones de su grupo.

[![img](https://www.google.com/s2/favicons?domain=//azurecomcdn.azureedge.net/cvt-233147754f3cbba3c733e98527f90b7173b78e5c437a095e31cb4f5ec7d35283/images/icon/favicon.ico)Soluciones de Azure | Microsoft Azure](https://azure.microsoft.com/es-es/solutions/)

## Suscripciones y grupos de administración

Se necesita de una suscripción de Azure para utilizar sus servicios:

- Desarrollador: pagas por los servicios a medida que los utilices.
- Prueba: experimentar de manera gratuita.
- Suscripción: a través de un partner compras servicios de Azure.
- Estudiante: a través de un email autorizado (.edu)

### Limites

1. **Facturación:** forma de facturarse. Cada suscripción tiene su factura.
2. **Control de acceso:** cada suscripción tiene directivas de acceso.

### ¿Cuándo se necesita más suscripciones?

- **Entorno:** separación de entornos de trabajos como desarrollo, pruebas, aislamiento de datos, entre otros.
- **Estructura Organizacional:** limitaciones según presupuesto, tiempo, por equipos o acceso a recursos.
- **Facturación:** para facilitar el seguimiento de costos según entornos como producción, desarrollo o pruebas.
- **Límites por suscripción:** Pueden haber algunas limitaciones de hardware por suscripción, entonces es necesario crear nuevas.

![img](https://ftrasvent.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F7e1a5616-1b89-4851-aa12-36040a289c48%2FUntitled.png?table=block&id=2a618b12-2ee3-42f9-9e52-766fbd6d5783&spaceId=a1d40c1f-847c-4e6e-a021-b93b7f5ebb7b&width=1890&userId=&cache=v2)

### Grupos de Administración

![img](https://ftrasvent.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F089c2ae4-3713-4919-8a17-500b35015491%2FUntitled.png?table=block&id=2fb88faa-7a10-4d1c-93f5-8bbf8a6a912c&spaceId=a1d40c1f-847c-4e6e-a021-b93b7f5ebb7b&width=1890&userId=&cache=v2)

**Consideraciones:**

- Hasta 10 000 grupos de administración en un único directorio.
- El árbol de grupo de administración puede admitir hasta seis niveles de profundidad.
- Cada grupo de administración y suscripción solo puede admitir un elemento primario.
- Cada grupo de administración puede tener muchos elementos secundarios.
- Todas las suscripciones y grupos de administración están dentro de una única jerarquía en cada directorio.

## Recursos y grupos de recursos

**Recurso:** elemento administrable en Azure.

**Grupo de recursos:** contenedor de recursos relacionados a una solución.

### Características

- Todos los recursos deben estar en un grupo.
- Un recurso solo puede pertenecer a un grupo.

Cuando eliminas un grupo de recursos, también elimina todos los recursos contenidos.

### Autorización

Utilizan permisos de control basado en roles (RBAC), permitiendo acceso solo a lo necesario.

### Herramientas

**Azure Resource Manager**

![img](https://ftrasvent.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fe79eca66-f03f-42fd-bf26-97fe925906a0%2FUntitled.png?table=block&id=9d1c34e8-7d34-4520-9b8a-cd1d521f12b6&spaceId=a1d40c1f-847c-4e6e-a021-b93b7f5ebb7b&width=1890&userId=&cache=v2)

- Plantillas en JSON.
- Administrar recursos por grupo.
- Capacidad de reutilización.
- RBAC.
- Etiquetas.
- Facturación.

## Regiones

Área geográfica con por lo menos un data center. Algunos servicios son exclusivos de ciertas regiones.

- Canada East
- North Europe
- South Africa North

**Regiones Especiales**

- US DoD
- US Gov Virginia
- US Gov Iowa
- China East
- China North

Azure es el proveedor con más regiones globales y en constante expansión.

https://docs.microsoft.com/en-us/learn/modules/azure-architecture-fundamentals/regions-availability-zones

### Zonas de disponibilidad

- Distintos data centers en una misma región equipados con energía de emergencia, refrigeración y redes independientes.

**Propósito**

- Permiten redudancia de servicios y datos ante errores, desastres u otros imprevistos.

**Consideraciones**

- No todas las regiones son compatibles con zonas de disponiblidad.
- Esto puede implicar un costo.

![img](https://ftrasvent.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F18802415-d20b-4bae-a99b-a9303c6d13e0%2FUntitled.png?table=block&id=3314370f-a7cf-4a5c-8519-203fb48890a4&spaceId=a1d40c1f-847c-4e6e-a021-b93b7f5ebb7b&width=1890&userId=&cache=v2)

### Pares de regiones

Regiones con por lo menos 500 km de distancia entre ambas para replicar recursos en caso de interrupciones, como:

- Desastres naturales.
- Incendios.
- Disturbios civiles.
- Ausencia de electricidad.
- Daños en la red física.
- Otros.

![img](https://ftrasvent.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fe35fe829-135a-43b9-9e26-250e38ca5869%2FUntitled.png?table=block&id=3311125f-516f-4d77-b23b-a19952b68648&spaceId=a1d40c1f-847c-4e6e-a021-b93b7f5ebb7b&width=1890&userId=&cache=v2)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Servicios de Azure compatibles con Availability Zones | Microsoft Docs](https://docs.microsoft.com/es-es/azure/availability-zones/az-region)

## Laboratorio: crear un sitio en WordPress

### Labs

[Ejercicio: Creación de un sitio web hospedado en Azure - Learn](https://docs.microsoft.com/es-mx/learn/modules/azure-architecture-fundamentals/exercise-create-website)

# 3. Servicios de Azure


## Análisis y bases de datos


## Servicios de cómputo en la nube


## Almacenamiento


## Red


## Inteligencia artificial


## DevOps


## Monitoreo y supervisión


## Administración y configuración de entorno


## Serverless


## IoT


## Seguridad

# 4. Protección de datos


## Privacidad, cumplimiento y protección de datos

# 5. Acuerdos de nivel de servicio (SLA)


## Administración de costos de servicio


## Acuerdos de nivel de servicio y ciclo de vida

# 6. Bonus: Laboratorios para aprender más de Azure


## Conociendo los servicios básicos de Azure


## Conoce los servicios especializados de Azure


## Introducción a SQL Server en Linux


## Hospedaje de una aplicación web


## Creación de lógica serverless con Azure Functions

# 7. Seguir aprendiendo sobre la nube


## Certifícate en Azure
