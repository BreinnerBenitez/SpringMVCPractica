
# Spring MVC Practica 
### 1) imgenes del web proyect, y configuracion xml Spring MVC para esacaneos en el paquete correspondiente y recursos estaticos de vista
###  tambien configuracion de archivo xml web de java ee para uso con springMVC 

___

 
![imagencarpeta](img/imagen1.JPG)

___

## spring_mvc_servlet.xml

![imagencarpeta](img/xml/spring_mvc_servlet.JPG)
___



## web.xml


![imagencarpeta](img/xml/web.JPG)



___
### 2)   cuando se ejecuta  el pryecto  ` MVCSpring ` inicia con el archivo jsp paginaEjemplo configurado con el Controlador

![imagencarpeta](img/imguso/imgen1.JPG)


## controlador 


![imagencarpeta](img/imagen1.1.JPG)


## codigo de  ` paginaEjemplo `  con jsp y html 

![imagencarpeta](img/imgen2jsp.JPG)


___
### 3) cuando pulsa ir al formulario alumnos del punto 2, me envia a al `Alumnocontroller.java `  y me devuelve el `alumnoRegistroFormulario.jsp`
## se procesa el modelo dandole un atributo al objeto alumno para poder ser utilizado en vista `elalumno` y procesar los datos registrados.
![imagencarpeta](img/imgen3.1.JPG)


## codigo del jsp   alumnoRegistroFormulario.jsp con jsp tags. 


![imagencarpeta](img/imgen3.JPG)


## procesa tambien los metodos get y set del Alumnos.java (imagen de abajo)  con el atributo path.de imgen de arriba   

![imagencarpeta](img/setterygetter.JPG)



## formulario en el navegador (ver imgen de abajo) 

![imagencarpeta](img/imguso/imgen2.JPG)

___


### 4) una ves ingresados los datos son procesados en  `procesarFormulario` de Alumnocontroller.java ` ingresados en Objeto Alumno el cual nos devuelve 
### ` confirmacionRegistroAlumno.jsp`  si las validaciones atraves de Hibernate validetion se cumplen.

![imagencarpeta](img/validacion4.2.JPG)

## una ves validado  me muestra la informacion  


![imagencarpeta](img/confirmacionregistro5.JPG)



![imagencarpeta](img/imguso/imgen3.JPG)



___

   
