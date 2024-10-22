> # Responsabilidad compartida

El modelo de responsabilidad compartida propone que en el momento en que establecemos un servicio web, tenemos la responsabilidad de administrar y velar por la integridad de ciertos servicios.
Esta responsabilida varia dependiendo del tipo de modelo que adoptemos para desarrollar nuestro servicio web. Hay tres modelos principales para esto:

>- ## IaaS(infrastructure as a Service):
En este enfoque se nos brinda la infraestructura para implementar nuestro servicio web, por lo mismo, nosotros somos responsables de manejar aspectos como la seguridad, integridad de datos, etc...
Dado a que solamente buscamos una mejor infraestructura para el desarrollo de nuestro servicio web, el proveedor tiene únicamente la responsabilidad de mantener continuamente en condiciónes optimas la insfrastestructura que solicitamos.

>- ## PaaS (Platform as a Service):
En este enfoque se nos brinda un servicio hibrido en el cual hay aspectos los cuales el proveedor y el usuario comparten responsabilidad en la implemetación de un servicio. Algunos de estos aspectos pueden ser el control de las aplicaciones, directorio e identidad de la infraestructura y el control de la red. Ademas contamos con las mismas responsabilidades como la seguridad, integridad de datos, etc...
Este servicio se centra en presentarnos una forma de implementar servicios web de forma más sencilla sin perder tanto control.


>- ## SaaS (Software as a Service):
Este enfoque se centra en brindar la mayor cantidad de facilidad al usuario al momento de desarrollar su servicio web, se encarga de aspectos como el sistema operativo, control de red, control de infraestructura y otras facilidades que permiten al usuario centrarse en mayor medida en el desarollo de su servicio.
Aunque la identida y directorio de la infraestructura sigue siendo una responsabilidad compartida entre el proveedor y el usuario, facilita en gran medida la implementacion de servicios web.

When using a cloud provider, you’ll always be responsible for:

The information and data stored in the cloud
Devices that are allowed to connect to your cloud (cell phones, computers, and so on)
The accounts and identities of the people, services, and devices within your organization
The cloud provider is always responsible for:

The physical datacenter
The physical network
The physical hosts
Your service model will determine responsibility for things like:

Operating systems
Network controls
Applications
Identity and infrastructure
