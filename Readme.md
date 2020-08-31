[//]: # ( En VSCode mostrar la paleta de comandos y buscar **"Markdown: Open Preview"** sobre este archivo para lograr visualizar de manera correcta o dar click en el ícono de preview.)
[//]: # ()
# Inicializar configuración de Git
Para cambiar el nombre de la persona que se va a identificar en git. Es decir el nombre que va a aparecer cuando se realicen los commits. Si el nombre posee espacios utilizamos comillas dobles.

``git config --global user.name "Joma Espinoza"``

Para cambiar el email de la persona que se va a identificar en git.  

``git config --global user.email "satancito@email.com"``

Estas configuraciones se pueden cambiar las veces que deseamos, existen muchas otras pero estas son las más elementales. El ambito **--global** indica que se va a establecer los valores de las variables de configuración a nivel de usuario actual del sistema operativo.

Podemos establecer variables de configuración en tres ámbitos:  
+ **--system**: se aplicará a todo el sistema operativo.
+ **--global**: se aplicará a nuestro usuario dentro del sistema operativo.  
+ **--local**: se aplicará a un repositorio local concreto.  

Si varios ámbitos tienen especificado valor en una misma variable de configuración se toma el valor de mayor precedencia. **local** > **global** > **system**.
<br><br>
# Crear repositorio
Con este comando agregamos la carpeta actual para ser gestionada por git.  

``git init ``  

Podemos agregar un nombre de carpeta y si la carpeta no existe está será creada e inicializado un nuevo repositorio. Si el nombre de la carpeta tiene espacios utilizamos comillas dobles.

``git init "Mi Proyecto"``