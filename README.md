### Node-Express-Sass-Starter Entwicklungsumgebung

### `node` `express` `sass` `pug` `concurrently` `nodemon` `livereload` `prettier`

> node v18.17.1

> Framework: express

> Template Engine: Pug

## Installation

> CMD: Projektordner erstellen und hinein wechseln

    mkdir Name; cd Name

> **Schnellstart**

> CMD: git clone & git remote remove orgin & npm install & npm run dev

    git clone https://github.com/tBrause/npm-express-sass-livereload.git .; git remote remove origin; npm install; npm run dev

> \_Erfolgreich getestet: 15.09.2023

## Struktur und Dateien

- bin
  - www
- public
  - stylesheets
    - style.css
    - style.css.map
- routes
  - index.js
- src
  - scss
  - globals
    - \_index.scss
    - \_reset.scss
    - \_variables.scss
  - main.scss
- views
  - error.pug
  - index.pug
  - layout.pug
- .gitignore
- app.js
- package-lock.json
- package.json
- prettier.config.cjs
- README.md

## Konfiguration

### scripts

- dev: nodemon, sass
- start: node

### dependencies

- cookie-parser
- debug
- express
- http-errors
- morgan
- pug

### devDependencies

- concurrently
- nodemon
- sass
- livereload
- connect-livereload

## Erweiterungen für Visual Studio Code

- Prettier
- ESLint

## Prettier Konfiguration

- useTabs: false
- singleQuote: true

[![Watch the video](https://img.youtube.com/vi/T-D1KVIuvjA/maxresdefault.jpg)](https://youtu.be/T-D1KVIuvjA)
