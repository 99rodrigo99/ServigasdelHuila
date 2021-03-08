# ServigasdelHuila
Proyecto Programación 1 FET

Rodrigo Humberto González Tafur
ING de software
Semestre 3
Noche

SERVIGAS DEL HUILA

Se esta realizando una pagina web para la empresa servigas del huila donde se presenta la informacion de la empresa y los servicios que esta presta, esta contara con un sistema de registro e inicio de sesion para los usuarios.

Se adiciono la libreria Layout, añadieron URLS amigables desde el archivo routes.php remplazando la estructura index.php/controlador/funcion y se edito el fichero .htaccess para reescribir las URLS.

VISTAS.
/Auth
- Login:
Esta vista contiene un formulario de inicio de sesion para que los usuarios registrados ingresen con los datos email y contraseña.

- Register:
Esta vista contiene un formulario de registro para nuevos usuarios.


/Controller_1

- inicio:
Esta vista contiene Un mensaje de bienvenida junto con el logo de la empresa, un boton que redirige a los usuarios hacia la vista quienes_somos, en la parte inferior contiene una barra donde se encuentran las marcas aliadas de la empresa.

- nuestra_empresa:
En esta vista se presenta una breve descripción de la empresa y un boton que redirecciona a los usuarios hacia la vista servicios.

- servicios:
Esta vista contiene los servicos que presta la empresa estos estan contenidos en cards.

- contacto:
En esta vista se presenta la informacion de contacto de la empresa como direccion numero telefonico correo y electronico, cuenta con un formulario de contacto para comunicarse via email.


/Layouts
- Layout:
En esta vista se encuentran el llamado de los archivos css, js, y la barra de navegación la cual cuenta con un menu que redirecciona a cada una de las seis vistas, ademas cuenta con un boton el cual nos redirecciona hacia WhatsApp para realizar la solicitud de un tecnico.
