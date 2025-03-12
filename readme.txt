# Proyecto de Diapositivas

Este proyecto contiene una serie de diapositivas diseñadas con HTML y CSS. El diseño incluye secciones, imágenes, formularios, botones y estilos.
A continuación se describe la estructura del proyecto, cómo navegar por las diapositivas y detalles adicionales que el cliente debería conocer.


## Estructura del Proyecto

La estructura básica del proyecto es la siguiente:


### Descripción de los Archivos:

- /index.html: El archivo principal HTML que estructura las diapositivas.
- /html/*: Almacena todos los documentos HTML a excepción del index.html.
- /estilos/genericos.css: Define los estilos iguales de todas las páginas.
- /estilos/header.css: Define los estilos del header que se usarán en todas las páginas por igual.
- /estilos/*.css: Define los estilos de cada página individualmente.
- /imagenes/*: Contiene las imágenes utilizadas en las diapositivas.

#### Como navegar entre Diapositivas:

En el header de cada HTML, se encuentran los enlaces a las distintas diapositivas, representados con una sola palabra.


##### Decisiones tomadas:

 - Header:
    - El logo de la página que se encuentra en el header es un enlace a la página de inicio.
    - Cuando te encuentras en una página concreta en el header no aparece la opción de ir a la misma página
    - Al usarse en dispositivos móviles o reducir la ventana a menos de 768 píxeles el menú del header pasa a ser un desplegable que se abre al pasar el cursor por encima.
 - Index.html:
    - El tamaño de las imagenes cambian según el tamaño de la ventana o el dispositivo.
    - El botón de "COMPRAR AHORA" nos redirige a la página de la tienda.
    - Cuando la página ocupa un tamaño inferior a 768 píxeles se redistribuyen las imágenes para que se vea mas ordenado.
 - Nosotros:
    - Las imágenes de redes sociales nos redirigen a ellas, abriendo una nueva ventana y no permitiendo volver a la misma página por seguridad.
    - Al usarse en dispositivos móviles, la imagen pasa a estar encima del texto para que todo ocupe un buen espacio.
    - El logo de la empresa nos redirige a la página de inicio.
 - Cursos:
    - Los botones de "LEER MÁS" nos redirigen a la página de la tienda.
 - Tienda:
    - Cuando la ventana ocupa menos de 768px, se ajusta el tamaño de las imágenes para evitar colisiones.
 - Contacto:
    - El nombre es obligatorio, al igual que aceptar las condiciones.
    - Los datos ingresados se almacenan en una base de datos real.
    - Las imágenes de redes sociales y el logo te redirigen a las mismas.