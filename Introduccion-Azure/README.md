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

<img src="https://ssl.gstatic.com/docs/common/profile/crow_lg.png" alt="Cuervo anónimo" style="zoom:25%;" />[**Ejercicios Azure**](https://docs.google.com/document/d/1nT6lvqlRPhlPCy1a-Xknp-aPwBjm5gKHqk5QW2CLj6s/edit)

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

NO SQL

- Cosmos DB

SQL

- Azure SQL Database
- Azure Database for Mysql
- Azure Database for PostgreSQL

Big Data

- Azure Synapse Analytics
- Azure HDInsight
- Azure DAtabricks
- Azure Data Lake Analytics

> .CLR: Es el entorno de ejecución de código .NET en SQL que se encarga de compilar y convertir el código pára que sea ejecutado en la CPU de la máquina.

#### **Tipos de bases de datos:**

- Estructuradas (SQL)
- No Estructuradas (NoSQL)

#### **Tipos de Datos**

- Estructurados
- Semi-estructurados
- No estructarados

#### Servicios

1. **Azure Cosmo DB**

   - Servicio de bases de datos NoSQL, elástico e independiente al rendimiento y almacenamiento de las regiones.
   - Almacena datos en formato de secuencia de registro de átomos (ARS).
   - Se abstraen los datos y se proyectan como una API.
   - Compatibilidad con SQL, Gremlin, Cassandra, MondoDB

2. **Azure SQL Database**

   - Basado en Microsoft SQL Server.
   - Alto rendimiento
   - Confiable
   - Administrada
   - Segura
   - Compatible con NoSQL
   - Funciona como PaaS controlando las funciones administrativas de una BD:
     - Actualizaciones
     - Revisiones
     - Backups
     - Supervisión

3. **Azure SQL Managed Instance**

   - Comando para backup.
   - Common language runtime (CLR).

   > **CLR:** Es el entorno de ejecución de código .NET en SQL que se encarga de compilar y convertir el código pára que sea ejecutado en la CPU de la máquina.

   - Transacciones entre bases de datos.
   - No cuenta con escalado automático.

#### Servicios para motores específicos

1. Azure Database for MySQL
   - Basado en MySQL Community Edition 5.6, 5.7 y 8.0.
   - Alta disponibilidad.
   - Escalado en segundos.
   - Protección de información.
   - Backups automáticos.
2. Azure Database for PostgreSQL
   - Basado en PostgreSQL.
   - Opción de servidor único:
     - Básico
     - Uso general
     - Optimizado
   - Hiperscala (Citus) para cargas de
     100 GB o más.

#### Servicios de análisis y big data

1. Azure Synapse Analytics
   - Análisis de datos de todo tipo: sin procesar, refinados o seleccionados.
   - Por medio de recursos sin servidor o provisionados.
   - Compatible con SQL y Apache Spark.
2. Azure HDInsight
   - Análisis de datos de open source.
   - Procesa grandes volúmenes de datos.
   - Puede crear clusters de tipo Spark, Hadoop, Kafka, HBase y más.
   - Admite ETLs.
3. Azure Databricks
   - Descubre información de volúmenes masivos de datos.
   - Compatible con Apache Spark.
   - Funciona Python, Scala, R, Java, SQL, TensorFlow, PyTorch y Scikit-Learn.
4. Azure Data Lake Analytics
   - Realiza análisis bajo demanda.
   - Enfocado a ETL en lugar de configurar hardware.
   - Modelo pay as you go.

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Compare the database engine features of SQL Database and SQL Managed Instance - Azure SQL Database & SQL Managed Instance | Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-sql/database/features-comparison)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación de una base de datos SQL - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/azure-database-fundamentals/exercise-create-sql-database)

## Servicios de cómputo en la nube

**Azure Virtual Machine:** Maquina Virtual o IaaS
\- Azure Batch: Conjunto de VMs con aumento y/o disminución automática.

**Azure Container Instances:** Administrador de Contenedores.

**Azure Kubernetes Services:** Orquestador de Contenedores.

**Azure App Service:** es un PaaS para aplicaciones web. api y moviles.

**Serverless:** Dirigido por eventos y pago por uso.
\- Azure Functions: Responden a eventos y escalan automáticamente.
\- Azure Logic Apps: Responden a eventos y cuentan con GUI.

**Windows Virtual Desktop:** Acceder a una maquina Windows mediante escritorio remoto.

#### Azure Virtual Machines

- IaaS
- Conveniente para:
  - Pruebas y desarrollo.
  - Ejecutar aplicaciones en la nube.
  - Extender recursos en la nube.
  - Recuperación ante desastres.
- Migración (lift-and-shift)
- Azure Batch:
  - Conjuntos de VMs.
  - Configuración en minutos de máquinas idénticas.
  - Aumento o disminución automático.

