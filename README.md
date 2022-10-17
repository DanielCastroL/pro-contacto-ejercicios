
` $ npm install `

# Evaluación Práctica 123
<br>

# Ejercicio 1

![](Colocar imagenes)

# Ejercicio 2

***1.	¿Qué es un servidor HTTP?***<br>
Es una pieza de software que comprende las direcciones web y los protocolos de los navegadores, accediendo a sitios web por medio de los nombres de dominio.

***2.	¿Qué son los verbos HTTP?*** *Mencionar los más conocidos*<br>
Son métodos de petición que indican una acción que se desea realizar para un recurso determinado. Los más conocidos son: GET, POST, PUT, DELETE, PATCH, entre otros.

***3.	¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?***<br>
- **Request** es el mensaje con una petición o solicitud que es enviada desde una computadora o cliente a otra computadora o servidor.
**Response** es el mensaje de respuesta que da la segunda computadora o servidor, solicitado por la primera computadora o cliente.<br>
- Los **Headers** (o cabeceras) es información que esta constituida por metadatos, que permite enviar información adicional en los request/response.

***4.	¿Qué es un queryString?*** *(En el contexto de una url)*<br>
Son una serie de parametros o datos que se incluyen en las URL y hacen referencia a una interacción con la base de datos.

***5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?***<br>
Son diferentes códigos que indican el estado respuesta de una solicitud HTTP. Las respuestas se dividen en cinco categorías.
- Informativas (100-199)
- Stisfactorias (200-299)
- Redirecciones(300-399)
- Errores de clientes (400-499)
- Errores de servidores (500-599)

***6.	¿Cómo se envía la data en un Get y cómo en un POST?***<br>
Con **GET**, los datos que se envíen al servidor se encontrarán situados en el mismo URL. por lo que podrán ser visualizados.
Con **POST**, los datos son introducidos en la solicitud HTTP para el servidor. Por lo queno podrán ser visualizados por el usuario.

***7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?***<br>
Se utiliza **GET**, debido a que por protocolo el navegador solo necesita una URL para indicarle al servidor wue contenido traer.

***8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.***<br>
**JSON** (notación de objetos de JavaScript) es un formato de transmisión de datos basado en texto, que puede estructurar dichos datos como arreglos u objetos.<br>
```JSON
{
  "libreria": "El Sótano",
  "estado": "CDMX",
  "sucursal": "Zócalo",
  "activo": true,
  "empleado": [
    {
      "nombre": "Manuel Sanchez",
      "age": 29,
      "empleadoID": "175",
      "puestos": [
        "Gerente de sucursal",
        "Cajero"
      ]
    }
  ]
}
```
**XML** (lenguaje de marcado extensible) es un formato de texto empleado para almacenar e intercambiar datos estructurados.
```XML
<libreria> 
  <libro>
    <autores>
        <autor>L.G. Wade</autor> 
    <autores>
    <volumenes>
        <volumen>1</volumen> 
    <volumenes>
    <titulo>Química Orgánica</titulo> 
    <editorial>Pearson</editorial>
    <precio moneda="MXN">510</precio>
    <descriptores>
        <descriptor>Química<descriptor>
        <descriptor>Ciencia<descriptor>
    <descriptores>
  </libro> 
</libreria>
```
***9.	Explicar brevemente el estándar SOAP***<br>
**SOAP** (protocolo simple de acceso a objetos) es un protocolo estándar basado en XML que hace posible la comunicación entre entre aplicaciones con diferentes lenjuages y plataformas. Aunque se lleva generalmente a través de HTTP, el transporte de SOAP es independiente.

***10. Explicar brevemente el estándar REST Full***<br>
**RESTful** (transferencia de estado representacional) es un tipo de arquitectura de desarrollo web que se apoya en el estándar HTTP y se compone de una lista de reglas en cuanto al diseño de la arquitectura de una API que se deben cumplir.

***11. ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?***<br>
Los headers transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, entre otros datos.<br> 
El content-type es un recurso utilizado en el header, que le indica al cliente qué tipo de contenido será enviando por el servidor.
<br>
<br>

# Ejercicio 3

1.	![](Colocar imagenes)

2.	![](Colocar imagenes)

3.	![](Colocar imagenes)

¿Qué diferencias se observan entre las llamadas el punto 1 y 3?<br>
En la primera llamada de observó que el tamaño fue de 13.01 KB, mientras que en la última el tamaño fue de 13.09 KB. Significando que obviamente hubo un cambio, el cual fue el POST a la URL con la información adicional que agregamos en body. Dicha información agregada se encontrará en la última lína de código del archivo JSON.
<br>


# Ejercicio 4

PerfilLink salesforce https://trailblazer.me/id/danielcastrol
<br>
<br>

# Ejercicio 5

