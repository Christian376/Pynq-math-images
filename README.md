# Pynq-math-images

This repository contains a project that creates fractals using the Xilinx Pynq framework.

The following 8 notebooks are in the project:
*	Mandelbrot & Julia sets
*	Sierpinski’s triangle, Sierpinksi’s carpet, right angled triangle example (Software)
*	Sierpinski’s triangle, Sierpinksi’s carpet, right angled triangle example (Hardware)
* Koch Snowflake

The Sierpinski fractal software notebooks illustrate how to use libraries within python to create the fractals. The hardware examples make use of code from the “PYNQ-HelloWorld image resizer” example. It illustrates how to resize the images required for the fractal on hardware. 

The Mandelbrot & Julia Sets notebook explain how these sets are generated, gives an overview of the system architecture of the IP core and a step-by-step process to generate the fractals along with user interactivity to change certain properties of the images. The System Generator file used to create the IP is included to allow you to explore this in more detail

## Installation Guide

To run the notebooks in the project first ensure your PYNQ-Z2 board is connected and running. In the **‘This PC’** tab of your file explorer click the **‘Map Network Drive’** icon at the top. Enter the IP address for your PYNQ-Z2 board to create a network drive for it. You may need to refresh your file explorer for the new network location to appear. Once this appears you are now able to quickly transfer folders to the board. 

To get the notebooks onto Jupyter, download and extract the .zip. Copy the **‘Mandelbrot_and_Julia_Notebook'** folder contained in the **‘Mandelbrot_and_Julia_Sets’** into the folder used to look at your Jupyter notebooks. Similarly copy the **‘Sierpinski_fractals’** and **'kochcurve'** folders into the same folder as before. You should now be able to access the notebooks by heading to where you usually open your notebooks.

## Supported Boards

The PYNQ-Z2 board was used while creating this project. Similar boards may also work but have not been tested and could give unexpected results.

## Authors

* David Sutherland
* Christian Anderson
* Michael McDonald

## GitHub Link

https://github.com/Christian376/Pynq-math-images
