# Sistema Vacaciones

El sistema de vacaciones se trata de un software con la capacidad de gestionar las solicitudes de vacaciones de los empleados de una empresa.

Para su instalacion, debe de seguir estos pasos:

Descargar el comprimido rar "sistemagestionVacaciones.rar", descomprimirlo y abrirar la carpeta en Visual Studio Code. Posteriormente a esto descarga el archivo "sistemaVacacionesScript" y abrirlo con algun entorno que pueda correr SQL FIlE (De preferencia My SQL WorkBench).

La modificacion necesaria en la logica del proyecto solo radica en la modifiacion del siguiente fragmente de codigo:

const conexion = mysql.createConnection({
  host: 'TuHost', //Debera de reemplazar "TuHost" con el host que tenga planficado usar.
  user: 'Usuario', //Debe de reemplazar "Usuario" con el nombre de usuario de la base de datos en este caso
  password: 'TuContraseña', //Debe de reeemplazar "TuContraseña" con la contraseña de su entorno.
  database: 'mydb' //Indica el nombre de la base de datos, sin embargo con la ejecucion del script no es necesario.
});



