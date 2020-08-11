# Inicio proyecto

## Para iniciar un project preparo git y npm

`npm init -y` para inicializar el package.json
`git init` en el bash de git para inicializar git


Crear el ** .gitignore ** y especificar los file que no van en el commit


# Configuro webpack

`npm i -D webpack webpack-cli webpack-dev-server` instalo en desarrollo(-D) **webpack** y su servidor.

Crear el ** webpack.config.js ** para configurar webpack( por ahora lo copio de los viejos proyectos)


# Modulos npm de instalar

Los siguientes modulos son necesarios a gestionar pug, scss, archivos.

```bash
npm i style-loader css-loader sass-loader mini-css-extract-plugin node-sass html-webpack-plugin pug pug-loader file-loader
```



Plugins utiles para el desarrollo con bootstrap y jquery
```bash
npm i bootstrap jquery popper.js
```