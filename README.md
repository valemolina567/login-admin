# Login Responsive - AdminExpress

## Descripción

Este proyecto consiste en la creación de una interfaz de inicio de sesión (*Login*) para **AdminExpress**, desarrollada como parte de la actividad en clase de la materia **Ingeniería Web** de la Universidad de las Américas (UDLA).

El objetivo es replicar un diseño de login utilizando HTML y CSS, aplicando CSS Grid y Media Queries para lograr una interfaz responsive que se adapte a diferentes tamaños de pantalla.

## Características

* Diseño dividido en dos paneles: uno azul con el nombre de la aplicación y otro con el formulario de inicio de sesión.
* Formulario con campos de correo electrónico y contraseña.
* Iconos de sobre, candado y visibilidad de contraseña.
* Botón de inicio de sesión (*Sign In*).
* Enlaces de recuperación de contraseña y registro.
* Diseño responsive para computadoras, tabletas y celulares.
* Efectos visuales al pasar el cursor sobre el botón y al seleccionar los campos.

## Tecnologías utilizadas

* **HTML5:** estructura del contenido y formulario.
* **CSS3:** estilos, colores, distribución y diseño visual.
* **CSS Grid:** organización de los paneles principales.
* **Flexbox:** alineación de elementos dentro de los componentes.
* **Media Queries:** adaptación a diferentes resoluciones de pantalla.
* **Font Awesome:** iconos del formulario.

## Estructura del proyecto

```text
login-admin/
├── index.html
├── README.md
└── css/
    └── estilos.css
```

## Cómo ejecutar el proyecto

1. Clonar el repositorio:

   ```bash
   git clone URL_DE_TU_REPOSITORIO
   ```

2. Ingresar a la carpeta del proyecto:

   ```bash
   cd login-admin
   ```

3. Abrir el archivo `index.html` en el navegador.

   También puedes utilizar la extensión **Live Server** de Visual Studio Code para visualizar los cambios en tiempo real.

> **Nota:** Para cargar los iconos de Font Awesome es necesaria una conexión a Internet.

## Diseño responsive

La interfaz utiliza Media Queries para adaptar su estructura según el ancho de la pantalla:

* **Escritorio:** muestra el panel azul y el formulario en dos columnas.
* **Tableta:** ajusta la proporción de las columnas para dar más espacio al formulario.
* **Celular:** oculta el panel azul y muestra el formulario en una sola columna.

## Objetivo académico

Aplicar los fundamentos de HTML y CSS mediante la construcción de una interfaz web, utilizando estructuras de diseño flexibles y técnicas de diseño responsive.

## Limitaciones

Este proyecto corresponde únicamente a la interfaz visual del inicio de sesión. No cuenta con un sistema de autenticación ni conexión a una base de datos. Los enlaces de recuperación de contraseña y registro son demostrativos.

---

**Materia:** Ingeniería Web

**Institución:** Universidad de las Américas (UDLA)
