Para poder utilizar los servicios de IBM necesitamos crear una cuenta.

BlueMix
Entrar en https://console.bluemix.net. Allí cliquear el botón Create a free account
Completar los datos
Una vez creada la cuenta nos llegará un mail de verificación.
Una vez creada la cuenta podremos loguearnos con nuestro IBMId (el mail con el que nos registramos).

Creando un servicio
Para utilizar un servicio de la nube, por ejemplo Watson, tenemos que crearlo. Esto nos dará acceso a sus credenciales para poder usarlo.

Cliquear donde dice Create resource. Esto desplegará una lista de todos los recursos disponibles.
Seleccionar Natural Language Understanding-3u. Este servicio nos permitirá utilizar la detección de sentimiento y emociones en el texto.
Obtener credenciales
Dirigirse a la sección Manage. El botón podrás encontrarlo al costado superior izquierdo.
Una vez allí podrás ver tus credenciales. Guardalas en algún lugar porque las vas a tener que utilizar en tu código.
Ahora, dirigite a la documentación de python: https://cloud.ibm.com/apidocs/natural-language-understanding?language=python. Allí te dirá cómo utilizar tus credenciales en el código.




Agregando recurso Machine Learning
Antes de continuar con la siguiente clase, si todavía no tenés una cuenta en la IBM Cloud, deberás crear una siguiendo los pasos de la clase “Creando un servicio”.

Creando un nuevo recurso
Ahora deberás crear el recurso Machine Learning

Cliquear donde dice Create resource. Esto desplegará una lista de todos los recursos disponibles.
Seleccionar Machine Learning. Este servicio nos permitirá realizar el deploy de nuestro modelo en la nube.
Obtener credenciales
Dirigirse a la sección Service credentials. El botón podrás encontrarlo al costado superior izquierdo.
Una vez allí podrás crear nuevas credenciales para tu servicio cliqueando en new credentials.
Las credenciales que aparezcan serán las que utilizarás para completar en tu notebook de la siguiente clase. Guardalas.
Ahora podrás subir tu modelo a la nube y utilizar las funcionalidades de la API Machine Learning.