***1.	Lead.*** <br> 
Es un cliente potencial que ha mostrado interes en un producto o servicio que su compañía ofrece. Almacena información acerca de sus intereses en su compañia.

***2.	Account.*** <br>
Es una organización, compañía o consumidor del que se desea realizar un seguimiento, como un cliente, socio o competidor. Almacena datos relacionados a su organización y puede contener muchos contacto. Además se relaciona indirectamente con las otras palabras debido a que todo inicia con una cuenta. 

***3.	Contact.*** <br>
Son las personas asociadas a sus cuentas, aunque también se pueden asociar a Opportunities. Almacenan información sobre las personas con las que hace negocios.

***4.	Opportunity.*** <br>
Es un acuerdo en curso que realiza un seguimiento de las ventas y tratos pendientes. Almacena datos como las cuentas implicadas y las ventas potenciales.

***5.	Product.*** <br>
Es un artículo o servicio que su organización vende. Es definido por el PriceBook y puede ser agregado a Oppotunities.

***6.	PriceBook.*** <br>
Es una lista que almacena datos acerca de los productos o servicios que su organización vende.  

***7.	Quote.*** <br>
Es un registro que muestra los precios propuestos para los productos y servicios. La Quote o cotización se crea a partir de una Opportunity y su producto.

***8.	Asset.*** <br>
Es un modelo específico o tipo de producto específico adquirido o instalado que un cliente posee. 

***9.	Case.*** <br>
Es una pregunta, comentario o problema detallado de un cliente. Empleada para que los agentes del servicio de atención puedan ayudar y brindar un mejor servicio. 

***10.	Article.*** <br>
Es un documento que captura información acerca de los productos y servicios de su compañia, de los cuales se quiere la disponibilidad en la base de datos. Almacena datos sobre sus productos o preguntas frecuentes, relacionandoce con Cases o Assets.
<br>

DIAGRAMA

<br>

# Ejercicio 6

## Soluciones de Salesforce <br>

***A.	¿Qué es Salesforce?*** <br>
Es un grupo de tecnologías que admite el desarrollo de otras tecnologías sobre ella. Logrando la gestión de relaciones que une empresas y clientes. 

***B.	¿Qué es Sales Cloud?*** <br>
Es una herramienta de ventas y CRM que gestiona las relaciones con los clientes, pudiendo crear cuentas, buscar clientes, cerrar acuerdos, etc.

***C.	¿Qué es Service Cloud?*** <br>
Es una herramienta que ofece la capacidad de brindar soporte instantáneo y personalizado a través de teléfono, correo electrónico, chat o LiveMessage.

***D.	¿Qué es Health Cloud?*** <br>
Es una tecnología basada en la nube hecha para el cuiado de la salud, manteniendo la información de los pacientes almacenada en un solo lugar y con disponibilidad.

***E.	¿Qué es Marketing Cloud?*** <br>
Es una plataforma que cualquier empresa puede utilizar para realizar estrategias de email marketing a nivel profesional, planificando, personalizando y optimizando el recorrido de los clientes. 
<br>
<br>

## Funcionalidades de Salesforce <br>

***A.	¿Qué es un RecordType?*** <br>
Es un campo disponible para ciertos registros que pueden incluir valores estandar de la lista de selección y personalizados para ese registro. Pudiendo asociar los RecordType con perfiles para que solo los valores de lista de selección incluidos estén disponibles para los usuarios con ese perfil.


***B.	¿Qué es un ReportType?*** <br>
Define el conjunto de registros y campos disponibles para un informe en función de las relaciones entre un objeto principal y sus objetos relacionados.


***C.	¿Qué es un Page Layout?*** <br>
Es una organización de campos, lenlaces personalizados y listas relacionadas en una página de edición o detalle de registro. Utilizados principalmente para organizar páginas para sus usuarios. 


***D.	¿Qué es un Compact Layout?*** <br>
Es un diseño compacto que muestra los campos clave de un registro en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.

***E.	¿Qué es un Perfil?*** <br>
Es un conjunto de configuraciones que definen los permisos de un usuario para realizar diferentes funciones dentro de la plataforma Salesforce.

***F.	¿Qué es un Rol?*** <br>
Es la asignación de responsabilidades para los usuarios, cuenta de socios o contactos para cuentas y oportunidades específicas.


***G.	¿Qué es un Validation Rule?*** <br>
Es una regla que impide que se guarde un registro si no cumple con los estándares que se especifican.

***H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?*** <br>
La relación Master Detail es una relación padre-hijo, por lo que son obligatorios esos campos. Si se elimina el master o padre, el hijo también se eliminará, mientras que en la relación Lookup el padre no es un campo obligatorio.

