# Control de Gastos en React 

Este es un proyecto de control de gastos personales desarrollado en React + Vite. La aplicación se enfoca en el uso de los principales hooks de React, como `useState` y `useEffect`, y utiliza el almacenamiento local (`localStorage`) para proporcionar persistencia de datos incluso después de recargar la página.

## Demostración

Puedes acceder a una versión desplegada de la aplicación [aquí](https://control-de-gastos-react-svg.vercel.app/).


## Funcionalidades

- Definir un presupuesto inicial.
- Agregar gastos con nombre, cantidad y fecha.
- Ver la lista de gastos registrados.
- Eliminar gastos individualmente.
- Editar gastos individualmente.
- Total de gastos acumulados.
- Filtrar gastos por categoria.
- Almacenamiento local para persistencia de datos.

## Dependencias

Este proyecto utiliza las siguientes dependencias para crear efectos en la aplicación:

- [react-circular-progressbar](https://www.npmjs.com/package/react-circular-progressbar) - Versión 2.1.0
- [react-swipeable-list](https://www.npmjs.com/package/react-swipeable-list) - Versión 1.9.1


Sigue estos pasos para ejecutar la aplicación en tu entorno local:

1. Clona el repositorio: `git clone https://github.com/sevalenciagr/control-de-gastos-react.git`
2. Navega al directorio del proyecto: `cd control-de-gastos-react`
3. Instala las dependencias: `npm install`
4. Inicia el servidor local: `npm run dev`
