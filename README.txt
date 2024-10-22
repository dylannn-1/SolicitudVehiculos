Especificaciones página web: Revisión de solicitudes para vendedores

URL: https://solicitudesvehiculos.netlify.app/
Servidor(Gratuito): https://www.netlify.com/

Pasos previo a subir la página web al servidor:

1. Descargar el archivo excel en drive asociado a las solicitudes de parte de los vendedores.
2. Modificar excel y guardarlo en formato .csv
	2.1 Modificaciones obligatorias:
		- La columna [Marca temporal] dejarla en formato de fecha corta.
		- La columna [Patente] pasar todo a mayúsculas, usar función en excel MAYUSC().
		- Eliminar todos los filtros y dejar solo las columnas [Marca temporal, Centro de Venta, Escriba su nombre, Patente, Descripción de la falla,Estado]
		- Las columnas deben estar ordenadas de la siguiente forma: [Marca temporal, Centro de venta, Escriba su nombre, Patente, Estado, Descripción de la falla]
		- Eliminar filas a gusto, es posible que se puedan eliminar solicitudes que ya hayan pasado un tiempo 
		 y estén completas.
		- Ya con todo listo, guardar en la carpeta con nombre "datos.csv". Ojo con el formato.
3. Ir a https://github.com/, crear una cuenta.
4. Ir a + ("Create new") en la esquina superior derecha y seleccionar "New repository".
5. Incluir un nombre al repositorio, un nombre representativo. Podría ser "SolicitudVendedores".
6. Click en "Create repository".
7. Buscar y hacer click en la opción "uploading an existing file." en un recuadro celeste.
8. Click en "choose your files" y subir todos los archivos de la carpeta asociada a la página web.

Pasos para subir la página web al servidor:

1. Dirigirse a https://www.netlify.com/, crear una cuenta
2. Dirigirse a "Sites", hacer click en "Import from git".
3. Hacer click en "Deploy with GitHub", enlazar las cuentas y seleccionar el repositorio creado en GitHub.
4. Definir un site name: "solicitudvehiculos", lo cual creará una URL con aquel nombre (Ej: https://solicitudesvehiculos.netlify.app/)
5. Hacer click en "Deploy SolicitudVendedores" y la página estará arriba.

Paso para actualizar la página:

1. Solo basta dirigirse a https://github.com/, presionar en el logo parecido a una M verde que está en la zona superior derecha.
2. Hacer click en "your repositories".
3. Hacer click en "SolicitudVendedores". 
4. Hacer click en "add file".
5. Hacer click en "Upload files".
6. Hacer click en "Choose your files.
7. Seleccionar el archivo "datos.csv", esperar a que cargue y hacer click en "Commit changes"
8. Cerrar la página y esperar unos minutos a que actualice, abrir nuevamente.

