Sistema de Gestión de Usuarios - CRUD App
Una aplicación web completa para la gestión de usuarios que implementa operaciones CRUD (Crear, Leer, Actualizar, Eliminar) utilizando Flask, MongoDB y Vue.js.
Tecnologías utilizadas
Backend

Python: Lenguaje de programación principal
Flask: Framework web ligero y flexible
PyMongo: Adaptador de MongoDB para Python
Flask-CORS: Manejo de solicitudes de origen cruzado

Frontend

Vue.js: Framework JavaScript progresivo
Bootstrap/Bootswatch: Para el diseño y componentes de UI
Axios: Cliente HTTP para realizar peticiones a la API

Características

  Crear nuevos usuarios con nombre, apellido, email y contraseña
  Listar todos los usuarios registrados en el sistema
  Buscar usuarios por nombre o email
  Ver detalles específicos de cada usuario
  Actualizar información de usuarios existentes
  Eliminar usuarios del sistema
  
Instalación y ejecución
Backend

Crear un entorno virtual e instalar dependencias:

bashcd backend
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
pip install flask flask-pymongo flask-cors

Iniciar MongoDB

Ejecutar el servidor Flask:

bashpython app.py
Frontend

Instalar dependencias:

bashcd frontend
npm install
Uso

Accede a la aplicación en: http://localhost:8080
Utiliza la interfaz para realizar las diferentes operaciones CRUD:

Crear nuevos usuarios mediante el botón "Nuevo Usuario"
Ver la lista de usuarios existentes
Buscar usuarios con la barra de búsqueda
Ver detalles, editar o eliminar usuarios mediante los botones de acción



API Endpoints

GET /users: Obtener todos los usuarios
GET /users/<id>: Obtener un usuario específico por ID
POST /users: Crear un nuevo usuario
PUT /users/<id>: Actualizar un usuario existente
DELETE /users/<id>: Eliminar un usuario
Instalar dependencias específicas:

bashnpm install bootstrap bootswatch axios

Ejecutar el servidor de desarrollo:

bashnpm run serve
