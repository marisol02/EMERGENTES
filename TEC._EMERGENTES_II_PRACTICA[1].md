### <center> UNIVERSIDAD PÚBLICA DE EL ALTO</center>

***Carrera:*** Ingenieria de Sistemas

***Materia:*** Tecnologías emergentes II

***Docente:*** Lic. Mario Torrez C.

***Estudiante:*** Marisol Hilari Mamani 	***C.I.:*** 12450268LP

### <center> SISTEMAS EMPRESARIALES </center>

>***1.Explique que son los sistemas empresariales***

<p> El sistema empresarial constituye el conjunto de recursos de la empresa que sirven como soporte para el proceso básico de captación, transformación y comunicación de la información. </p>
<p> Un sistema de información debe ser eficaz y eficiente. Es eficaz si facilita la información necesaria, y es eficiente si lo realiza con los menores recursos posibles. </p>

>***2.Describa cuales son las caracteristicas mas importantes de una aplicacion empresarial***

**Flexible y escalable.-** Para que crezca según las necesidades de la empresa. Es decir, se trata de que el software sea capaz de adaptarse a las funciones y necesidades que vayan surgiendo en la organización. 

**Ágil y multidispositivo.-** Los usuarios deben poder acceder a los datos desde cualquier lugar de forma segura y fiable. 

**Sencillo.-** Para no perder tiempo con programas informaticos complicados. Lo ideal es que las herramientas sean muy intuitivas y fáciles de usar. Es importante también contar con un buen soporte por si surge cualquier tipo de problema.

>***3.Investigue y proponga cinco instituciones que requeririan aplicaciones de mision critica.***

- ASFI
- INSTITUCIONES BANCARIAS
- SEGIP 
- ATT 
- RECINTOS POLICIALES COMO FELCC
- LA OEP 
- MINISTERIO DE JUSTICIA Y TRANSPARENCIA INSTITUCIONAL

Estas instituciones manejan informaciones relevantes para el Estado y también personales. Son datos que no se los puede manejar a riendas sueltas
>***4.Explique cuales son las diferencias entre la escalabilidad horizontal y escalabilidad vertical***

***Escalabilidad horizontal.-*** Se refiere a aumentar el número de componentes. Un sistema escala horizontalmente si al agregar más nodos al mismo, el rendimiento de éste mejora. Por ejemplo, al añadir una computadora nueva a un sistema que balancee la carga entre la antigua y la nueva puede mejorar el rendimiento de todo el sistema.

 La escalabilidad horizontal consiste en potenciar el rendimiento del sistema desde un aspecto de mejora global, a diferencia de aumentar la potencia de una única parte del mismo. Este tipo de escalabilidad se basa en la modularidad de su funcionalidad. Por ello suele estar conformado por una agrupación de equipos que dan soporte a la funcionalidad completa. Normalmente, en una escalabilidad horizontal se añaden equipos para dar mas potencia a la red de trabajo.

***Escalabilidad vertical.-*** Se refiere a actualizaciones o modernización de componentes existentes. Un sistema escala verticalmente o hacia arriba, cuando al añadir más recursos a un nodo particular del sistema, este mejora en conjunto. Por ejemplo, añadir memoria o un disco duro más rápido a una computadora puede mejorar el rendimiento del sistema global.

>***5.Qué es un servidor web y que es un servidor de aplicación***

***Un servidor Web*** es un programa que utiliza el protocolo de transferencia de hiper texto, HTTP (Hypertext Transfer Protocol), para servir los archivos que forman páginas Web a los usuarios, en respuesta a sus solicitudes, que son reenviados por los clientes HTTP de sus computadoras. Las computadoras y los dispositivos dedicados también pueden denominarse servidores Web.

El proceso es un ejemplo del modelo cliente/servidor. Todos los equipos que alojan sitios Web deben tener programas de servidor Web. Los principales servidores Web incluyen Apache (el servidor Web más ampliamente instalado), Internet Information Server (IIS) de Microsoft y nginx (que se pronuncia engine X) de NGNIX. Otros servidores Web incluyen el servidor NetWare de Novell, el servidor Web de Google (GWS) y la familia de servidores Domino de IBM.

Los servidores Web a menudo forman parte de un paquete más amplio de programas relacionados con internet e intranet para servir correo electrónico, descargar solicitudes de archivos de protocolo de transferencia de archivos (FTP) y crear y publicar páginas Web.

***Un servidor de aplicaciones*** es un programa de servidor en un equipo en una red distribuida que proporciona la lógica de negocio para un programa de aplicación. El servidor de aplicaciones se ve frecuentemente como parte de una aplicación de tres niveles, que consta de un servidor gráfico de interfaz de usuario (GUI), un servidor de aplicaciones (lógica empresarial) y un servidor de bases de datos y transacciones. De manera más descriptiva, se puede visualizar como la división de una aplicación en:

1. Una interfaz gráfica de usuario de primer nivel, de front-end, basada en el navegador web, normalmente en un equipo de cómputo personal o una estación de trabajo.

2. Una aplicación de lógica de negocio de nivel medio o conjunto de aplicaciones, posiblemente en una red de área local o un servidor de intranet.

3. Un servidor de back-end, base de datos y transacciones de tercer nivel, a veces en un mainframe o servidor grande.

>***6.Con un gráfico explique com funciona el protocolo HTTP***

