# Image Segmentation Project

Junio 2019

Para ejecutar el programa es ir a la carpeta mediante su consola o terminal al folder
en el que se encuentra el programa.

Debe ingresar y digitar en la consola o terminal:

$ make



Diseño, programación en el lenguaje de programación C y pruebe un proyecto en “CodeBlocks” denominado “image_segmentation_project” que realice:

1.1.Lea una imagen de color en formato “.bmp” del disco duro.

1.2.Calcule la imagen de intensidad de la imagen de color obtenida en el punto a) y almacene la imagen de intensidad resultante en el disco duro bajo el nombre “imagenDeIntensidad.bmp”, en formato “.bmp”.

1.3.Umbralice la imagen de intensidad obtenida en el punto b) y almacene la imagen segmentada resultante en el disco duro bajo el nombre “imagenSegmentada.bmp”, en formato “.bmp”. El umbral deberá calcularse en forma automática mediante la aplicación del algoritmo de Kittler a la imagen de intensidad. El umbral, los pesos, las medias y las varianzas óptimas deberán visualizarse en el terminal y salvarse en un archivo de texto denominado “resultadosOptimosSegunKittler.txt”. Para las pruebas utilice la imagen “cuadro1_00.bmp”, que podrá bajarse de Mediación Virtual, para la cual el algoritmo de Kittler da como resultado los siguientes valores óptimos:

Ubuntu 32 bit:

th=165

mean1=148.451151

var1=15.428531

mean2=218.506530

var2=10.100316


Ubuntu 64 bit:

th=166

mean1=149.287913 

var1=15.381974 

mean2=219.336596 

var2=9.867214

El directorio y nombre de la imagen de color de entrada y sus dimensiones (ancho y alto), deberán leerse de un archivo de parámetros de control denominado “current_control_parameters.txt”. Asimismo, en dicho archivo deberá indicarse el directorio de salida, donde las imágenes “imagenDeIntensida.bmp” e “imagenSegmentada.bmp”, y el archivo de texto “resultadosOptimosSegunKittler.txt”, deberán almacenarse. Un ejemplo de archivo de parámetros de control es el siguiente:


Entrada: input/cuadro1_00.bmp 

ancho: 756

alto: 455

Salida: output/
