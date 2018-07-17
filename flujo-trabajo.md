# Flujo de trabajo para la traducción y revisión de capítulos

* La persona responsable de la traducción debe trabajar sobre el archivo .Rmd del capítulo correspondiente, disponible en el repositorio [r4ds](https://github.com/cienciadedatos/r4ds). En el archivo [README](https://github.com/cienciadedatos/r4ds/blob/traduccion/README.md) de ese repositorio encontrará las indicaciones sobre cómo trabajar con git. 
* Una vez terminada la propuesta de traducción, se hace un _pull request_.  En caso de que la persona que traduce no sepa utilizar git, puede enviar el archivo a Pacha a través del Slack del proyecto. 
* [@pachamaltese](https://github.com/pachamaltese) hace el merge.
* [@rivaquiroga](https://github.com/rivaquiroga) crea un _issue_ para iniciar el proceso de revisión. El mensaje de inicio contendrá los siguientes elementos:
  - aviso de que se abre el proceso de revisión del capítulo xxxxxx.
  - url directa al archivo .Rmd.
  - explicitación del código de conducta del proyecto
  - nombre de usuario de Github de las personas responsables de la revisión
* Las personas a cargo de la revisión responden el mensaje de inicio comprometiendo una fecha para tener sus comentarios. 
* Cuando han terminado la revisión del capítulo, publican los comentarios como respuesta al issue abierto. 
* Una vez publicadas las revisiones, la persona a cargo de la traducción incorpora los comentarios que le parecen pertinentes y, en caso de que haya alguno sobre el que tenga dudas o que considere que necesita mayor explicación por parte de quien revisó, lo indica como respuesta al issue abierto. 
* Cuando las modificaciones ya están incorporadas, se hace un nuevo _pull request_ con la versión final del capítulo.
* [@pachamaltese](https://github.com/pachamaltese) hace el _merge_.
* [@rivaquiroga](https://github.com/rivaquiroga) cierra el _issue_.
