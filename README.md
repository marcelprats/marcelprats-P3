Html:

    -head: Conecta con el documento styles.css y la fuente api de google.

    -body:
        -header: Primera franja rosa con datos de contacto, ademas el menu de navegación.

        -footer: Mismo código para las 3 páginas.

        -script: Para ocultar/mostrar el menú de navegación en dispositivos. 


        -main:

            Página index.html:

                - <section class="intro-section">: Primer container con el texto en grande, el buscador y los 3 iconos con texto.

                - <section class="popular-courses">: Lista de los 8 cursos más importantes.

                - <section class="learning-path">: Sección para el learning path.

                - <section class="online-learning-solutions">, <section class="top-categories"> & <section class="become-instructor">: Las demás secciones de la página

            
            Página become-an-instructor.html:

                - Primero se crean dos columnas para separar el contenido.

                - <section class="instructor-section">: Texto de introducción e imagen.

                - <section class="steps-to-instructor">; Lista de los pasos a seguir.

                - <section (id="step1", id="step2", id="step3" & id="step4") class="step-details">: Explicación de cada uno de los 4 pasos en detalle.

                - <section class="instructor-career-path">: Columna de la derecha.

            Página contact.html:

                - La página consta de una sola sección dividida por divs que se divide en dos columnas.

                - <div class="offices">: Las 3 ciudades de contacto.

                - <div class="ambassadors"> & <div class="ambassador">: Contiene a los 4 ambassadors.

                - <div class="call-form">: Define las características del formulario de la columna de la derecha.



Css:

    - header: Modificaciones del header.

    - footer & .newsletter: Define las características del footer y su interior.

    - browse-all-btn, .apply-now-btn, .register-now-btn, .apply-btn, ... : Definicion de las características de los diferentes botones de la página.

        Página index.html:

            - .intro-section, .search-form & .features: Modificaciones para el texto, el buscador y los 3 iconos con texto de la primera sección.

            - .popular-courses: Características de <section class="popular-courses">.

            - .learning-path: Características de <section class="learning-path">.

            - .online-learning-solutions, .top-categories & .become-instructor: Características de <section class="learning-path">, <section class="top-categories"> & <section class="become-instructor">

            - .top-categories: Características de <section class="learning-path">.

        Página become-an-instructor.html:

            - .instructor-section, .steps-to-instructor, .step-details: Características de las 3 secciones de la columna de la izquierda.

            - .career-path: Define las características de la columna de la derecha.

        Página contact.html:

            - .instructor-career-path: Define el formulario de la columna de la derecha.

            - .offices & .ambassador: Define las caraacterísticas de las secciones de la columna de la izquierda.
    
    - .menu-toggle: Define las características del menu para dispositivos.


    - @media: Define las características para dispisitivos.

