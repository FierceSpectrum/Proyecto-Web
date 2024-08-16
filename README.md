# Proyecto de Página Web de Videojuegos

Este proyecto fue desarrollado por [Benjamín Sandí](https://github.com/FierceSpectrum) y [Josafat Ramírez](https://github.com/Josafath17) como su primer proyecto en el ámbito de desarrollo web. El objetivo era crear una página web de información sobre videojuegos utilizando únicamente HTML y CSS, junto con Sass para los estilos. No se utilizó JavaScript en este proyecto.

## Descripción del Proyecto

La página web se enfoca en proporcionar información sobre videojuegos en tres categorías populares: MMORPG, MOBA y Shooter. Dentro de cada categoría se destacan cuatro videojuegos, proporcionando detalles como la fecha de lanzamiento, desarrolladores, y características del juego.

### Estructura del Sitio

- **Home:** La página principal donde se muestran los "Top 5 mejores juegos" y juegos organizados por categorías (MMORPG, MOBA y Shooter). También incluye un video de fondo con efectos de luces moradas y rosadas para ambientar la experiencia.
  
- **Categories:** En esta página se presentan los juegos según su categoría, con la posibilidad de navegar entre Shooters, MMORPG y MOBAs. Cada categoría cuenta con un header, una breve descripción, y tarjetas de juegos que muestran información adicional al pasar el mouse por encima.

- **About Us:** Una página donde se presentan los desarrolladores del proyecto, Benjamín Sandí y Josafat Ramírez, junto con enlaces a sus redes sociales.

### Características Técnicas

- **Responsividad:** El sitio es completamente responsive. El menú de navegación se convierte en un menú hamburguesa cuando el ancho de la pantalla es menor a 540 píxeles.
- **Animaciones:** En la versión móvil, las animaciones que normalmente se activan al pasar el mouse por encima, se muestran de inmediato cuando se presiona un elemento.
- **Sass:** Se utilizó Sass para la creación de estilos. Los archivos `.scss` se convirtieron automáticamente a CSS utilizando un convertidor dentro del proyecto (probablemente con Node.js y un módulo de npm para manejar Sass).

## Uso

Para clonar y ejecutar este proyecto localmente:

1. Clona el repositorio en tu máquina local:
    ```bash
    git clone https://github.com/FierceSpectrum/Proyecto-Web
    ```
2. Abre el proyecto en tu editor de código preferido.
3. Si deseas compilar Sass, asegúrate de tener instalado Node.js y las dependencias necesarias ejecutando:
    ```bash
    npm install
    ```
4. Para compilar los archivos Sass a CSS, puedes utilizar el siguiente comando:
    ```bash
    npm run sass
    ```
5. Abre el archivo `HOME.html` en tu navegador o utiliza una extensión como Live Server en VS Code para visualizar el proyecto.

## Estado del Proyecto

Este proyecto fue creado en el 2023, durante el segundo cuatrimestre del año, como una práctica para aprender los fundamentos del desarrollo web. Actualmente, se están realizando algunas actualizaciones para mejorar la estructura del código y la organización del repositorio en GitHub.

## Licencia

Este proyecto no tiene una licencia formal. Fue creado con fines educativos y no está destinado para uso comercial. Los desarrolladores son estudiantes de ingeniería de software que están aprendiendo y mejorando sus habilidades.
