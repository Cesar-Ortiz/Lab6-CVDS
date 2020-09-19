# Escuela Colombiana de Ingenier�a

# Introducci�n a proyectos Web

### Integrantes:

* Maria Ang�lica Alfaro Fandi�o
* C�sar Fernando Ortiz Rocha

### Parte I - Jugando a ser un cliente HTTP

3. Antes de que el servidor cierre la conexi�n por falta de comunicaci�n:
Revise el resultado obtenido. �Qu� codigo de error sale?
  *  ***301 Movido Permanentemente:*** Esta y todas las solicitudes futuras deben dirigirse al URI dado 

![](https://github.com/Cesar-Ortiz/Lab5-CVDS/blob/master/Servlet/src/main/resources/error.png)

Qu� otros c�digos de error existen?, �En qu� caso se manejar�n?

![](https://github.com/Cesar-Ortiz/Lab5-CVDS/blob/master/Servlet/src/main/resources/tiposErrores.png)

5. �Cu�l es la diferencia entre los verbos GET y POST? �Qu� otros tipos de peticiones existen?

![](https://github.com/Cesar-Ortiz/Lab5-CVDS/blob/master/Servlet/src/main/resources/otros.png)

### Parte III
18. El formulario debe usar como m�todo �POST�, y como acci�n, la ruta relativa del �ltimo servlet creado (es decir la URL pero excluyendo �http://localhost:8080/�).

![](https://github.com/Cesar-Ortiz/Lab5-CVDS/blob/master/Servlet/src/main/resources/FormularioHTML.PNG)

20. Cambie el formulario para que ahora en lugar de POST, use el m�todo GET . Qu� diferencia observa?

***M�todo GET***

![](https://github.com/Cesar-Ortiz/Lab5-CVDS/blob/master/Servlet/src/main/resources/HTMLGet.PNG)

***M�todo POST***

![](https://github.com/Cesar-Ortiz/Lab5-CVDS/blob/master/Servlet/src/main/resources/HTMLPost.PNG)

* La diferencia se puede evidenciar cuando se observa la URL de la p�gina WEB ya que al utilizar el m�todo GET se muestran el par�metro id ingresado anteriormente, algo que no sucede con el POST.

21. �Qu� se est� viendo? Revise c�mo est�n implementados los m�todos de la clase Service.java para entender el funcionamiento interno.
* En la clase service.java se realiza una conexi�n entre la URL original y la URL connection lo que permite obtener la informaci�n de tipo HTML para que el navegador la reconozca y as� mismo mostrar dicha informaci�n en forma de tabla o en forma de fila.

### Parte IV. - Frameworks Web MVC � Java Server Faces / Prime Faces

10. Si todo funcion� correctamente, realice las siguientes pruebas:
c. Dado la anterior, �Cu�l es la diferencia entre los backing-beans de sesi�n y los de aplicaci�n?
* Los backing-beans de session crean una nueva instancia del bean por cada dispositivo que se conecte al servicio. Los de aplicaci�n crean solo un bean independientemente de los dispositivos que se conecten al servicio

d. Por medio de las herramientas de desarrollador del explorador (Usando la tecla "F12" en la mayor�a de exploradores):

* Ubique el c�digo HTML generado por el servidor y busque el elemento oculto:

![](https://github.com/Cesar-Ortiz/Lab5-CVDS/blob/master/PrimeFaces/src/main/resources/contenido%20oculto.PNG)

* En la secci�n de estilos, deshabilite el estilo que oculta el elemento para que sea visible.

![](https://github.com/Cesar-Ortiz/Lab5-CVDS/blob/master/PrimeFaces/src/main/resources/contenido%20actualizado.PNG)

# Referencias

<https://developer.mozilla.org/es/docs/Web/HTTP/Methods>

<https://en.wikipedia.org/wiki/List_of_HTTP_status_codes>

<https://es.wikipedia.org/wiki/PrimeFaces>

<https://www.primefaces.org/showcase/ui/panel/panelGrid.xhtml>