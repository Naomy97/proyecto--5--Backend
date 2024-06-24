# proyecto--5--Backend

Este proyecto es sobre una tienda de videojuegos, donde en la parte del backend creamos varias APIS desarrolladas con Node.js que incluyen varias funcionalidades como login, manejo de usuarios, juegos, biblioteca, publicaciones y soporte.

Tabla de Contenidos:
•	Inicio del Proyecto
•	Dependencias
•	APIs
•	Login
•	User
•	Games
•	Library
•	Post
•	Support
•	Cómo Ejecutar el Proyecto
•	Inicio del Proyecto


Inicio del proyecto:

1.	Clonar el repositorio. 
git clone https://github.com/Naomy97/proyecto--05--Backend.git
cd proyecto—05—Backend

2.	Inicializar el proyecto:

npm init -y

3.	Crear la estructura de carpetas:
Src
Drives
Helpers
Models
Routes
Instalar dependencias 

Npm install bcryptjs
    Npm install cors
    Npm install dotenv
    Npm install express
    Npm install jsonwebtoken
    Npm install mongodb
    Npm install mongoose
    Npm install morgan
    Npm install multer
    Npm install fs-extra

Dependencias de desarrollo:
npm install --save-dev nodemon

utilidad:

express: Framework para construir aplicaciones web y APIs en Node.js.
mongoose: ODM para modelar datos en MongoDB.
bcryptjs: Biblioteca para cifrar y comparar contraseñas.
jsonwebtoken: Biblioteca para crear y verificar tokens JWT.
cors: Middleware para habilitar CORS en aplicaciones Express.
dotenv: Carga variables de entorno desde un archivo .env.
nodemon: Herramienta para reiniciar automáticamente el servidor en desarrollo.


APIs
Login:
Ruta: /api/login
Método: POST
Descripción: Autentica a un usuario y devuelve un token JWT.
User:
Ruta: /api/users
Método: GET, POST, PUT, DELETE
Descripción: Maneja las operaciones CRUD para los usuarios.

Games
Ruta: /api/games
Método: GET, POST, PUT, DELETE
Descripción: Maneja las operaciones CRUD para los juegos.
Library
Ruta: /api/library
Método: GET, POST, PUT, DELETE
Descripción: Maneja las operaciones CRUD para la biblioteca de juegos del usuario.
Post
Ruta: /api/posts
Método: GET, POST, PUT, DELETE
Descripción: Maneja las operaciones CRUD para las publicaciones.

Support
Ruta: /api/support
Método: POST, DELETE
Descripción: Maneja las solicitudes de soporte.

Cómo Ejecutar el Proyecto

Crear un archivo .env en la raíz del proyecto


Ejecutar el proyecto:

Npm run dev

Autores:

Andrés Rangel
Naomy Restrepo






