# Sitio web del Dataton Anticorrupción

Este repositorio tiene el código y versión en vivo del sitio web del datatón anticorrupción.

El repositorio tiene el código con el que se genera el sitio web utilizando el generador [Hugo](https://gohugo.io).

Hugo utiliza los archivos de configuración y plantillas y con ello genera un sitio estático que pone en la carpeta `/docs`. Esta carpeta /docs a su vez es servida por GitHub Pages en el dominio https://datatonanticorrupcion.mx


### Instrucciones para modificar el sitio

Para hacer cambios al sitio, recomendamos modificar los archivos y usar Hugo para "compilar" los archivos estáticos.

1. Instalar Hugo (https://gohugo.io).
2. Clonar este repositorio.
3. Modificar los archivos correspondientes:
    - `/config.toml` tiene la información general del sitio, mentores, jueces y patrocinadores
    - El resto de las páginas se contruye a partir de los archivos markdown bajo `/content/info`
    - El css está en `/themes/dataton-agency/static/css/agency.css`
    - Las imágenes se ponen en `/themes/dataton-agency/static/img`
4. Probar el sitio localmente con el comando `hugo server` desde el directorio raíz. Esto muestra el sitio en http://localhost:1313
5. Generar la versión estática del sitio con el comando `hugo` desde el directorio raíz. Esto actualizará los archivos bajo /docs.
6. Subir el repositorio actualizado a GitHub (`git add .` -> `git commit -m "..."` -> `git push origin master`)
