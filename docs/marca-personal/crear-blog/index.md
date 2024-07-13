---
layout: default
title: Creando un blog
parent: Marca Personal
nav_order: 2
has_children: true
---

# Creando un blog

Después mucho tiempo pensando en desarrollar mi imagen personal, decidí comenzar a escribir en un blog y para ello es necesario utilizar alguna plataforma de blogging o simplemente crear una página. 
La plataforma que más me gustaba es Medium debido a que mi audiencia lo utiliza mucho (mi gente de la informática lo usa como referencia a la hora de consultas). Sin embargo, al revisar un poco, me doy cuenta de que no acepta dominios personalizados desde hace tiempo y esto me llevó a buscar la forma de construir mi propio blog.

## Mis drivers

Lo que busco generalmente cuando comienzo un proyecto es automatizar lo mas posible cualquier proceso me parezca tediozo o complicado, y por supuesto, incurrir en el menor gasto posible. Partiendo de ese punto definí mis drivers:
- **Gratis**: Todo esto es un mvp por que debo gastar lo menos posible.
- **Curva de aprendizaje corta**: no quiero aprender ningún lenguaje de programación por años antes de tener mi blog. Sólo necesito escribir.
- **Escribir en markdown**: el famosos metalenguaje que usamos todos para documentar.
- **Separar el blog de los posts**: esto me da la ventaja de escribir desde cualquier lugar sin preocuparme de romper la página.
- **Uso de templates para el diseño**: Si en algún momento puedo generar algo de plata con el blog, lo primero que haría sería reinvertir la ganancia en un diseño llamativo.

Asi que, con mis drivers en mente, comencé a investigar y llegue a jekyll y github pages. Voy a explicarte la forma más rápida y barata de hacer una página estática y comenzar a subir tu contenido sin saber programar.

## Conocimientos necesarios

- **Markdown**: para escribir las entradas del blog
- **Git**: nivel básico para control versiones

## Pre requisitos

### Servicios
- **Github account**: para comenzar debes tener una cuenta de github creada.

### Local
- **Visual Studio Code**: o cualquier editor de texto que entienda markdown.
- **Git**: para versionar el codigo de la pagina y los posts del blog.

## Base teórica
Antes de comenzar vamos con un poco de contexto rápido. Dejemos que ChatGPT haga su magia...

### Que es Git?
Git es un sistema de control de versiones distribuido. Sirve para gestionar y registrar cambios en el código fuente, facilitando la colaboración entre desarrolladores y el seguimiento de la historia del proyecto.

Recurso: [git-scm.com](https://git-scm.com/)

### Qué es GitHub?
GitHub es una plataforma de desarrollo colaborativo basada en la web que utiliza Git para el control de versiones. Sirve para alojar repositorios de código, colaborar en proyectos, realizar revisiones de código, gestionar problemas y realizar despliegues continuos.

Recurso: [github.com](https://github.com/)

### Qué es GitHub Pages?
GitHub Pages es un servicio de alojamiento de sitios web estáticos. Sirve para publicar páginas web directamente desde un repositorio de GitHub, ideal para sitios personales, proyectos de código abierto y documentación.

Recurso: [pages.github.com](https://pages.github.com/)

### Qué es Ruby?
Ruby es un lenguaje de programación interpretado y orientado a objetos. Sirve para desarrollar aplicaciones web, automatizar tareas, manejar datos y crear scripts. Es conocido por su sintaxis sencilla y legible, lo que facilita su aprendizaje y uso.

Recurso: [ruby-lang.org](https://www.ruby-lang.org/)

### Qué es Jekyll?
Jekyll es un generador de sitios estáticos escrito en Ruby. Sirve para convertir archivos de texto plano en sitios web estáticos, ideal para blogs y proyectos de documentación, y es compatible con GitHub Pages para una fácil publicación.

Recurso: [jekyllrb.com](https://jekyllrb.com/)