#### Azure Container Instances

- PaaS para ejecución de contenedores
  - Sencillo
  - Sin servicios adicionales
  - Permite carga de contenedores

#### Azure Kubernetes Service

- Orquestación (automatización y administración) de contenedores en volumen.
- Utilidad de contenedores:
  - Dividir las partes de una aplicación.
  - Hacer cambios sin afectar otras partes.
  - Hacer pruebas en entornos aislados

#### Azure App Service

- PaaS para crear y alojar aplicaciones conectadas a la web.
- Compatible con Windows, Linux e implementaciones automatizadas.
- Tipos de servicios:
  - Aplicaciones web.
  - Aplicaciones de API.
  - Operaciones en segundo plano.
  - Aplicaciones móviles.

#### Azure Functions (serverless)

- Funciones que responden a eventos:
  - Peticiones REST.
  - Temporizador.
  - Mensajes de otro servicio.
- Escalan automáticamente.
- Sin estado.
- Con estado (Durable Functions).

#### Azure Logic Apps (serverless)

- Flujos de trabajo basados en eventos.
- Cuenta con una GUI.
- Se crean de forma visual o en JSON.
- Cuenta con más de 200 conectores y bloques.

#### Windows Virtual Desktop

- Tener Windows en cualquier lugar.
- Compatible con los sistemas operativos mas populares o incluso navegadores web.
- Ventajas:
  - Compatibilidad.
  - Mejor experiencia de uso.
  - Seguridad.
  - Rendimiento.
  - Inicio de sesión múltiple.
  - Licencias propias.

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación de una máquina virtual Windows - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/create-windows-virtual-machine-in-azure/3-exercise-create-a-vm)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Conexión a una máquina virtual Windows mediante RDP - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/create-windows-virtual-machine-in-azure/5-exercise-connect-to-a-windows-vm-using-rdp)

## Almacenamiento

#### Azure Blob Storage

- Almacenamiento no estructurado.
- Sin restricciones.
- Soporta miles de cargas simultáneas.
- Ideal para:
  - Visualizar imágenes o videos.
  - Acceso distribuido.
  - Streaming.
  - Backup.
  - Análisis de datos.
  - Almacenamiento de VMs >8 TB.

#### Azure Files

- Recursos compartidos administrados en la nube bajo protocolos SMB y NFS.
- Pueden estar en local o en la nube.
- Ideal para:
  - Cuando muchas aplicaciones usan recursos compartidos.
  - Acceder a recursos desde varias VMs.
  - Similar a OneDrive.

#### Niveles de acceso:

1. **Frecuente:** Imágenes o descargas de un sitio web.
2. **Esporádico (30 días):** Reportes mensuales, facturas, etc.
3. **Archivo (180 días):** Copias de seguridad.

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: creación de una cuenta de almacenamiento mediante Azure Portal - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/create-azure-storage-account/5-exercise-create-a-storage-account)

## Red

#### Azure Virtual Network

- Permite a los recursos de Azure comunicarse entre sí, con usuarios de internet y equipos cliente en local.
- Funcionalidades:
  - Aislamiento y segmentación
  - Comunicación con internet
  - Comunicación entre recursos
    - Redes virtuales.
    - Puntos de conexión de servicio.
  - Comunicación entre recursos locales
    - Redes virtuales de punto a sitio.
    - Redes privadas virtuales (VPN) de sitio a sitio.
    - Azure ExpressRoute.
  - Enrutamiento del tráfico de red
    - Tablas de ruta.
    - Protocolo de puerta de enlace de borde (BGP).
  - Filtrado del tráfico de red
    - Grupos de seguridad de red.
    - Aplicaciones virtuales de red.

#### Azure VPN Gateway

- Conecta redes locales a Azure vía VPN de sitio a sitio/punto, a sitio, a través de protocolos IPsec e IKE.

#### Azure ExpressRoute

- Genera conexiones privadas entre Azure y la infraestructura, de forma confiable y rápida, sin utilizar internet público.

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: creación de una red virtual de Azure - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/configure-network-for-azure-virtual-machines/3-exercise-create-azure-virtual-network)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación de una instancia de Azure VPN Gateway - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/configure-network-for-azure-virtual-machines/5-exercise-create-azure-vpn-gateway)

## Inteligencia artificial

El **Deep Learning** es lo que usan la mayoría de redes sociales y aplicaciones para recomendarnos publicidad de productos en los que estemos interesados o que estemos buscandoo. Lo hace aprendiendo de las cosas que consumimos o lo que decimos a través de toda la red (no escuchando nuestras palabras a través de micrófonos como muchos creen). A partir de que aceptamos las condicioines de cualquier sitio web, estamos autorizando a que se use la información de nuestras actividades para que una red neuronal aprenda de nosotros… Si, espeluznante

