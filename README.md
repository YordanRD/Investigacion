# Investigacion
Repositorio para el GitHub Pages para la investigacion del curso de Algoritmos y Estructuras de Datos 1, donde se investiga acerca del cloud computing.
***
## ¿Qué es Cloud Computing? 
De una manera simple, la computación en la nube (cloud computing) es una tecnología que permite acceso remoto a softwares, almacenamiento de archivos y procesamiento de datos por medio de Internet, siendo así, una alternativa a la ejecución en una computadora personal o servidor local. En el modelo de nube, no hay necesidad de instalar aplicaciones localmente en computadoras.

*** 

## ¿Cuándo surgió y quién desarrolló esta tecnología?
 
La expresión “Cloud Computing” surgió en 1997, en un seminario impartido por Ramnath Chellappa; sin embargo, este concepto ya estaba asociado a John Mccarthy, creador del lenguaje de programación LISP y pionero en la tecnología de Inteligencia Artificial, quien trabajó en el concepto de uso compartido del tiempo. Dicho concepto establecía la posibilidad de que dos o más usuarios utilizaran una computadora de forma simultánea, logrando así reducir los gastos, ya que que el usuario no pagaría más que por el uso de la tecnología.
Por otro lado, el físico Joseph Carl, otro científico trabajaba en un concepto que cambiaría el mundo: el Internet. Joseph trataba de hallar otras funciones para la computadora; así descubrió una forma de conectar personas, lo que condujo al intercambio de datos y a la comunicación a escala global. Así nació ARPANET, una red global de comunicación que hizo de la computación en la nube algo más que sólo un concepto..
Existen varias versiones sobre este tema: muchos dicen fue creado por Amazon, otros afirman que fue Google, incluso hay indicios de que fue AT&T el que inventó el concepto de nube, esto luego de que la revista Fio publicara la historia de Bill Atkinson y Andy Hertzfeld, dos ingenieros de Apple Macintosh, quienes  fundaron 1n 1990 la empresa General Magic y crearon Telescript, una plataforma de software licenciada desde 1994. Para entonces, el CEO de General Magic expresó que la nueva tecnología permitiría enviar mensajes de correo electrónico, hacer compras y controlar stocks, entre otras utilidades.

***

## Conceptos Basicos

***

### Virtualización
Puede definirse como  “Combinación de hardware y software que permite a un recurso físico funcionar como múltiples recursos lógicos.” (El Arte de virtualización, FLOSSystems S.L.); básicamente, es la reproducción virtual de un recurso tecnológico, sea un sistema operativo, plataforma de hardware, dispositivo de almacenamiento o cualquier otro recurso. Dentro de este concepto existen también diversos términos, siendo el más popular a nivel de usuario la virtualización de plataforma, que permite establecer múltiples “máquinas virtuales” sobre la misma “máquina física” (servicios como VirtualBox y VMWare Workstation nos ofrecen esta funcionalidad). Los Centros de Proceso de Datos (CPDs) actuales están mayoritariamente virtualizados y la tendencia es emplear:
Virtualización de plataforma para máquinas (con tecnologías como KVM, Xen y VMWare ESXI).
Virtualización a nivel de sistema operativo para crear los denominados contenedores (LXC , Docker y OpenVZ).
Virtualizar el almacenamiento y la redes (Software Defined Networking, SDN).

### Cloud Computing
Es un paradigma que permite ofrecer servicios de computación bajo demanda a través de una red, buscando usar la tecnología para implantar infraestructuras “invisibles” que permitan aplicar recursos tales como computación, almacenamiento, redes, aplicaciones, etc. en un servicio de uso pagado, sin inversiones iniciales. Con esto las organizaciones pueden externalizar parte de sus propios recursos a un proveedor que generalmente ofrece un modelo de pago por uso, o bien crear nubes privadas para no depender de un proveedor público.
La nube es por lo tanto una metáfora que abarca recursos virtuales y físicos alojados y ofrecidos por un determinado proveedor (Google, Amazon, Microsoft, ...), o creados de forma privada. Cada proveedor ofrece su servicios con un modelo de pago por uso, con el objetivo de ajustar el consumo de recursos a las necesidades de las aplicaciones y usuarios de forma eficiente y óptima, adaptando el consumo a la demanda.  
Tradicionalmente, las inversiones en hardware se quedan obsoletas rápidamente  y la demanda de recursos de cómputo puede variar mucho. Si hay un sobre-dimensionamiento, parte de los recursos no son aprovechados, implicando una inversión de hardware para ciertos intervalos de tiempo, mientras que con un sub-dimensionamiento, si hay picos de demanda que no se pueden atender, no se ofrece el servicio adecuadamente.

### Big Data

