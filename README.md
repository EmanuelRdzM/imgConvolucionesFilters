# imgConvolucionesFilters

Este repositorio contiene una aplicación de filtros de imágenes implementada en JavaScript utilizando la matriz de convoluciones. 
La matriz de convoluciones es una técnica poderosa en procesamiento de imágenes que permite realizar operaciones como desenfoque, nitidez, realce de bordes y más.

El concepto de convolución, es una operación matemática que combina dos conjuntos de datos para producir un tercer conjunto. En el contexto del procesamiento de imágenes, 
esta operación se aplica mediante una ventana de convolución (también conocida como kernel) que se desplaza sobre la imagen para realizar diversas transformaciones.

Algunos recursos útiles para entender la matriz de convoluciones son:

[Documentación de GIMP sobre la matriz de convoluciones](https://docs.gimp.org/2.8/en/plug-in-convmatrix.html)

[Wikipedia: Kernel (procesamiento de imágenes)](https://en.wikipedia.org/wiki/Kernel_(image_processing))

## Inicio rápido

Para ejecutar la aplicación y experimentar con los filtros de convolución, puedes utilizar un servidor web local. Aquí hay algunas opciones:

1. Clona este repositorio en tu maquina local:

        git clone https://github.com/EmanuelRdzM/imgConvolucionesFilters.git

2. Inicia un servidor web. Si estás en un entorno Linux o macOS, puedes usar Python 3:

        $ sudo python3 -m http.server [puerto]
    con windows

       python -m SimpleHTTPServer [puerto]
   
   ```
   py -m http.server [puerto]
   ```

3. Sube tus imagenes favoritas para realizar filtros en ellas, dentro de la carpeta del proyecto
4. Abre tu navegador web y accede a http://localhost:[puerto] para ver la aplicación en acción.





