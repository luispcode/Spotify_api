Hola Mundo! 🌎

# Trbajando la API de Spotify

<img src="https://developer.spotify.com/assets/branding-guidelines/logo@2x.png" width=70000></img>


En este repositorio utilizaremos la API de Spotify para obtener información sobre artistas, discos y tracks disponibles en Spotify. Pero primero:

#####  ¿Qué es una **API**?

Por sus siglas en inglés, una API es una interfaz para programar aplicaciones (*Application Programming Interface*). Es decir que es un conjunto de funciones, métodos, reglas y definiciones que nos permitirán desarrollar aplicaciones (en este caso un scraper) que se comuniquen con los servidores de Spotify. Las APIs son diseñadas y desarrolladas por las empresas que tienen interés en que se desarrollen aplicaciones (públicas o privadas) que utilicen sus servicios. Spotify tiene APIs públicas y bien documentadas que estaremos usando en el desarrollo de este proyecto.

#### REST

Un término se seguramente te vas a encontrar cuando estés buscando información en internet es **REST** o *RESTful*. Significa *representational state transfer* y si una API es REST o RESTful, implica que respeta unos determinados principios de arquitectura, como por ejemplo un protocolo de comunicación cliente/servidor (que será HTTP) y (entre otras cosas) un conjunto de operaciones definidas que conocemos como **métodos**, por ejemplo, el método GET para hacer solicitudes a servidores web.

#### Documentación

Las APIs son diseñadas por las mismas empresas que tienen interés en que se desarrollen aplicaciones (públicas o privadas) que consuman sus servicios o información. Es por eso que la forma de utilizar las APIs variará dependiendo del servicio que querramos consumir. No es lo mismo utilizar las APIs de Spotify que las APIs de Twitter. Por esta razón es de suma importancia leer la documentación disponible, generalmente en la sección de desarrolladores de cada sitio. [link API Spotify](https://developer.spotify.com/documentation/)

#### JSON
Json significa *JavaScript Object Notation* y es un formato para describir objetos que ganó tanta popularidad en su uso que ahora se lo considera independiente del lenguaje. Lo utilizaremos en este proyecto por más que estemos trabajando en Python, porque es la forma en la que obtendremos las respuestas a las solicitudes que realicemos utilizando las APIs.