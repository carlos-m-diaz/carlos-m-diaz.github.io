---
layout: default
title: Github pages y jekyll
parent: Creando un blog
grand_parent: Marca Personal
nav_order: 1
---

# Creando una página web gratis con Github Pages y Jekyll
Para no aburrirlos, voy primero con el resumen y luego con algo de detalle

{: .highlight }
> - Crearemos una cuenta en Github: Será nuestro servidor de hosting. Aquí alojaremos nuestra página.
> - Crearemos la página a partir un template de jekyll: El template que usaremos está guardado en los repositorios de github. Debemos clonarlo para crear nuestra página.
> - Ajustaremos el pipeline en Github Actions para aplicar los cambios a nuestra pagina.

## Crear cuenta en github
Primero lo primero: Vamos a crear una cuenta en github.
Accede a [github.com](https://github.com/) y presiona en **Sing Up**.

![sing up](/docs/marca-personal/crear-blog/github-pages-jekyll/images/1.png)

Coloca tu correo electronico y presiona **Continue**.

![email](/docs/marca-personal/crear-blog/github-pages-jekyll/images/2.png)

{: .warning }
> Asegúrate de que tu clave sea diferente a tu nombre de usuario y no coincida con tu correo.

![pass](/docs/marca-personal/crear-blog/github-pages-jekyll/images/3.png)

Pasa un largo proceso de verificación.

![verification 1](/docs/marca-personal/crear-blog/github-pages-jekyll/images/4.png)

![verification 2](/docs/marca-personal/crear-blog/github-pages-jekyll/images/5.png)

Luego te enviaran un código a tu correo para verificarlo.

![verification 3](/docs/marca-personal/crear-blog/github-pages-jekyll/images/6.png)

Listo!! Ya tienes tu cuenta de github. Ahora entra con tu usuario y clave.

![autentication](/docs/marca-personal/crear-blog/github-pages-jekyll/images/7.png)

## Crear página la partir de template de jekyll
Acceder al [template](https://just-the-docs.github.io/just-the-docs/#getting-started) y ubica el vinculo "use the template" o simplemente presiona [aquí](https://github.com/just-the-docs/just-the-docs-template/generate)

![template](/docs/marca-personal/crear-blog/github-pages-jekyll/images/8.png)

Crea tu nuevo repositorio siguiendo el siguiente patrón: {nombre de tu repositorio}.github.io

{: .warning }
> Es importante seguir el patrón mencionado arriba, de otra forma github no tomará tu repositorio como una página.

![repo name](/docs/marca-personal/crear-blog/github-pages-jekyll/images/9.png)

Agrega una descripción y mantén el repositorio público.

![repo options](/docs/marca-personal/crear-blog/github-pages-jekyll/images/10.png)

Despues de unos segundos, tienes el repo creado.

![repo creation 1](/docs/marca-personal/crear-blog/github-pages-jekyll/images/11.png)

![repo creation 2](/docs/marca-personal/crear-blog/github-pages-jekyll/images/12.png)

## Ajustar el pipeline en Github Actions

1.- Acceder a la pagina del template https://just-the-docs.github.io/just-the-docs/
2.- Click en "use the template" https://github.com/just-the-docs/just-the-docs-template/generate
Esto te llevará directamente a tu cuenta de github para crear un nuevo repositorio
4.- Crear el nuevo repositorio con el nombre {USERNAME}.github.io
5.- Configurar el pipeline
Bla bla bla
6.- Listo! Ya tienes una pagina gratis en github pages