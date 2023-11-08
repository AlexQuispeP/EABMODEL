# Sistema Vacaciones

El sistema de vacaciones se trata de un software con la capacidad de gestionar las solicitudes de vacaciones de los empleados de una empresa.

Para su instalacion, debe de seguir estos pasos:

Descargar el comprimido rar "sistemagestionVacaciones.rar", descomprimirlo y abrir la carpeta en Visual Studio Code. Posteriormente a esto descargar el archivo "sistemaVacacionesScript.sql" y abrirlo con el entorno MySQL WorkBench

La modificacion necesaria en la logica del proyecto solo radica en la modifiacion del siguiente fragmente de codigo en el archivo Servidor.js.

Fragmento de codigo indicado:

const conexion = mysql.createConnection({
  host: 'TuHost', //Debera de reemplazar "TuHost" con el host que tenga planficado usar.
  user: 'Usuario', //Debe de reemplazar "Usuario" con el nombre de usuario de la base de datos en este caso
  password: 'TuContraseña', //Debe de reeemplazar "TuContraseña" con la contraseña de su entorno.
  database: 'mydb' //Indica el nombre de la base de datos, sin embargo con la ejecucion del script no es necesario.
});