1. **Deep Learning:** usa redes neuronales para descubrir, aprender y crecer.
2. **Machine learning:** utiliza datos existentes para entrenar modelos y pronosticar.

#### Azure Machine Learning

- PaaS para realizar predicciones conectándose a datos para entrenar y probar modelos.
- Ofrece control completo del diseño y entrenamiento de algoritmos.

#### Azure Cognitive Services

- Modelos de ML creados que permiten a una aplicación ver, oír, hablar, entender y pensar. No se necesitan conocimientos en ML o DS.
- Categorías:
  - Lengua
  - Voz
  - Visión
  - Decisión

#### Azure Bot Service

- Azure Bot Service.
- Bot Framework.
- Creación de agentes virtuales que pueden usar otros servicios.

- **Deep learning:** usa redes neuronales para descubrir, aprender y crecer.
- **Machine learning:** utiliza datos existentes para entrenar modelos y pronósticar.

**AZURE MACHINE LEARNING**

Una de las ventajas de la nube es el poder disponer de esas VM con altas capacidades de procesamiento de cómputo para poderlas utilizar en IA.

Este servicio de Azure nos brinda una PaaS para realziar predicciones conectándose a datros para entrenar y probar modelos. Ofrece control completo del diseño y entrenamiento de algoritmos.

**AZURE COGNITIVE SERVICES**

Modelos de ML creados que permiten a una aplicación ver, oír, hablar, entender y pensar. No se necesitan conocimientos en ML o DS.

Categorías:

- Lenguaje
- Voz
- Visión
- Desición

**AZURE BOT SERVICE**

- Azure Bot Service.
- Bot Framework.
- Creación de agentes virtuales que pueden usar otros servicios.

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: análisis de imágenes con el servicio Computer Vision - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/analyze-images-computer-vision/3-analyze-images)

## DevOps

#### **Azure DevOps Services**

#### 1. Azure Repos

- Repositorios de código fuente centralizado para publicar código y colaborar.

#### 2. Azure Boards

- Tableros para gestión de proyectos como Kanban, informes, incidencias, epics, etc.

#### 3. Azure Pipelines

- Herramienta de automatización de:
  - Continuos Integration
  - Continuos Delivery

#### 4. Azure Artifacts

- Repositorio para alojar *artefactos* que se incluyen en el flujo de pruebas o implementación.

#### 5. Azure Test Plans

- Herramientas de pruebas automatizadas para garantizar la calidad antes de lanzar software.

#### GitHub & GitHub Actions

- **Git:** herramienta de control de versiones.
- **GitHub:** repositorio de código remoto.

1. **GitHub** Actions

- Automatización de flujos de trabajo basado en triggers, especialmente para CI/CD.

#### Azure DevTest Labs

- Medio automatizado para administrar proceso de compilación, configuración y anulación de VMs y otros recursos.

> ### 🦄DevOps✨
>
> **DevOps se refiere a una cultura de trabajo, más no a una persona. Se refiere a una conección entre el desarrollo y la operación, bajo una serie de actividades y roles que están relacionadas entre sí con el fin de que un servicio electrónico funcione de la mejor manera en cualquier plataforma.**

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación de una prueba de rendimiento para una aplicación web mediante Azure Portal - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/load-test-web-app-azure-devops/3-create-a-quick-performance-test-for-a-web-app-using-the-azure-portal)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Uso de Azure DevOps para personalizar y volver a configurar las pruebas de carga de aplicaciones web - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/load-test-web-app-azure-devops/6-use-azure-devops-to-customize-and-reconfigure-web-app-load-tests)

## Monitoreo y supervisión

**Azure Advisor:** nos brinda consejos y evalúa recursos a través del portal de Azure o su API.
**Azure Monitor**: recopila datos para tomar decisiones basados en métricas del entorno local o la nube. Las fuentes son diversas como ser SO, aplicaciones, suscripciones.
**Azure Service Health**: brinda una vista personalizada del estado de los servicios, regiones y recursos de Azure.

- Azure Advisor, evalua recursos, brinda recomendaciones y notificaciones en confiabilidad, seguridad, rendimiento, costos.
- Azure monitor, recopila, análiza y muestra datos para tomar acciones basadas en métricas tanto del entorno local como de Azure.
- Azure Service Health, brinda el estado de los servicios.

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Configuración de una máquina virtual con diagnósticos de arranque - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/monitor-azure-vm-using-diagnostic-data/3-exercise-create-virtual-machine)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Configuración de la extensión Azure Diagnostics - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/monitor-azure-vm-using-diagnostic-data/6-exercise-configure-azure-diagnostic-extension)

