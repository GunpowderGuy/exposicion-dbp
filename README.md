# Server Side Rendering vs Client Side Rendering
![image](https://user-images.githubusercontent.com/91635108/200248529-5d4b3337-4c59-41ed-8c89-082ff9c7a354.png)


## Introducción
- Antes las páginas mostraban contenido estático
- La representación del lado del servidor era la única forma de mostrar HTML
- Sitios web son más interactivos (ahora)
- Más énfasis: renderizado del lado del cliente 
- Para diseñar una página web es importante el tipo de renderizado


## Conceptos
- Cliente: Sistema que solicita servicios o datos de un servidor
- Servidor: Sistema que contiene datos o proporciona recursos a los que deben acceder otros sistemas de la red
![image](https://user-images.githubusercontent.com/91635108/200249695-a8f58f59-cc93-46c6-a3e0-1de2a7c6966e.png)
- Templates: Es el método más común para client side rendering. Consiste de html con secciones que no están predeterminadas sino reflejan la información del servidor
- Frameworks declarativo (client side rendering) Consiste de funciones puras que procesan los eventos del usuario y retornan como resultado el GUI(graphics user interface).


## Server Side Rendering
![image](https://user-images.githubusercontent.com/91635108/200251182-c42cb0e5-1bde-446f-bbee-42a7ef75b433.png)


## Client Side Rendering
![image](https://user-images.githubusercontent.com/91635108/200251231-0cb95231-8bf4-4801-92a8-c53fcc96377e.png)


## Importancia
- Diferencias en la infraestructura
    Server side rendering consume más procesamiento en el servidor
![image](https://user-images.githubusercontent.com/91635108/200250358-b5494e00-9f08-4732-9cd5-e49a9a417fb1.png)

- Diferencias en la experiencia de usuario:
    La primera carga es más lenta en client side rendering
![image](https://user-images.githubusercontent.com/91635108/200250691-be4498ae-f53f-4c87-a649-7d31aed666ad.png)


### Los Crawlers
- Los crawlers son el software que los motores de búsqueda usan para coleccionar información sobre los sitios web
- Muchos no pueden interpretar el contenido de las páginas con client side rendering
- Hay soluciones como adaptar la página para que se le muestre una versión simple a los crawlers
![image](https://user-images.githubusercontent.com/91635108/200251716-b06ad609-fd9d-4661-ad2a-70c27e3f281a.png)


## Ejemplo aplicativo de Server Side Rendering

## Ejemplo aplicativo de Client Side Rendering


# Nuxt.js
![image](https://user-images.githubusercontent.com/91635108/200252118-a8874db0-011f-4015-b6e9-425b67bb1228.png)

- Framework basado en Vue.js
- Escrito en JS
- Características de Vue + SSR -> lo vuelve más potente
- Características ya estructuradas
- Usa estándares de industria
- Cada vez que usuario necesita una página, peticiones se renderizan en el servidor 
![image](https://user-images.githubusercontent.com/91635108/200252177-c9c93105-7723-4167-85a5-a80b1c6320e5.png)


## Ejemplo aplicativo de Nuxt.js

