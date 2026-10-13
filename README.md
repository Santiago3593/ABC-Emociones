# Instalar Node.js

Se necesita instalar Node.js version 22.12.0 o superior (https://nodejs.org/es/download)

Si se esta usando  windows es recomendable instalar el Windows Intaller(.msi)

Luego de abrir el instaler y hacer todo lo que pide ya debería estar instalado Node.js, 
para comprobarlo, abrir un cmd si se esta windows y colocar el comando:

```sh
node -v
```

# Abrir el servidor local del proyecto de Astro

Dentro del cmd tiene que estar ubicado en la carpeta del proyecto(ABC-Emociones):

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```

Una vez seguro de que esta dentro de esa ruta en el cmd colocar el siguiente comando:

```sh
npm run dev --host
```

# Ingresar a la página

Al ingresar el comando y darle a enter debe mostrar un apartado similar a:

```text
 astro  v7.3.5 ready in 252 ms
┃ Local    http://localhost:4321/
┃ Network  http://192.168.3.229:4321/
           http://192.168.14.23:4321/
```

Al ingresar a cualquiera de los enlaces que se mostraron si no hubo un error en nada, debería abrir el navegador y la página.