## Administración y configuración de entorno

**Herramientas grafica**s (Azure Portal, Azure Mobile App, en ambos se puede ejecutar código con bash o PowerShell a través de, Cloud Shell “la terminal incrustada” en el navegador web).
**Herramientas de comandos** (Azure PowerShell (comandos command lets”cmdlets”), Azure CLI, Cloud Shell.
**Azure Resource Manager Templates**: format JSON, se puede definer estado y configuración de cada recurso y la plantilla se encarga del resto.

Al trabajar en la nube es necesario tener un buen control y administración del trabajo. Azure nos brinda de herramientas para la administración de trabajo, las cuales pueden ser visuales o basadas en código.

**AZURE PORTAL**

Es una consola unificada basada en web que proporciona una alternativa a las herramientas de línea de comandos. Con Azure Portal, puede administrar su suscripción a Azure mediante una interfaz gráfica de usuario.

**AZURE MOBILE APP**

- Compatible con iOS y Android
- Supervisa estado de Azure
- Alertas, diagnósticos y correcciones
- Ejecutar comandos de CLI o Azure PowerShell

**HERRAMIENTAS BASADAS EN CÓDIGO**

- Azure PowerShell
- Azure CLI
- Cloud Shell

**AZURE RESOURCES MANAGER TEMPLATES**

Es un administrador de plantillas de recursos

- Formato JSON
- Se comprueban antes de ejecutarse
- Se define el estado y configuración de cada recurso, la plantilla hace el resto

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación de una aplicación de funciones en Azure Portal - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/create-serverless-logic-with-azure-functions/3-create-an-azure-functions-app-in-the-azure-portal?pivots=javascript)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Incorporación de lógica a la aplicación de funciones - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/create-serverless-logic-with-azure-functions/5-add-logic-to-the-function-app?pivots=javascript)

## Serverless

### Azure Functions

- Alojamiento de métodos o funciones que se ejecutan enrespuesta a eventos:
  - Solicitudes HTTP
  - Temporizadores
  - Mensajes
  - Acciones
- Ventajas:
  - Escalado automático.
  - Pago por función ejecutada.
  - Con o sin estado.
  - Tareas de orquestación (durable functions).
- Lenguajes compatibles
  - C#
  - JavaScript
  - Python
  - TypeScript
  - Java
  - Shell

### Azure Logic Apps

- No-code/Low-code.
- Ideal par automatizar y organizar.
- Integra aplicaciones, datos y sistemas.

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Incorporación de lógica a la aplicación de funciones - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/create-serverless-logic-with-azure-functions/5-add-logic-to-the-function-app?pivots=javascript)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación de una rama en función de las opiniones del tweet - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/route-and-process-data-logic-apps/8-ex-branch-based-on-tweet-sentiment)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación de una aplicación de funciones en Azure Portal - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/create-serverless-logic-with-azure-functions/3-create-an-azure-functions-app-in-the-azure-portal?pivots=javascript)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación de la aplicación lógica de seguimiento de redes sociales - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/route-and-process-data-logic-apps/4-ex-create-social-media-tracker)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Análisis del contenido de un tweet - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/route-and-process-data-logic-apps/6-ex-analyze-content-of-tweet)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación de una rama en función de las opiniones del tweet - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/route-and-process-data-logic-apps/8-ex-branch-based-on-tweet-sentiment)

## IoT

> El Internet of Things (IoT), describe la red de objetos físicos (cosas), que llevan sensores integrados, software y otras tecnologías, con el fin de conectar e intercambiar datos con otros dispositivos y sistemas a través de Internet.

#### ¿De dónde vienen los datos?

**Sensores**:

- Temperatura.
- Humedad.
- Códigos (barras, QR).
- Proximidad.
- Ubicación geográfica.
- Sonido.
- Movimiento.
- Biométricos.

### Azure IoT Hub

- Centro de mensajes entre aplicaciones IoT y dispositivos.
- Permite control remoto manual o automatizado de dispositivos.
- Cuenta con supervisión

### Azure IoT Central

- Basado en IoT Hub con interfaz visual.
- Posee plantillas para escenarios comunes.

### Azure Sphere

- Avnet Azure Sphere MT3620 Starter Kit
- Seeed MT3620 Mini Dev Board
- Kit de desarrollo de Seeed Azure Sphere MT3620
- Partes:
  - Unidad de Microcontrolador (MCU).
  - Sistema operativo (SO).
  - Servicio de seguridad (AS3).
