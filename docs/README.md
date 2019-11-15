
Este repositorio tiene el código del sitio web en https://datatonanticorrupcion.mx.

Está hecho con Hugo (https://gohugo.io/), un generador de sitios estáticos.

La carpeta /docs es la que tiene el sitio estático, que se está sirviendo via GitHub Pages.

## Procedimiento para modificar el sitio
Para hacer cambios al sitio, se haría lo siguiente:

1. Instalar Hugo en tu computadora.
2. Clonar este repositorio.
3. Hacer los cambios requeridos:
    - Textos del homepage, menú de navegación, info de mentores y faq están en **config.toml** 
    - Otras páginas, como la de Contexto o Datos son archivos en markdown que están bajo **content/info/**
    - El css que se usa es **themes/dataton-agency/static/css/agency.css**
    - Las imagenes se suben a **themes/dataton-agency/static/img/**
4. Puedes probar el sitio localmente corriendo `hugo serve` desde el directorio raíz.
5. Para "compilar" el sitio en archivos estáticos, ejecutar `hugo` desde el directorio raíz, y esto va a poner los archivos estáticos en  el directorio /docs
