# Clase7-Uzcategui
# Clase 7 Primera Entrega del Proyecto Final
## Routing y Navegación
##### El proyecto es una aplicación react sencilla, que reproduce la funcionalidad básica de un ecommerce "Carrito de compras", hasta el momento se han implementado las funcionalidades correspondientes a la barra de navegación, las diferentes opciones de la barra contienen navegacion a diferentes categorias del catalogo así como a algunas páginas agregadas por mi como lo son la de "error 404" y la página "about", se definió un json de datos para simular la conexion a los datos persistentes, sin embargo se usa promesas para leer el archivo json y cargar la data en la aplicación, el catalogo se muestra mediante componentes contenedor/items los cuales al ser iterados mediante map construyen cada producto, se esta usando la libreria Materia UI "MUI", y como lenguaje de codificacion Typescript.  
##

#### El proyecto incluye lo siguiente...
 1. Se implementa el uso de la libreria "react-router-dom" ✅
 2. Se implementa el uso de BrowserRouter, Routes, Route ✅
 3. Se colocan los diferentes paths de la barra de navegacion ✅
 4. Se realiza la logica para redefinir los diferentes productos segun la categoria ✅
 5. se pasan parametros en el path para obtener informacion ✅
 6. se usa el hook useParams para determinar los valores que se envian en el path ✅
 7. se implementa el uso de promesas para la obtencio de datos ✅
 8. se usa la separacion de responsabilidades de componentes ✅

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
