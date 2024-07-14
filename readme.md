
https://www.themoviedb.org/settings/api


https://www.themoviedb.org/

https://developer.themoviedb.org/docs/getting-started

https://api.themoviedb.org/3"

Creamos el proyecto lo tenemos listo y..

Deploy
-npm run build ->crea carpeta dist

--
-npm run preview ->muestra el proyecto predeploy

--
Deploy en githubpage
-npm i gh-pages -D ->D es por que va a desarrollo se usa para diferenciar de produccion


--subir a git normal git init git add git remote origin git push
-
----
configurar vite.config

base: /deploy/ -> nombre del brach repo" en mi caso "/movies-React/"

-npm run build
--
-npm run gh-pages -d dist -> toma dist y lo sube a una rama
o
-agregar a scripts "deploy":"gh-pages -d dist"
npm run deploy

--
en git hub tenemos una rama nueva 
esperamos un rato a que aparesca en el menu a la derecha enviroments..

..