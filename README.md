# Practica-Rogelio Hernández Pérez

# Ejercicio 1
### Git Bash
![Get](https://github.com/RogelioHernandezPerez/Practica/blob/main/git%20bash.png)
### Visual Code
![Get](https://github.com/RogelioHernandezPerez/Practica/blob/main/vs%20code.png)
# Ejercicio 2
Las siguientes preguntas están orientadas a la comprensión del protocolo HTTP. Son agnósticas al lenguaje de programación, la idea es comprender los conceptos del estándar:

	1 ¿Qué es un servidor HTTP?
  Es un programa informático que procesa una aplicación del lado del servidor.

	2 ¿Qué son los verbos HTTP?
 Son conjuntos  de métodos para indicar la acción de un recurso determinado. Alguno los que se utilizan para la creación de Restfull son:<br> -Get <br>
-Post<br>
-Put<br>
-Delete.

	3 ¿Qué es un request y un response en una comunicación HTTP?
   Request: es una petición que se hace desde el cliente. <br>
Response: el response se muestra en URL como la descripción de dicho recurso solicitado.
 
	
         ¿Qué son los headers?
Header se refiere a la información suplementaria que está al principio de un bloque de información, esta contiene información necesaria para el correcto tratamiento del bloque de información.
 
	4 ¿Qué es un queryString? (En el contexto de una url)
Se utiliza para hacer referencias a una interacción con una base de datos. Es la parte de la URL que contiene los datos que deben pasar a las aplicaciones web. 

	5 ¿Qué es el responseCode?
Los códigos de estado de respuesta HTTP indican si se ha completado satisfactoriamente una solicitud HTTP específica.

 	¿Qué significado tiene los posibles valores devueltos?
Respuestas informativas 100–199.  <br>
Respuestas satisfactorias 200–299. <br>
Redirecciones 300–399. <br>
Errores de los clientes 400–499. <br>
Errores de los servidores 500–599.
						

	6 ¿Cómo se envía la data en un Get y cómo en un POST? 
  En el GET la información codificada del usuario en el header del HTTP request, usando la propia URL, en este los datos son visibles, por lo que nunca se envía información sensible. <br>
  En el POST también se codifica la información, pero esta se envía a través del body del HTTP Request, por lo que no aparece en la URL.

	7 ¿Qué verbo http utiliza el navegador cuando accedemos a una página?
   Get porque es el que se utiliza para acceder a los sitios web.

      Explicar brevemente qué son las estructuras de datos JSON y XML dando
JSON:  Representan formas a base de objetos, un objeto es un conjunto desordenado de pares nombre/valor.ejemplo de estructuras posibles.
XML: Es siempre descriptivo y se compara con un árbol porque cuenta con elementos secundarios.  <br>
*JSON:*

{ 
"llave1": "valor1",
 "llave2": "valor2",
 "llave3": "valor3",
 "llave4": 7,
 "llave5": null,
 "favAmigos": ["Kolade", "Nithya", "Dammy", "Jack"],
 "favJugadores": {"uno": "Kante", "dos": "Hazard", "tres": "Didier"}
 }

*XML:*

<.Receptor>
	</DireccionReceptor>
		<.Direccion>1 Av Patria </Direccion >
		<.CodigoPostal>   45070      </CodigoPostal>
		<.Municipio> Zapopan </Municipio>
		<.País> México </País>
	<.DireccionReceptor>
<.Receptor>.
	  
	8 Explicar brevemente el estándar SOAP
Es un protocolo estándar que se creó para permitir la comunicación entre las aplicaciones diseñadas con diferentes lenguajes y plataformas, ofrecen normas integradas que pueden ser de utilidad en el sector empresarial.

	10 Explicar brevemente el estándar REST Full
Es un servicio que funciona para compartir información en un sistema de doble vía, consulta y respuesta (Request=> Response).

       11 ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?
Son la parte central de los HTTP requests y responses. Transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc. El Key Content-type le dice al cliente que tipo de contenido será retornado.

# Ejercicio 3

## Get1
![Get](https://github.com/RogelioHernandezPerez/Practica/blob/main/Get%201.png)

## Post
![Get](https://github.com/RogelioHernandezPerez/Practica/blob/main/Post%201.png)

## Get final
![Get](https://github.com/RogelioHernandezPerez/Practica/blob/main/get%202.png)

	¿Qué diferencias se observan?
En el primero me muestra los datos existentes en la base al momento de la consulta y en el segundo GET se agregan los datos insertados mediante el POST.


# Ejercicio 4
Perfil personal [Trailhead](https://trailblazer.me/id/rhernandezperez)
![GET](https://github.com/RogelioHernandezPerez/Practica/blob/main/Perf%C3%ADl%20p%C3%BAblico.png)

# Ejercicio 5
|Objeto		| Definición 					| 
|---------------|-----------------------------------------------|
|Lead           |Registro de posible cliente, el cual se encuentra en el proceso de evaluación. |			 
|Account	|Registro de un cliente, este puede ser de una empresa o persona individual. |
|Contact	|Es el registro que se lleva a cambio de las personas que mantienen relación a dicha cuenta. |
|Opportunity	|El proceso de ventas. |
|Product	|Catálogo de productos o servicios que ofrece la empresa. |
|PriceBook	|Lista de precios de los productos y servicios. |
|Quote		|Es la cotización que se envía a los clientes. |
|Asset		|Producto comprado o instalado por el cliente. |
|Case		|Registro de una situación o problema de un cliente. Un caso se puede asociar a un lead, a una cuenta a un contacto y a una oportunidad. |
|Article	|Documentos de información o procesos. |

## Diagrama UML
![Diagrama UML](https://github.com/RogelioHernandezPerez/Practica/blob/main/Relacion%20de%20objetos.jpg)

# Ejercicio 6

### Soluciones de Salesforce

     1.¿Qué es Salesforce? 
 Es una plataforma CRM, es una solución de gestión de relaciones con clientes.
   
     2.¿Qué es Sales Cloud?
 Es un módulo de Salesforce que facilita la gestión de las relaciones con los clientes y la colaboración entre equipos comerciales.

     3.¿Qué es Service Cloud?
 Es la aplicación para atención al cliente de Salesforce.
  
      4.¿Qué es Health Cloud?
 Es una plataforma que permite gestionar de forma integral la relación médico-paciente.
   
      5.¿Qué es Marketing Cloud?
 Es una plataforma de marketing que contiene múltiples herramientas diseñadas para gestionar de manera eficiente la interacción de la marca con sus clientes (y potenciales) a través de diferentes canales.

### Funcionalidades de Salesforce

     1 ¿Qué es un RecordType?
Es la herramienta que determina que proceso comercial, los diseños de página y los valores de lista de selección a los que los usuarios tienen acceso.
   
     2 ¿Qué es un ReportType? 
	
 Es una plantilla que define los objetos y campos que estarán disponibles en el reporte que se creará.
   
     3 ¿Qué es un Page Layout?
Se encarga de controlar el diseño y organización de los botones, campos,  control, visualforce y listas relacionadas en las páginas de registro de objetos.

     4 ¿Qué es un Compact Layout?
Muestra los campos clave de un registro en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.

     5 ¿Qué es un Perfil?
Los perfiles se encargan de controlar al acceso a los datos y que pueden hacer en la aplicación de los usuarios.

     6 ¿Qué es un Rol?
Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización.

     7 ¿Qué es un Validation Rule?
Se encargan de verificar que los datos que el usuario ingresa en el registro cumple con los estándares solicitados antes de que el usuario pueda guardar el registro.

     8 ¿Qué diferencia hay entre una relación Master Detail y Lookup?
Master detail se basa en una clase principal (padre) y una secundaria (hijo), mientras que lookup se crea una relación entre dos objetos iguales.

     9 ¿Qué es un Sandbox?
Es una herramienta para copiar los metadatos desde la organización de producción a una de prueba.

     10 ¿Qué es un ChangeSet?
   
Es una función que contiene solo las modificaciones y modifica la metadata.

     11 ¿Para qué sirve el import Wizard de Salesforce?
   
Funciona para importar cualquier dato estándar de Salesforce como objetos, cuentas, contactos, etc, fácilmente.

     12 ¿Para qué sirve la funcionalidad Web to Lead?
	      
Para recopilar información de los sitios web de la empresa.

     13 ¿Para qué sirve la funcionalidad Web to Case?

Para Recopilar solicitudes de atención al cliente directamente desde el sitio web de su empresa.

     14 ¿Para qué sirve la funcionalidad Omnichannel?
   
Para conectar a diferentes redes simultáneamente y en tiempo integral.

     15 ¿Para qué sirve la funcionalidad Chatter?
   
Para mantenerse conectado con sus constituyentes y en toda la organización internamente.

### Conceptos generales

   	1 ¿Qué significa SaaS? 
Software As A Service   
   
   	¿Salesforce es Saas? 
	
Si.
   
   	2 ¿Qué significa que una solución sea Cloud?
Que se puede conseguir el servidor de la nube de una página web.

   	3 ¿Qué significa que una solución sea On-Premise?
Qu se puede ejecutar desde el operador local del dispositivo y la empresa de hace cargo de la seguridad e disponibilidad.
	
   	4 ¿Qué es un pipeline de ventas?
Es el mapa de las actividades diarias del proceso de ventas en el trabajo de un representante comercial.
	
   	5 ¿Qué es un funnel de ventas?
Es una representación del ciclo o procesos de venta.
	
  	6 ¿Qué significa Customer Experience? 
Es como percibe racional, física, emocional y/o psicológicamente cualquier parte de una empresa un cliente.
	
  	7 ¿Qué significa omnicanalidad?
Es el uso de múltiples canales de comunicación para tener una mejor interacción.
	
  	8 ¿Qué significa que un negocio sea B2B?
Que es de empresa a empresa no al consumidor directamente. 

	¿Qué significa que un negocio sea B2C?
Que es de empresa a consumidor directo.

  	9 ¿Qué es un KPI?
Es un indicador de desempeño o rendimiento en un proceso.
	
  	10 ¿Qué es una API y en qué se diferencia de una Rest API? 
Es una interfaz de programación de aplicaciones, Rest api funciona con la arquitectura rest y permite la interacción con servicios web de restful.
	
  	11 ¿Qué es un Proceso Batch?
Es la ejecución de un programa sin el control o supervisión directa del usuario.
	
  	12 ¿Qué es Kanban?
Es un método visual que se utiliza para controlar las tareas a través de su división por fases hasta su finalización.
	
       13 ¿Qué es un ERP? 
Sistema de planificación de recursos empresariales que manejan negocios asociados a las operaciones de producción y de los aspectos de distribución de una compañía en la producción de bienes o servicios.
	
	¿Salesforce es un ERP?
Si, porque es un sofware que permite hacer de forma automatica prácticas de negocio.

# Ejercicio 7

### Importación de cuentas
![Get](https://github.com/RogelioHernandezPerez/Practica/blob/main/cuentas%201.png)
### Importación de cuentas 2
![Get](https://github.com/RogelioHernandezPerez/Practica/blob/main/cuentas%202.png)
### Archivo de cuentas importadas
https://github.com/RogelioHernandezPerez/Practica/blob/main/dataloader_succes_account.csv
