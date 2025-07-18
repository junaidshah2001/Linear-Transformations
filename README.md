# Linear-Transformations
Linear Transformations Lab
This repository contains a Jupyter Notebook (C1W3_UGL_3_linear_transformations.ipynb) that explores linear transformations, visualizes their results, and demonstrates how matrix multiplication can be used to apply various linear transformations.

Table of Contents
1 - Transformations

2 - Linear Transformations

3 - Transformations Defined as a Matrix Multiplication

4 - Standard Transformations in a Plane

4.1 - Example 1: Horizontal Scaling (Dilation)

4.2 - Example 2: Reflection about y-axis (the vertical axis)

5 - Application of Linear Transformations: Computer Graphics

Overview
In this lab, you will gain a deeper understanding of linear transformations, which are fundamental concepts in linear algebra with wide applications in computer graphics, data science, and many other fields. You will learn:

What a transformation is and how to represent it mathematically.

The properties that define a linear transformation.

How linear transformations can be expressed as matrix multiplications.

Common standard transformations in a 2D plane, such as scaling and reflections.

The practical application of linear transformations in computer graphics for manipulating shapes and images efficiently.

Packages
The following Python packages are required to run the notebook:

numpy: For numerical operations, especially matrix manipulations.

opencv-python (cv2): For image transformations.

matplotlib: For plotting and visualizing transformations.

You can install these packages using pip:

pip install numpy opencv-python matplotlib

How to Run
Clone the repository:

git clone https://github.com/junaidshah2001/Linear-Transformations-Lab.git
cd Linear-Transformations-Lab

Install the required packages (if you haven't already):

pip install -r requirements.txt

(Note: A requirements.txt file is not provided in the original content, but it's good practice to create one with numpy, opencv-python, and matplotlib listed.)

Open the Jupyter Notebook:

jupyter notebook C1W3_UGL_3_linear_transformations.ipynb

This will open the notebook in your web browser, where you can execute the cells and explore the concepts.

Examples Covered
The notebook includes practical examples and visualizations for:

Defining transformations: Understanding the function T(v)=w.

Verifying linearity: Checking the properties T(kv)=kT(v) and T(u+v)=T(u)+T(v).

Matrix representation: Deriving the transformation matrix A such that T(v)=Av.

Horizontal Scaling (Dilation): Visualizing how a polygon stretches horizontally.

Reflection about y-axis: Demonstrating how a polygon reflects across the vertical axis.

Image transformations: A simple example using OpenCV to rotate and shear a leaf image, illustrating the power of linear transformations in graphics.

Contributing
Feel free to fork this repository, experiment with different transformations, and contribute your own examples! You can find the repository at https://github.com/junaidshah2001/Linear-Transformations.

Contact
For any questions or suggestions, please open an issue on the GitHub repository or reach out to www.linkedin.com/in/junaidshah2001.
