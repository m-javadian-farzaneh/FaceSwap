# Face Swap

#### Input Images:
<img src="jj.jpg"
     style="width:250px;height:250px;" />

<img src="w.jpg"
     style="width:250px;height:250px;" />
#### Output Image

<img src="facewap.jpg" style="width:250px;height:250px;" />
## Project Description

The Face Swap project allows users to seamlessly switch the faces of two individuals in provided images. The process involves detecting faces using the Dlib library, followed by extracting facial landmarks using a 68-point model. By using these landmarks, the boundary of the faces is determined, and a convex hull is created. This hull aids in extracting the faces from the images. Triangulation of the facial landmarks further enables the calculation of an affine transformation matrix. This matrix is used to apply the style of one face onto another, resulting in a natural-looking swap. Unlike a simple hull switch, the applied geometry transformation ensures a more fitting and realistic result. Finally, seamless cloning and median noise removal are applied to enhance the color and quality of the new image.

## Installation Instructions

To use this code, follow these steps:

1. Install Python on your system.
2. Install Jupyter Notebook.
3. Install the Dlib library and other required Python libraries.
4. Clone this repository to your local machine.

## Usage Guide

1. Navigate to the project directory.
2. Open the Jupyter Notebook file.
3. Follow the instructions within the notebook to load your images and perform the face swap.

## Features

* Face detection using Dlib library.
* Facial landmarks extraction using a 68-point model.
* Convex hull creation for precise face extraction.
* Triangulation for calculating affine transformation matrix.
* Seamless cloning and median noise removal for image enhancement.

## Technologies Used

   * Python
   * Jupyter Notebook
   * Dlib library

## Contact Information

For any inquiries or questions, feel free to reach out to the project owner at m.javadian213@gmail.com.
