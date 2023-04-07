# e-commerce App

¡Bienvenido a mi aplicación! Esta es una aplicación en donde el usuario puede loguearse, ver y filtrar productos, añadirlos al carrito y comprarlos. Esta aplicación fue creada con Vite y React.


## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.\
Open [http://localhost:5174](http://localhost:5174) to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

### `npm run build`

Builds the app for production to the dist folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!


## Tecnologías
▪	Vite
▪	React
▪	Axios
▪	react-hook-form
▪	react-redux
▪	react-router-dom

## Instalación
Clona este repositorio en tu computadora local.
Abre una terminal y navega a la carpeta del proyecto.
Ejecuta el siguiente comando para instalar las dependencias:

### `npm install`

Una vez que se hayan instalado las dependencias, puedes correr la aplicación con el siguiente comando:

### `npm run dev`


## Contribuir
Si quieres contribuir a este proyecto, por favor sigue los siguientes pasos:

Haz un fork de este repositorio.
Crea una nueva rama con tus cambios:

### `git checkout -b my-feature`

Haz tus cambios y haz un commit:

### `git commit -m "mi mensaje de commit"`

Haz un push a tu rama:

### `git push origin my-feature`

Abre un Pull Request y describe tus cambios.

## ¡Gracias por contribuir!

<br>

## Algunas Características de mi App 

Consumo de API: https://documenter.getpostman.com/view/8450870/2s847ESZzN, se utiliza para poder hacer todas las funcionalidades.

Esta API necesita autenticación con token de tipo Bearer para poder consumir los endpoints de “/cart” y “/purchases”. Puedes loguearte de la siguiente forma: “Email: john@gmail.com y Password: john1234”

Creación de la ruta raíz “/”, en la cual se listarán todos los productos.

Cada producto será un link que llevará a la ruta “/product/:id”, cuyo id dependerá del producto seleccionado. Se listan las categorías de los productos. Al darles clic se filtran los productos de acuerdo a la categoría seleccionada.

Creación de un input para que el usuario pueda buscar un producto por el nombre.

Creación de la ruta “/products/:id”. El id será de uno de los productos de la API, en esta ruta se mostrará toda la información del producto: nombre, imágenes, descripción y precio. Contiene un contador para que el usuario seleccione cuántos productos desea comprar y hay un botón para agregar el producto al carrito.

Creación de la ruta “/purchases” La cuál es una ruta protegida. Aquí el usuario podrá ver los productos que ha comprado. 

Creación de la ruta pública “/login”, donde el usuario puede loguearse en la aplicación.

<br>

## ¿Quieres ver mi app despleagada?
Visita <a href="https://e-commerce-ct.netlify.app/" target="_blank">e-commerce</a>.





