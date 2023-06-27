# Red Social de Viajes

Esta aplicación es una red social destinada a los amantes de los viajes. Los usuarios pueden hacer publicaciones, ganar amigos, tener seguidores, dar me gusta a las publicaciones, compartir fotos y mucho más. Además, la aplicación sugiere amigos en base a tus hobbies y permite conectarte con personas que han visitado los países que te gustaría visitar. La aplicación ofrece información útil sobre los destinos de viaje.

## Características

- **Publicaciones**: Los usuarios pueden compartir sus experiencias, pensamientos y fotos de viajes.
- **Amigos y Seguidores**: Los usuarios pueden seguir a otros, hacer amigos y interactuar con su contenido.
- **Me gusta**: Los usuarios pueden expresar su aprecio por el contenido con la función de "me gusta".
- **Sugerencias de Amigos**: La aplicación sugiere amigos en función de los hobbies del usuario.
- **Conexión basada en Destinos de Viaje**: Los usuarios pueden conectarse con personas que han visitado los lugares que les gustaría visitar.
- **Información sobre Destinos**: La aplicación ofrece información útil sobre diversos destinos de viaje.

## Tecnologías utilizadas

- **Frontend**: React.js, Ant Design
- **Backend**: Express.js, Node.js, MongoDB

## Instalación

Asegúrate de tener instalado Node.js y MongoDB en tu sistema antes de seguir estos pasos.

1. **Clonar el repositorio**:
   ```
   git clone 'url de este repo'
   ```

2. **Ir al directorio de la aplicación**:
   ```
   cd 'nomadSociety-frontend'
   ```

3. **Instalar las dependencias necesarias**. Esto se hace con el comando npm install en ambos directorios, /frontend y /backend.
   ```
   cd frontend && npm install
   cd ..
   cd backend && npm install
   ```

4. **Configurar las variables de entorno**. En el directorio /backend, crea un archivo `.env` y añade lo siguiente (reemplaza `yourMongoDBUrl` por la URL de conexión de tu MongoDB):
   ```
   MONGO_DB_URL=*****
   ```

5. **Iniciar el servidor y el cliente**. Primero, inicia el servidor desde el directorio /backend con `npm start`, luego inicia el cliente desde el directorio /frontend también con `npm start`.
   ```
   cd ../backend && npm start
   cd ../frontend && npm start
   ```

¡Eso es todo! Ahora deberías poder acceder a la aplicación en `http://localhost:3000`.




## Contacto
Eduardo G - eduardog.carbonell.@gmail.com - 617680026
