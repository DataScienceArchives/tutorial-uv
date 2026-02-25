# tutorial-uv

**URL**: <https://datasciencearchives.github.io/tutorial-uv/>.

Este es un tutorial práctico y a nivel introductorio sobre [Astral uv](https://github.com/astral-sh/uv),
una herramienta de gestión de proyectos de programación en Python. El tutorial se ha creado con
[Quarto](https://quarto.org/) un sistema de publicación científica y técnica.

Astral uv está escrita en [Rust](https://rust-lang.org/), lo que le otorga una gran rapidez. Además, aprovecha las mejoras
que se introdujeron en la gestión de proyectos de Python mediante los documentos 
[PEP 518](https://peps.python.org/pep-0518/) (especificación de las dependencias software para construir
y ejecutar un paquete Python), [PEP 621](https://peps.python.org/pep-0621/) (almacenamiento de metadados
de un proyecto en `pyproject.toml`) y [PEP 658](https://peps.python.org/pep-0658/) (servicio de metadatos acerca de la distribución de un
paquete). Como resultado, sus principales características son:

- &#9889; Ejecución entre 10-100 veces más rápida que `pip` u otros gestores similares de paquetes Python.
- 🗂️ Gestión integral del proyecto con un archivo *lock* universal
y un archivo `pyproject.toml`, en texto legible, con todos los datos de configuración y
dependencias del proyecto (para ejecución y para desarrollo).
- 💾 Gestión eficiente de espacio en disco, con una caché global
para mantenimiento de dependencias y eliminación de duplicados.
- 🖥️ Soporte multiplataforma (Linux, macOS y Windows).



## Tareas pendientes

- [ ] Agregar ejemplos de dependecias para desarrollo de los proyectos.
- [ ] Comentarios adicionales para el ejemplo paso a paso de uso del entorno virtual integrado en el proyecto.
- [ ] Incluir capturas GIF dinámicas para ilustrar la ejecución de algunos de los comandos.

## Planificación
TBD: Agregar un *roadmap* para mejoras en este tutorial.

## Contribuciones
Se aceptan contribuciones y mejoras vía *pull requests*, así como peticiones de mejora para incluir nuevos
elementos avisar de errores, a través del sistema de seguimiento de notificaciones (*issues*) de este
repositorio.

## Autores y reconocimientos

Autor principal: Felipe Ortega (DSLAB, CETINIA, URJC).

Gran parte de la información incluida en este tutorial proviene de la documentación oficial de Astral uv,
disponible en <https://docs.astral.sh/uv>.


## Licencias
Salvo que se indique expresamente lo contrario en algún pasaje, toda la documentación incluida en este
tutorial se publica bajo una licencia Creative Commons Atribución-Compartir Igual (CC-BY-SA) versión 4.0, disponible en <https://creativecommons.org/licenses/by-sa/4.0/deed.es>.

La herramienta Astral uv está publicada bajo una doble licencia de software libre, por lo que se puede
escoger a conveniencia entre las dos opciones siguientes:

* Apache License, Version 2.0, ([LICENSE-APACHE](https://github.com/astral-sh/uv/blob/main/LICENSE-APACHE) or <https://www.apache.org/licenses/LICENSE-2.0>).
* MIT license ([LICENSE-MIT](https://github.com/astral-sh/uv/blob/main/LICENSE-MIT) or <https://opensource.org/licenses/MIT>).

[Quarto](https://quarto.org/), la herramienta para crear este tutorial, está publicada bajo
[licencia MIT](https://opensource.org/license/mit/) (a partir de su versión 1.4).

## Estado del proyecto

El desarrollo de este tutorial se encuentra **activo** y en proceso de expansión y mejora de sus contenidos.