***I.	¿Qué es un Sandbox?*** <br>
Es una copia casi idéntica de una organización de producción de Salesforce para desarrollo, pruebas y capacitación. Cuyo contenido y el tamaño varían dependiendo del tipo y la edición de la organización de producción asociada. 

***J.	¿Qué es un ChangeSet?*** <br>
Es un sistema de conjunto de cambiós utilizado para enviar personalizaciones de una organización de Salesforce a otra.

***K.	¿Para qué sirve el import Wizard de Salesforce?*** <br>
Para facilitar la importación de datos para muchos objetos estándar de Salesforce, incluidas cuentas, contactos, clientes potenciales, soluciones, miembros de campaña y cuentas personales.

***L.	¿Para qué sirve la funcionalidad Web to Lead?*** <br>
Para capturar la información del visitante en un sitio web y almacenar esa información como un nuevo prospecto.

***M.	¿Para qué sirve la funcionalidad Web to Case?*** <br>
Para recopilar solicitudes de atención al cliente directamente desde el sitio web de su empresa y generar automáticamente nuevos casos, logrando una mejor atención al cliente. 

***N.	¿Para qué sirve la funcionalidad Omnichannel?*** <br>
Para establecer una buena comunicación con los clientes por medio de diferentes canales como correo electrónico, redes sociales, pagina web, etc. 

***O.	¿Para qué sirve la funcionalidad Chatter?*** <br>
Para ayudar a conectarse, colaborar y actuar de manera eficiente en el dia a dia con los clientes.
<br> 
<br>

## Conceptos generales

***A.	¿Qué significa SaaS?*** <br>
Software as a Service, es un modelo de entrega de software basado en la nube donde el proveedor desarrolla y mantiene las aplicaciones en la nube, poniendolo a disposición de sus clientes a través de Internet.

***B.	¿Salesforce es Saas?*** <br>
Si, debido a que es simple y de fácil acceso al no necesitar instalar, mantener y actualizar hardwares y softwares.

***C.	¿Qué significa que una solución sea Cloud?*** <br>
Que emplea una tecnología con acceso remoto a softwares, almacenamiento y procesamiento de datos.

***D.	¿Qué significa que una solución sea On-Premise?*** <br>
Que se está realizando alguna acción de manera local en una computadora en las instalaciones de su propia empresa.

***E.	¿Qué es un pipeline de ventas?*** <br>
Es el proceso de actividades y estrategias que un vendedor necesita para acelerar el ciclo de ventas.

***F.	¿Qué es un funnel de ventas?*** <br>
Es un esquema que representa las etapas del proceso de desición de una venta en la que un usuario pasa a ser un cliente.

***G.	¿Qué significa Customer Experience?*** <br>
Son los factores que afectan la percepción y sentimientos de un cliente sobre una marca.

***H.	¿Qué significa omnicanalidad?*** <br>
Es una estrategia de marketing en la que se puede establecer comunicación con los clientes por medio de diferentes canales como correo electrónico, redes sociales, pagina web, físicamente, etc. 

***I.	¿Qué significa que un negocio sea B2B?, ¿Qué significa que un negocio sea B2C?, ¿Qué es un KPI?*** <br>
B2B significa business to business y es un modelo de negocio en el que las transacciones comerciales se levan a cabo entre empresas. <br>
BCB significa business to consumer y es un modelo de negocio en el que las transacciones comerciales se levan a cabo de empresas a consumidores. <br>
Un KPI es un indicador de rendimiento de un equipo o empresa en el que se evalua el progreso hacia los objetivos empresariales.

***J.	¿Qué es una API y en qué se diferencia de una Rest API?*** <br>
Una API es un conjunto de definiciones y protocolos que se usa para diseñar e integrar el software de las aplicaciones y así mejorar la interacción.
La principal diferencia entre una API y una REST API es la estructura. Debido a que una API sigue el formato de aplicación a aplicación, mientras que una REST API sigue una estructura cliente-servidor.

***K.	¿Qué es un Proceso Batch?*** <br>
Es un proceso por lotes donde se ejecuta un programa sin la supervisión de un usuario, utilizado generalmente para procesos repetitivos.

***L.	¿Qué es Kanban?*** <br>
Es un método para gestionar el flujo de trabajo y tener una mejor organización y distribución de tareas.

***M.	¿Qué es un ERP?*** <br>
Es un tipo de software que ayuda a gestionar y planificar las actividades empresariales diarias, dando soporte a la contabilidad, aprovisionamiento, gestión de proyectos, gestión de riesgos, operaciones de la cadena de suministro, entre otras. 

***N.	¿Salesforce es un ERP?*** <br>
No, debido a que la función de una ERP es gestionar empresas. Más bien Salesforce sería una CRM que gestiona las relaciones con los clientes.
<br>
<br>

# Ejercicio 7





