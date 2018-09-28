# Flujo de trabajo para la traducción y revisión de capítulos

* La persona responsable de la traducción debe trabajar sobre el archivo .Rmd del capítulo correspondiente, disponible en el repositorio [r4ds](https://github.com/cienciadedatos/r4ds). En el archivo [README](https://github.com/cienciadedatos/r4ds/blob/traduccion/README.md) de ese repositorio encontrará las indicaciones sobre cómo trabajar con git. 
* Una vez terminada la propuesta de traducción, se debe verificar que es posible generar el libro en html localmente. Una vez comprobado eso, se hace el _pull request_. 
* [@rivaquiroga](https://github.com/rivaquiroga) deja un mensaje en el _pull request_ en el que se incluye el enlace a las orientaciones sobre esta parte del proceso y los nombres de las personas encargadas de la revisión. 
* [@pachamaltese](https://github.com/pachamaltese) asigna el _pull request_ a quienes se encargarán de hacer la revisión. 
* Los comentarios sobre la traducción se deben ir haciendo en el mismo _pull request_. En el documento [orientaciones-revision](https://github.com/cienciadedatos/descripcion-y-orientaciones/blob/master/orientaciones-revision.md) se describe cómo funciona esa parte del proceso.
* A medida que vayan terminando de hacer sus comentarios, las personas encargadas avisan por el Slack que su revisión está lista.
* Una vez revisado el archivo, la persona a cargo de la traducción hace _commit_ a los cambios que considere pertinentes para que se actualize el _pull request_ y avisa por el Slack que ya está lista la última versión.
* [@pachamaltese](https://github.com/pachamaltese) hace el _merge_.
* [@rivaquiroga](https://github.com/rivaquiroga) actualiza el documento con el seguimiento. 
