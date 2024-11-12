<h1><strong></strong>Ejercicio-Práctico 2</strong> </h1> <br>

<p>Desarrollo de la Página Web de un Hospital</p>

<h2>Contexto</h2>

Un hospital privado está buscando mejorar su presencia en línea mediante la creación de un sitio web que proporcione información clara y fácil de navegar para los pacientes. El sitio web debe reflejar la identidad del hospital, con información sobre los servicios médicos, el equipo médico, y una manera sencilla para que los pacientes puedan contactarse.

Trabajo práctico para desarrollar una página web de hospital que debe contener las siguientes páginas:

1. Vista Principal (Home o Index)
2. Vista del Equipo Médico
3. Vista de Contacto

Este proyecto tiene como objetivo realizar mejoras a la página del hospital desarrollada en el ejercicio anterior, aplicando SASS.

Para mayor claridad, decidí realizar este ejercicio desde cero y luego integrar parte del contenido realizado en el ejercicio anterior, además de dividir el trabajo por páginas y secciones semánticas (header, footer, etc).

Instrucciones de uso
Clonar el repositorio desde GitHub, o en su defecto descargar los contenidos como zip.
Luego, abrir `index.html` en su navegador por defecto, pero se recomienda Chrome para una mejor experiencia.

<h3>Estructura del proyecto</h3>

## Centro médico
    ├── assets
    	 ├── /css              # Archivos css preprocesados con SASS
		 ├── /style.css
		 ├── /style.css.map
    	 ├── /img              # Imágenes utilizadas en el proyecto
    ├── scss                 # SASS estructura, usando solo carpetas relevantes           
    ├──── /abstracts         # Variables y mixins
		 ├── __mixins.scss
		 ├── __variables.scss
    ├──── /base              # Estilos base / generales
		 ├── __base.scss
		 ├── __reset.scss
    ├──── /components         # Módulos, footer, header y botones.
		 ├── __buttons.scss
		 ├── __footer.scss
		 ├── __header.scss
    ├──── /layout              # Estilos para estructuras semánticas
		 ├── __container.scss
		 ├── __grid.scss
    ├──── /pages              # Estilos para paginas especificas
		 ├── __contact.scss
		 ├── __home.scss
		 ├── __services.scss
    ├──── /main.scss          # Contiene todas las referencias de SASS
    ├── contact.html          # Página de contacto
    ├── home.html             # Página de inicio
    ├── services.html         # Página de nosotros y servicios
    └── README.md             # Ud. se encuentra aqui

  
Este texto se subio como archivo a la plataforma, agrego link que redirige a esta misma páginas donde se pueden visualizar las carpetas creadas https://github.com/Byskachita/Front-End_M2-ACT2
