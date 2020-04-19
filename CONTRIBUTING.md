# Contributing

Esta guia te va a instruir en los guidelines establecidos en Tecnócratas Digitales.

## General

Esta sección contiene las normas generales para escribir y mantener el blog.

### Normas generales

* El idioma oficial de los post y los guidelines es el castellano.
* Toda parte hecha con código, incluidos los comentarios, será hecho en Inglés.
* Para crear un nuevo post se deberá seguir las `Normas de publicación`
 establecidas más abajo siguiendo los `Guidelines de publicación`.
* Antes de aceptar un Pull request a master es necesaria una aprobación de request.
 Está Configurado en Github para ser estrictamente necesario.
* Sé siempre educado.
* Acepta las críticas constructivas.
* Evita EL USO DE MAYUSCULAS para dar enfásis en las discusiones.
* Solo abre un merge request a la vez. No los uses como borrador de articulos.

### Consejos

* Se recomienda usar Visual Code (IDE opensource y modular) con la extensión `markdownlint`
* Puedas usar Atom, vim, o tu favorito, siempre que cumplas el linting.
 
## Publicación

Esta sección es de obligado cumplimento a la hora de colaborar escribiendo articulos con
Tecnócratas Digitales.

### Normas de publicación

* Elección de articulo.
    * Comenta de que va a tratar.
    * Asegurate que el articulo aporta valor.
* Redacción del articulo.
    * Utiliza material propio.
    * Si te basas en datos y articulos, añadelos en la sección de Bibliografia después del articulo.
    * Respeta las normas de linting.

### Guidelines de publicación

* [ ] Sugiere el articulo al resto.
* [ ] Redactalo a tu gusto.
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
    * Comprueba que se cumplen las reglas de linting
* Comprueba que todo sigue funcionando antes de merguear.

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
    * [ ] Comprueba el linting y los tests-
    * [ ] Cuando el cambio sea aprobado, pulsa en Merge Pull Request.