- Requisitos:
  - Kit de desarrollo.
  - Windows
    - Visual Studio.
    - Visual Studio Code.
    - Línea de comandos con CMake.
  - Linux
    - Visual Studio Code.
    - Línea de comandos con CMake.

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación de un servicio de aprovisionamiento de dispositivos, un certificado raíz y una inscripción de grupo - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/securely-provision-iot-devices-at-scale-with-device-provisioning-service/4-exercise-create-dps-resource-root-certificate-group-enrollment)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Creación del código para los dispositivos de sensor - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/securely-provision-iot-devices-at-scale-with-device-provisioning-service/6-exercise-create-code-sensor-devices?pivots=vscode)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Comprobación de que varios dispositivos se aprovisionan automáticamente y se asignan al centro - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/securely-provision-iot-devices-at-scale-with-device-provisioning-service/7-exercise-test-multiple-devices-provision-correctly)

## Seguridad

### Azure Security Center

- Servicio que brinda visibilidad del nivel de seguridad de los servicios en Azure y local.
- Supervisa la configuración de seguridad.
- Aplica cambios automáticamente.
- Brinda recomendaciones.
- Detecta y bloquea amenazas de malware con ML.
- Detecta ataques e investiga amenazas.
- Proporciona control de acceso *Just-in-Time.*

#### Puntuación de seguridad

Es la medida del nivel de seguridad y permite:

- Notificar el estado actual.
- Mejorar el nivel.
- Compara puntos de referencia.

### Azure Sentinel

- SIEM en la nube de análisis de seguridad y amenazas.
  - Recopila datos en volumen.
  - Detecta amenazas
  - Investiga con IA.
  - Responde a incidentes.

### Azure Key Vault

- Servicio centralizado para almacenar datos confidenciales.

- Administra

  :

  - Secretos.
  - Claves de cifrado.
  - Certificados SSL/TLS.
  - Respaldos por módulos de seguridad de hardware (HMS).

### Azure Dedicated Host

- Servidores físicos que no se comparten con otros inquilinos y/o aplicaciones.
- Ofrece visibilidad y control.
- Asegura requisitos de cumplimiento.
- Personalizable.
- Puede tener mayor costo.

### Servicios de Seguridad de Red

### Azure Firewall

### Azure DDoS Protection

### Servicios de Identidad

- **Autenticación (AuthN):** Solicitar credenciales legítimas.
- **Autorización (AuthZ):** Establecer el nivel de acceso a una persona o servicio autenticado.

### Azure Active Directory

### Multi-Factor Authentication

### Inicio de Sesión Único (SSO)

- Azure Security Center, visibilidad a nivel de seguridad de los servicios de Azure y local
- Azure Sentinel, análisis de seguridad y amenazas
- Azure Key Value, Administrar secretos, claves, certificados ssl, etc.
- Azure Dedicate Host
- Azure Firewall, Azure DDoS
- Autenticación; solicitar credenciales legítimas. Autorización; establecer niveles de acceso
- Azure Active Directory, Multi-Factor Autentication, Inicio de Sesión Único (SSO)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Administración de una contraseña en Azure Key Vault - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/protect-against-security-threats-azure/5-manage-password-key-vault)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: agregar o eliminar usuarios en Azure Active Directory - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/create-users-and-groups-in-azure-active-directory/3-exercise-add-delete-users-azure-ad)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: asignar usuarios a grupos de Azure Active Directory - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/create-users-and-groups-in-azure-active-directory/5-exercise-assign-users-azure-ad-groups)

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Ejercicio: Habilitación de Azure AD Multi-Factor Authentication - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/secure-aad-users-with-mfa/4-exercise-mfa)

# 4. Protección de datos

## Privacidad, cumplimiento y protección de datos

> Los datos de nuestros clientes NO son nuestros datos.

## ¿Cumplimiento?

Cumplir con una ley, estándar, conjunto de directrices, normas o requerimientos.

- Globales
- Gubernamentales
- Sectoriales
- Regionales

### Declaración de privacidad

- Explica qué datos personales recopila Microsoft, cómo los usa y para qué.
- Abarca todos sus servicios, sitios, software, servidores y dispositivos.

### Términos de los servicios en línea

- Contrato legal entre Microsoft y el cliente.
- Detalla las obligaciones de ambas partes respecto al procesamiento y seguridad de los datos.
- ***Aplica a servicios bajo licencia.\***

### Anexo de protección de datos **(Data Protection Addendum)**

