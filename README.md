# Prueba Técnica Frontend TypeScript

Clona el repositorio y una vez terminado el tiempo límite o terminada la prueba, deberás enviar tu propio repositorio público (github o bitbucket) al correo electrónico de la persona que te ha contactado.

## Prueba

Esta prueba técnica consta de varios puntos a realizar, en la cual deberás crear una aplicación React Ecommerce utilizando una API Rest con las siguientes rutas de la aplicación:

- Home con el listado de productos => "/"
- Detalle de producto usando el ID del producto => "/product/:id"
- Detalle de categoría con el listado de producto según ID de categoría => "/category/:categoryId"
- Login con nombre de usuario y contraseña => "/login"
- Account detalle de usuario con el listado de órdenes => "/account". Si no existe autenticación, debería redirigir al "/login".

Tienes libertad para usar las librerías que requieras, así como también para el diseño.
Te recomendamos que te enfoques en el funcionamiento más que en el diseño, no obstante, si se ve bien, mucho mejor.

Para poder realizar esta prueba deberás utilizar una API Rest:

Endpoint principal: `https://selection-test-api.vercel.app/api`

- Listado de productos: "/products" GET
- Producto por ID: "/products/:productId" GET
- Listado de categorías: "/categories" GET
- Listado de productos por ID de categoría: "/categories/:categoryId" GET
- Para iniciar sesión: "/account/login" POST (`username`: user `password`: superSECRET123)
- Para obtener la información del usuario con sesión iniciada con token: "/account/current-user" GET con Token

Para el `current-user` deberás usar el token que devuelve el `login` como "Bearer token".

## Aspectos Técnicos

- Puedes utilizar `npm` o `yarn`.
- El proyecto incluye prettier y eslint con reglas específicas que deberás cumplir
- El proyecto viene con `create-react-app` por ende, puedes utilizar todas las características que trae.
- Para los estilos puedes usar css o sass, como también modules o style in js (soportado por CRA).
- Para el enrutado puede usar React Router Dom u otros.

## Extras

Estos "extras" no son obligatorios, pero si los haces, tendrás puntos extras.

- Publicar la app en algún servicio gratuito como Vercel, Heroku o Netlify
- Menejar los datos de la API en caché (SWR, React Query o Apollo)
- Realizar Tests unitarios y de integración
- Realizar Test End To End
- Agregar Docker al proyecto
- Si lo deseas, puedes realizar el proyecto con `Nextjs`, siempre y cuando incluya las mismas reglas de prettier y eslint.

## Entrega

Deberás entregar el link de tu repositorio a la persona que te ha contactado (incluir link de la app publicada si se ha realizado).

**MUCHA SUERTE 😊**