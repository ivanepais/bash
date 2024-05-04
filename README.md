# Linux Shell

|| Command Line

	Terminal o shell, es una interfaz de usuario en la que puedes interactuar con una computadora o sistema operativo (núcleo/kernel) ingresando comandos de texto en lugar de utilizar una interfaz gráfica de usuario (GUI) con ventanas y elementos gráficos.
	

	Sintaxis de comandos: 

		Los comandos en la línea de comandos tienen una sintaxis específica que debes seguir.

		Suelen consistir en el nombre del comando seguido de opciones y argumentos que modifican el comportamiento del comando.


	Automatización: 

		La línea de comandos es poderosa para la automatización de tareas repetitivas. 

		Puedes crear scripts que ejecuten una serie de comandos en secuencia.


	Acceso a herramientas avanzadas:

		Muchas herramientas y utilidades avanzadas de un sistema operativo o aplicaciones pueden ser accedidas más fácilmente a través de la línea de comandos en lugar de la GUI.


	Acceso a sistemas remotos: 

		La línea de comandos es una forma común de administrar sistemas remotos a través de SSH u otras conexiones de red seguras.



|| Shells

	Es una capa de software que actúa como intermediaria entre el usuario y el sistema operativo. 

	La shell acepta comandos de entrada escritos por el usuario y los traduce en instrucciones que el sistema operativo puede entender y ejecutar.

	Hay varias shells disponibles en diferentes sistemas operativos, y cada una tiene sus propias características y comandos.


	GNU/Bash o Bash (Bourne-Again Shell): 

		Una de las shells más populares y ampliamente utilizadas en sistemas Unix y Linux. 

		Bash es una extensión de la shell original de Unix, la "Bourne Shell" (sh), y agrega muchas características y mejoras.


	Zsh (Z Shell): 

		Una shell potente y altamente personalizable que es popular entre los usuarios avanzados.

		Ofrece completado de comandos mejorado, historial avanzado y más.


	Fish (Friendly Interactive Shell):

		Diseñada para ser amigable y fácil de usar, Fish ofrece características modernas y una sintaxis más sencilla. 

		Es popular entre aquellos que buscan una experiencia de línea de comandos más amigable.


	PowerShell: 

		Una shell de Microsoft diseñada principalmente para entornos Windows, pero también disponible para Linux y macOS.

		Es muy potente y se centra en la automatización y la gestión de sistemas.



|| Bash
	
	Cada shell tiene su propia sintaxis de comandos y características únicas. 

	La elección de una shell depende de las preferencias del usuario y de las tareas específicas que se deben realizar.

	Bash es una de las shells más comunes y es ampliamente utilizada en sistemas Unix y Linux. 


    Historial de comandos: 

    	Bash guarda un historial de los comandos que has ejecutado, lo que facilita la repetición de comandos anteriores.


    Completado de comandos: 

    	Bash ofrece completado automático de comandos y nombres de archivos, lo que acelera la entrada de comandos.


    Scripts: 

    	Puedes escribir scripts Bash para automatizar tareas y procesos. 

    	Estos scripts son secuencias de comandos Bash almacenados en archivos de texto.


    Variables y expresiones: 

    	Bash admite variables, operaciones matemáticas y expresiones lógicas, lo que lo hace poderoso para la programación de scripts.


    Redirección y tuberías: 

    	Puedes redirigir la entrada y salida de comandos y crear tuberías (pipes) para combinar múltiples comandos en una sola línea.


	Bash es una herramienta versátil que es esencial para la administración de sistemas Unix/Linux y la automatización de tareas en estos sistemas. 

	Los usuarios de Linux y macOS a menudo interactúan con Bash a través de una terminal o emulador de terminal para realizar una variedad de tareas, desde la gestión de archivos hasta la administración de servidores.


	Cubre una amplia variedad de tareas en sistemas Linux y Unix:

	1. Gestión de archivos y directorios:

        Navegación por el sistema de archivos.

        Creación de directorios con el comando 'mkdir'.

        Eliminación de archivos y directorios con el comando 'rm'.
        
        Copia de archivos con el comando 'cp'.

        Movimiento y cambio de nombre de archivos y directorios con el comando 'mv'.

        Listado de archivos y directorios con el comando 'ls'.


    2. Administración de usuarios y permisos:

        Creación de usuarios con el comando 'useradd'.

        Cambio de contraseñas de usuarios con el comando 'passwd'.

        Asignación de permisos de archivo y directorio con el comando 'chmod'.

        Gestión de grupos de usuarios con los comandos 'groupadd', 'usermod', etc.


    3. Redes y conectividad:

        Configuración de interfaces de red con el comando 'ifconfig' o 'ip'.

        Prueba de conectividad con el comando 'ping'.

        Gestión de conexiones SSH con el comando 'ssh'.


    4. Gestión de paquetes de software:

        Instalación de software nuevo con el gestor de paquetes (apt, yum, dnf, etc.).

        Actualización de software con el gestor de paquetes.

        Búsqueda de paquetes con el gestor de paquetes.


    5. Tareas de administración del sistema:

        Reinicio y apagado del sistema con el comando 'reboot' o 'shutdown'.

        Monitoreo de recursos del sistema con comandos como 'top', 'htop', 'free', etc.

        Configuración de tareas programadas con 'cron'.


    6. Manipulación de texto:

        Visualización y edición de archivos de texto con comandos como 'cat', 'less', 'nano', 'vim', etc.

        Búsqueda y manipulación de texto con comandos como 'grep', 'sed', 'awk', etc.


    7. Gestión de procesos:

        Listado de procesos en ejecución con el comando 'ps'.

        Finalización de procesos con el comando 'kill'.


    8. Seguridad y autenticación:

        Gestión de contraseñas con el comando 'passwd'.

        Configuración de políticas de seguridad con el comando 'sudo'.


    9. Compilación y desarrollo de software:

        Compilación de programas desde el código fuente con comandos como 'gcc', 'make', etc.

        Gestión de sistemas de control de versiones como 'git'.


    10. Automatización de tareas:

        Creación de scripts de shell para automatizar tareas repetitivas.



|| whoami

	se utiliza para mostrar el nombre del usuario que está actualmente conectado y ejecutando comandos en la sesión de la terminal. 

	Su función principal es proporcionar el nombre de usuario del contexto actual. 

	Verás el nombre de usuario asociado con esa sesión. 

	Esto puede ser útil cuando estás trabajando en un sistema multiusuario y necesitas confirmar quién está actualmente conectado y trabajando en la terminal.


	Ejemplo: 

		```
		$ whoami
		usuario

		```
		'usuario' es el nombre de usuario que está utilizando la sesión de la terminal en ese momento.



|| man

	Se utiliza para acceder a las páginas del manual del sistema, que son documentos de referencia detallados que describen el funcionamiento y el uso de los comandos, utilidades y programas disponibles en el sistema operativo.

	```
	man ls

	```
	Esto abrirá la página del manual para el comando "ls".	


	Las páginas del manual se presentan en un visor de texto en la terminal que te permite desplazarte hacia arriba y hacia abajo para leer la documentación.

	Puedes usar las teclas de dirección o las teclas de desplazamiento (si tu terminal lo permite) para navegar por el contenido del manual. 

	Para salir del visor de "man" y regresar a la línea de comandos, generalmente se utiliza la tecla "q".



|| clear

	Se utiliza para borrar la pantalla y eliminar todo el contenido visible en la ventana de la terminal, lo que proporciona una pantalla en blanco o limpia. 

	Esto puede ser útil cuando la terminal se llena de texto y deseas tener una pantalla vacía para trabajar o simplemente para mejorar la legibilidad.

	```
	clear

	```	

	No elimina ningún archivo ni realiza cambios en el sistema de archivos, solo afecta la presentación visual en la ventana de la terminal.



|| pwd

	Muestra el directorio de trabajo actual, es decir, el directorio en el que te encuentras actualmente en la jerarquía de directorios del sistema de archivos.

	Cuando navegas a través de los directorios en la línea de comandos, es posible que desees saber en qué ubicación exacta te encuentras en el sistema de archivos.

	```
	$ pwd
	/home/usuario/documentos

	```	

	Cualquier archivo o directorio que crees o manipules desde este punto se ubicará dentro de "/home/usuario/documentos".



|| ls

	listar los archivos y directorios en el directorio actual o en un directorio específico.

	```
	ls [opciones] [directorio]

	```

    [opciones]: 

    	Estas son banderas opcionales que puedes proporcionar para modificar el comportamiento de "ls". Algunas opciones comunes incluyen:

        -l: 
        	Muestra un listado largo que incluye información detallada sobre archivos y directorios, como permisos, propietario, grupo, tamaño y fecha de modificación.

        -a: 

        	Muestra todos los archivos, incluyendo los ocultos (los que comienzan con un punto, como ".config").

        -h: 

        	Muestra los tamaños de archivo en un formato legible por humanos, como "1.2K" en lugar de bytes.

        -t: 

        	Ordena la lista por fecha de modificación, mostrando primero los archivos más recientes.

        -r: Muestra la lista en orden inverso (descendente).


    [directorio]: 

    	Especifica el directorio del cual deseas listar el contenido. 

    	Si no se proporciona un directorio, "ls" listará el contenido del directorio actual.


    Ejemplo: 

	    ```
	    ls

	    ```

	    Archivos y directorio actual.


		```
		ls /home/usuario/documentos

		```

		Archivos y directorios específico


		```	
		ls -alh

		```

		Listar archivos ocultos y mostrar tamaños legibles por humanos en un formato largo.


		```
		ls -lt

		```

		archivos en orden inverso por fecha de modificación.



|| cd

	'change directory' se utiliza para cambiar el directorio de trabajo actual.

	Puede navegar por la jerarquía de directorios del sistema de archivos y acceder a diferentes carpetas o ubicaciones en tu sistema.

	```
	cd [directorio]

	```

    [directorio]: 

    	Especifica el directorio al cual deseas cambiar.

    	Puede ser una ruta absoluta (comenzando desde la raíz del sistema de archivos) o una ruta relativa (relativa al directorio actual). 

    	Si no proporcionas un directorio, "cd" te llevará de vuelta al directorio de inicio de tu usuario.


    ```
    cd

    ``` 
    Cambiar al directorio de inicio del usuario actual.


    ```
    cd /home/usuario/documentos

    ```
    Cambiar al directorio específico. 


    ```
    cd ..

    ```
    Cambiar al directorio padre (un nivel arriba) desde el directorio actual


    ```
    cd ~/archivos

    ```
    Cambiar al directorio "archivos" dentro del directorio de inicio del usuario actual utilizando una ruta relativa.


	"cd" Te permite moverte rápidamente por el sistema de archivos y acceder a diferentes ubicaciones para realizar tareas y operaciones en diferentes directorios    

    Para verificar el directorio de trabajo actual en cualquier momento, puedes utilizar el comando "pwd" (print working directory).



|| mkdir

	Crear nuevos directorios o carpetas en el sistema de archivos.

	Significa "make directory".

	```
	mkdir [opciones] nombre_del_directorio

	```

	[opciones]: 

		Banderas opcionales para modificar el comportamiento de "mkdir".

	    -p: 

	    	Crea directorios padres si no existen. 

	    	Por ejemplo, si deseas crear "/nuevo/directorio" pero "/nuevo" no existe, "mkdir -p /nuevo/directorio" creará ambos directorios.


	nombre_del_directorio: 

		Especifica el nombre del directorio que deseas crear.

		Puedes proporcionar una ruta absoluta (desde la raíz del sistema de archivos) o una ruta relativa (relativa al directorio actual).


	Ejemplos:

		```	
		mkdir mi_carpeta

		```
		nuevo directorio llamado "mi_carpeta" en el directorio actual.


		```
		mkdir documentos/proyectos

		```
		Crear un directorio llamado "proyectos" dentro de otro directorio llamado "documentos".


		```
		mkdir -p vacaciones/2023/fotos

		```
		Crear un directorio llamado "fotos" y sus directorios padres "vacaciones" y "2023" si no existen.


		```	
		mkdir directorio1 directorio2 directorio3

		```		
		Crear varios directorios a la vez.



