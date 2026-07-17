# Proyecto Forrest Gump - Final de programación web 1! - cuatrimestre 1-2026

Este proyecto es la mejora visual y de compatibilidad del sitio realizado para el segundo parcial. 
Incluyendo mejoras en las páginas fuera del HOME, mejorando la comportamiento responsive del sitio, e incorporando un par de tácticas para que esto funcione bien


# Cambios y decisiones del proyecto (*esto es realmente del segundo parcial, pero sigue siendo todo cierto jaja*)
Una de las primeras decisiones fue cambiar la sección llamada “Sobre” por “Película”. Me parecía que “sobre” quedaba medio raro como nombre de sección, es como una traducción literal de about y me suena a sobre de carta. Como el contenido habla de la película, su sinopsis, contexto e iframe multimedia, preferí llamarla directamente “Película”.
También se reorganizó el sitio para que no quede todo en una sola página. Ahora cada sección principal tiene su propio HTML:
    -index.html: página principal del sitio.
    -pelicula.html: información general, sinopsis e iframe multimedia.
    -reparto.html: actores y personajes principales.
    -produccion.html: información sobre producción, rodaje y efectos.
    -curiosidades.html: curiosidades, premios e impacto cultural.
    -contacto.html: formulario de contacto.
    -confirmacion.html: página de confirmación del formulario.
    -404.html: página de error con la misma estética del sitio.

# Diseño visual (*cambió mucho, sobre todo en cuanto a responsive*)
La estética del sitio intenta acompañar el tono nostálgico de Forrest Gump. Para eso usé una paleta de colores cálidos, verdes apagados, marrones y fondos tipo papel.
Se cambió la tipografía a Libre Baskerville bajo consejo del profesor y criterio propio 100% de acuerdo con el consejo. 
Se utilizó mejor el tema de las tarjetas, para que funcionen bien con respecto a distintos tamaños de tarjetas, separandose en columnas cuando haya espacio suficiente, e incluyendo imágenes en las de Reparto

# Organización del CSS (*acá no hubo grandes cambios, en la estructura al menos, a pesar de que dentro de cada uno haya cambiado UNA BOCHA*)
El CSS fue separado en varios archivos para no tener todo mezclado:
    -styles.css: estilos generales, header, navegación, footer, colores base y clases reutilizables.
    -home.css: estilos específicos de la página principal.
    -pages.css: estilos compartidos por las páginas internas.
    -contacto.css: estilos del formulario y de la página de confirmación.
La intención fue evitar repetir código y usar clases reutilizables como contenedor, tituloPrincipal, tituloSeccion, texto-largo y textoJustificado.

# Recursos multimedia (*pequeñas adiciones*)
En la página pelicula.html se incluyó un iframe de YouTube con el trailer de Forrest Gump. 
Elegí usar iframe en lugar de un archivo de audio local para evitar problemas con archivos de audio con copyright y porque la consigna permitía usar audio o iframe.
También ahora se agregaron imágenes a cada una de las tarjetas de la sección Reparto. No hubo otros cambios en los contenidos multimedia.

# Interactividad y responsive
*El sitio usa solamente HTML y CSS. No se utilizó JavaScript ni frameworks.*
Se agregaron efectos simples con hover, transition y cambios visuales en botones, tarjetas y navegación. También se utilizó grid para organizar la portada y las tarjetas de la página principal, y flex para la estructura general del body y la navegación.
El menú tiene una versión responsive con hamburguesa hecha solo con HTML y CSS. 
Todas las páginas muestran ahora comportamiento responsive, cambios respecto a 3 tamaños, MOVIL; TABLET; PC (375px, 676px, 1024px) 

# Tecnologías utilizadas
- HTML5 semántico.
- CSS3.
- Flexbox y CSS Grid.
- Media queries para el diseño responsive.
- Git y GitHub para el control de versiones.
- Vercel para el despliegue.

# Despliegue (*sin cambios*)
Sitio desplegado en Vercel: https://forrest-gump-mw-2026.vercel.app/

# Repositorio (*sin cambios*)
Repositorio en GitHub: https://github.com/MarWG/forrest_gump_MW_2026