![](http://img.youtube.com/vi/tN9yBV-B8Hw/0.jpg)

>***7.Explique los elementos importantes de REQUEST en HTTP***

**HTTP Request Structure from Client**

Un simple mensaje de request de un cliente tiene los siguientes componentes:

1. Una línea de request para obtener el recurso, por ejemplo un request con el método **GET** /content/page1.html está requiriendo el recurso llamado /content/page1.html del servidor

2. Encabezados. Indican cosas como el lenguaje, codificación, tipo de datos **(XML,JSON, etc).** (Por ejemplo– Accept-Language: EN).

3. Una línea vacía.

4. Un cuerpo del mensaje que es opcional. Entre aplicaciones esta es la parte mas importante. Por ejemplo, yo puedo enviar un XML o un JSON  a otra máquina, y el servidor web interpretara la información que yo le mando.

Todas las líneas terminan con un retorno de carro y nueva línea. La línea vacía sólo contiene el retorno de carro y la nueva línea sin espacios.

>***8.Explique los elementos importantes de RESPONSE en HTTP***

**HTTP Response Structure from Web Server**

Un simple response del servidor web contiene lo siguiente:

1. HTTP Status Code (Por ejemplo HTTP/1.1 301 Movido Permanentemente, significa que el recurso requerido fue movido permanentemente y redirigido a otro recurso).

2. Encabezados. Igual que en el request, describen el contenido del response (Example – Content-Type: html)

3. Una línea vacía.

4. Un cuerpo de mensaje, que es opcional. Cuando trabajamos con aplicaciones, aquí puede venir la respuesta en XML u otro formato. Cuando es una página del navegador, contiene el código HTML que forma nuestra página.

Todas las líneas terminan con un retorno de carro y nueva línea. La línea vacía sólo contiene el retorno de carro y la nueva línea sin espacios.

No hay mayor ciencia en la comunicación bajo el protocolo HTTP. Pero es poderoso y flexible por que permite desde visualizar páginas web , hasta intercambiar datos entre aplicaciones.

>***9.Describa con un gráfico la arquitectura Java EE***

![](https://image.slidesharecdn.com/jatunandjavaee-110905104600-phpapp02/95/desarrollo-de-aplicaciones-empresariales-con-java-ee-4-728.jpg?cb=1316098712)

>***10.Explique cuales son los contenedores, componentes y  servicios de Java EE.***

***LOS PRINCIPALES COMPONENTES DE JAVA EE SON:***

**1. COMPONENTES DE NEGOCIO:** Resuelven satisfacen las Necesidades de la ONU en particular Dominio de Negocio Como la banca, venta al por menor o La financiación this un cargamento de grano de las Naciones Unidas de la empresa Que se ejecutan en la capa de Negocio.

**2. ARQUITECTURA DE LOS COMPONENTES JAVABEANS** El servidor y el cliente pueden incluir componentes JavaBeans para administrar el flujo de datos entre una aplicación cliente o un applet y componentes que se ejecutan en el servidor JEE o entre componentes de servidor y BD.

**3. Las Aplicaciones cliente y los applets **hijo Componentes Que se ejecutan en el cliente. Java Servlet, hijo JavaServerFaces y JavaServerPages Componentes Web Que se ejecutan en el Servidor. Enterprise JavaBeans (EJB) hijo Componentes de Negocio Que se ejecutan en el Servidor.

**4. COMPONENTES:** Una aplicación Java EE esta creada de componentes. Un componente es una unidad autónoma de software funcional que se ensambla en una aplicación Java EE con sus clases y archivos relacionados y que se comunica con otros componentes.

**5. JAVA EE:** Es una colección de especificaciones que definen una infraestructura para desarrollar aplicaciones distribuidas multicapa.

***TIPOS DE CONTENEDORES Y SERVICIOS***

**Java EE Server:** La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.

**Contenedor EJB:** Maneja la ejecución de los enterprise beans.

**Contenedor Web:** Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.

**Contenedor de aplicación cliente:** Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.

**Contenedor Applet:** Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.

>***11.Investique los metodos mas utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse***

***Métodos de HttpServlet***

public abstract class HttpServlet extends GenericServlet: Es la clase de la cual se debe extender para crear un servlet HTTP. De la clase que extiende obtiene los métodos ya definidos además de los cuales define:

1. doGet(HttpServletRequest req, HttpServletResponse resp): Es el método llamado para procesar información que haya sido enviado con el método GET. Este método es llamado concurrentemente para cada cliente por lo que hay que estar atento por posibles variables compartidas que causen problemas.

2. doPost(HttpServletRequest req, HttpServletResponse resp): Ídem al anterior pero para el método POST, en general se implementa sólo un método y el otro lo referencia

***Métodos de HttpServletRequest***

public abstract interface HttpServletRequest extends ServletRequest: Permite obtener del cliente la información que es dependiente del protocolo, en este caso HTTP. Entre sus métodos están:

**1. getHeader(String name):** Permite obtener el valor de los Headers de HTTP con que fue llamado el servlet.

**2. getCookies():** Retorna un arreglo que contiene todas las cookies que el cliente envía al servlet.

**3. getSession():** Retorna la sesión en la cual se encuentra el cliente.

***Métodos de HttpServletResponse***

public abstract interface HttpServletResponse extends ServletResponse: Permite enviar al cliente respuestas específicas del protocolo HTTP.

**1. addCookie(Cookie cookie):** Para definir nuevas cookies en el cliente.

**2. setHeader(String name, String value):** Para definir un header HTTP a enviar al cliente.

**3. sendRedirect(String location):** Envía un mensaje al cliente para redireccionar la respuesta a la dirección señalada.

