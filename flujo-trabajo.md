# Flujo de trabajo para la traducción y revisión de capítulos

* La persona responsable de la traducción debe trabajar sobre el archivo .Rmd del capítulo correspondiente, disponible en el repositorio [r4ds](https://github.com/cienciadedatos/r4ds). En el archivo [README](https://github.com/cienciadedatos/r4ds/blob/traduccion/README.md) de ese repositorio encontrará las indicaciones sobre cómo trabajar con git. 
* Una vez terminada la propuesta de traducción, se hace un _pull request_.  En caso de que la persona que traduce no sepa utilizar git, puede enviar el archivo a Pacha a través del Slack del proyecto. 
* [@rivaquiroga](https://github.com/rivaquiroga) crea un _issue_ para iniciar el proceso de revisión. El mensaje de inicio contendrá los siguientes elementos:
  - aviso de que se abre el proceso de revisión del capítulo xxxxxx.
  - indicación del _pull request_ asociado
  - explicitación del código de conducta del proyecto
  - nombre de usuario de Github de las personas responsables de la revisión (si es que ya están definidas)
  - período de tiempo en que estará abierto el proceso de revisión
* Los comentarios sobre la traducción se deben ir haciendo en el mismo _pull request_ (hacer clic sobre `+` en la línea del código que se quiere comentar). 
* Una vez revisado el archivo, la persona a cargo de la traducción hace _commit_ a los cambios que considere pertinentes para que se actualize el _pull request_.
* [@pachamaltese](https://github.com/pachamaltese) hace el _merge_.
* [@rivaquiroga](https://github.com/rivaquiroga) cierra el _issue_.
