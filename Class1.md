### Cómo funciona una página web?
Comencemos con la forma más fácil de usar internet, visitando una página como:  https://bit.ly/2Js0KP5
En el momento que ingresamos la información en el buscador y le damos ENTER, muchas cosas pasan:
- La URL se resuelve.
- Una solicitud (Request) es enviada al servidor web.
- La respuesta (Response) del servidor es analizada.
- La página es renderizada y mostrada.
 ![mapa](https://user-images.githubusercontent.com/45574618/100818572-6b5c4280-3418-11eb-924e-f91f5b1a3b7a.jpg)</br>
Obviamente esto es más complejo, pero para empezar estamos bien.
Desglosemos cada parte del proceso para entender a detalle:

- URL  se resuelve.</br>
El código fuente de la página obviamente no está guardado en nuestras computadoras, por esto debemos buscar esa información en otra computadora donde está almacenado. Lo que llamamos otra computadora, en realidad es el SERVIDOR, porque tiene como propósito servir, en este caso a la página web.

Digamos que buscas www.google.com (Este es el dominio), sin embargo el servidor el cual almacena el código fuente de la página web, está identificado con un IP (Internet protocol) address. El buscador envía una petición (Request) al servidor con la IP address que buscamos o ingresamos indirectamente (www.google.com).

Una IP adress normalmente se ve así  208.67.222.222, aunque hoy en día existe la IPv6 que se ve así 2001:4860:4860::8888, pueden investigar más sobre el tema acá <a href="https://es.wikipedia.org/wiki/Direcci%C3%B3n_IP">En Wikipedia.</a>

Ustedes se preguntarán, ¿cómo el dominio se traduce a la IP address?</br>
Existe un servidor especial en internet que se encarga de esto, es el DNS Server (Domain Name System).

Básicamente lo que hace es traducir el dominio a IP address, cuando nosotros ingresamos cualquier página web, este servidor sirve como un diccionario que guarda todos los dominios y sus IP addresses.

*El servidor DNS está incrustado (Built in) en el buscador.

