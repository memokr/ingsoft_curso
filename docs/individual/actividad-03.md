# Actividad 3
## **¿Qué es JSON y XML?**

## **JSON** 

Los datos son lo más importante. Pero saber cómo trabajar con una variedad de datos se ha vuelto aún más importante. Los programadores, desarrolladores y profesionales de TI necesitan transferir estructuras de datos pobladas de cualquier idioma a formatos reconocibles por otros idiomas y plataformas. JavaScript Object Notation (JSON) es el formato de cambio de datos que lo hace posible.

JSON se ha convertido en un formato de datos popular para los desarrolladores debido a su texto legible por humanos, que es ligero, requiere menos codificación y se procesa más rápido.

![](https://www.yudana.id/wp-content/uploads/2015/11/json_logo-555px.png)

## **XML**
XML son las siglas de Extensible Markup Language, que podemos traducir como Lenguaje de Marcas Extensibles, aunque realmente es un meta-lenguaje.

Los archivos XML se componen de etiquetas que nos aportan datos e información que queremos procesar. Estas etiquetas pueden estar de forma individual o anidadas.

Habitualmente un fichero XML incluye mucha información y debe de ser procesada correctamente por el usuario, en este caso el desarrollador. Cuanto más grande sea un fichero XML nos estará indicando que más información trae.

Lo primero que debemos saber de un fichero XML es que siempre contendrá una única etiqueta dando la introducción a dicho fichero, y a partir de ella podremos crear cualquier tipo de archivo XML.

Dentro de estos archivos XML tendremos una o varias etiquetas, que a su vez tendrán otras etiquetas, que podrán estar o no anidadas.

![](https://previews.123rf.com/images/yupiramos/yupiramos1612/yupiramos161202796/68635656-ilustraci%C3%B3n-de-vector-de-almacenamiento-de-base-de-datos-de-lenguaje-xml.jpg)


## **Características de JSON**

* JSON es solo un formato de datos.
* Requiere usar comillas dobles para las cadenas y los nombres de propiedades. Las comillas simples no son válidas.
* Una coma o dos puntos mal ubicados pueden producir que un archivo JSON no funcione. 
* Puede tomar la forma de cualquier tipo de datos que sea válido para ser incluido en un JSON, no solo arreglos u objetos. Así, por ejemplo, una cadena o un número único podrían ser objetos JSON válidos.
* A diferencia del código JavaScript, en el que las propiedades del objeto pueden no estar entre comillas, en JSON solo las cadenas entre comillas pueden ser utilizadas como propiedades.

## **Características XML**


* XML es un subconjunto de SGML que incorpora las tres características más importantes de este: Extensibilidad, Estructura, Validación

* Basado en texto.
* Orientado a los contenidos no presentación.
* Las etiquetas se definen para crear los documentos, no tienen un significado preestablecido.
* No es sustituto de HTML.
* No existe un visor genérico de XML.

## **Usos JSON**
1. **La generación de un objeto JSON a partir de datos generados por el usuario**
JSON es perfecta para almacenar datos temporales. Por ejemplo, los datos temporales pueden ser datos generados por el usuario, como un formulario enviado en un sitio web. JSON también se puede utilizar como formato de datos para cualquier lenguaje de programación para proporcionar un alto nivel de interoperabilidad.

2. **Transferencia de datos entre sistemas**
Una base de datos de sitio web tiene la dirección postal de un cliente, pero la dirección debe verificarse a través de una Interfaz de Programación de Aplicaciones para asegurarse de que es válida. Envío de los datos de dirección en formato JSON a la API de servicio de validación de direcciones.

3. **Configuración de datos para aplicaciones**
Al desarrollar aplicaciones, cada aplicación necesita las credenciales para conectarse a una base de datos, así como una ruta de acceso de archivo log. Las credenciales y la ruta de acceso al archivo se pueden especificar en un archivo JSON disponible y listo.

4. **Simplificar modelos de datos complejos**
JSON simplifica los documentos complejos hasta los componentes que se han identificado como significativos mediante la conversión del proceso de extracción de datos en un archivo JSON predecible y legible por humanos.

## **Usos XML**
Actualmente las aplicaciones del lenguaje XML son muy extensas. Se ha utilizado tanto para la definición de archivos de configuración, numerosos protocolos de comunicación y otros, hasta como base para la especificación de otros sublenguajes, por ejemplo en XHTML, RSS, RDF o Atom.

Algunos de sus usos más extendidos son:

* Intercambio de datos entre sistemas, uno de los objetivos fundamentales de XML es permitir la posibilidad de intercambiar datos de forma estructurada entre diferentes sistemas. Al tratarse de un formato de texto plano y ser un lenguaje estandarizado, hace que esta transferencia sea muy ágil e independiente de la plataforma utilizada.

* Base de datos, XML permite guardar datos de forma estandarizada para luego poder ser tratados por multitud de lenguajes diferentes. Su manejo es mucho más sencillo que bases de datos como MySQL y mucho más rico que utilizar ficheros de texto planos.

* Conversor, actualmente son muchos los formatos que ofrecen servicios de conversión a XML, como PDF, HTML, .text, .docx o XHTML.

![](https://iberdok.com/wp-content/uploads/2017/06/XML-Conversion-Services-e1498747153567.png)
## **Ventajas y desventajas de JSON**

### **Ventajas**

* Es autodescriptivo y fácil de entender.
* Su sencillez le ha permitido posicionarse como alternativa a XML.
* Es más rápido en cualquier navegador.
* Es más fácil de leer que XML.
* Es más ligero (bytes) en las transmisiones.
* Se parsea más rápido.
* Velocidad de procesamiento alta.
* Puede ser entendido de forma nativa por los analizadores de JavaScript.

### **Desventajas**

* Algunos desarrolladores encuentran su escueta notación algo confusa.
* No cuenta con una característica que posee XML: extensibilidad.
* No soporta grandes cargas, solo datos comunes.
* Para la seguridad requiere de mecanismos externos como expresiones regulares.

## **Ventajas y desventajas de XML**

### **Ventajas**

* Tiene un formato estructurado y fácil de comprender.
* Separa radicalmente la información o el contenido de su presentación o formato.
* Está diseñado para ser utilizado en cualquier lenguaje o alfabeto.
* Su análisis sintáctico es fácil debido a las estrictas reglas que rigen la composición de un documento.
* Tiene soporte a cualquier tipo de datos.
* Se pueden definir estructuras complejas y reutilizables.

### **Desventajas**

* El formato es sumamente estricto.
* Lleva más tiempo procesarlo.
* Complejidad de analizador (parser).
* Un error en cualquier parte del formato puede hacer que todo el documento sea inválido.

![](https://sawakinome.com/img/images/difference-between-json-and-xml_2.jpg)

## **Ejemplos**
<img src="/archivos/index/ejemplo1.png" alt="drawing" width="800" style="width: 100%;"/>

<img src="/archivos/index/ejemplo2.png" alt="drawing" width="800" style="width: 100%;"/>

<img src="/archivos/index/ejemplo3.png" alt="drawing" width="800" style="width: 100%;"/>


## **Referencias**
https://www.oracle.com/mx/database/what-is-json/

https://blogs.imf-formacion.com/blog/tecnologia/json-y-xml-las-principales-diferencias-202102/

https://openwebinars.net/blog/que-es-xml-y-para-que-se-usa/

https://www.mundolinux.info/que-es-xml.htm

https://www.nextu.com/blog/que-es-json/

https://es.sawakinome.com/articles/protocols--formats/unassigned-2505.html