Este es un término que agrupa toda clase de técnicas de procesamiento de grandes volúmenes de datos, dejando de lado los análisis y herramientas clásicas. Este concepto engloba gran variedad de ideas y aproximaciones,todas el objetivo de extraer información valiosa de los datos, que pueda ser útil para decisiones y procesos de negocio (fuente: UAM).
Todos somos conscientes de que las grandes compañías (en todos los ámbitos) recopilan gran cantidad de información, cada vez mayor, que gracias a las nuevas capacidades de procesamiento es usada para analizar y extraer patrones  que permitan responder a  muchas preguntas e incluso predecir eventos, sienpre y cuando estos datos sean correctamente comprendidos.
Destacar que los IaaS ofrecen un entorno apto para desplegar rápidamente clusters con la capacidad de cómputo y almacenamiento requeridos para gestionar estas cantidades de datos y el software que los analiza.

***

## Modelos de despliegue.

***


### Nube pública
Las nubes públicas son propiedad de otros proveedores de servicios en la nube, que las administran y ofrecen sus recursos informáticos, como servidores y almacenamiento, a través de Internet. Microsoft Azure es un ejemplo de nube pública. Con una nube pública, todo el hardware, software y demás componentes de la infraestructura subyacente son propiedad del proveedor de servicios en la nube, que también los administra. Usted obtiene acceso a estos servicios y administra su cuenta a través de un explorador web.
 
### Nube privada
Una nube privada hace referencia a recursos informáticos en la nube que utiliza exclusivamente una empresa u organización. Una nube privada puede encontrarse físicamente en el centro de datos local de una compañía. Algunas compañías pagan también a proveedores de servicios externos para que hospeden su nube privada. Una nube privada es aquella en la que los servicios y la infraestructura se mantienen en una red privada.

### Nube híbrida
Las nubes híbridas combinan nubes públicas y privadas, enlazadas mediante tecnología que permite compartir datos y aplicaciones entre ellas. Al permitir que los datos y las aplicaciones se desplacen entre las nubes privadas y públicas, una nube híbrida aporta a su negocio mayor flexibilidad, más opciones de desarrollo y ayuda a optimizar la infraestructura, la seguridad y el cumplimiento existentes.

***

## Modelos de servicio

### Infraestructura como servicio (IaaS)
Es la categoría más básica de servicios informáticos en la nube. Con IaaS, se alquila infraestructura de TI (servidores, máquinas virtuales, almacenamiento, redes, sistemas operativos) a un proveedor de servicios en la nube y se paga por uso.

### Plataforma como servicio (PaaS)
Plataforma como servicio hace referencia a los servicios de informática en la nube que suministran un entorno a petición para desarrollar, probar, entregar y administrar aplicaciones de software. PaaS está diseñado para facilitar a los desarrolladores la creación rápida de aplicaciones web o móviles, sin necesidad de preocuparse por la configuración o administración de la infraestructura de servidores subyacente, el almacenamiento, la red y las bases de datos necesarias para el desarrollo.

### Software como servicio (SaaS)
Software como servicio es un método de entrega de aplicaciones a través de internet a petición y, normalmente, con una suscripción. Con SaaS, los proveedores de nube hospedan y administran las aplicaciones y la infraestructura subyacente, y se encargan del almacenamiento, como la aplicación de actualizaciones de software y revisiones de seguridad. Los usuarios se conectan a la aplicación a través de internet, normalmente con un explorador web en su teléfono, tableta o PC.

***

## Comparativa de los tres principales proveedores de cloud computing.

### Amazon Elastic Compute Cloud (EC2)
Amazon EC2 es un servicio web que brinda capacidad informática de tamaño ajustable en la nube, diseñado para facilitar a los usuarios recursos informáticos escalables y basados en web. Amazon EC2 reduce el tiempo necesario para obtener nuevas instancias de servidor, lo que permite escalar rápidamente la capacidad, ya sea aumentándola o reduciéndola, según sus necesidades. También cambia el modelo económico de la informática, al permitir pagar sólo por la capacidad realmente usada.

### Windows Azure
Windows Azure es una plataforma abierta y flexible que permite compilar, implementar y administrar aplicaciones rápidamente en una red global de centros de datos administrados por Microsoft, y es capaz de compilar aplicaciones en cualquier lenguaje, herramienta o marco, permitiendo además integrar sus aplicaciones de nube públicas con el entorno de TI existente.

### IBM SmartCloud
SmartCloud ofrece una gestión de cloud con el valor agregado que permite la elección y la automatización más allá del aprovisionamiento de máquinas virtuales. IBM SmartCloud Enterprise+ es un entorno Cloud seguro, totalmente administrado y listo para producción, diseñado para garantizar una alta performance y disponibilidad. Asimismo, ofrece completo control  de «governance», administración y gestión, permitiendo definir acuerdos de nivel de servicio para alinear las necesidades de negocio y los requisitos de uso.

![](https://github.com/YordanRD/Investigacion/blob/master/CuadroComparativo.JPG)