|| touch

	Crear archivos vacíos o para actualizar la fecha de acceso y modificación de un archivo existente. 

	```
	touch [opciones] nombre_del_archivo

	```

	[opciones]: 

		banderas opcionales para modificar el comportamiento de "touch". 

		Sin embargo, en la mayoría de los casos, no es necesario utilizar opciones.


	nombre_del_archivo: 

		Especifica el nombre del archivo que deseas crear o actualizar.

		Puedes proporcionar una ruta absoluta (desde la raíz del sistema de archivos) o una ruta relativa (relativa al directorio actual)


	Ejemplos: 

		```
		touch mi_archivo.txt

		```
		Nuevo archivo vacío llamado "mi_archivo.txt" en el directorio actual.


		```
		touch documentos/notas.txt

		```
		Crear un archivo llamado "notas.txt" en el directorio "documentos".


		```
		touch registro.txt

		```
		fecha de acceso y modificación de un archivo existente llamado "registro.txt"  (sin modificar el contenido).		

		```
		touch archivo1.txt archivo2.txt archivo3.txt

		```
		Crear varios archivos a la vez.


	Puede utilizarse para crear archivos de registro vacíos, actualizar archivos de configuración, o como parte de secuencias de comandos para administrar archivos y directorios.



|| rmdir

	Eliminar directorios vacíos en el sistema de archivos (sin archivos o subdirectorio en su interior). 

	Su nombre es una abreviatura de "remove directory". 

	```
	rmdir [opciones] nombre_del_directorio

	```

	[opciones]: 

		Para modificar el comportamiento de "rmdir". 

		Em la mayoría de los casos, no es necesario utilizar opciones.


    nombre_del_directorio: 

    	Especifica el nombre del directorio que deseas eliminar. 

    	Puedes proporcionar una ruta absoluta (desde la raíz del sistema de archivos) o una ruta relativa (relativa al directorio actual).


    Ejemplos: 

    	```
    	rmdir mi_carpeta

    	```
    	Eliminar un directorio vacío llamado "mi_carpeta" en el directorio actual.


    	```
    	rmdir documentos/fotos

    	```
    	Eliminar un directorio vacío llamado "fotos" dentro del directorio "documentos":


    	```
    	rmdir directorio1 directorio2 directorio3

    	```
    	Eliminar varios directorios vacíos a la vez.


    Si intentas usar "rmdir" en un directorio que aún tiene contenido, obtendrás un mensaje de error y el directorio no se eliminará. 

    Para eliminar directorios que contengan archivos o subdirectorios, generalmente se utiliza el comando "rm" con la opción "-r" para eliminar recursivamente.

    La eliminación de directorios incorrectos podría afectar el funcionamiento del sistema.



|| rm

	Eliminar archivos y directorios. Su nombre es una abreviatura de "remove".

	Elimina archivos y directorios de forma permanente, sin enviarlos a la papelera de reciclaje ni a una carpeta de recuperación.

	```
	rm [opciones] nombre_del_archivo

	```
	Elimina archivos vacíos.


	```
	rm [opciones] -r nombre_del_directorio

	```
	Para eliminar directorios y su contenido.

	[opciones]: 	

		Para modificar el comportamiento de "rm". 

    	-f: 

    		Forzar la eliminación sin preguntar confirmación, útil cuando se eliminan muchos archivos o directorios.

       	-i: 

       		Solicitar confirmación antes de eliminar cada archivo.

        -r o -R: 

        	Utilizado para eliminar directorios y su contenido de manera recursiva (necesario para eliminar directorios).


    nombre_del_archivo o nombre_del_directorio: 

    	Especifica el nombre del archivo o directorio que deseas eliminar. 

    	Puedes proporcionar una ruta absoluta o relativa al archivo o directorio que deseas eliminar.



|| xdg-open

	Abrir archivos y URLs utilizando la aplicación predeterminada asociada a cada tipo de archivo o URL. 

	Es similar en funcionalidad al comando "open" en macOS.

	```
	xdg-open [archivo_o_URL]

	```

	[archivo_o_URL]: 

		Especifica el nombre del archivo o la URL que deseas abrir.

		Puedes proporcionar una ruta absoluta o relativa al archivo o simplemente la URL.


	```
	xdg-open documento.txt

	xdg-open foto.jpg

	```
	Abrir un archivos con su programa predeterminado. 



	```
	xdg-open https://www.ejemplo.com

	```	
	Abrir una URL en el navegador web predeterminado.



	```
	xdg-open directorio/

	```
	Abrir un directorio con el gestor de archivos predeterminado



|| mv
	
	Mover o renombrar archivos y directorios. 

	El nombre "mv" es una abreviatura de "move".


	```
	mv [opciones] origen destino

	```
	
	[opciones]: 

		Para modificar el comportamiento de "mv". 

        -i: 

        	Solicitar confirmación antes de sobrescribir archivos existentes.

        -u: 

        	Mover solo cuando el archivo de origen sea más nuevo o no exista en el destino.


    origen: 

    	Especifica la ubicación del archivo o directorio que deseas mover o renombrar.

    	Puede ser una ruta absoluta o relativa.


    destino: 

    	Indica la ubicación a la que deseas mover el archivo o directorio, o el nuevo nombre que deseas asignarle. 

    	También puede ser una ruta absoluta o relativa.


    Ejemplos: 

    	```
    	mv documento.txt /home/usuario/documentos

    	```
    	Mover un archivo llamado "documento.txt" del directorio actual al directorio "/home/usuario/documentos".


    	```
    	mv archivo_viejo.txt archivo_nuevo.txt

    	```	
    	Renombrar un archivo llamado "archivo_viejo.txt" a "archivo_nuevo.txt"


    	```
    	mv proyecto documentos/

    	```
    	Mover un directorio llamado "proyecto" al directorio "documentos".


    Manipulación de archivos y directorios, como mover, renombrar y cambiar la ubicación de elementos en el sistema de archivos.



|| cp

	Copiar archivos y directorios. 

	Su nombre es una abreviatura de "copy".

	```
	cp [opciones] origen destino

	```

	[opciones]: 

		Para modificar el comportamiento de "cp". 

        -r o -R: 

        	Utilizado para copiar directorios y su contenido de manera recursiva (necesario para copiar directorios completos).

        -i: 

        	Solicitar confirmación antes de sobrescribir archivos existentes.

        -u: 

        	Copiar solo cuando el archivo de origen sea más nuevo o no exista en el destino.


    origen: 

    	Especifica la ubicación del archivo o directorio que deseas copiar. 

    	Puede ser una ruta absoluta o relativa.


    destino: 

    	Indica la ubicación donde deseas crear una copia del archivo o directorio. 

    	También puede ser una ruta absoluta o relativa.


    Ejemplos: 

    	```
    	cp documento.txt /home/usuario/documentos

    	```
    	Copiar un archivo llamado "documento.txt" del directorio actual al directorio "/home/usuario/documentos


    	```
    	cp archivo.txt copia.txt

    	```
    	Copiar un archivo llamado "archivo.txt" y darle un nuevo nombre "copia.txt" en el mismo directorio


    	```
    	cp -r proyecto respaldo/

    	```
    	Copiar un directorio llamado "proyecto" y todo su contenido al directorio "respaldo".


    	```
    	cp reporte.pdf ~/reportes/

    	```
    	Copiar un archivo llamado "reporte.pdf" al directorio de inicio del usuario actual


    Puedes utilizarlo para realizar copias de seguridad, crear réplicas de archivos, mover archivos a diferentes ubicaciones y más. 

    Ten en cuenta que cuando copias directorios con la opción -r, se copia todo el contenido del directorio, incluyendo subdirectorios y archivos, de manera recursiva.



|| head

	Mostrar las primeras líneas de un archivo de texto. 

	Por defecto, "head" muestra las primeras 10 líneas de un archivo, pero puedes especificar un número diferente de líneas si lo deseas.

	```
	head [opciones] [archivo]

	```

	[opciones]: 

		Modificar comportamiento:

        -n NUM: 

        	Especifica el número de líneas que deseas mostrar en lugar de las 10 líneas por defecto.

        -c NUM: 

        	Muestra los primeros "NUM" bytes en lugar de líneas.

        -q: 

        	Suprime las cabeceras de nombre de archivo cuando se procesan múltiples archivos.


    [archivo]: 

    	Especifica el nombre del archivo del cual deseas mostrar las primeras líneas.

    	Puede ser una ruta absoluta o relativa al archivo.


    Ejemplos: 

    	```
    	head archivo.txt

    	```
		Mostrar las primeras 10 líneas de un archivo llamado "archivo.txt".    	


		```
		head -n 5 documento.txt

		```
		Mostrar las primeras 5 líneas de un archivo llamado "documento.txt".


		```
		head -c 100 datos.bin

		```
		Mostrar los primeros 100 bytes de un archivo llamado "datos.bin".


		```
		head -n 20 -q archivo1.txt archivo2.txt archivo3.txt

		```
		Primeras 20 líneas de varios archivos a la vez y suprimir las cabeceras de nombre de archivo.



|| tail

	Mostrar las últimas líneas de un archivo de texto. 

	Por defecto, "tail" muestra las últimas 10 líneas de un archivo, pero al igual que con "head", puedes especificar un número diferente de líneas si lo deseas.


	```
	tail [opciones] [archivo]

	```

	[opciones]: 

        -n NUM: 

        	Especifica el número de líneas que deseas mostrar en lugar de las 10 líneas por defecto.

        -c NUM: 

        	Muestra los últimos "NUM" bytes en lugar de líneas.

        -f: 

        	Muestra las últimas líneas del archivo en tiempo real y continúa mostrando nuevas líneas a medida que se agregan al archivo (útil para seguir registros en tiempo real).


    [archivo]: 

    	Especifica el nombre del archivo del cual deseas mostrar las últimas líneas.

    	Puede ser una ruta absoluta o relativa al archivo.


    Ejemplos: 

    	```
    	tail archivo.txt

		tail -n 5 registro.log

		tail -c 200 datos.bin

		tail -f registro.log			
    	```	

    	Mostrar las últimas 10 líneas de un archivo llamado "archivo.txt".

    	Mostrar las últimas 5 líneas de un archivo llamado "registro.log".

    	Mostrar los últimos 200 bytes de un archivo llamado "datos.bin".

    	Seguir en tiempo real las nuevas líneas que se agregan a un archivo de registro llamado "registro.log".



|| date

	Mostrar o configurar la fecha y la hora del sistema.

	Obtener información sobre la fecha y la hora actual, así como para configurar la fecha y la hora del sistema, siempre que tengas permisos adecuados.	

	```
	date [opciones]

	```

	Ejemplos: 

		```
		date

		date "+%Y-%m-%d %H:%M:%S"

		sudo date -s "2023-10-01 15:30:00"

		date -u

		date "+%Y"

		date "+%A"

		```

		Mostrar la fecha y la hora actuales en un formato predeterminado.

		Mostrar la fecha y la hora en un formato personalizado (por ejemplo, "Año-Mes-Día Hora:Minuto:Segundo").

		Configurar la fecha y la hora del sistema de forma manual (debes tener permisos de superusuario).

		Mostrar la fecha en formato UTC (Tiempo Universal Coordinado).

		Mostrar solo el año actual.

		Mostrar el día de la semana.



