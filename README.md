
1. ## DOCKER

3. ### Índice

    - [Introducción](https://www.docker.com/)
    - [Creación de Dockers](https://www.hostinger.mx/tutoriales/como-crear-contenedor-docker)
    - [Orquestación de Dockers](https://revistaecys.github.io/16Edicion/08_rcutz.html)
    - [Razones por la cual usar Docker](https://aws.amazon.com/es/docker/)
    - [Administración de contenedores y clusters de Docker](https://learn.microsoft.com/es-es/dotnet/architecture/containerized-lifecycle/run-manage-monitor-docker-environments/manage-production-docker-environments)

#### Introducción: ¿Qué es? 

Es un proyecto de codigo abierto para automatizar la implementación de aplicaciones , Docker fue liderado por Salomon Hykes , como un proyecto interno dentro de la empresa dotCloud.Docker     fue lanzado como codigo abierto en Marzo del 2013. Docker facilita el proceso de creación y diseño de contenedores,el envio de imagenes y creación de versiones de imagen. 
Los contenedores se usan como máquinas virtuales , pero a diferencia de las máquinas virtuales suelen utilizarse para levantar máquinas independientes con sistemas operativos muy ligeros.
Realmente un contenedor de docker es una imagen de docker instanciada o en ejecución.

![Logo de Docker](https://d1.awsstatic.com/acs/characters/Logos/Docker-Logo_Horizontel_279x131.b8a5c41e56b77706656d61080f6a0217a3ba356d.png "Logo de Docker")

#### Creación de Dockers

Los contenedores Docker ejecutan instancias de imágenes Docker. Ejecutar una imagen crea un contenedor Docker. Las imágenes proporcionan una plantilla que se puede utilizar para la creación de contenedores. Estas contienen la información que se requiere para crear contenedores. Las imágenes pueden almacenarse localmente o remotamente.

Para instalar Docker, dependiendo de qué sistema operativo utilices, solo hay que ir a su web de documentación oficial y seguir las instrucciones: https://docs.docker.com/install/#supported-platforms
     
#### Orquestación

Las herramientas de orquestación permiten manejar y gestionar los contenedores y recursos en aplicaciones y servicios. Dependiendo de la plataforma de contenedores que se utiliza existen herramientas de orquestación que ofrecen o no compatibilidad. Las herramientas de orquestación están enfocados a manejar escalabilidad y monitoreo de los contenedores que conforman una aplicación. Existen diferentes tipos de orquestación mostrados a continuación:
  
  _Kubernetes_

Es una herramienta de código abierto bastante popular para la orquestación de contenedores, permite desplegar y manejar aplicaciones que están conformadas por múltiples contenedores, ayuda a administrar la aplicación contenerizada de diferentes tipos, física, virtual y ambientes de nube. Kubernetes es usualmente utilizada con Docker, pero puede trabajar con cualquier sistema de contenedores que se apegue a los estándares de imágenes de contenedores. 

_Docker Swarm_

Es la herramienta de orquestación de contenedores en clústeres que proporciona Docker, permite desplegar y orquestar contenedores en número grande de anfitriones que corren el motor de Docker. Se hace referencia a esta herramienta que proporciona Docker como el modo Swarm. 

_AWS ECS_

Llamada “Amazon Elastic Container Service”, una herramienta para el manejo de contenedores alta mente escalable y rápida, es provista por Amazon para correr contenedores en clúster de máquinas virtuales que tienen el motor de Docker preinstalado. 
#### Razones por la cual usar Docker

_Las principales razones para usar docker es la siguiente:_

1.**Envia el software más rápido:** La frecuencia media de envío de software de los usuarios de Docker es siete veces superior a la de aquellos que no lo usan.

2.**Estandariza las operaciones:** Las aplicaciones con contenedores facilitan la implementación, la identificación de problemas y el retorno a una fase anterior para remediarlos.

3.**Transfiere de manera sencilla:** Las aplicaciones basadas en Docker pueden transferirse a la perfección desde equipos de desarrollo locales a implementaciones de producción en AWS.

4.**Ahorra dinero:** Los contenedores de Docker facilitan la ejecución de más código en cada servidor, mejorando su uso y ahorrándole dinero.



         
| Herramientas de administracion | Descripción  |  orquestadores relacionados |
| --------- | --------- | --------- |
| Azure Monitor para contenedores| Herramienta de administración de Kubernetes dedicada a Azure. | Azure Kubernetes Services (AKS)|
| Interfaz de usuario web de Kubernetes (panel) | Herramienta de administración de Kubernetes que puede supervisar y administrar un clúster local de Kubernetes.| Azure Kubernetes Service |
| Azure Portal para Service Fabric Azure Service Fabric Explorer| Versión de escritorio y en línea para administrar clústeres de Service Fabric en Azure | Azure Service Fabric|
| Supervisión de contenedores (Azure Monitor)| Administración de contenedores general y solución de supervisión.| Azure Service Fabric, Azure kubernetes Service|




