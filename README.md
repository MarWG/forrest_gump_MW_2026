# Proyecto Forrest Gump - Segundo Parcial Programación Web 1-cuatrimestre 2-2026

Este proyecto es la """continuación""" del sitio realizado para el primer parcial. La idea fue tomar la base que ya tenía y reorganizarla como un sitio más completo, separando el contenido en distintas páginas y mejorando la estética general.
(_continuación entre muchas comillas, porque lo rehice entero realmente, no quedó ni una coma del anterior de chat jajaja_)

# Cambios y decisiones del proyecto
Una de las primeras decisiones fue cambiar la sección llamada “Sobre” por “Película”. Me parecía que “sobre” quedaba medio raro como nombre de sección, es como una traducción literal de about y me suena a sobre de carta. Como el contenido habla
de la película, su sinopsis, contexto e iframe multimedia, preferí llamarla directamente “Película”.
También se reorganizó el sitio para que no quede todo en una sola página. Ahora cada sección principal tiene su propio HTML:

    -index.html: página principal del sitio.
    -pelicula.html: información general, sinopsis e iframe multimedia.
    -reparto.html: actores y personajes principales.
    -produccion.html: información sobre producción, rodaje y efectos.
    -curiosidades.html: curiosidades, premios e impacto cultural.
    -contacto.html: formulario de contacto.
    -confirmacion.html: página de confirmación del formulario.
    -404.html: página de error con la misma estética del sitio.

# Diseño visual
La estética del sitio intenta acompañar el tono nostálgico de Forrest Gump. Para eso usé una paleta de colores cálidos, verdes apagados, marrones y fondos tipo papel.
También se cambió la tipografía de los títulos usando Bodoni Moda desde Google Fonts, porque me parecía que combinaba mejor con una estética más clásica/cinematográfica que la fuente básica inicial.

# Organización del CSS

El CSS fue separado en varios archivos para no tener todo mezclado(_y porque la consigna lo pedía_):

    -styles.css: estilos generales, header, navegación, footer, colores base y clases reutilizables.
    -home.css: estilos específicos de la página principal.
    -pages.css: estilos compartidos por las páginas internas.
    -contacto.css: estilos del formulario y de la página de confirmación.

La intención fue evitar repetir código y usar clases reutilizables como contenedor, tituloPrincipal, tituloSeccion, texto-largo y textoJustificado.

# Recursos multimedia
En la página pelicula.html se incluyó un iframe de YouTube con el trailer de Forrest Gump. Elegí usar iframe en lugar de un archivo de audio local para evitar problemas con archivos de audio con copyright y porque la consigna permitía usar audio o iframe.

# Interactividad y responsive
*El sitio usa solamente HTML y CSS. No se utilizó JavaScript ni frameworks.*
Se agregaron efectos simples con hover, transition y cambios visuales en botones, tarjetas y navegación. También se utilizó grid para organizar la portada y las tarjetas de la página principal, y flex para la estructura general del body y la navegación.
El menú tiene una versión responsive con hamburguesa hecha solo con HTML y CSS. (a mejorar, si.)

# Despliegue
Sitio desplegado en Vercel: https://forrest-gump-mw-2026.vercel.app/

# Repositorio
Repositorio en GitHub: https://github.com/MarWG/forrest_gump_MW_2026
