¡De una, Thiago! Acá te dejo el paso a paso bien claro y directo para que tengas tu machete y sepas exactamente cómo encender el servidor y todo el sistema cuando lo abras en otra computadora:
Paso 1: Activar XAMPP (Base de datos)
 * Abrí el panel de control de XAMPP en la computadora.
 * Hacé clic en el botón Start al lado de Apache.
 * Hacé clic en el botón Start al lado de MySQL.
 * ¿Cómo sabés que está bien? Ambos servicios tienen que quedar marcados con el fondo verde en el programa.
Paso 2: Abrir el proyecto
 * Abrí Visual Studio Code.
 * Arrastrá o abrí la carpeta de tu proyecto (Aerolineas-Low-Cost) desde donde la tengas guardada (o clonala de tu GitHub).
Paso 3: Instalar las dependencias (Solo si es una PC nueva)
Si es la primera vez que abrís el proyecto en esa computadora, como la carpeta node_modules no se sube a GitHub para ahorrar espacio, tenés que descargarla de nuevo:
 * Abrí la terminal integrada en VS Code (abajo).
 * Escribí el siguiente comando y apretá Enter:
   npm install

Paso 4: Prender el Servidor Backend (Node.js)
 * En la misma terminal de VS Code, asegurate de estar parado en la carpeta del servidor o backend.
 * Escribí el comando para encender el servidor:
   node server.js

 * ¿Cómo sabés que funcionó? La consola de la terminal te va a arrojar el mensaje confirmando que el servidor backend está corriendo y conectado a la base de datos de MySQL.
Paso 5: Prender la Página Web (React)
 * Abrir otra pestaña o ventana nueva en la terminal de Visual Studio Code sin cerrar la anterior.
 * Ejecutá el comando para arrancar la interfaz visual:
   npm run dev

   (o npm start según tu configuración).
 * ¡Listo! Se abrirá automáticamente la página en tu navegador web conectada al backend y lista para hacer reservas de prueba con su ID directo de MySQL.