|| redirecting standard output

	Redirigir la salida estándar se refiere al proceso de cambiar hacia dónde se dirige la salida estándar de un comando o programa. 

	En sistemas tipo Unix, la salida estándar se representa como 'stdout'.

	Por defecto, cuando ejecutas un comando en una terminal, la salida estándar se muestra en la pantalla de la terminal. 

	Sin embargo, puedes redirigir esta salida a diferentes destinos, como archivos u otros comandos, utilizando símbolos especiales.


	1. Redirigir a un archivo (>): 

		Puedes utilizar el símbolo > para redirigir la salida estándar a un archivo.

		```	
		comando > salida.txt

		```

		Por ejemplo: 

		```
		date > salida.txt

		```

		Si usamos:  

		```
		head salida.txt

		```

		El archivo salida.txt mostrará la fecha actual. 


		Si "salida.txt" ya existe, será sobrescrito. 

		Si deseas agregar la salida a un archivo existente, puedes usar >> de esta manera

		```
		comando >> salida.txt

		```


	2. Redirigir a un Dispositivo (>/dev/null): 

		Puedes usar /dev/null para descartar la salida estándar.

		```
		comando > /dev/null

		```
		Ejecutará "comando" pero descartará cualquier salida que produzca.


	3. Redirigir a Otro Comando (|):

		Puedes usar el símbolo de tubería (|) para redirigir la salida estándar de un comando hacia otro comando como entrada.

		```
		comando1 | comando2

		```
		Esto ejecuta "comando1" y utiliza su salida estándar como entrada estándar para "comando2".

		Esto es útil para encadenar varios comandos y realizar operaciones más complejas.

		```
		head | date salida.txt

		```
		Al usar 10 líneas sale del comando. 


	4. Redirigir la Salida Estándar y la Salida de Error Estándar (2>&1): 

		Puedes redirigir tanto la salida estándar (stdout) como la salida de error estándar (stderr) al mismo lugar.

		```
		comando > salida.txt 2>&1

		```
		Enviará tanto la salida estándar como la salida de error a "salida.txt".


	5. Generar informes y estadísticas:

		Puedes utilizar la redirección de salida para extraer datos de archivos o comandos y generar informes o estadísticas. 

		Esto es común en el procesamiento de registros y la generación de informes automatizados.

	
	6. Depuración y registro: 

		Al redirigir la salida de error estándar (stderr) a un archivo diferente, puedes separar los mensajes de error de la salida normal.

		Esto es útil cuando estás depurando un programa o script y deseas examinar los errores más tarde 

		```
		comando 2> errores.txt

		```


	7. Mantener un registro de comandos: 

		Cuando estás trabajando en una tarea compleja o realizando una serie de comandos, redirigir la salida estándar a un archivo de registro te permite documentar lo que has hecho y facilita la revisión y el seguimiento de tus acciones.


	8. Generar salidas formateadas: 

		Al redirigir la salida estándar a un archivo o tubería, puedes formatear los datos en la forma deseada para su uso posterior o para que sean más legibles.





	Permite capturar y manipular la salida de los comandos de diversas formas, como guardarla en archivos, filtrarla a través de otros comandos o suprimirla por completo.



|| cat
	
	Concatenar y mostrar el contenido de archivos en la salida estándar (normalmente, la pantalla). 

	El nombre "cat" es una abreviatura de "concatenate", que significa "concatenar".

	Aunque su función principal es mostrar el contenido de archivos, también se utiliza para crear nuevos archivos o concatenar varios archivos en uno solo.
	
	```	
	cat [opciones] archivo1 [archivo2...]

	```

	[opciones]: 

		Modificar "cat". 

   		-n: 

   			Mostrar números de línea junto al contenido.

    	-b: 

    		Mostrar números de línea solo en líneas no vacías.

    	-E: 

    		Mostrar un carácter "$" al final de cada línea.

    	-T: 

    		Mostrar caracteres de tabulación como "^I".


	[archivo1] [archivo2...]:

		Especifica uno o más archivos cuyo contenido deseas mostrar o concatenar.

		Puedes proporcionar varios nombres de archivo para mostrar o concatenar varios archivos en el orden en que se enumeran


	Ejemplos:

		```
		cat archivo.txt	
		
		cat archivo1.txt archivo2.txt archivo3.txt

		cat archivo1.txt archivo2.txt > archivo_combinado.txt

		cat -n archivo.txt

		```

		Mostrar el contenido completo de un archivo llamado "archivo.txt".

		Mostrar el contenido de varios archivos uno tras otro.

		Crear un nuevo archivo combinando el contenido de dos archivos y guardarlos en un tercero.

		Mostrar el contenido de un archivo con números de línea.



|| less

	Visualizar y navegar a través de archivos de texto largos o que no caben completamente en la pantalla. 

	A diferencia del comando "cat", que simplemente muestra el contenido de un archivo en su totalidad, "less" permite que los usuarios desplacen y naveguen por el contenido de manera más eficiente.

	```
	less [opciones] archivo

	```


	[opciones]: 

		Personalizar la visualización y la navegación en "less". 

	    -N: 
	    	Muestra números de línea.

	    -i: 

	    	Realiza búsquedas sin distinción entre mayúsculas y minúsculas.

	    -f: 

	    	Muestra una indicación al final del archivo.

	    -q: 

	    	Sale de "less" después de mostrar el archivo si este cabe en una sola pantalla.

	    -G: 

	    	Desactiva la búsqueda de coincidencias en líneas largas.

	    -r: 

	    	Muestra caracteres de control ANSI en color.

	    -h: 

	    	Muestra una ayuda con las teclas de navegación en la parte inferior.


	[archivo]: 

		Especifica el nombre del archivo de texto que deseas ver con "less". 

		Puede ser una ruta absoluta o relativa al archivo.


	Controles de la visualización de archivos:

		Flechas arriba y abajo para desplazarte hacia arriba y hacia abajo en el archivo.

		Barra espaciadora para avanzar una página completa hacia adelante.

		B" para retroceder una página completa hacia atrás.

		Barra diagonal ("/") seguida de un término de búsqueda para buscar texto en el archivo.

		"q" para salir de "less" y regresar al shell.



|| echo

	Se utiliza para imprimir o mostrar mensajes de texto en la pantalla o para redirigirlos hacia un archivo. 

	Es una forma simple de generar salidas de texto y se usa con frecuencia en scripts de shell y secuencias de comandos para mostrar información al usuario o para generar resultados.

	```
	echo [opciones] [mensaje]

	```
	
	[opciones]: 

		Puedes proporcionar opciones para personalizar la salida del comando "echo". 

		Sin embargo, las opciones disponibles pueden variar según el sistema operativo y la shell que estés utilizando. 

		En la mayoría de las shells, las opciones comunes incluyen: 

		-n: 

			Suprimir el salto de línea al final. 

		-e: 

			Interpretar secuencias de escape en el mensaje.


	[mensaje]: 

		Es el texto que deseas imprimir en la pantalla o redirigir a un archivo.

		Puede ser una cadena de caracteres o una variable que contenga texto	


	Ejemplos: 

		```
		echo "Hola, mundo!"

		```
		Mostrar un mensaje en la pantalla.


		```
		mi_variable=$(echo "Este es un mensaje.")

		```
		Almacenar el resultado de "echo" en una variable.


		```
		echo "Esto se guardará en un archivo." > archivo.txt

		```
		Redirigir la salida de "echo" a un archivo de texto.


		```	
		# script.sh
		echo "Proceso en curso..."

		```
		Utilizar "echo" en un script para mostrar información.


		```	
		echo -e "Línea 1\nLínea 2\nLínea 3"

		```
		Utilizar secuencias de escape con "echo" para dar formato al texto.



|| wc

	"word count" se usa para contar palabras, líneas y caracteres en un archivo o en la entrada estándar.

	```	
	wc [opciones] [archivo]

	```	
	w: 

		Muestra el número de palabras en el archivo.

    -l: 

    	Muestra el número de líneas en el archivo.

    -c: 

    	Muestra el número de caracteres en el archivo.


	[archivo]: 

		Especifica el nombre del archivo del cual deseas realizar el conteo. 

		Puede ser una ruta absoluta o relativa al archivo. 

		Si no se proporciona ningún archivo, "wc" contará la entrada estándar, lo que permite contar el contenido de lo que se pasa a través de una tubería o utilizando redirección.	


	Ejemplos: 

		```	
		wc documento.txt

		wc -w archivo.txt

		cat archivo.txt | wc -l			
		wc -c archivo.txt

		resultado=$(ls | wc -w)

		```

		Contar palabras, líneas y caracteres en un archivo llamado "documento.txt".

		Contar solo el número de palabras en un archivo.

		Contar líneas en la entrada estándar (útil con tuberías).

		Contar caracteres en un archivo y mostrar el resultado.

		Contar palabras en el resultado de un comando y guardar el resultado en una variable.


	"wc" es útil cuando necesitas obtener estadísticas básicas sobre el contenido de archivos de texto, como contar palabras en un documento o líneas en un archivo de registro. 

	También se utiliza en secuencias de comandos de shell y tuberías para realizar cálculos o procesamiento de datos basado en conteos.



|| pipe

	Permite tomar la salida de un comando y utilizarla como entrada para otro comando.

	El símbolo para crear una tubería es el caracter vertical (|).

	Permite encadenar comandos para realizar tareas complejas y procesamiento de datos de manera eficiente, ya que puedes combinar pequeños comandos simples para lograr una tarea más grande y compleja sin la necesidad de escribir archivos intermedios.

	```
	comando1 | comando2

	```

	La salida del "comando1" se convierte en la entrada del "comando2". 

	Los dos comandos se ejecutan en secuencia, y el resultado final es el resultado del "comando2", que se ha alimentado con la salida del "comando1".


	1. Filtrado de texto: 

		Puedes utilizar "grep" para buscar líneas que coincidan con un patrón en un archivo y luego utilizar una tubería para filtrar aún más los resultados.

		```
		cat archivo.txt | grep "palabra clave"

		```


	2. Conteo de líneas: Puedes contar las líneas en un archivo utilizando "wc -l" después de la tubería para obtener el número de líneas en el archivo.

		```
		cat archivo.txt | wc -l

		```


	3. Ordenamiento de datos: 

		Puedes ordenar las líneas de un archivo utilizando "sort" y luego utilizar una tubería para redirigir las líneas ordenadas a otro comando o archivo.

		```
		cat archivo.txt | sort | otro_comando

		```

	4. Transformación de texto:

		Puedes realizar transformaciones complejas en el texto utilizando una serie de comandos encadenados en una tubería.

		Por ejemplo, para convertir todas las letras en minúsculas y eliminar duplicados en un archivo de texto.

		```
		cat archivo.txt | tr 'A-Z' 'a-z' | sort -u

		```


	5. Procesamiento de registros de registro: 

		Puedes usar tuberías para filtrar registros de registro y extraer información relevante:

		```
		cat registro.log | grep "Error" | awk '{print $3}'

		```


	6. Manipulación de datos en tiempo real: 

		En algunos casos, puedes utilizar tuberías junto con comandos como "tail" o "less" para monitorear y procesar datos en tiempo real, como registros en un archivo de registro en constante actualización.


	7. Búsqueda y extracción de información: 

		Puedes buscar y extraer información específica de la salida de comandos utilizando herramientas como "grep" y "awk" en una tubería. 

		Para encontrar archivos que contengan una palabra clave:

		```
		find /ruta -type f | xargs grep "palabra clave"

		```