- Define términos de seguridad y procesamiento de datos para servicios en línea:

  - Cumplimiento de leyes
  - Revelación de datos
  - Seguridad de datos

  > 🦄Si en algún momento no nos llegó a importar esos acuerdos a los que simplemente le poníamos “estoy de acuerdo” sin por lo menos leerlos. Ahora es nuestra obligación leer esos acuerdos para poder ejercer como comunicadores con los clientes que estén interesados en el tema✨
  >
  > Es la capacidad de un sistema para salvaguardar información sensible y que no se debe o quiere compartir.
  >
  > - Cumplimiento con leyes, estándares, directrices, normas pueden ser globales, gubernamentales, sectoriales, regionales.
  > - Declaración de privacidad, contrato legal entre el cliente y Microsoft.

  

  [![img](https://www.google.com/s2/favicons?domain=//azurecomcdn.azureedge.net/cvt-233147754f3cbba3c733e98527f90b7173b78e5c437a095e31cb4f5ec7d35283/images/icon/favicon.ico)Información legal de Microsoft Azure | Microsoft Azure](https://azure.microsoft.com/es-mx/support/legal/)

[![img](https://www.google.com/s2/favicons?domain=//azurecomcdn.azureedge.net/cvt-233147754f3cbba3c733e98527f90b7173b78e5c437a095e31cb4f5ec7d35283/images/icon/favicon.ico)Confíe en su nube | Microsoft Azure](https://azure.microsoft.com/es-mx/overview/trusted-cloud/)

# 5. Acuerdos de nivel de servicio (SLA)

## Administración de costos de servicio

### Calculadora de costo total de propiedad (TOC)

- Ayuda a calcular los costos de Azure vs. local.
- Deben considerarse costos indirectos, diferencias de zona, promedios, etc.

#### ¿Cómo funciona?

1. Definir cargas de trabajo.
2. Ajustar supuestos.
3. Consultar informe.

### Comprar servicios

- Contratos Enterprise (B2B).
- En la web.
- Proveedor de soluciones (Microsoft partner)

#### ¿Qué afecta a los costos?

- Tipo de recurso.
- Medidores de uso: tiempo, tráfico, tamaños y cantidades.
- Uso de recursos.
- Región.

### Reducción de costos

#### ¿Qué afecta a los costos?

- Estimar antes de implementar.
- Azure Advisor.
- Limitar presupuestos.
- Pagar por adelantado.
- Licenciamiento.
- Disponer de regiones y ubicaciones de bajo costo.
- Investigar ofertas de ahorro.
- Azure Cost Management + Billing.
- Etiquetas para identificar costos.
- Cambiar el tamaño de recursos.
- Desasignar recursos.
- Eliminar recursos no utilizados.
- Migrar de IaaS a PaaS.

[![img](https://www.google.com/s2/favicons?domain=//azurecomcdn.azureedge.net/cvt-233147754f3cbba3c733e98527f90b7173b78e5c437a095e31cb4f5ec7d35283/images/icon/favicon.ico)Información general sobre precios - Cómo funcionan los precios de Azure | Microsoft Azure](https://azure.microsoft.com/es-mx/pricing/)

[![img](https://www.google.com/s2/favicons?domain=//azurecomcdn.azureedge.net/cvt-233147754f3cbba3c733e98527f90b7173b78e5c437a095e31cb4f5ec7d35283/images/icon/favicon.ico)Calculadora de precios | Microsoft Azure](https://azure.microsoft.com/es-mx/pricing/calculator/)

[![img](https://www.google.com/s2/favicons?domain=//azurecomcdn.azureedge.net/cvt-233147754f3cbba3c733e98527f90b7173b78e5c437a095e31cb4f5ec7d35283/images/icon/favicon.ico)Calculadora del costo total de propiedad (TCO) | Microsoft Azure](https://azure.microsoft.com/es-mx/pricing/tco/calculator/)

[![img](https://www.google.com/s2/favicons?domain=//azurecomcdn.azureedge.net/cvt-233147754f3cbba3c733e98527f90b7173b78e5c437a095e31cb4f5ec7d35283/images/icon/favicon.ico)Optimización de costos en la nube | Microsoft Azure](https://azure.microsoft.com/es-mx/overview/cost-optimization/)

## Acuerdos de nivel de servicio y ciclo de vida

**Acuerdo de nivel de servicio**

Contrato formal entre empresa de servicios y cliente.
Define estándares de rendimiento que Microsoft se compromete a brindar.

**¿Qué incluyen?**

- Introducción.
- Términos generales.
- Detalles del SLA (Service Level Agreement).

**Importancia**
**Entender:**

- Garantías de servicio.
- Hacerlas efectivas.
- Disponibilidades.

**Elementos para aumentar SLA**

- Tipo de discos.
- Niveles superiores de servicio.
- Redundancia en regiones.
- Redundancia en zonas de disponibilidad.

**Ciclo de vida**
Forma en que cada servicio está disponible.

**Fases:**

- Desarrollo
- Preliminar
- Disponibilidad general (GA)
- Desaconsejado

- SLA, Acuerdo de nivel de servicio entre Microsoft y los clientes.
- Si un servicio es <95% hay un crédito del 100%. <99% un crédito del 25%, 99.99% es del 10%.
- Ciclo de vida de un servicio: Desarrollo, Preliminar, Disponibilidad general, depreciado.

### ¿Por qué son importantes los acuerdos de nivel de servicio?

La comprensión del acuerdo de nivel de servicio de los servicios de Azure que use le ayudará a conocer las garantías que puede esperar.

La disponibilidad de los servicios que usa afecta al tiempo de actividad y en el rendimiento de las aplicaciones que se compilan en Azure.

### ¿Cómo puedo solicitar un crédito de servicio a Microsoft?

Normalmente, deberá presentar una reclamación a Microsoft para recibir un crédito de servicio. Si adquiere los servicios de Azure de un partner proveedor de soluciones en la nube (CSP), este suele encargarse de administrar el proceso de reclamación.

Cada acuerdo de nivel de servicio especifica el plazo en el que se debe enviar la reclamación y el plazo para que Microsoft la procese. En muchos servicios, la reclamación debe enviarse antes de que finalice el mes natural siguiente al mes en el que se produjo el incidente.

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Elección de los servicios de Azure adecuados según los Acuerdos de Nivel de Servicio y el ciclo de vida del servicio (AZ-900) - Learn | Microsoft Docs](https://docs.microsoft.com/es-es/learn/modules/choose-azure-services-sla-lifecycle/)

[![img](https://www.google.com/s2/favicons?domain=//azurecomcdn.azureedge.net/cvt-233147754f3cbba3c733e98527f90b7173b78e5c437a095e31cb4f5ec7d35283/images/icon/favicon.ico)Contratos de nivel de servicio - Página principal | Microsoft Azure](https://azure.microsoft.com/es-mx/support/legal/sla/)

# 6. Bonus: Laboratorios para aprender más de Azure

## Conociendo los servicios básicos de Azure

## **Crea una cuenta en Microsoft Learn y regístrate a los laboratorios.**

Para ello solo tienes que seguir estos pasos:

1. Ingresa a la [página de Microsoft Learn](https://docs.microsoft.com/es-es/learn/).

![https://i.imgur.com/i3zJvyM.png](https://i.imgur.com/i3zJvyM.png)

En parte superior derecha encontrarás un botón para iniciar sesión.

1. Inicia sesión en el portal. Lo podrás hacer con cualquier cuenta de Microsoft existente que tengas. En caso de que no tengas una da clic en el enlace para crear una.

![https://i.imgur.com/OoxdXtx.png](https://i.imgur.com/OoxdXtx.png)

1. Una vez inicies sesión, te pedirá llenar unos datos extra para completar tu perfil dentro de la plataforma.

![https://i.imgur.com/KsCvh6p.png](https://i.imgur.com/KsCvh6p.png)

1. Por último, regístrate al [desafío de la Escuela de Cloud Computing con Azure.](https://docs.microsoft.com/es-mx/learn/challenges?id=2cceec57-42f9-4350-8b82-1fc4fe0034fa)

![https://i.imgur.com/Aigzdiq.png](https://i.imgur.com/Aigzdiq.png)

1. ¡Listo! Ya tienes tu cuenta en Microsoft Learn vinculada a la Escuela de Azure de Platzi y puedes comenzar a realizar los laboratorios de práctica asociados a este curso.

## Conociendo los servicios básicos de Azure

La nube de Azure cuenta con un sin fin de servicios: desde bases de datos hasta almacenamiento. En este módulo de Microsoft Learn podrás conocer e identificar los servicios básicos que ofrece Azure.

En este módulo aprenderás sobre:

- Los servicios de Azure Compute
- Los servicios de red de Azure
- Los servicios de Azure Storage
- Los servicios de análisis y bases de datos de Azure

Si deseas acceder a este módulo puedes [ir al siguiente enlace.](https://docs.microsoft.com/es-es/learn/paths/az-900-describe-core-azure-services/?ns-enrollment-type=Collection&ns-enrollment-id=xgg5bxjg1owzm7)

## Conoce los servicios especializados de Azure

Aunque ya conoces los servicios que Azure ofrece para soluciones generales como almacenamiento, red o computo existen todavía una amplia gama de problemas que necesitan soluciones mucho más especializadas.

Para ello te recomendamos que tomes el siguiente módulo en Microsoft Learn donde aprenderás:

- Elegir el mejor servicio de Azure IoT para tu aplicación
- Elegir el mejor servicio de IA para tus necesidades
- Elegir la mejor tecnología *serverless* de Azure para un escenario empresarial
- Elegir las mejores herramientas para ayudar a que las organizaciones creen mejores soluciones
- Elegir las mejores herramientas para administrar y configurar un entorno de Azure
- Elegir el mejor servicio de supervisión para visibilidad, información y mitigación de interrupciones

Si deseas desarrollar este módulo lo puedes encontrar en el [siguiente enlace.](https://docs.microsoft.com/es-es/learn/paths/az-900-describe-core-solutions-management-tools-azure/?ns-enrollment-type=Collection&ns-enrollment-id=xgg5bxjg1owzm7)

## Introducción a SQL Server en Linux

Una de las bases de datos más importantes en el sistema corporativo es SQL Server de Microsoft. Como profesional de la nube de Azure es bueno que conozcas este gestor de bases de datos relacionales y sepas cómo implementarlo en tus soluciones:

Para ello te recomiendo que tomes el siguiente módulo en la plataforma de Microsoft Learn en el cual aprenderás a:

- Describir las ventajas principales de ejecutar SQL Server en Linux
- Describir las herramientas de Windows y multiplataforma que se pueden usar para administrar SQL Server en Linux.
- Describir las ventajas de ejecutar SQL Server en máquinas virtuales Linux.
- Describir las ventajas de ejecutar SQL Server en entornos de ejecución de contenedor, como Docker.

Si deseas realizar este módulo puedes iniciar en el [siguiente enlace.](https://docs.microsoft.com/es-es/learn/modules/introduction-sql-server-linux/?ns-enrollment-type=Collection&ns-enrollment-id=xgg5bxjg1owzm7)

## Hospedaje de una aplicación web

Azure App Service te permite crear y hospedar aplicaciones web en el lenguaje de programación que prefiera sin tener que administrar la infraestructura. Aprende a crear un sitio web mediante la plataforma de aplicaciones web hospedada en Azure App Service.

En este módulo de Microsoft Learn aprenderás a:

- Usar Azure Portal para crear una aplicación web de Azure App Service.
- Usar herramientas de desarrollo para crear el código para una aplicación web de inicio.
- Implementar el código en Azure App Service.

Para iniciar con este módulo puedes iniciar en el [siguiente enlace](https://docs.microsoft.com/es-es/learn/modules/host-a-web-app-with-azure-app-service/?ns-enrollment-type=Collection&ns-enrollment-id=xgg5bxjg1owzm7).

## Creación de lógica serverless con Azure Functions

Azure Functions permite a los desarrolladores hospedar lógica de negocio que se puede ejecutar sin administrar ni aprovisionar infraestructura. Podemos verlo como un pequeño pedazo de código que podemos ejecutar en cualquier momento de manera remota.

Si quieres aprender más sobre cómo crear e implementar este tipo de funciones te recomiendo tomar el siguiente módulo de Microsoft Learn en el cual aprenderás a:

- Decidir si la informática sin servidor es adecuada para las necesidades empresariales
- Crear una aplicación de función de Azure en Azure Portal
- Ejecutar una función mediante desencadenadores
- Supervisar y probar la función de Azure desde Azure Portal

Si quieres desarrollar este módulo puedes encontrarlo en el [siguiente enlace.](https://docs.microsoft.com/es-es/learn/modules/create-serverless-logic-with-azure-functions/?ns-enrollment-type=Collection&ns-enrollment-id=xgg5bxjg1owzm7)

Los dos métodos más comunes son Azure Logic Apps y Azure Functions

- **Azure Functions**
  Permite hospedar la lógica de negocios que se puede ejecutar sin aprovisionar infraestructura. Proporciona escalabilidad intrínseca y solo se cobra por los recursos usados. Se admiten los administradores de paquetes como NuGet y NPM.

### Ventajas

- Lógica sin estado
- Controladas por eventos
- Utilizarse en entornos de proceso tradicionales

### Desventajas

- Tiempo de ejecución
- Frecuencia de ejecución

![Preview](https://static.platzi.com/media/user_upload/azure-900-cloudfundamentals-1-cloud-computing-18c775db-ff4e-4395-851f-85af55b58ad2.jpg)

# 7. Seguir aprendiendo sobre la nube

## Certifícate en Azure

[![img](https://www.google.com/s2/favicons?domain=https://static.platzi.com/media/favicons/platzi_favicon.png)Microsoft Certifications | Microsoft Docs](https://docs.microsoft.com/es-mx/learn/certifications/)

### Domina la nube

La verdadera nube
¡Lo que aprendiste!

- Qué es la nube
- Sus tipos y formas
- Qué es Azure y sus características
- Servicios de Azure
- Diseñar una arquitectura de servicios
- SLA
- Administración de costos

¡Lo que puedes lograr!

- Certificarte
- Seguir algún rol de la nube
- Analizar el desarrollo de un sistema en la nube
- Tomar decisiones de negocio

## Contenido de apoyo: Sesiones en vivo Azure

### Certifícate en Microsoft Azure, últimos consejos
