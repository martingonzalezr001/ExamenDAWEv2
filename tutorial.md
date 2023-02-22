##Examen final 2ev

##Muestra una captura con la pantalla de creación de la instancia RDS con todas las opciones que hayas seleccionado.
--Hacemos click en **Crear base de datos**
--Seleccionamos la opción de Mysql
--Elegimos que nos cree la capa gratuita
--Introducimos el identificador bajo el nombre **wp_db** con el nombre **user_wp** y la contraseña **pass1234**
--Activamos la opción de **Conectarse a un recurso informatico de EC2** para más tarde conectarlo con nuestra instancia EC2.
--Dejamos el tema del almacenamiento y la configuración como está por defecto
--Hacemos click en **Configuración adicional**
--Introducimos en el nombre de la base de datos el que hemos escrito inicialmente que es **Wordpress** y lo demás se queda como está por defecto.
--Hacemos click en **Crear base de datos**.
--Ya nos aparece creada la base de datos en la instancia RDS.
##Importación en AWS de la clave pública SSH proporcionada 
--Una vez creada la instancia(en el apartado 3), hacemos click en **Par de claves** en menu de la izquierda en la pestaña que configura nuestra instancia.
--Nos mandan a esta pestaña, ahora hacemos click en **Importar par de claves**
--Se nos abre un nuevo menú en el que tenemos que introducir un nombre para la clave y donde dice **Archivo par de claves** tenemos que seleccionar el archivo que nos hemos descargado del BlackBoard con el nombre **examen_daw.pub** 
--Una vez hemos hecho ambas cosas, hacemos click en **Importar par de claves**
--Nos sale el par de claves y el mensaje superior que indica que el par de claves se ha importado correctamente.
##Creacion de la instancia EC2
--La instancia se crea haciendo click en **Lanzar instancia**
--Una vez tenemos la instancia, vamos a configurar los grupos de seguridad para permitir el tráfico de SSH y HTTP, tenemos que hacer click en **Editar reglas de entrada**.
--Una vez hemos activado los puertos de http y de ssh hacemos click en el botón de la esquina inferior derecha donde dice **Guardar reglas**.
