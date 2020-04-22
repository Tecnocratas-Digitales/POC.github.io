# Contributing

Esta guía te va a instruir en los guidelines establecidos en Tecnócratas Digitales.

## General

Esta sección contiene las normas generales para escribir y mantener el blog.

### Normas generales

* El idioma oficial de los post y los guidelines es el castellano.
* Toda parte hecha con código, incluidos los comentarios, será hecho en inglés.
* Para crear un nuevo post se deberá seguir las `Normas de publicación`
 establecidas más abajo siguiendo los `Guidelines de publicación`.
* Antes de aceptar un Pull Request a master, es necesaria una aprobación del PR.
 Está configurado en Github para que sea estrictamente necesario.
* Sé siempre educado.
* Acepta las críticas constructivas.
* Evita EL USO DE MAYÚSCULAS para dar enfásis en las discusiones.
* Sólo abre un PR a la vez. No los uses como borrador de artículos.

### Consejos

* Se recomienda usar Visual Studio Code (IDE opensource y modular) con la extensión `markdownlint`
* Puedes usar Atom, Vim, o tu editor favorito, siempre que cumplas el linting.
 
## Publicación

Esta sección es de obligado cumplimento a la hora de colaborar escribiendo artículos con
Tecnócratas Digitales.

### Normas de publicación

* Elección de artículo.
    * Comenta de qué va a tratar.
    * Asegúrate que el artículo aporta valor.
* Redacción del artículo.
    * Utiliza material propio en la medida de lo posible.
    * Si te basas en datos y artículos, añadelos en la sección de Bibliografía después del artículo.
    * Respeta las normas de linting.

### Guidelines de publicación

* [ ] Sugiere el artículo en Tecnócratás Digitales.
* [ ] Redáctalo a tu gusto.
* [ ] Pide revisión.
* [ ] Publícalo.

## Blog developing

Esta sección está diseñada únicamente para los desarrolladores del blog. 
Si vienes para publicar puedes ignorarla.

### Normas de desarrollo del blog

* Diseño de la feature
    * Consulta antes con tus compañeros si el cambio es necesario.
* Durante el Desarrollo
    * Haz los cambios pertinentes en commits atómicos.
    * Pide feedback a los otros desarrolladores cuando sea necesario.
    * Comprueba que se cumplen las reglas de linting.
* Comprueba que todo sigue funcionando antes de mergear.

### Guidelines de desarrollo de features del blog

* [ ] Crea una rama en local y en el repositorio.
    * [ ] El nombre debe tener el formato `git checkout -b feature-${NOMBRE_DE_LA_FEATURE}`
    * [ ] Crea los ficheros nuevos sin editar que necesites.
    * [ ] Haz un push sin cambios para crear el pull request `git push origin feature-${NOMBRE_DE_LA_FEATURE}`
    * [ ] Accede a la página de [pulls](https://github.com/Tecnocratas-Digitales/POC.github.io/pulls)
    * [ ] Pulsa en `New pull request`
    * [ ] Compara base:master con comparte:feature-${NOMBRE_DE_LA_FEATURE}
    * Pulsa en `Create Pull Request` y añade descripción.
* [ ] Desarrollo
    * [ ] Haz los cambios pertinentes en commits atómicos.
    * [ ] Pide feedback a los otros desarrolladores cuando sea necesario.
* [ ] Integración
    * [ ] Solicita revisión a los colaboradores.
    * [ ] Comprueba el linting y los tests.
    * [ ] Cuando el cambio sea aprobado, pulsa en Merge Pull Request.
