# Introducción. #

Bienvenido a GluePHP, un *framework* para el desarrollo de [aplicaciones web de una sola página](https://es.wikipedia.org/wiki/Single-page_application) empleando el [paradigma de la programación dirigida por eventos](https://es.wikipedia.org/wiki/Programaci%C3%B3n_dirigida_por_eventos).

## Requerimientos. ##
- PHP 7.1

## Licencia. ##
- MIT

## Instalación. ##

>Tenga en cuenta que el proyecto se encuentra en una fase inestable.

La instalación de GluePHP se realiza mediante composer. Para esto es necesario declarar las siguientes dependencias en el archivo *composer.json*.

    {
        "require": {
            "glueapps/composed-views": "dev-0.1a",
            "glueapps/glue-php": "dev-0.1a"
        }
    }

Seguidamente se debe ejecutar el comando:

    $ composer update

## Terminología. ##

Las aplicaciones hechas con GluePHP las definimos como **glue apps**. Una de las características de estas aplicaciones es que son compuestas, por lo que a sus componentes les llamamos **glue components**. Éstos componentes presentan datos compartidos y sincronizados entre el navegador y el servidor a los cuales definimos como **glue attributes**. Por otra parte, definimos como **glue kit** a un conjunto de *glue components* reutilizables.

Durante el desarrollo práctico del libro podrá comprender a fondo estos conceptos. No obstante, queremos aclarar que éstos solo tienen un significado local a nuestro proyecto y no guardan relación con otros ya bien conocidos en la informática como *glue code*, *glue framework*, etc.

Por razones de simplicidad, a lo largo del libro usaremos de manera equivalente los términos app, componente y kit, para referirnos a *glue app*, *glue component* y *glue kit* respectivamente.

## Filosofía. ##

Desarrollar una *glue app* es muy similar a desarrollar una aplicación con interfaz gráfica para el *desktop* o para móviles. En esos casos se cuenta con una serie de componentes gráficos que son añadidos al diseño de la interfaz donde más tarde se les programa sus eventos. Esta filosofía de desarrollo se corresponde con el paradigma de la programación dirigida por eventos y es la empleada en el desarrollo con GluePHP.

Dada la gran diversidad que existe en el aspecto de las aplicaciones web, a la hora de desarrollar una *glue app* suele ser común tener que crear primeramente los componentes gráficos denominados *glue componentes* según nuestra terminología. No obstante, gracias a las facilidades que brinda GluePHP esta tarea se realiza de una manera muy sencilla.

## Ventajas y desventajas. ##

GluePHP facilita muchos de los esfuerzos necesarios para el desarrollo de aplicaciones web de una sola página en PHP. Es por esto que reduce considerablemente los tiempos de desarrollo sobre todo en las aplicaciones basadas en kits de componentes reutilizables como son las administraciones o aplicaciones de gestión en general.

No obstante, en aplicaciones con gran cantidad de componentes y/o alta concurrencia de eventos puede verse afectado el rendimiento.

## Contribuyendo. ##

[https://github.com/GlueApps/GluePHP#contribuyendo](https://github.com/GlueApps/GluePHP#contribuyendo)