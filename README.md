# Tienda-node-mongo

## Instalación
1. Clona este repositorio.
2. Instala las dependencias con `npm install`.
3. Asegúrate de tener MongoDB instalado en tu sistema.
4. Crea un archivo `.env` en el directorio raíz del proyecto y configura las variables de entorno necesarias. Puedes usar el archivo `.env.example` como referencia:

```plaintext
   PORT=3000
   DB_CONN_STRING="mongodb://127.0.0.1:27017"
   DB_NAME="shop"
   USER_COLLECTION="users"
   PRODUCT_COLLECTION="products"
   ORDER_COLLECTION="orders"
```
## Uso
Para arrancar el proyecto, sigue estos pasos:

1. Inicia el servidor de MongoDB:
   ```bash
   npm run mongo

2. Compila el código TypeScript:
   ```bash
    npm run build
3. Sincroniza los archivos estáticos y las vistas:
   ```bash
   npm run sync
4. Inicia la aplicación:
    ```bash
    npm start