|| sort
	
	Ordenar líneas de texto en un archivo o en la entrada estándar (normalmente, la pantalla).

	Puedes usar "sort" para ordenar líneas alfabéticamente, numéricamente o basadas en otro criterio específico.

	```
	sort [opciones] [archivo]

	```

	-r: 

		Ordena en orden inverso (descendente).

    -n: 

    	Ordena numéricamente en lugar de alfabéticamente.

    -t CARACTER: 

    	Especifica un delimitador para campos si deseas ordenar por una columna específica en un archivo de valores separados por algún carácter.

    -k N[,M]: 

    	Ordena por el campo N (y opcionalmente M si se especifica), donde los campos están separados por el delimitador especificado con -t.


	[archivo]: 

		Especifica el nombre del archivo cuyas líneas deseas ordenar. 

		Puede ser una ruta absoluta o relativa al archivo. 

		Si no se proporciona ningún archivo, "sort" ordenará las líneas de la entrada estándar, lo que permite ordenar el contenido de lo que se pasa a través de una tubería o mediante redirección.


		```
		sort lista.txt

		sort -n numeros.txt

		sort -r inverso.txt

		sort -t ',' -k 2 archivo.csv

		cat archivo.txt | sort

		```	

		Ordenar líneas alfabéticamente en un archivo llamado "lista.txt".

		Ordenar líneas numéricamente en un archivo llamado "numeros.txt".

		Ordenar líneas en orden inverso en un archivo llamado "inverso.txt".

		Ordenar líneas en un archivo CSV (valores separados por comas) por la segunda columna.

		Ordenar las líneas generadas por otro comando (como "cat" o "ls").



|| Archivos CSV

	Comma-Separated Values" o "Valores Separados por Comas" son un formato comúnmente utilizado para almacenar datos tabulares, como hojas de cálculo, bases de datos simples y registros de datos en general.

	Un archivo CSV está formado por líneas de texto en las que los valores de cada fila están separados por comas u otro carácter delimitador, como punto y coma o tabulación. 	


	Características:

		Valores separados por comas: 

			El formato CSV suele usar una coma (",") como carácter delimitador para separar los valores en cada fila. 

			Sin embargo, en algunos casos, otros caracteres, como punto y coma (";") o tabulaciones, se utilizan como delimitadores.


		Filas y columnas: 

			Los datos en un archivo CSV se organizan en filas y columnas. 

			Cada fila representa un registro o una entrada de datos, y las columnas contienen los valores correspondientes para diferentes atributos o campos.


		Texto plano: 

			Los archivos CSV son archivos de texto plano, lo que significa que se pueden abrir y editar con editores de texto simples. 

			Esto los hace ampliamente compatibles y legibles por humanos.


		No tiene un estándar estricto: 

			Aunque el formato CSV es ampliamente utilizado, no hay un estándar estricto que defina cómo deben ser los archivos CSV. 

			Esto puede llevar a diferencias en la forma en que se manejan los delimitadores, las comillas para encerrar valores de texto, y otros detalles en diferentes implementaciones.


	Ejemplo: 

		```csv

		Nombre,Edad,Ciudad
		Juan,30,Nueva York
		María,28,Los Ángeles
		Carlos,35,Chicago

		```

		Cada fila representa un individuo con tres atributos: Nombre, Edad y Ciudad. 

		Las comas separan los valores en cada fila, y las filas se separan por saltos de línea.


	Pipes:	

		Procesamiento de datos CSV:

			Puedes utilizar tuberías para procesar datos en archivos CSV.

			Por ejemplo, para calcular el promedio de una columna en un archivo CSV

			```
			cat archivo.csv | cut -d ',' -f 3 | awk '{sum += $1} END {print sum/NR}'

			```


	Son utilizados en una amplia variedad de aplicaciones, como la importación y exportación de datos entre aplicaciones, el análisis de datos en hojas de cálculo, la carga de datos en bases de datos y la generación de informes. 

	Dado que son archivos de texto plano simples, son una opción versátil para compartir y manipular datos tabulares.


|| uniq
		
	Encontrar y eliminar líneas duplicadas en un archivo de texto o en la entrada estándar (normalmente, la pantalla). 

	"Uniq" es especialmente útil cuando trabajas con datos donde deseas identificar o eliminar duplicados rápidamente.

	```
	uniq [opciones] [archivo]

	```

	Opciones:

	    -d o --repeated: 

	    	Muestra solo las líneas duplicadas, es decir, aquellas que aparecen más de una vez en el archivo de entrada.

	    -u o --unique: 

	    	Muestra solo las líneas únicas, es decir, elimina las líneas duplicadas y muestra solo una instancia de cada línea única.

	    -c o --count: 

	    	Muestra el número de ocurrencias de cada línea en lugar de las propias líneas.

	    -i o --ignore-case: 

	    	Realiza la comparación de líneas sin distinción entre mayúsculas y minúsculas.


	[archivo]: 

		Especifica el nombre del archivo del cual deseas eliminar o encontrar duplicados. 

		Puede ser una ruta absoluta o relativa al archivo. 

		Si no se proporciona ningún archivo, "uniq" opera en la entrada estándar, lo que permite procesar datos que se pasan a través de tuberías o redirección.


	Ejemplos: 

		```
		uniq datos.txt

		uniq -d archivo.txt

		uniq -c archivo.txt

		uniq archivo.txt > archivo_sin_duplicados.txt

		sort archivo.txt | uniq

		```

		Eliminar líneas duplicadas y mostrar solo líneas únicas en un archivo llamado "datos.txt".

		Mostrar solo las líneas duplicadas en un archivo.

		Mostrar el número de ocurrencias de cada línea en un archivo.

		Eliminar líneas duplicadas en un archivo y guardar el resultado en un nuevo archivo.

		Eliminar líneas duplicadas en un archivo y mostrar solo líneas únicas en orden numérico.


	Cuando necesitas limpiar datos eliminando duplicados o cuando deseas contar las ocurrencias de líneas en un archivo. 

	Se utiliza comúnmente en combinación con otros comandos de la línea de comandos, como "sort" y "grep", para realizar tareas específicas de procesamiento de datos.



