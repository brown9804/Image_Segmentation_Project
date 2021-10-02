# Image Segmentation Project

----------

Universidad de Costa Rica

Belinda Brown, belindabrownr04@gmail.com

Junio, 2019

----------

## Problem statement 

Design, programming in the C programming language and testing a project in “CodeBlocks” called “image_segmentation_project” that performs:

1.1.Read a color image in “.bmp” format from the hard disk.

1.2.Calculate the intensity image of the color image obtained in point a) and store the resulting intensity image on the hard disk under the name "IntensityImage.bmp", in ".bmp" format.

1.3. Threshold the intensity image obtained in point b) and store the resulting segmented image on the hard disk under the name “segmented image.bmp”, in “.bmp” format. The threshold should be calculated automatically by applying the Kittler algorithm to the intensity image. The optimal threshold, weights, means, and variances should be displayed on the terminal and saved in a text file called “optimalResultsSegunKittler.txt”. For the tests use the image "table1_00.bmp", which can be downloaded from Virtual Mediation, for which the Kittler algorithm gives the following optimal values:

```
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
```

The directory and name of the input color image and its dimensions (width and height) must be read from a control parameter file called “current_control_parameters.txt”. Likewise, in said file the output directory must be indicated, where the images "imagenDeIntensida.bmp" and "imagenSegmentada.bmp", and the text file "ResultsOptimosSegunKittler.txt", must be stored. An example of a control parameter file is as follows:


```
Entrada: input/cuadro1_00.bmp 

ancho: 756

alto: 455

Salida: output/
```

![](https://github.com/brown9804/Image_Segmentation_Project/blob/master/docs/img/output_img_seg_project_def.png)

## How to run

Para ejecutar el programa es ir a la carpeta mediante su consola o terminal al folder
en el que se encuentra el programa.

Debe ingresar y digitar en la consola o terminal:

```
$ make
```






