# `Prueba T茅cnica - Varadero Software Technology `

## `馃師 Reto planteado para proceso de selecci贸n. `

#### Objetivos 馃弫

-   Objetivos requeridos
    -   HTML y CSS
    -   Estructura, organizaci贸n y claridad de c贸digo
    -   Programaci贸n basada en estilos
    -   Conocimiento de responsive
-   Objetivos opcionales
    -   Conocimientos de uso de jQuery
    -   Conocimiento de SEO
    -   Conocimiento de Accesibilidad

---

##### Estructura del proyecto 馃椇

Organizaci贸n de ficheros.

-   Package.json (para la ejecuci贸n de Sass)
-   _Index.html_
-   Sass (hojas de estilos de scss y css)
    -   Core
        -   Funciones (funci贸n para poder escribir unidades en rem)
        -   Mixins (diferentes patrones de estilos)
        -   Variables (estilo general, colores y fuentes)
    -   Layout (dise帽os por estructuras/componentes)
        -   Header
            -   _header.scss_
        -   Main
            -   _main.scss_
            -   Content Info
                -   _contentInfo.scss_
            -   Aside
                -   _aside.scss_
        -   Foooter
            -   _footer.scss_
            -   information
                -   _information.scss_
            -   copy
                -   _copys.scss_
-   Img (im谩genes, assets)

---

#### `馃鈥嶁檧锔? Desaf铆os y conclusiones `

Adjunto algunos desaf铆os y conclusiones para contextualizar la prueba y dar a conocer parte de este proceso t茅cnico.

馃摎 Inicialemente decid铆 desarrollar la maquetaci贸n utilizado Sass (habiendo esbozado un sketch de la estructura HTML sobre papel) porque es una herramienta que me gusta y que sobre todo, sigo descubriendo. Fue un peque帽o reto iniciarla (pues es la primera vez que la utilizo sin NPM) aunque finalmente no fue tan complejo. Tambi茅n me he apoyado en el uso de pluggins para vsCode relativos al preprocesador CSS, siendo Sass y Live Sass Compiler.

馃搳 Otro de los retos encontrados ha sido aplicar conocimientos de SEO y tratar de garantizar una correcta accesibilidad (en la medida de lo posible). Es a lo que mas tiempo he dedicado pues en ambos tengo que seguir aprendiendo, sin embargo, esta prueba me ha dado la oportunidad de profundizar un poquito mas sobre ello y estoy agradecida.
鉁? He descubierto Accessibility insights (for Web, https://accessibilityinsights.io/) para detectar problemas de accesibilidad y estoy muy contenta por poder contar a partir de ahora con esta herramienta. Destacar que la misma, me ha motivado a modificar el dise帽o en algunas zonas (en cuanto a contraste) y algunos de los errores mas comunes con los que he contado han sido:

-   1锔忊儯 Corregir el bajo contraste (es por ello que en ciertas 谩reas el tono del azul es mas oscuro).
-   2锔忊儯 Dotar de accesibilidad a elementos declarativos en grupos.
-   3锔忊儯 Aplicar correctamente atributos para elementos enfocables.

鈿狅笍 En cuanto a estilos, comentar que la apariencia de los elementos decorativos (l铆neas separadoras) no las he logrado implementar como me gustar铆a. Est谩n intruducidas desde las hojas de estilos, no utilic茅 estructura sem谩ntica para ellas y el restultado ha sido aproximado.
馃 Me gustar铆a conocer el modo correcto para ajustarlo lo m谩ximo posible al dise帽o dado.

馃弸馃徑 Y aunque me hubiese gustado completar la prueba realizado un dise帽o mas abarcable para diferentes dispositivos, aplicando mediaqueries o lograr alcanzar todos los objetivos (como aplicar JQuery), dotar de cierta funcionalidad a la web, como por ejemplo habilitar el uso del formulario, dotar de eventos a los botones, y complementar o justificar cierta interacci贸n con alguna animaci贸n, etc. Entrego este reto **agradecida por la oportunidad y contenta de seguir recibiedo est铆mulos que contin煤an motivando mi objetivo laboral**.

馃檪 Muchas gracias

#
