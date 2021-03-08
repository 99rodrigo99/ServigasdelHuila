# ServigasdelHuila
Proyecto Programación 1 FET

Rodrigo Humberto González Tafur 
ING de software 
Semestre 3 
Noche

SERVIGAS DEL HUILA

Se está realizando una página web para la empresa servigas del huila donde se presenta la información de la empresa y los servicios que esta presta, esta contara con un sistema de registro e inicio de sesión para los usuarios.
Se adiciono la librería Layout, añadieron URLS amigables desde el archivo routes.php remplazando la estructura index.php/controlador/función y se editó el fichero .htaccess para reescribir las URLS.

VISTAS. 

/Auth
-	Login: Esta vista contiene un formulario de inicio de sesión para que los usuarios registrados ingresen con los datos email y contraseña.

-	Register: Esta vista contiene un formulario de registro para nuevos usuarios.


/Controller_1
-	inicio: Esta vista contiene Un mensaje de bienvenida junto con el logo de la empresa, un botón que redirige a los usuarios hacia la vista quienes_somos, en la parte inferior contiene una barra donde se encuentran las marcas aliadas de la empresa.

-	nuestra_empresa: En esta vista se presenta una breve descripción de la empresa y un botón que redirecciona a los usuarios hacia la vista servicios.
-	servicios: Esta vista contiene los servicios que presta la empresa estos están contenidos en cards.

-	contacto: En esta vista se presenta la información de contacto de la empresa como dirección número telefónico correo y electrónico, cuenta con un formulario de contacto para comunicarse vía email.


/Layouts
-	Layout: 
En esta vista se encuentran el llamado de los archivos css, js, y la barra de navegación la cual cuenta con un menú que redirecciona a cada una de las seis vistas, además cuenta con un botón el cual nos redirecciona hacia WhatsApp para realizar la solicitud de un técnico.
