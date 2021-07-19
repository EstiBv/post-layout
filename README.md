# `Prueba Técnica - Varadero Software Technology `

## `🎟 Reto planteado para proceso de selección. `

#### Objetivos 🏁

-   Objetivos requeridos
    -   HTML y CSS
    -   Estructura, organización y claridad de código
    -   Programación basada en estilos
    -   Conocimiento de responsive
-   Objetivos opcionales
    -   Conocimientos de uso de jQuery
    -   Conocimiento de SEO
    -   Conocimiento de Accesibilidad

---

##### Estructura del proyecto 🗺

Organización de ficheros.

-   Package.json (para la ejecución de Sass)
-   _Index.html_
-   Sass (hojas de estilos de scss y css)
    -   Core
        -   Funciones (función para poder escribir unidades en rem)
        -   Mixins (diferentes patrones de estilos)
        -   Variables (estilo general, colores y fuentes)
    -   Layout (diseños por estructuras/componentes)
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
-   Img (imágenes, assets)

---

#### `🧗‍♀️ Desafíos y conclusiones `

Adjunto algunos desafíos y conclusiones para contextualizar la prueba y dar a conocer parte de este proceso técnico.

📚 Inicialemente decidí desarrollar la maquetación utilizado Sass (habiendo esbozado un sketch de la estructura HTML sobre papel) porque es una herramienta que me gusta y que sobre todo, sigo descubriendo. Fue un pequeño reto iniciarla (pues es la primera vez que la utilizo sin NPM) aunque finalmente no fue tan complejo. También me he apoyado en el uso de pluggins para vsCode relativos al preprocesador CSS, siendo Sass y Live Sass Compiler.

📊 Otro de los retos encontrados ha sido aplicar conocimientos de SEO y tratar de garantizar una correcta accesibilidad (en la medida de lo posible). Es a lo que mas tiempo he dedicado pues en ambos tengo que seguir aprendiendo, sin embargo, esta prueba me ha dado la oportunidad de profundizar un poquito mas sobre ello y estoy agradecida.
✨ He descubierto Accessibility insights (for Web, https://accessibilityinsights.io/) para detectar problemas de accesibilidad y estoy muy contenta por poder contar a partir de ahora con esta herramienta. Destacar que la misma, me ha motivado a modificar el diseño en algunas zonas (en cuanto a contraste) y algunos de los errores mas comunes con los que he contado han sido:

-   1️⃣ Corregir el bajo contraste (es por ello que en ciertas áreas el tono del azul es mas oscuro).
-   2️⃣ Dotar de accesibilidad a elementos declarativos en grupos.
-   3️⃣ Aplicar correctamente atributos para elementos enfocables.

⚠️ En cuanto a estilos, comentar que la apariencia de los elementos decorativos (líneas separadoras) no las he logrado implementar como me gustaría. Están intruducidas desde las hojas de estilos, no utilicé estructura semántica para ellas y el restultado ha sido aproximado.
🤓 Me gustaría conocer el modo correcto para ajustarlo lo máximo posible al diseño dado.

🏋🏽 Y aunque me hubiese gustado completar la prueba realizado un diseño mas abarcable para diferentes dispositivos, aplicando mediaqueries o lograr alcanzar todos los objetivos (como aplicar JQuery), dotar de cierta funcionalidad a la web, como por ejemplo habilitar el uso del formulario, dotar de eventos a los botones, y complementar o justificar cierta interacción con alguna animación, etc. Entrego este reto **agradecida por la oportunidad y contenta de seguir recibiedo estímulos que continúan motivando mi objetivo laboral**.

🙂 Muchas gracias
# post-layout
