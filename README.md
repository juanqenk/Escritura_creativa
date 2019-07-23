# Escritura Creativa

_Una colección de plantillas para ayudarte a planificar tu libro._

Visita la [web del proyecto](https://github.com/juanqenk/Escritura_creativa)


### Requerimientos para descargar las plantillas:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0

``` bash
$ pip install cookiecutter
```

o bien,

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### Empezando un nuevo libro:
------------

    cookiecutter https://github.com/juanqenk/Escritura_creativa

or 

     cookiecutter gh:juanqenk/Escritura_creativa


### Estructura
------------

Al lanzar el comando anterior se crea la siguiente estructura de carpetas y archivos: 

```
├── LICENSE
├── {tu_titulo}.md          <-  Plantilla resumen
├── AUTORES.md 
├── personajes
│     ├── biografia.md
│     ├── lista_personajes.md
│     ├── perfil.md
├── lugares
│     ├── lista_lugares.md
│     ├── mundo.md
├── estructura
│     ├── capitulos.mg
│     ├── hilos_narrativos.md
├── capitulos
│     ├──capitulo1
│     ├── ...
├── herramientas 
├── autopublicacion
     ├── autopublicacion.md
```


## Autor

* **Juan Cuenca**  - [web personal](https://juanqenk.github.io/juan/)


## Licencia


El contenido de este proyecto esta sujeto a una licencia del tipo [Creative Commons Attribution 3.0 Unported license](https://creativecommons.org/licenses/by/3.0/), y el código incluido en el proyecto se somete a una licencia   [MIT license](LICENSE.md).


