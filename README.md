# webpack

## For windows

set build as :

{
"scripts": {
"build": "set NODE_ENV=production && webpack"
}
}

## For Mac

"build": "NODE_ENV='production' webpack",

## Folder Structure

.
|-- README.md
|-- app
| |-- README.md
| `-- index.js
|-- dist
|   |-- README.md
|   |-- bundle.js
|   `-- index.html
|-- package-lock.json
|-- package.json
`-- webpack.config.js

<!--  -->
