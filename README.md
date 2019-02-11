# Aplicacion corporativa PMK APP
Este repositorio contendra una explicacion con ayuda de imagenes de algunas de las funcionalidades que se desarrollaron para este proyecto corporativo. Todo el desarrollo evidenciado es realizado por Diego Sebastian camargo Lopez, con una vinculacion legal en la empresa.

#### Herramientas:
Para el desarrollo de este proyecto se utilizo codigo en lenguaje

* Java para la logica 
* XMl para las vistas
* Shared Preferences, SQLite y MySQL para asegurar la persistencia de los datos, MySQL se utilizo por medio de un servidor donde la app tenia una conexion cliente-servidor para su debido funcionamiento.


## 1. Login:

Aqui veremos lo que el usuario ve al ejecutar la aplicacion, esto teniendo en cuenta si no ha iniciado una sesion antes, pues si esto fuera asi, la aplicacion iniciaria con una sesion abierta. Para validar esto, se realiza una consulta interna que verifica si existe una sesion creada y si sigue activa. Como no es el caso, se le solicita al usuario el correo corporativo y la contraseña, o la posibilidad de crear una nueva cuenta.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/login.PNG)


## 2. Registro:

Podemos observar la vista al formulario de registro, para que con unos datos basicos un usuario se pueda registrar para poder tener acceso a la aplicacion.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registro.PNG)


## 3. Registro, fecha:

Este sera el picker para poder seleccionar la fecha de nacimiento del usuario.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroFecha.PNG)


## 4. Registro, datos solicitados:

Podremos ver un ejemplo de como un usuario realizaria el registro, tengamos en cuenta que para este caso el usuario estaria registrandose con un dominio que no es el corporativo.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroLleno.PNG)


## 5. Registro, error en el correo:

Como lo mensionamos anteriormente, el usuario estaria realizando un registro con un correo que no es el corporativo, para hacer cumplimiento a uno de los requerimientos de desarrollo, una persona solo podia registrarse si contaba con un correo corporativo, si no es el caso se le mostraria la siguiente alerta.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroCorreoPMK.PNG)


## 6. Login, correo no encontrado:

En la siguiente imagen podremos ver que la aplicacion en el login realiza las respectivas validaciones de seguridad, para este caso, el correo ingresado no pertenece a una direccion que ya haya creado la compañia.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/loginVerificacionMail.PNG)


## 7. Login, contraseña errada:

La segunda validadcion que realiza el Login es la posibilidad de mostrarle al usuario que al tratar de ingresar esta teniendo errores en la contraseña.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/loginVerificacionPass.PNG)


## 8. Login, exitoso:

En esta imagen podremos ver que los datos proporsionados por el usuario son correcto para que en la siguiente imagen se pueda observar como se evidencia la app con una sesion iniciada.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/loginLleno.PNG)

## Para entender mejor sobre la aplicacion y sus sesiones, esta se desarrollo inicialmente con dos perfiles, uno para empleado y otro para jefe o lider. Las diferencias principales se podran encontrar mas adelante, primero se hablara de la sesion del un empleado.

## 9. Home:

Esta vista sera igual para los dos roles. En el home podremos observar noticias o articulos de interes que son compartidos para la toda compañia, la idea era generar un espacio de conocimiento y de cultura organizacional mas centralizado y de interes general.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/home.PNG)


## 10. Vista a algun articulo:

Esta imagen podra dar a conocer como se visualiza un articulo por independiente, el usuario al presionar el articulo del cual queria saber mas al respecto.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/viewArticle.PNG)


## 11. Vista a algun articulo:

Este sera el menu donde encontraremos varias funciones de configuracion de la cuenta, datos de la aplicacion y el cierre de sesion, esta vista es igual para los dos roles.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/options.PNG)


## 12. Acerca de:

Aqui encontraremos una ventana modal que nos dira datos sobre la aplicacion.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/about.PNG)


## 12. Registro con ubicacion (ROL EMPLEADO):

Haciendo uso del api de google maps, se realizo un registro, capturando la geoposicion de la persona, junto con la hora y el tipo de registro (Entrada o Salida). En siguiente vista se observa que la opcionde registrar la salida no estara disponible si el usuario no ha registrado su llegada anteriormente, un requerimiento solicitado para la funcion.


![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroLlegada.PNG)



## 13. Registro con ubicacion (ROL EMPLEADO), confirmacion:

En esta imagen se observa que antes de enviar los datos, se le pregunta al usuario se en realidad quiere ralizar este registro.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroLlegadaConfirmacion.PNG)

Este repositorio contendrá una explicación con ayuda de imágenes de algunas de las funcionalidades que se desarrollaron para este proyecto corporativo. Todo el desarrollo evidenciado es realizado por Diego Sebastian Camargo López, con una vinculación legal en la empresa.

#### Herramientas:
Para el desarrollo de este proyecto se utilizó código en lenguaje

* Java para la lógica 
* XMl para las vistas
* Shared Preferences, SQLite y MySQL para asegurar la persistencia de los datos, MySQL se utilizó por medio de un servidor donde la app tenía una conexión cliente-servidor para su debido funcionamiento.


## 1. Login:

Aquí veremos lo que el usuario ve al ejecutar la aplicación, esto teniendo en cuenta si no ha iniciado una sesión antes, pues si esto fuera así, la aplicación iniciaría con una sesión abierta. Para validar esto, se realiza una consulta interna que verifica si existe una sesión creada y si sigue activa. Como no es el caso, se le solicita al usuario el correo corporativo y la contraseña, o la posibilidad de crear una nueva cuenta.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/login.PNG)


## 2. Registro:

Podemos observar la vista al formulario de registro, para que con unos datos básicos un usuario se pueda registrar para poder tener acceso a la aplicación.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registro.PNG)


