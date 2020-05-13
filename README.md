# Pynq-math-images

This repository contains a project that creates fractals using the Xilinx Pynq framework.

The following 7 notebooks are in the project:
*	Mandelbrot & Julia sets
*	Sierpinski’s triangle, Sierpinksi’s carpet, right angled triangle example (Software)
*	Sierpinski’s triangle, Sierpinksi’s carpet, right angled triangle example (Hardware)

The Sierpinski fractal software notebooks illustrate how to use libraries within python to create the fractals. The hardware examples make use of code from the “PYNQ-HelloWorld image resizer” example. It illustrates how to resize the images required for the fractal on hardware. 

The Mandelbrot & Julia Sets notebook explain how these sets are generated, an overview of the system architecture of the IP core and a step-by-step process to generate the fractals along with user interactivity to change certain properties of the images. The System Generator file used to create the IP is included to allow you to explore this in more detail

## Installation Guide

To run the notebooks in the project first ensure your PYNQ-Z2 board is connected and running. In the **‘This PC’** tab of your file explorer click the **‘Map Network Drive’** icon at the top. Choose an unused drive and in the folder textbox type **‘\\192.168.2.99\xilinx’**. Click the **‘Finish’** button and a prompt will appear to enter a username and password. Enter **‘xilinx’** for both and click **‘OK’**. You may need to refresh your file explorer for the new network location to appear. Once this appears you are now able to quickly transfer folders to the board. 

To get the notebooks onto Jupyter download and extract the .zip. Copy the **‘Mandelbrot_and_Julia_Notebook'** folder contained in the **‘Mandelbrot_and_Julia_Sets’** into the **‘jupyter_notebooks’** folder located inside of the new network drive created. Similarly copy the **‘Sierpinski_fractals’** folder into the **‘jupyter_notebooks’** folder. Enter **‘192.168.2.99’** into your internet browser address bar and enter **‘xilinx’** as the password. You should now be able to access the notebooks by heading to the two folders previously mentioned. 

## Supported Boards

The PYNQ-Z2 board was used while creating this project. Similar boards may also work but have not been tested and could give unexpected results.

## Authors

* David Sutherland
* Christian Anderson
* Michael McDonald

## GitHub Link

https://github.com/Christian376/Pynq-math-images/tree/master
