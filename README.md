# Proyecto de Pregunta-Respuesta construido en Vite, ReactJS y Tailwind
   App de quiz. Cuenta con diferentes campos de conocimiento, y cada campo tiene varias preguntas con sus respectivas dificultades. 
   
   Por pregunta habrá respuesta correcta y 3 incorrectas.

   Las preguntas se eligen aleatoriamente dentro del campo de conocimiento.

   Al contestar las 5 preguntas del campo de conocimiento elegido, se muestra un puntaje con el porcentaje de aciertos.

# Instalación del Proyecto
  - ## Instalar vite
    ```bash
     npm create vite
    ```
    - configurar para trabajar con React y Javascript
  - ## Instalar paquetes de node
    ```bash
     npm i
    ```
  - ## Instalar React Router Dom para manejar las rutas
    - Ir al sitio web:  https://reactrouter.com/en/main/start/tutorial#tutorial
    - Instalar:
      ```bash
       npm install react-router-dom
      ```
  - ## Instalar Tailwind para React
    - Ir al sitio web:  https://tailwindcss.com/docs/guides/vite
    - Comenzamos por el paso 2 ()
    1. Install Tailwind CSS
        ```bash
         npm install -D tailwindcss postcss autoprefixer
         npx tailwindcss init -p
        ```
    2. Editar el archivo **tailwind.conf.cjs**
        
        ```js
        /** @type {import('tailwindcss').Config} */
        export default {
        content: [
            "./index.html",
            "./src/**/*.{js,ts,jsx,tsx}",
        ],
        theme: {
            extend: {},
        },
        plugins: [],
        }
        ```
    3. Agregar directivas de Tailwind a mi CSS
       - Modificar el archivo index.css
       ```css
        @tailwind base;
        @tailwind components;
        @tailwind utilities;
       ```


# Ejecución
  
  ```bash
   npm run dev
  ```