# IT_ACADEMY_S4.01_N3_SpringPostman 

****POSTMAN************************************************************************************************************************************************
 Aplicación que se utiliza para probar y realizar solicitudes a APIs (Application Programming Interfaces) de forma fácil y eficiente.
 Testea colecciones de APIs: mediante el envio de solicitudes HTTP a una API y recibe las respuestas correspondientes. Esto es útil para verificar el 
 comportamiento de una API y asegurarse de que está funcionando correctamente tanto en el frontend como en el backend.
 Facilita el trabajo con diferentes entornos, como calidad, desarrollo y producción.
 Envia solicitudes HTTP a diferentes endpoints de una API, ya sea para obtener datos, enviar datos o realizar cualquier otra operación permitida por la API.
 Permite exportar e importar entornos, lo que facilita la colaboración y el intercambio de configuraciones entre diferentes equipos o miembros del equipo. 
 Puedes exportar un entorno como un archivo JSON y luego importarlo en otro lugar.
************************************************************************************************************************************************************ 

- Ejercicio Postman (Se trata de probar los anteriores proyectos desde Postman).
  
1 Crea dos entornos:
- Proyecto Maven
- Proyecto Gradle
2 Ambos entornos tendrán dos variables:
- Servidor, que en los dos casos tendrá el valor http://localhost
- Puerto, que en el caso del proyecto Maven tendrá el valor 9000, y en el caso del proyecto Gradle, 9001.
3 Que tienes que entregar? (4 archivos):
- Los dos entornos exportados.
- Un pantallazo por cada entorno, donde se vea la ejecución desde Postman usando el entorno y las variables definidas en ellos.
- Puedes probar la URL: http://localhost:xxxx/*HelloWorld/*elmeunom, o cualquier otra de las que admiten los dos proyectos. (recuerda que para que la ejecución funcione correctamente, tendrás que tener en ejecución los dos proyectos a Eclipse).
Ejecuta desde IDE(Eclipse/Visual Studio/IntelliJ) los proyectos creados a los dos niveles anteriores, y muestra el retorno obtenido en cada proyecto, cuando llamamientos a algunas de las peticiones disponibles, usando los entornos creados y sus variables.
Tendrás que entregar dos pantallazos, una por la ejecución de cada entorno, y dos archivos con formato JSON, con los entornos exportados.

## Enlaces

   - [Enlace 1](https://desarrolloweb.com/articulos/como-usar-postman-probar-api)
   - [Enlace 2](https://www.youtube.com/watch?v=FQAQO90LoQU)
     
## Uso

   Para utilizar la aplicación Postman, sigue los siguientes pasos:

   1. Abre Postman después de la instalación.
   2. Para realizar una nueva solicitud, haz clic en el botón "Nuevo" y selecciona "Requisición HTTP".
   3. Aparecerá una pantalla donde podrás ingresar los detalles de la solicitud, como la URL, el método HTTP y los parámetros.
   4. Completa los campos requeridos según la API que estés probando(Ejemplo, puedes ingresar una URL de una API y seleccionar el método GET para obtener datos).
   5. Haz clic en el botón "Enviar" para enviar la solicitud y ver la respuesta de la API.
