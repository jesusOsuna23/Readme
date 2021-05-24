# Ejercicio 1
### Git Bash
![Get](https://github.com/jesusOsuna23/Readme/blob/main/GIT%20Bash.png)
### Visual Code
![Get](https://github.com/jesusOsuna23/Readme/blob/main/Visual%20code.png)
# Ejercicio 2
1.	**¿Qué es un servidor HTTP?**
Es el servidor online que se encarga de conectar al usuario con la aplicación.
2.	**¿Qué son los verbos HTTP? Mencionar los más conocidos**
Son las instrucciones de qué hacer con los datos del url.
Get, Put, Delete, Post
3.	**¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?**
Request es cuando la página le solicita la información al servidor y response es cuando responde este.
Los headers son los “separadores” del código, por ejemplo, para distinguir head de body.
4.	**¿Qué es un queryString? (En el contexto de una url)**
Es la interacción de la página con la base de datos para pasar los datos a la pagina web.
5.	**¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?**
Es la señal que devuelve el sistema para saber si se realizó el proceso correctamente o no, los valores devueltos pueden ser informativos, satisfactorios, redirecciones y errores.
6.	**¿Cómo se envía data en un Get y cómo en un POST?**
Get lo envía por medio del url directo y post lo hace con procesos secundarios ocultos del usuario.
7.	**¿Qué verbo http utiliza el navegador cuando accedemos a una página?**
connect
8.	**Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.**
JSON se basa en JavaScript por una serie de pares de nombres, valores y el uso de llaves y XML se basa en textos y etiquetas parecido a HTML.

**JSON:**
```
{
“tipo” “class”
“Nombre:” “persona”
“Operaciones” (“Consultar”,” Insertar”,” Actualizar”)
“Vistas” (“PDF”, “XML”, “cargo”)
}
```
**XML:**
```
<Receptor>
	<DireccionReceptor>
		<Direccion>1 Avenida 9-59 Zona 1 </Direccion >
		<CodigoPostal> 01001 >/CodigoPostal>
		<Municipio> Zapopan </Municipio>
		<País> México </País>
	<DireccionReceptor>
<Receptor>
```

9.	**Explicar brevemente el estándar SOAP**
Como dos procesos diferentes se comunican mediante la transmisión de datos en XML
10.	**Explicar brevemente el estándar REST Full**
Es un sistema bidireccional de request y response.
11.	**¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?**
Los headers transmiten la información acerca del navegador del cliente, de la página solicitada, del servidor, etc., y el key content se usa para informar que tipo de dato se retorna.

# Ejercicio 3

## Get
![Get](https://github.com/jesusOsuna23/Readme/blob/main/get.png)

## Post
![Get](https://github.com/jesusOsuna23/Readme/blob/main/Post.png)

## Get final
![Get](https://github.com/jesusOsuna23/Readme/blob/main/get%20final.png)

**¿Qué diferencias se observan?**
Se le agregaron 5 líneas de código al url final, las mismas 5 de código que se le agregaron al body anteriormente.


# Ejercicio 4
Perfil personal trailhead [Trailhead](https://trailblazer.me/id/josuna)

# Ejercicio 5
|Objeto		| Definicion 					| datos         |
|---------------|-----------------------------------------------|---------------|
|Lead           |Es un cliente potencial.			|String		|
|Account	|Una cuenta individual de afin a la empresa.	|String		|
|Contact	|Es la persona que esta relacionada con la cuenta.| String, int		|
|Opportunity	|Es la oportunidad de una venta o un trato.	| String, Currency		|
|Product	|Lo que la empresa puede ofrecer al cliente.	|String		|
|PriceBook	|Es una lista de los productos y precios ofrecidos.| string, currency		|
|Quote		|Son los precios propuestos en las cotizaciones.| String, Currency		|
|Asset		|Es un producto que el cliente compro o instalo.|int, String		|
|Case		|Represente un problema o inconveniente del cliente.| String		|
|Article	|Son documentos de informacion o de los procesos.|String		|

## Diagrama UML
![Diagrama UML](https://github.com/jesusOsuna23/Readme/blob/main/Ejercicio%205.jpg)

# Ejercicio 7

### Soluciones de Salesforce
- **¿Qué es Salesforce?** Es una empresa americana de que hace software a gran escala tipo google.
- **¿Qué es Sales Cloud?** Es una aplicacion que gestiona las relaciones de salesforce mediante la nube.
- **¿Qué es Service Cloud?** Son los servicios que se realizan en la nube.
- **¿Qué es Health Cloud?** En un software que permite ofrecer informacion medica del paciente a las entidades medicas.
- **¿Qué es Marketing Cloud?** Software y servicios de análisis y automatización de marketing digital. 

### Funcionalidades de Salesforce
- **¿Qué es un RecordType?**  Es una herramienta que determina los procesos comerciales, los diseños de página y los valores de lista de selección a los que los usuarios tienen acceso.
- **¿Qué es un ReportType?** Es una plantilla que define los objetos y campos que estaran disponibles en el reporte que se creara.
- **¿Qué es un Page Layout?**  Se encarga de controlar el diseño y organizacion de los botones, campos, s control, visual-force and listas relacionadas enlas paginas de registro de objetos.
- **¿Qué es un Compact Layout?** Muestra los campos clave de un registro en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.
- **¿Qué es un Perfil?** Los perfiles se encargan de controlar al acceso a los datos y que pueden hacer en la aplicacion de los usuarios.
- **¿Qué es un Rol?** Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización.
- **¿Qué es un Validation Rule?** Se encragan de verificar que los datos que el usuario ingresa en el registro cumple con los estándares solicitados antes de que el usuario pueda guardar el registro.
- **¿Qué diferencia hay entre una relación Master Detail y Lookup?** Master detail se basa en una clase principal(padre) y una secundaria(hijo), mientras que lookup se crea una relacion entre dos objetos iguales.
- **¿Qué es un Sandbox?** Es una herramienta para copiar la metadata desde la organizacion de produccion a una de pruebas.
- **¿Que es un ChangeSet?** Es una funcion que contiene solo las modificaciones y modifica la metadata.
- **¿Para qué sirve el import Wizard de Salesforce?** Funciona para importar cualquier dato estandar de salesforce como objetos, cuentas, contactos, etc, facilmente.
- **¿Para qué sirve la funcionalidad Web to Lead?** Para recopilar informacion de los sitios web de la empresa.
- **¿Para qué sirve la funcionalidad Web to Case?** Para Recopilar solicitudes de atención al cliente directamente desde el sitio web de su empresa.
- **¿Para qué sirve la funcionalidad Omnichannel?** Para conectar a diferentes redes simultaneamente y en tiempo integral.
- **¿Para qué sirve la funcionalidad Chatter?** Para mantenerse conectado con sus constituyentes y en toda la organización internamente.

### Conceptos generales
- **¿Qué significa SaaS? ¿Salesforce es Saas?** Software as a Service, Si.
- **¿Que significa que una solución sea Cloud?** Que se encuentra el servio en la nube.
- **¿Que significa que una solución sea On-Premise?** Que se encuentra en la computadora local.
- **¿Que es un pipeline de ventas?** Es el mapa de las actividades diarias que del proceso de ventas en el trabajo de un representante comercial
- **¿Que es un funnel de ventas?** Es una representacion del ciclo o procesos de venta.
- **¿Qué significa Customer Experience?** Es como percibe racional, física, emocional y/o psicológicamente cualquier parte de una empresa un cliente.
- **¿Qué significa omnicanalidad?** Es el uso de multiples canales de comunicacion para tener una mjeor comunicacion.
- **¿Qué significa que un negocio sea B2B?** Que es de empresa a empresa no al consumidor directamente.
- **¿Qué significa que un negocio sea B2C?** Que es de empresa a consumidor directo.
- **¿Qué es un KPI?** Es un indicador de desempeño o rendimineto en un proceso.
- **¿Qué es una API y en qué se diferencia de una Rest API?** Es una interfaz de programacion de aplicaciones, Rest api funciona con la qrquitectura rest y permite la interraccion con servicios web de restful.
- **¿Qué es un Proceso Batch?** Es la ejecución de un programa sin el control o supervisión directa del usuario.
- **¿Qué es Kanban?** Es un sistema que controla armonicamente la fabricación de los productos necesarios en la cantidad y tiempo necesarios en cada uno de los procesos que tienen lugar tanto en el interior de la fábrica o una compañia.
- **¿Qué es un ERP? ¿Salesforce es un ERP?** Son los sistemas gerenciales que integran y manejan negocios asociados a las operaciones de producción y de los aspectos de distribución de una compañía en la producción de bienes o servicios, Si.