|| expansiones
	
	Es la forma en que la línea de comandos de Unix y Linux interpreta y expande ciertos caracteres y patrones antes de ejecutar un comando. 

	Estas expansiones permiten realizar tareas como la 'expansión de comodines' (wildcards), 'la expansión de variables' y 'la expansión de comandos'.


	Expansión de comodines (Wildcards): 

		Los comodines, como el asterisco (*) y el signo de interrogación (?), se utilizan para hacer coincidir archivos y directorios con nombres que siguen un patrón. 

		Por ejemplo, *.txt coincidirá con todos los archivos que tengan la extensión ".txt" en un directorio.


	Expansión de variables: 

		Puedes utilizar variables en la línea de comandos para almacenar y manipular datos.

		La expansión de variables se realiza reemplazando el nombre de la variable con su valor actual. 

		Por ejemplo, si tienes una variable llamada nombre con el valor "Juan", puedes hacer referencia a ella como $nombre y se expandirá a "Juan".


	Expansión de comandos: 

		La expansión de comandos permite ejecutar un comando dentro de otro comando y reemplazarlo con la salida del comando interno. 

		Esto se hace utilizando comillas invertidas (` `) o $(). Por ejemplo, echo $(date) mostrará la fecha y hora actual.


	Expansión de rutas: 

		Cuando proporcionas una ruta relativa o absoluta a un archivo o directorio como argumento a un comando, la línea de comandos expande la ruta a su ubicación completa antes de ejecutar el comando.


	Expansión de variables de entorno: 

		Puedes acceder a las variables de entorno del sistema utilizando la notación $VAR, donde VAR es el nombre de la variable de entorno. 

		Por ejemplo, $HOME se expandirá a la ruta del directorio de inicio del usuario actual.


	Expansión de tilde (~): 

		El símbolo de tilde (~) se utiliza para representar el directorio de inicio del usuario. 

		Por ejemplo, ~/Documentos se expandirá a la ruta al directorio "Documentos" en el directorio de inicio del usuario actual.


	Ejemplos: 

	Expansión de comodines (Wildcards):

	    *: 

	    	Coincide con cualquier conjunto de caracteres, incluyendo ninguno.

	    ?: 

	    	Coincide con un solo carácter.

	    [conjunto]: 

	    	Coincide con un solo carácter que esté en el conjunto especificado.

	    [!conjunto] o [^conjunto]:

	    	Coincide con un solo carácter que no esté en el conjunto especificado.


	Expansión de variables:

	    $nombre_variable: 

	    	Expande el valor de la variable nombre_variable.


	Expansión de comandos:

	    `comando`: 

	    	Ejecuta el comando y reemplaza la expansión con la salida del comando.

	    $(comando): 

	    	Similar a `comando`, ejecuta el comando y reemplaza la expansión con la salida del comando.


	Expansión de rutas:

	    ~/directorio: 

	    	Expande a la ruta completa del directorio en el directorio de inicio del usuario.

	    ../directorio: 

	    	Expande a la ruta del directorio un nivel superior.

	    /ruta/completa/directorio:

	    	Expande a la ruta completa especificada.


	Expansión de variables de entorno:

	    $VAR: 

	    	Expande a la variable de entorno VAR.


	Expansión de alias:

	    $alias: 

	    	Expande a la expansión del alias si existe.


	Expansión de historia:

	    !n: 

	    	Expande a un comando específico del historial por su número.

	    !!: 
	    	Expande al último comando ejecutado.

	    !string: 

	    	Expande al último comando que comienza con "string".


	Expansión de caracteres especiales:

	    \: 

	    	Escapa un carácter especial para que se interprete literalmente.


	Expansión aritmética:

	    $((expresión)): 

	    	Permite realizar cálculos aritméticos y expandir el resultado.


	Expansión de longitud de cadena:

	    ${#variable}: 

	    	Expande a la longitud de la cadena contenida en la variable.
	


|| diff

	Comparar dos archivos de texto línea por línea y mostrar las diferencias entre ellos. 

	Es una herramienta útil para identificar y visualizar las discrepancias entre dos conjuntos de datos o dos versiones de un archivo. 

	Especialmente útil en situaciones en las que necesitas realizar un seguimiento de las modificaciones realizadas en un archivo a lo largo del tiempo o cuando deseas verificar la igualdad o diferencia entre dos archivos.

	```
	diff [opciones] archivo1 archivo2

	```

	[opciones]:

        -u o --unified: 

        	Produce una salida en formato unificado que muestra las diferencias en un formato más legible y que se utiliza a menudo para parches.

        -c o --context: 

        	Produce una salida en formato de contexto, que incluye líneas de contexto alrededor de las diferencias.

        -i o --ignore-case:

        	Realiza la comparación de archivos sin distinción entre mayúsculas y minúsculas.

        -q o --brief: 

        	Muestra un mensaje simple indicando si los archivos son iguales o diferentes.


    archivo1 y archivo2: 

    	Estos son los nombres de los dos archivos que deseas comparar.


    Ejemplos:

    	```
    	diff -u archivo1.txt archivo2.txt

    	diff -c archivo1.txt archivo2.txt

    	diff -q archivo1.txt archivo2.txt

		diff -r directorio1/ directorio2/ 
		
		diff -u archivo_original.txt archivo_modificado.txt > parche.diff   	

    	```

    	Comparar dos archivos y mostrar las diferencias en el formato unificado.

    	Comparar dos archivos y mostrar las diferencias en formato de contexto.

    	Verificar si dos archivos son iguales (sin mostrar las diferencias).

    	Comparar directorios enteros (recursivamente).

    	Generar un archivo de parche con las diferencias.



|| find
	
	Buscar archivos y directorios en un sistema de archivos basado en una serie de criterios de búsqueda. 

	Permite encontrar archivos y directorios que coincidan con patrones específicos en una jerarquía de directorios, lo que es útil para tareas de administración de archivos y búsqueda de contenido.

	```
	find [directorio] [opciones] [patrón]

	```

	[directorio]:

		Especifica el directorio desde el cual comenzar la búsqueda. 

		Si no se proporciona, "find" buscará desde el directorio actual.


    [opciones]: 

        -name patron: 

        	Busca archivos y directorios cuyos nombres coincidan exactamente con el patrón especificado.

        -type tipo: 

        	Permite buscar solo archivos (f) o directorios (d).

        -mtime n: 

        	Encuentra archivos modificados en los últimos n días.

        -size n: 

        	Encuentra archivos con un tamaño específico.

        -exec comando {} \;: 

        	Ejecuta un comando en cada archivo encontrado.


    [patrón]: 

    	Especifica un patrón de búsqueda para los nombres de archivo o directorio.

    	Puedes utilizar comodines (wildcards) para patrones más flexibles.


    Ejemplo: 

    	```
    	find . -name archivo.txt

    	```
    	Buscar un archivo por nombre en el directorio actual y sus subdirectorios.


    	```
    	find /ruta/del/directorio -type f -name "*.log"

    	```
    	Buscar todos los archivos en un directorio y sus subdirectorios que tengan la extensión ".log".


    	```
    	find /ruta/del/directorio -type d -empty

    	```
    	Buscar directorios vacíos en un directorio específico.


    	```
    	find /ruta/del/directorio -type f -mtime -7

    	```
    	Buscar archivos modificados en los últimos 7 días en un directorio y sus subdirectorios.


    	```
    	find /ruta/del/directorio -type f -mtime +30 -exec rm {} \;
    	```
    	Eliminar archivos antiguos en un directorio y sus subdirectorios (ten cuidado con este comando).



    	```
    	find /ruta/del/directorio -type f -size +100M

    	```
    	Buscar archivos grandes (más de 100 MB) en un directorio y sus subdirectorios.



|| grep

	Buscar patrones de texto en archivos o en la entrada estándar. 

	El nombre "grep" proviene de la palabra "global/regular expression/print" y es una herramienta poderosa para buscar y filtrar líneas de texto que coinciden con un patrón especificado. 

	Puedes usar "grep" para buscar palabras, frases o patrones específicos en archivos de texto.

	```
	grep [opciones] patrón [archivo(s)]

	```
	[opciones]:

	    -i o --ignore-case: 

	    	Realiza la búsqueda sin distinción entre mayúsculas y minúsculas.

	    -r o --recursive: 

	    	Realiza una búsqueda recursiva en directorios y subdirectorios.

	    -l o --files-with-matches:

	    	Muestra solo los nombres de los archivos que contienen al menos una coincidencia.

	    -n o --line-number: 

	    	Muestra los números de línea junto con las coincidencias encontradas.


	patrón: 

		Especifica el patrón de texto que deseas buscar en los archivos.
	

	[archivo(s)]: 

		Son los archivos en los que deseas realizar la búsqueda.

		Puedes proporcionar uno o varios nombres de archivo.


	Ejemplos: 

		```
		grep "patron" archivo.txt

		```
		Buscar una palabra en un archivo específico.


		```
		grep "patron" archivo1.txt archivo2.txt.

		```
		Buscar una palabra en varios archivos.


		```
		grep -r "patron" /ruta/del/directorio

		```
		Buscar una palabra en todos los archivos de un directorio (de manera recursiva).


		```
		grep -i "patron" archivo.txt

		```
		Buscar una palabra ignorando mayúsculas y minúsculas.


		```
		grep -n "123" archivo.txt

		```
		Buscar un patrón numérico en un archivo junto con los números de línea.


		```
		grep -v "patron" archivo.txt

		```
		Buscar un patrón inverso (líneas que NO coinciden con el patrón).


	Utilizado para buscar información específica en archivos de registro, código fuente, documentos de texto y más. 

	Puedes combinar "grep" con otras herramientas de la línea de comandos, como "find" y "sed", para realizar tareas más avanzadas de manipulación y extracción de datos.



|| kill
	
	Enviar señales a procesos en ejecución con el fin de controlar su comportamiento o terminarlos. 

	Es una herramienta esencial para administrar procesos en un sistema y es especialmente útil cuando necesitas finalizar un proceso que no responde o realizar otras acciones relacionadas con el control de procesos.

	```
	kill [opciones] PID

	```

	[opciones]: 
		
        -l o --list: 

        	Muestra una lista de todas las señales disponibles.

        -s o --signal: 

        	Especifica la señal que deseas enviar (por ejemplo, SIGTERM, SIGKILL).

        -<numero de señal>: 

        	Puedes especificar el número de señal directamente (por ejemplo, "-9" para SIGKILL).


    PID: 

    	Es el identificador de proceso (PID) del proceso que deseas afectar. 

    	Puedes encontrar el PID de un proceso utilizando comandos como "ps" o "top".


    Ejemplo: 

    	```
    	kill 12345

    	```	
    	Finalizar un proceso específico por su PID (por ejemplo, PID 12345).


    	```
    	kill -s SIGTERM PID

    	```
    	Finalizar un proceso con una señal específica (por ejemplo, SIGTERM).


    	```
    	kill -9 PID

    	```
    	Finalizar un proceso de manera forzada con la señal SIGKILL (también puede usarse con el número de señal -9).


    	```
    	kill -l

    	```
    	Listar todas las señales disponibles.


    	```
    	kill -s SIGSTOP PID

    	```
    	Enviar una señal al proceso en segundo plano usando su PID (por ejemplo, SIGSTOP para suspender el proceso).



|| kilall
	
	Finalizar procesos basándose en sus nombres en lugar de sus identificadores de proceso (PID). 

	Es una herramienta útil cuando deseas detener todos los procesos que tienen un nombre específico. 

	Esto puede ser útil cuando tienes múltiples instancias de un programa en ejecución y deseas detenerlas todas al mismo tiempo.

	```
	killall [opciones] nombre_del_proceso

	```

	[opciones]:

        -e o --exact: 

        	Especifica que el nombre del proceso debe coincidir exactamente con el nombre proporcionado.

        -s o --signal: 

        	Permite especificar la señal que deseas enviar a los procesos. 

        	De forma predeterminada, se envía SIGTERM.

        -u o --user: 

        	Permite especificar el usuario que debe ser propietario de los procesos a finalizar.


    nombre_del_proceso: 

    	Es el nombre del proceso que deseas finalizar. 

    	Puede ser el nombre del programa o el comando utilizado para iniciar el proceso.


    Ejemplos: 

    	```
    	killall myprogram

    	```
    	Finalizar todos los procesos con un nombre específico (por ejemplo, "myprogram").


    	```
    	killall -s SIGKILL myprogram

    	```
    	Finalizar todos los procesos con un nombre específico utilizando una señal diferente (por ejemplo, SIGKILL).


    	```
    	killall -e myprogram

    	```
    	Finalizar todos los procesos con un nombre exacto (coincidencia exacta) (por ejemplo, solo "myprogram" y no otros nombres que lo contengan).


    	```
    	killall -u user1 myprogram

    	```
    	Finalizar todos los procesos con un nombre específico que pertenezcan a un usuario específico (por ejemplo, "user1").



|| nano
	
	Editor de texto en línea de comandos que se utiliza en sistemas Unix y Linux. 

	Es una herramienta simple y fácil de usar, especialmente para usuarios principiantes o aquellos que prefieren una interfaz de usuario más sencilla en comparación con editores de texto más avanzados como "vi" o "emacs".

	
	```
	nano nombre_del_archivo

	```	
	Abrir un archivo.


	Atajos: 	

		Ctrl + O: Guardar el archivo.
		Ctrl + X: Salir de nano.
		Ctrl + G: Mostrar la ayuda de nano.
		Ctrl + K: Cortar texto.
		Ctrl + U: Pegar texto.
		Ctrl + W: Buscar texto.
		Ctrl + \: Reemplazar texto
		Ctrl + G: Ayuda, detalles y opciones.


	Ejemplos:

		```
		nano archivo.txt

		```
		Abrir un archivo existente.


		```
		nano nuevo_archivo.txt

		```
		Crear un nuevo archivo y editarlo.


		```
		nano mi_script.py

		```
		Abrir un archivo con resaltado de sintaxis para código fuente en Python.



|| xargs
	
	Construir y ejecutar comandos a partir de la entrada estándar o de una lista de elementos proporcionada como argumentos.

	Su nombre proviene de "eXtended ARGuments" (argumentos extendidos).

	La principal función de "xargs" es tomar una lista de elementos (por lo general, nombres de archivos o cadenas de texto) y pasarlos como argumentos a otro comando especificado. 

	Esto es especialmente útil cuando necesitas realizar una acción en varios elementos de manera eficiente. 

	Por ejemplo, podrías utilizar "xargs" para eliminar varios archivos o buscar cadenas de texto en varios archivos.	

	```
	comando_que_genera_la_lista | xargs comando_que_se_ejecutara

	```
    comando_que_genera_la_lista: 

    	Es el comando que genera la lista de elementos que deseas procesar. 

    	Este comando puede ser una tubería (pipe) o cualquier otro comando que genere una salida.


    comando_que_se_ejecutara: 

    	Es el comando que se ejecutará utilizando los elementos de la lista como argumentos.


    Ejemplos: 

    	```
    	ls *.txt | xargs rm

    	```
    	Eliminar varios archivos que coinciden con un patrón de nombres (por ejemplo, eliminar todos los archivos .txt en un directorio).


    	```
    	grep "error" *.log | xargs -n 1 -I {} echo "Se encontró error en el archivo: {}"

    	```
    	Buscar una cadena de texto en varios archivos (por ejemplo, buscar la palabra "error" en todos los archivos de registro).

    	-n 1 especifica que se procesará un elemento a la vez, y -I {} indica que se usará "{}" como marcador de posición para el elemento en el comando que se ejecutará.



    	```
    	ls *.txt | xargs wc -l

    	```
    	Contar la cantidad de líneas en varios archivos (por ejemplo, contar líneas en todos los archivos de texto en un directorio).


    	```
    	ls *.jpg | xargs -I {} cp {} /directorio/destino/

    	```
    	Copiar varios archivos a un directorio de destino.


    "xargs" toma la salida del comando que genera la lista y la pasa como argumentos al comando especificado. 

    Esto permite realizar acciones en lotes de elementos de manera eficiente y automatizada.


|| awk
	
	Herramienta de procesamiento de texto.

	Realiza tareas de procesamiento, análisis y manipulación de datos en archivos de texto.


	Extracción de Datos: 

		awk puede utilizarse para buscar y extraer datos específicos de un archivo de texto, basándose en patrones o campos específicos. 

		Es especialmente útil cuando se trabaja con archivos de registro o archivos de datos estructurados.


    Transformación de Datos: 

    	Puedes utilizar awk para aplicar transformaciones a los datos de entrada, como cambiar el formato de fecha, reemplazar caracteres o realizar cálculos matemáticos en los números.


    Generación de Informes: 

    	awk es útil para generar informes o resúmenes a partir de datos de entrada.

    	Puedes calcular estadísticas, contar registros, realizar agregaciones y más.


    Manipulación de Campos y Columnas: 

    	awk permite dividir líneas en campos y trabajar con columnas específicas de datos. 

    	Puedes modificar, eliminar o reorganizar columnas según sea necesario.


    Automatización de Tareas: 

    	awk se puede utilizar en scripts y secuencias de comandos para automatizar tareas de procesamiento de datos de manera eficiente.


    ```
    awk 'patrón {acción}' archivo

    ```
    patrón: 

    	Es una expresión que describe qué líneas de entrada deben procesarse. 

    	Si no se proporciona un patrón, awk procesará todas las líneas de entrada.


    acción: 

    	Es el conjunto de instrucciones que se ejecutarán en las líneas que coincidan con el patrón. 

    	Puede incluir comandos para trabajar con campos, realizar cálculos, imprimir resultados y más.


    Ejemplos: 

    	```
    	awk '{print}' archivo

    	```
    	imprimir todas las líneas de un archivo.


    	```	
    	awk -F ',' '{print $1}' archivo.csv

    	```
    	Imprimir la primera columna de un archivo CSV (valores separados por comas).


    	```
    	awk '/error/ {print}' archivo.log

    	```
    	Encontrar líneas que contengan la palabra "error" en un archivo de registro.


    	```
    	awk '{suma += $1} END {promedio = suma / NR; print promedio}' archivo.txt

    	```
    	Calcular el promedio de una columna de números en un archivo.


    Su capacidad para trabajar con patrones y campos hacen que sea una herramienta poderosa para automatizar tareas relacionadas con datos en sistemas Unix.


|| sed


|| chowm


|| chmod


|| ln


|| history
	
	Mostrar una lista de comandos previamente ejecutados en la sesión actual del terminal.

	```
	history

	```
	Lista completa de comandos ejecutados en la sesión actual.


	```
	!25

	```
	Ejecutar comando anterior utilizando el número de comando mostrado en la lista de historial (ej. Número 25).
	

	```
	!!

	```
	Ejecutar el último comando ejecutado (equivalente a !!).


	```
	!-1

	```
	Ejecutar el comando anterior (equivalente a !-1).


	```
	!buscar

	```
	Ejecutar un comando específico por su contenido (por ejemplo, ejecutar el último comando que contenía la palabra "buscar").


	El historial de comandos es específico de la sesión actual del terminal. 

	Cuando cierras la sesión o el terminal, el historial se pierde, a menos que se haya configurado para que se almacene en un archivo específico. 

	Además, la cantidad de comandos que se mantienen en el historial puede estar limitada por la configuración del sistema, por lo que es posible que no todos los comandos se muestren en la lista de historial.



|| alias
	


-----

|| Comandos red/inet

|| who
	
	Mostrar información sobre los usuarios que están actualmente conectados al sistema. 

	Proporciona detalles como los nombres de usuario, las terminales que están utilizando y la hora en que iniciaron sesión. 

	"who" es útil para ver quién está interactuando con el sistema en un momento dado.

	```
	who

	```
	Sin opciones muestra una lista de usuarios que están actualmente conectados al sistema, con información sobre sus sesiones, como el nombre de usuario, la terminal (tty), la fecha y la hora en que iniciaron sesión.

	```
	usuario1  tty1         2023-10-01 10:00
	usuario2  pts/0        2023-10-01 11:30 (192.168.1.2)
	usuario3  pts/1        2023-10-01 12:15 (192.168.1.3)

	```
	Muestra que tres usuarios están conectados al sistema:

    "usuario1" está conectado a través de la terminal "tty1" a las 10:00.

    "usuario2" está conectado a través de la terminal pseudo-TTY "pts/0" a las 11:30 desde la dirección IP 192.168.1.2.

    "usuario3" está conectado a través de la terminal pseudo-TTY "pts/1" a las 12:15 desde la dirección IP 192.168.1.3.


	Opciones: 	

		-H: 

			Muestra encabezados de columna en la salida.
    	
    	-q: 

    		Muestra solo la cantidad de usuarios conectados en lugar de detalles completos.


   	Ejemplos: 

   		```
   		who -q

   		```
   		Mostrar solo la cantidad de usuarios conectados.

   		Salida:

   		```
   		Usuarios conectados: 3

   		```




|| ttyX
	
	Las terminales con nombres como "tty1", "tty2", etc., representan las consolas virtuales o terminales físicas del sistema. 

	En sistemas Linux, generalmente hay varias consolas virtuales disponibles (por ejemplo, "tty1" a "tty6") que los usuarios pueden usar para iniciar sesión directamente en el sistema.

	Estas son las terminales de texto que puedes ver presionando Ctrl + Alt + F1 hasta Ctrl + Alt + F6 en muchos sistemas	



|| pts/X
	
	pts/X (Terminal de seudoterminal), Las terminales con nombres como "pts/0", "pts/1", etc., representan terminales de seudoterminal.

	Estas son sesiones de usuario que se inician en un entorno gráfico o que se conectan de forma remota al sistema a través de SSH u otros protocolos de acceso remoto. 

	Las terminales de seudoterminal son típicamente utilizadas por usuarios que inician sesión en el sistema desde una interfaz gráfica de usuario o desde una conexión SSH.


	?: 

		En algunas salidas de "who", es posible que veas un signo de interrogación "?" en lugar de nombres específicos de terminales. 

		Esto generalmente indica que la información sobre la terminal no está disponible o que la terminal se ha desconectado.
	

|| netstat
	
	Mostrar información detallada sobre la configuración de red, conexiones de red activas y estadísticas de red. 

	Con "netstat", puedes obtener información sobre los puertos que están en escucha (listening), las conexiones de red activas, las tablas de enrutamiento y más. 

	Esta herramienta es útil para diagnosticar problemas de red y monitorear la actividad de red en un sistema.

	```
	netstat [opciones]

	```
	opciones:  

		Personalizar la salida y la información que se muestra.


	Ejemplos: 

		```
		netstat -tuln

		```
		Mostrar conexiones activas.

		Para ver una lista de todas las conexiones de red activas.

		Mostrará una lista de puertos en escucha (listening) y las conexiones establecidas en el sistema.


		```
		netstat -s

		```
		Mostrar estadísticas detalladas.

		Si deseas obtener estadísticas detalladas sobre las interfaces de red, las conexiones y más, puedes usar la opción "-s" o "--statistics".

		Esto mostrará una amplia gama de estadísticas de red, como paquetes transmitidos, paquetes recibidos, errores, y más.


		```
		netstat -r

		```
		Mostrar información sobre las rutas de red. 

		Para ver la tabla de enrutamiento del sistema, puedes utilizar la opción "-r".

		Mostrará la tabla de enrutamiento, que indica cómo se dirigen los paquetes de red en el sistema.


		```
		netstat -tuln -p

		```
		Mostrar programas que utilizan puertos.

		Puedes usar la opción "-p" para ver qué programas están utilizando los puertos.

		Mostrará los programas junto con los puertos que están en escucha.


		```
		netstat -i nombre_de_interfaz

		```
		Mostrar información detallada de una interfaz específica.

		Para ver información detallada sobre una interfaz de red específica, puedes usar la opción "-i" seguida del nombre de la interfaz.


		```
		netstat -x

		```
		Mostrar conexiones UNIX.

		Para ver conexiones UNIX locales, puedes usar la opción "-x".

		Mostrará conexiones UNIX locales utilizadas por procesos en el sistema.


		```
		netstat -I

		```
		Mostrar estadísticas ICMP.

		Si deseas ver estadísticas específicas sobre el protocolo ICMP (Internet Control Message Protocol), puedes usar la opción "-I".


	En algunos sistemas más recientes, "netstat" ha sido reemplazado por herramientas como "ss" y "ip", que ofrecen funcionalidades similares pero con opciones más avanzadas.



|| ssh
	
	Protocolo de red seguro que se utiliza para acceder de forma segura a sistemas remotos a través de una conexión encriptada. 

	SSH permite a los usuarios iniciar sesión y gestionar sistemas remotos de manera segura, así como transferir datos de manera segura entre sistemas. 

	Es una herramienta fundamental en la administración de sistemas y en el trabajo con servidores remotos.


    Autenticación segura: 

    	SSH utiliza un método de autenticación fuerte basado en criptografía de clave pública/privada. 

    	Esto significa que los usuarios pueden autenticarse en un servidor remoto sin enviar contraseñas en texto claro por la red. 

    	En lugar de eso, generan un par de claves (una pública y una privada) y solo la clave pública se comparte con el servidor.


    Cifrado de datos: 

    	Todas las comunicaciones entre el cliente y el servidor SSH están cifradas, lo que garantiza la confidencialidad de los datos transmitidos. 

    	Esto es especialmente importante cuando se trata de datos sensibles, como contraseñas o información confidencial.


    Túneles seguros: 

    	SSH permite crear túneles seguros para redirigir el tráfico de red a través de una conexión SSH. 

    	Esto es útil para proteger el tráfico de red en redes no seguras o para acceder a servicios que de otro modo no serían accesibles de forma segura.


    Acceso a la línea de comandos remota: 

    	SSH permite a los usuarios iniciar sesión en un sistema remoto y ejecutar comandos en la línea de comandos de ese sistema como si estuvieran físicamente presentes en el mismo.


    Transferencia segura de archivos: 

    	Además del acceso a la línea de comandos, SSH también proporciona un protocolo llamado SFTP (SSH File Transfer Protocol) para transferir archivos de manera segura entre sistemas.


    Reenvío de X11: 

    	SSH puede reenviar conexiones de servidor gráfico X11 de manera segura, lo que permite ejecutar aplicaciones gráficas en un servidor remoto y verlas en la máquina local.


    Puertos personalizables: 

    	SSH generalmente utiliza el puerto 22 de forma predeterminada, pero se puede configurar para utilizar otros puertos si es necesario. 

    	Esto es útil para evitar ataques automatizados en el puerto estándar.



|| SCP
	
	Es un comando y un protocolo de red que se utiliza para copiar archivos y directorios de forma segura entre dos sistemas, generalmente a través de una conexión SSH (Secure Shell).

	SCP proporciona una forma segura y cifrada de transferir archivos entre una máquina local y un sistema remoto, o entre dos sistemas remotos.

	```
	scp [opciones] origen destino

	```
	opciones: 

		Personalizar la operación de SCP, como la especificación de un puerto SSH personalizado, la visualización del progreso de la transferencia y más.

		Puedes consultar la página de manual de SCP escribiendo 'man scp' en la terminal para obtener más detalles sobre estas opciones.



    origen: 

    	Especifica el archivo o directorio que deseas copiar. 

    	Puede ser una ruta local o remota en la forma "usuario@host:archivo_o_directorio".


    destino: 

    	Indica la ubicación de destino donde se copiarán los archivos o directorios.

    	Al igual que el origen, puede ser una ruta local o remota.


    Ejemplos: 

    	```
    	scp archivo.txt usuario@host:/ruta/remota/

    	```
		Copiar archivos desde local a remoto.

		Para copiar un archivo desde tu máquina local a un sistema remoto, puedes usar SCP de la siguiente manera.

		Copiará "archivo.txt" desde tu máquina local al sistema remoto en la ubicación "/ruta/remota/".


		```
		scp usuario@host:/ruta/remota/archivo.txt archivo_local.txt

		```
		Copiar archivos desde remoto a local.

		Para copiar un archivo desde un sistema remoto a tu máquina local, simplemente invierte el orden de origen y destino.

		Copiará "archivo.txt" desde el sistema remoto a tu máquina local con el nombre "archivo_local.txt".


		```
		scp -r directorio usuario@host:/ruta/remota/

		```
		Copiar directorios de forma recursiva.

		SCP también puede copiar directorios de forma recursiva utilizando la opción "-r" (recursivo).

		Copiará todo el contenido del directorio y sus subdirectorios al sistema remoto.





	

|| wget

|| dig



----


|| POSIX
	
	'Portable Operating System Interface for Unix' o 'Interfaz Portátil del Sistema Operativo' para Unix. 

	Es un conjunto de estándares que define la interfaz y el comportamiento de las funciones del sistema operativo en sistemas tipo Unix. 

	Los estándares POSIX fueron desarrollados para promover la compatibilidad y la portabilidad entre sistemas Unix y sistemas similares a Unix, como sistemas Linux y sistemas BSD (Berkeley Software Distribution). 

	POSIX define una serie de especificaciones que los sistemas Unix deben seguir para garantizar la interoperabilidad entre diferentes implementaciones de Unix.


	Estandarización: 

		POSIX estandariza la interfaz de programación de aplicaciones (API) y el comportamiento del sistema operativo en áreas como la manipulación de archivos, la administración de procesos, la comunicación entre procesos, la administración de usuarios y grupos, la administración de señales y más.


    Portabilidad: 

    	Uno de los objetivos principales de POSIX es permitir que las aplicaciones escritas para un sistema Unix funcionen en otros sistemas Unix compatibles sin modificaciones significativas. 

    	Esto facilita la portabilidad de software entre diferentes implementaciones de Unix.


    Compatibilidad: 

    	Los sistemas operativos que cumplen con las especificaciones POSIX se consideran compatibles entre sí en términos de la API del sistema. 

    	Esto significa que las aplicaciones desarrolladas para uno de estos sistemas deberían funcionar en otros sistemas compatibles sin requerir cambios significativos.


    Conformidad: 

    	La conformidad con POSIX puede variar entre sistemas operativos y versiones. 

    	Los sistemas pueden cumplir con diferentes niveles de especificaciones POSIX, como POSIX.1 o POSIX.2, dependiendo de las características que implementen.


    Estándares relacionados: 

    	Además de POSIX.1, que establece las funciones básicas del sistema operativo, existen otros estándares POSIX relacionados que abordan áreas específicas, como POSIX.2 (para la línea de comandos y utilidades), POSIX.3 (para interfaces de tiempo), POSIX.4 (para comunicaciones en tiempo real) y más.


    Certificación POSIX: 

    	Algunas organizaciones y sistemas operativos buscan la certificación POSIX para demostrar su cumplimiento con los estándares POSIX.

    	Esto es especialmente importante en entornos gubernamentales y militares donde la interoperabilidad y la portabilidad son críticas.


    Beneficios: 

    	Los estándares POSIX han contribuido significativamente a la interoperabilidad de software en el mundo Unix y han permitido que aplicaciones y utilidades desarrolladas en un sistema Unix funcionen en otros sistemas Unix sin modificaciones importantes.



|| stdin
	
	standard input o entrada estándar, es uno de los tres flujos de datos estándar que están disponibles en la mayoría de los sistemas operativos Unix y Linux, junto con "stdout" (salida estándar) y "stderr" (salida de error estándar).

	"stdin" se refiere al canal o flujo de entrada a través del cual un programa o proceso puede recibir datos desde una fuente externa, como un archivo, un dispositivo o, más comúnmente, desde la entrada del teclado del usuario. 

	Es la forma estándar en la que los programas en línea de comandos, scripts y aplicaciones en Unix y Linux aceptan datos de entrada.


	Entrada de Teclado: 

		Cuando un programa espera entrada del usuario, por ejemplo, un comando en la línea de comandos, generalmente lee datos desde "stdin". 

		Esto significa que puedes escribir texto o datos en el teclado y presionar "Enter" para proporcionar la entrada al programa.


	Redirección: 

		"stdin" se puede redirigir para que los datos provengan de un archivo en lugar de la entrada del teclado. 

		Por ejemplo, puedes usar el operador < en la línea de comandos para redirigir "stdin" desde un archivo específico.

		```
		mi_programa < archivo_de_entrada.txt

		```
		"mi_programa" leerá la entrada desde "archivo_de_entrada.txt" en lugar de esperar que el usuario escriba algo en el teclado.


	Pipes (tuberías): 

		"stdin" se puede conectar a la "stdout" de otro programa mediante el uso de tuberías (pipes). 

		Esto permite que los programas se comuniquen entre sí y procesen datos de manera continua.

		```
		programa1 | programa2

		```	
		La salida estándar de "programa1" se convierte en la entrada estándar de "programa2" a través de una tubería.	
		

	Cierre de "stdin": 

		Algunos programas pueden cerrar "stdin" después de leer todos los datos que necesitan. 

		Esto evita que el programa espere continuamente más entrada del usuario o de un archivo.



|| stdout
	
	standard output o salida estándar, es uno de los tres flujos de datos estándar que están disponibles en la mayoría de los sistemas operativos Unix y Linux, junto con "stdin" (entrada estándar) y "stderr" (salida de error estándar).

	"stdout" se refiere al canal o flujo de salida a través del cual un programa o proceso envía datos o resultados a una ubicación de destino. 

	Es la forma estándar en la que los programas en línea de comandos, scripts y aplicaciones en Unix y Linux presentan información al usuario o redirigen datos para su procesamiento o almacenamiento.


	Salida a la Pantalla: 

		Cuando un programa genera resultados, mensajes o datos de salida, generalmente los envía a "stdout". 

		Esto significa que los resultados se muestran en la pantalla del usuario por defecto.


	Redirección: 

		"stdout" se puede redirigir para que los datos de salida se envíen a un archivo en lugar de mostrarse en la pantalla. 

		Puedes usar el operador > en la línea de comandos para redirigir la salida estándar a un archivo

		```
		programa > archivo_de_salida.txt

		```
		La salida generada por "programa" se guarda en el archivo "archivo_de_salida.txt" en lugar de mostrarse en la pantalla.


	Tuberías (Pipes): 

		"stdout" se puede conectar a la "stdin" de otro programa mediante el uso de tuberías (pipes). 

		Esto permite que los programas se comuniquen entre sí y procesen datos de manera continua.

		```
		programa1 | programa2

		```
		la salida estándar de "programa1" se convierte en la entrada estándar de "programa2" a través de una tubería.


	Redirección de Errores: 

		A veces, los mensajes de error también se envían a "stdout". 

		Para separar la salida normal de los errores, es común redirigir "stdout" y "stderr" a ubicaciones diferentes.

		```
		programa > archivo_de_salida.txt 2> archivo_de_errores.txt

		```
		La salida estándar se redirige a "archivo_de_salida.txt", mientras que los errores se redirigen a "archivo_de_errores.txt".



|| stderr
	
	standard error o salida de error estándar, uno de los tres flujos de datos estándar que están disponibles en la mayoría de los sistemas operativos Unix y Linux.

	Canal o flujo de salida a través del cual un programa o proceso envía mensajes de error, advertencias o información de diagnóstico. 

	A diferencia de "stdout", que se usa para datos y resultados normales, "stderr" se utiliza específicamente para indicar problemas o excepciones en la ejecución de un programa.


	Mensajes de Error: 

		Cuando un programa encuentra un error o una condición excepcional durante su ejecución, generalmente envía un mensaje de error a "stderr". 

		Estos mensajes pueden incluir información sobre lo que salió mal y por qué.


	Separación de Salida y Errores:

		La separación de "stdout" y "stderr" es útil para distinguir entre la salida normal del programa y los mensajes de error. 

		Esto permite que los usuarios o scripts de automatización redirijan y gestionen los mensajes de error de manera diferente de la salida normal.


	Redirección de "stderr": 

		Al igual que "stdout", "stderr" se puede redirigir a un archivo o a otro destino. 

		Puedes utilizar el operador 2> para redirigir "stderr" a un archivo específico.

		```
		programa 2> archivo_de_errores.txt

		```
		Los mensajes de error generados por "programa" se escribirán en el archivo "archivo_de_errores.txt".


	Redirección Conjunta: 

		Si deseas redirigir tanto "stdout" como "stderr" a un archivo o a un destino, puedes hacerlo de la siguiente manera:	

		```
		programa > archivo_de_salida.txt 2>&1

		```	
		Redirigirá tanto la salida estándar como los mensajes de error a "archivo_de_salida.txt".


	Tuberías (Pipes): 

		Al igual que "stdout", "stderr" se puede conectar a la "stdin" de otro programa mediante el uso de tuberías (pipes). 

		Esto permite que los programas capturen y procesen los mensajes de error generados por otros programas.

		Los pipes son eficientes porque evitan la necesidad de almacenar temporalmente grandes cantidades de datos en archivos intermedios. 

		En lugar de eso, los datos se transfieren directamente de un proceso a otro a medida que se generan y se procesan.


----


|| Comandos config

|| bash scripting

|| .bashrc file

|| ifconfig

|| wich

|| whatis


----

|| Comandos adm sys

|| su
	
	Switch User o SuperUser en sistemas Unix y Linux se utiliza para cambiar de usuario en una sesión de terminal. 

	Por lo general, se usa para acceder a cuentas de usuario con privilegios elevados, como la cuenta de superusuario (root), o para cambiar a otra cuenta de usuario en la misma terminal.

	```
	su [opciones] [nombre_de_usuario]

	```
	[opciones]: 

		Puedes proporcionar diversas opciones para controlar el comportamiento de "su".
	

	[nombre_de_usuario]: 

		Especifica el nombre de usuario al que deseas cambiar. 

		Si no se proporciona un nombre de usuario, "su" asume que deseas cambiar a la cuenta de superusuario (root) de forma predeterminada.


	```
	su

	```
	Cambiar a la cuenta de superusuario (root).

	Cuando ejecutas "su" sin especificar un nombre de usuario, se te pedirá la contraseña de la cuenta de superusuario. 

	Después de ingresar la contraseña correcta, estarás trabajando con privilegios elevados como root.


	```
	su nombre_de_usuario

	```	
	Cambiar a una cuenta de usuario específica.

	Puedes usar "su" para cambiar a otra cuenta de usuario, reemplazando "nombre_de_usuario" con el nombre de usuario de la cuenta a la que deseas cambiar.

	Deberás ingresar la contraseña de esa cuenta para iniciar sesión.


	```
	su -c "comando" nombre_de_usuario

	```
	Ejecutar comandos como otro usuario.

	Puedes utilizar "su" para ejecutar un comando específico como otro usuario. 

	Esto es útil cuando deseas ejecutar un comando en el contexto de una cuenta de usuario diferente sin cambiar por completo de sesión.


	```
	su -s /bin/sh nombre_de_usuario

	```
	Cambiar a otra cuenta con un shell específico.

	Si deseas cambiar a una cuenta de usuario y especificar un shell diferente, puedes hacerlo utilizando la opción "-s". 

	En este ejemplo, se cambia a la cuenta de usuario y se utiliza "/bin/sh" como shell en lugar del shell predeterminado.


	En muchas distribuciones de Linux, el uso del comando "su" para cambiar a la cuenta de superusuario (root) puede estar restringido por motivos de seguridad, y es preferible utilizar el comando "sudo" para ejecutar comandos con privilegios elevados. 

	"sudo" permite a los usuarios autorizados ejecutar comandos como superusuario después de autenticarse con sus propias contraseñas, lo que ofrece un mayor control y trazabilidad de las acciones realizadas con privilegios elevados.



|| sudo

	"superuser do" permite a los usuarios autorizados ejecutar comandos con privilegios elevados, generalmente como superusuario o "root". 

	"sudo" se utiliza para mejorar la seguridad y la administración de sistemas, ya que permite un control más granular sobre quién puede realizar acciones administrativas en un sistema sin la necesidad de compartir la contraseña de superusuario.
	
	```
	sudo [opciones] comando

	```
	[opciones]: 

		Puedes proporcionar diversas opciones para controlar el comportamiento de "sudo".
	
	comando: 

		Especifica el comando que deseas ejecutar con privilegios elevados.	


	Ejemplos: 


		```
		sudo comando

		```
		Ejecutar un comando como superusuario.

		el comando especificado se ejecutará con los privilegios de superusuario después de que el usuario ingrese su propia contraseña.

		Esto permite realizar tareas administrativas sin tener que iniciar sesión directamente como superusuario.


		```
		sudo -i

		```
		Cambiar al shell de superusuario (root).

		Cambia al shell de superusuario, lo que significa que estás trabajando en una sesión de superusuario. 

		Puedes utilizarlo para realizar múltiples tareas administrativas sin tener que ingresar "sudo" antes de cada comando.


		```
		sudo -u nombre_de_usuario comando

		```
		Ejecutar un comando como otro usuario.

		Puedes ejecutar un comando como un usuario diferente al especificar el nombre de usuario después de la opción "-u". 

		Esto es útil para realizar tareas en el contexto de otra cuenta de usuario.


		```
		sudo -i -u nombre_de_usuario

		```
		Cambiar al shell de otro usuario y luego ejecutar comandos con privilegios elevados en ese contexto.


	Características:

		Control de acceso granular:

			"sudo" permite a los administradores de sistemas especificar de manera detallada quién puede ejecutar qué comandos con privilegios elevados. 

			Esto es útil para garantizar que solo los usuarios autorizados realicen tareas administrativas.


	    Auditoría de acciones:

	    	"sudo" registra las acciones realizadas por los usuarios con privilegios elevados, lo que facilita la trazabilidad y la auditoría de cambios en el sistema.


	    Seguridad mejorada: 

	    	"sudo" reduce la necesidad de compartir la contraseña de superusuario, lo que disminuye el riesgo de acceso no autorizado a privilegios elevados.


	    Concesión temporal de privilegios: 

	    	Los usuarios pueden ejecutar comandos con privilegios elevados solo cuando sea necesario, lo que minimiza la exposición a riesgos de seguridad.


	    Personalización: 

	    	Los archivos de configuración de "sudo" permiten a los administradores definir políticas específicas de acceso y asignar permisos personalizados a los usuarios.


|| passwd

	Cambiar la contraseña de un usuario. 

	Tanto los usuarios normales como el superusuario (root) pueden usar este comando para cambiar sus contraseñas o las contraseñas de otros usuarios, siempre que tengan los permisos adecuados.

	```
	passwd [opciones] [nombre_de_usuario]

	```
	[opciones]: Controlar el comportamiento del comando.

		-l o --lock: 

			Bloquea la cuenta de usuario, impidiendo que el usuario inicie sesión. 

			Esto se logra agregando un carácter "!" al principio de la contraseña en el archivo /etc/shadow.

	    -u o --unlock: 

	    	Desbloquea una cuenta de usuario que ha sido bloqueada previamente.

	    -S o --status: 

	    	Muestra el estado de la contraseña de un usuario. 

	    	Indicará si la contraseña está establecida o si la cuenta está bloqueada.

	    -d o --delete: 

	    	Borra la contraseña de un usuario, dejándola vacía. 

	    	Esto puede utilizarse para deshabilitar la autenticación de contraseña en una cuenta de usuario.


    [nombre_de_usuario]: 

    	Es opcional y se utiliza para especificar el nombre de usuario cuya contraseña deseas cambiar. 

    	Si no se proporciona, el comando cambiará la contraseña del usuario actual.


    Ejemplos:

    	```
    	passwd

    	```		
    	Cambiar tu propia contraseña.

		Para cambiar tu propia contraseña, simplemente ejecuta el comando "passwd" sin argumentos adicionales.

		El sistema te solicitará que ingreses tu contraseña actual y luego te pedirá que ingreses la nueva contraseña dos veces para confirmarla.


		```
		sudo passwd nombre_de_usuario

		```
		Cambiar la contraseña de otro usuario (requiere privilegios de superusuario).

		Si eres el superusuario (root) o tienes permisos adecuados, puedes cambiar la contraseña de otro usuario especificando su nombre de usuario como argumentos.

		El sistema te pedirá que ingreses la nueva contraseña dos veces para confirmarla.



|| apt-get


|| useradd


|| userdel


|| root
	
	Entidad especial en sistemas Unix y Linux que tiene privilegios de superusuario o administrador. 

	En otros sistemas operativos, a menudo se le conoce como "administrador" o "superusuario". 

	El usuario "root" tiene el control completo del sistema y puede realizar cualquier acción, incluyendo la administración del sistema, instalación de software, acceso a archivos protegidos y configuración del sistema.


	Privilegios Elevados: 

		El usuario "root" tiene privilegios elevados en el sistema, lo que significa que puede realizar tareas que están prohibidas para otros usuarios regulares.

		Esto incluye la capacidad de modificar configuraciones críticas del sistema, instalar o eliminar software, y acceder a archivos y directorios protegidos.


    Acceso a Todos los Recursos: 

    	El usuario "root" tiene acceso a todos los recursos del sistema, lo que incluye la capacidad de ver y modificar cualquier archivo o directorio, así como ejecutar comandos con privilegios de administrador.


    Responsabilidad: 

    	Dado que el usuario "root" tiene control total sobre el sistema, se espera que los administradores de sistemas utilicen esta cuenta con responsabilidad. 

    	Los errores cometidos por el usuario "root" pueden tener consecuencias graves, como la pérdida de datos o la corrupción del sistema.


    Seguridad: 

    	Por razones de seguridad, en la mayoría de los sistemas Unix y Linux, el acceso directo al usuario "root" está desactivado por defecto y se espera que los administradores utilicen otros usuarios regulares para realizar tareas diarias. 

    	En su lugar, pueden utilizar comandos como "sudo" para ejecutar tareas específicas con privilegios de superusuario cuando sea necesario.


    Prevención de Errores: 

    	Utilizar la cuenta "root" en forma constante puede aumentar el riesgo de cometer errores graves que afecten al sistema. 

    	Por lo tanto, se recomienda que los administradores utilicen la cuenta "root" con moderación y solo cuando sea absolutamente necesario.


    Cuenta Universal: 

    	El usuario "root" existe en todos los sistemas Unix y Linux, independientemente de la distribución o versión del sistema operativo. 

    	Esto asegura que haya un usuario con privilegios de superusuario disponible en todos los sistemas Unix y Linux.



|| permisos




|| top


|| ps


|| htop


|| d-bus


|| daemon


|| jobs


|| bg


|| fg


|| gzip


|| gunzip


|| tar


----

|| Comandos de hard

|| du

|| df


----

|| Lista comandos y banderas

	Comandos básicos:

	    pwd: Muestra el directorio de trabajo actual.

	    ls: Lista archivos y directorios en el directorio actual.

	    cd: Cambia de directorio.

	    touch: Crea archivos vacíos.

	    mkdir: Crea directorios.

	    rmdir: Elimina directorios vacíos.

	    rm: Elimina archivos y directorios.

	    cp: Copia archivos y directorios.

	    mv: Mueve o renombra archivos y directorios.

	    cat: Concatena y muestra contenido de archivos.

	    more / less: Permite ver archivos de texto página por página.

	    head / tail: Muestra las primeras o últimas líneas de un archivo.

	    file: Determina el tipo de archivo.

	    find: Busca archivos y directorios en el sistema.

	    grep: Busca patrones en archivos de texto.

	    locate: Busca archivos en una base de datos indexada.
	    
	    which: Muestra la ubicación de un ejecutable en el sistema.

	    whereis: Muestra la ubicación de archivos binarios, código fuente y páginas del manual.

	    type: Muestra información sobre un comando.


	Manipulación de texto:

	    echo: Muestra texto en la pantalla.

	    printf: Imprime texto formateado.

	    cut: Extrae secciones de líneas de texto.

	    sed: Editor de secuencias de comandos para manipulación de texto.

	    awk: Procesamiento de texto y datos tabulares.

	    sort: Ordena líneas de texto.

	    uniq: Filtra líneas de texto duplicadas o consecutivas.

	    wc: Cuenta palabras, líneas y caracteres en archivos de texto.


	Administración de procesos:

	    ps: Muestra información sobre procesos en ejecución.

	    top: Muestra una lista de procesos y su uso de recursos en tiempo real.

	    kill: Envía señales a procesos para detenerlos o controlar su comportamiento.

	    pkill: Termina procesos basados en sus nombres.

	    jobs: Muestra trabajos en segundo plano.

	    bg: Pone trabajos en segundo plano.

	    fg: Pone trabajos en primer plano.


	Administración de usuarios y grupos:

	    useradd: Agrega nuevos usuarios al sistema.

	    userdel: Elimina usuarios.

	    passwd: Cambia las contraseñas de los usuarios.

	    groupadd: Agrega nuevos grupos.

	    groupdel: Elimina grupos.

	    id: Muestra información sobre la identidad del usuario.

	    who: Muestra información sobre usuarios conectados.

	    w: Muestra información detallada sobre usuarios conectados.

	    su: Cambia de usuario o inicia una sesión de superusuario.


	Archivos y directorios:

	    stat: Muestra información detallada sobre archivos y directorios.

	    du: Muestra el uso de espacio en disco de archivos y directorios.

	    df: Muestra el espacio disponible en el sistema de archivos.

	    ln: Crea enlaces simbólicos y duros a archivos.


	Comandos de sistema:

	    uname: Muestra información sobre el sistema.

	    date: Muestra la fecha y la hora actual.

	    uptime: Muestra el tiempo de actividad del sistema.

	    shutdown: Apaga o reinicia el sistema.

	    reboot: Reinicia el sistema.

	    free: Muestra información sobre la memoria RAM y el intercambio.


	Redirección y tuberías:

	    >: Redirige la salida estándar a un archivo.

	    <: Redirige la entrada estándar desde un archivo.

	    |: Crea tuberías para pasar la salida de un comando como entrada a otro


	Banderas:
 
		-h o --help: Muestra información de ayuda y opciones disponibles para el comando.

		-v o --verbose: Ejecuta el comando en modo detallado, lo que significa que muestra más información o mensajes de depuración.

		-q o --quiet: Ejecuta el comando en modo silencioso, lo que significa que suprime la mayoría de los mensajes de salida.

		-r o --recursive: Realiza una operación de manera recursiva en directorios y subdirectorios.

		-f o --force: Forza una acción, como la eliminación de archivos o la sobrescritura, sin pedir confirmación.

		-l o --list: Lista información o contenido en lugar de realizar una acción.

		-a o --all: Incluye todos los elementos, incluso aquellos ocultos que comienzan con un punto (por ejemplo, archivos y directorios que comienzan con ".").

		-i o --interactive: Solicita confirmación antes de realizar una acción, como eliminar archivos.

		-u o --update: Copia o mueve archivos solo si el archivo de destino es más antiguo que el origen.

		-n o --no-clobber: No sobrescribe archivos existentes durante la copia o el movimiento.

		-c o --count: Cuenta elementos (por ejemplo, archivos o líneas) en lugar de realizar una acción.

		-p o --preserve: Preserva atributos, como permisos y tiempos de acceso y modificación, durante operaciones de copia o movimiento.

		-s o --symbolic: Crea enlaces simbólicos en lugar de copiar archivos.

		-R o --read-only: Monta un sistema de archivos o directorio en modo solo lectura.

		-w o --write: Monta un sistema de archivos o directorio en modo escritura.

		-x o --execute: Ejecuta un archivo o programa.

		-E o --extended-regexp: Utiliza expresiones regulares extendidas en lugar de las regulares básicas.

		-P o --perl-regexp: Utiliza expresiones regulares de Perl en lugar de las regulares básicas.

		-i o --ignore-case: Realiza una búsqueda o comparación sin distinguir entre mayúsculas y minúsculas.

		-g o --group: Especifica un grupo en operaciones que involucran permisos o propietarios.