## 3. Registro, fecha:

Este será el picker para poder seleccionar la fecha de nacimiento del usuario.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroFecha.PNG)


## 4. Registro, datos solicitados:

Podremos ver un ejemplo de cómo un usuario realizaría el registro, tengamos en cuenta que para este caso el usuario estaría registrándose con un dominio que no es el corporativo.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroLleno.PNG)


## 5. Registro, error en el correo:

Como lo mencionamos anteriormente, el usuario estaría realizando un registro con un correo que no es el corporativo, para hacer cumplimiento a uno de los requerimientos de desarrollo, una persona solo podía registrarse si contaba con un correo corporativo, si no es el caso se le mostraría la siguiente alerta.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroCorreoPMK.PNG)


## 6. Login, correo no encontrado:

En la siguiente imagen podremos ver que la aplicación en el login realiza las respectivas validaciones de seguridad, para este caso, el correo ingresado no pertenece a una dirección que ya haya creado la compañía.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/loginVerificacionMail.PNG)


## 7. Login, contraseña errada:

La segunda validación que realiza el Login es la posibilidad de mostrarle al usuario que al tratar de ingresar está teniendo errores en la contraseña.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/loginVerificacionPass.PNG)


## 8. Login, exitoso:

En esta imagen podremos ver que los datos proporcionados por el usuario son correcto para que en la siguiente imagen se pueda observar cómo se evidencia la app con una sesión iniciada.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/loginLleno.PNG)

## Para entender mejor sobre la aplicación y sus sesiones, esta se desarrolló inicialmente con dos perfiles, uno para empleado y otro para jefe o líder. Las diferencias principales se podrán encontrar más adelante, primero se hablara de la sesión de un empleado.

## 9. Home:

Esta vista será igual para los dos roles. En el home podremos observar noticias o artículos de interés que son compartidos para la toda compañía, la idea era generar un espacio de conocimiento y de cultura organizacional más centralizado y de interés general.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/home.PNG)


## 10. Vista a algun articulo:

Esta imagen podrá dar a conocer cómo se visualiza un artículo por independiente, el usuario al presionar el artículo del cual quería saber más al respecto.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/viewArticle.PNG)


## 11. Vista a algun articulo:

Este será el menú donde encontraremos varias funciones de configuración de la cuenta, datos de la aplicación y el cierre de sesión, esta vista es igual para los dos roles.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/options.PNG)


## 12. Acerca de:

Aquí encontraremos una ventana modal que nos dirá datos sobre la aplicación.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/about.PNG)


## 12. Registro con ubicación (ROL EMPLEADO):

Haciendo uso del api de google maps, se realizó un registro, capturando la geo posición de la persona, junto con la hora y el tipo de registro (Entrada o Salida). En siguiente vista se observa que la opción de registrar la salida no estará disponible si el usuario no ha registrado su llegada anteriormente, un requerimiento solicitado para la función.


![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroLlegada.PNG)



## 13. Registro con ubicación (ROL EMPLEADO), confirmación:

En esta imagen se observa que antes de enviar los datos, se le pregunta al usuario se en realidad quiere realizar este registro.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroLlegadaConfirmacion.PNG)


## 14. Registro con ubicación (ROL EMPLEADO), registro llegada realizado:

Aquí se observa que el usuario realizo el registro de llegada, cuando la aplicación detecta esto, inmediatamente desbloquea el registro de salida. Hay que tener presente que cada día se reinicia esta funcionalidad, por lo que si un usuario no llegase a registrar la salida, al día siguiente se inicia la funcionalidad desde el registro de entrada. Cada cambio de día se valida si el usuario realizo los dos registros, de lo contrario enviara la alerta a la base de datos.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroLlegadaRegistrada.PNG)


## 15. Registro con ubicación (ROL EMPLEADO), registro llegada realizado:

Aqui se observa que el usuario realizo el registro de llegada, cuando la aplicación detecta esto, inmediatamente desbloquea el registro de salida. Hay que tener presente que cada dia se reinicia esta funcionalidad, por lo que si un usuario no llegase a registrar la salida, al dia siguiente se inicia la funcionalidad desde el registro de entrada. Cada cambio de dia se valida si el usuario realizo los dos registros, de lo contraro enviara la alaerta a la base de datos.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroLlegadaRegistrada.PNG)



## 16. Registro con ubicación (ROL EMPLEADO), informacion del registro:

Cuando el usuario realiza un registro, este podrá ser observado desde un marcador que es puesto con los datos extraídos del registro (Longitud y Latitud), un marcador color azul para la entrada y uno color rojo para la salida.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/InfoRegistroLlegada.PNG)


## 17. Registro con ubicación (ROL EMPLEADO), registro llegada salida:

Se simula que el registro de salida está determinado con unos datos diferentes sobre la posición, para que se pueda apreciar la diferencia del marcador de salida.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/registroSalida.PNG)


## 18. Registro con ubicación (ROL EMPLEADO), registro llegada salida:

El usuario al realizar el registro, apreciara la aparición de dos marcadores, si queremos conocer los detalles del registro como la hora, podremos oprimir el marcador para desplegar un tooltip encima de este.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/inforegistroSalida.PNG)



## 19. Registro con ubicación (ROL JEFE O LIDER):

La diferencia es que para el rol de líder, la opción de registro no estará habilitada y a cambio de ello, el líder podrá observar solo a los empleados que tiene a cargo, así que en el mapa estaría lleno con marcadores de solo los empleados que el tiene a cargo, cada uno de estos con su nombre y la hora de llegada.

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/ViewMapCordinadorLlegada.PNG)

![alt text](https://github.com/essebas/APP_PMK/blob/master/PMK_appSS/ViewMapCordinadorSalida.PNG)
