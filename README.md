Portafolio Web — Nadja Villarroel

Sitio web de portafolio personal desarrollado con HTML, CSS y Bootstrap.

TECNOLOGÍAS UTILIZADAS
HTML5
CSS3
Bootstrap 5
Git
GitHub
GitHub Pages

ESTRUCTURA DEL PROYECTO

/
│ index.html
│ styles.css
│
├── assets/
│   ├── img/
│   └── doc/
│
└── menu/
    ├── studies.html
    ├── experience.html
    ├── projects.html
    └── contactme.html

CREACIÓN INICIAL DEL PROYECTO DESDE GIT CMD

Navegación y creación del proyecto:

cd (ruta) mkdir nv_tarea-3 cd nv_tarea-3

CREACIÓN DE CARPETAS

mkdir assets\img mkdir assets\doc mkdir menu

CREACIÓN DE ARCHIVOS BASE

probé la creación de archivos con contenido

echo ^ > index.html

echo *{ > styles.css 
echo box-sizing: border-box; >>styles.css 
echo margin: 0; >> styles.css 
echo padding:0; >> styles.css 
echo } >> styles.css

echo ^ > menu\contactme.html 
echo ^ > menu\experience.html 
echo ^ > menu\projects.html 
echo ^ > menu\studies.html

INICIALIZACIÓN DE GIT

git init 
git status 
git add . 
git commit -m "Primer commit..."

Posteriormente el proyecto fue abierto en Visual Studio Code para sincronizar la rama main con GitHub y continuar el desarrollo utilizando commits.

PUBLICACIÓN EN GITHUB PAGES

Para que las rutas funcionaran correctamente en GitHub Pages fue necesario reemplazar rutas absolutas (/) por rutas relativas utilizando:

./  y  ../

AUTOR

Nadja Villarroel* Me ayudé con la IA para que me ayudara con la estructura del README.md