# Colour_Detection_using_Pandas_and_OpenCV

In this color detection Python project, we are going to build an application through which you can automatically get the name of the color by clicking on them. 
So for this, we will have a data file that contains the color name and its values. Then we will calculate the distance from each color and find the shortest one.

The Dataset:

Colors are made up of 3 primary colors; red, green, and blue. In computers, we define each color value within a range of 0 to 255.
So in how many ways we can define a color? The answer is 256*256*256 = 16,581,375. There are approximately 16.5 million different ways to represent a color. 
In our dataset, we need to map each color’s values with their corresponding names. 
But don’t worry, we don’t need to map all the values. We will be using a dataset that contains RGB values with their corresponding names.

Prerequisites:

Before starting with this Python project with source code, you should be familiar with the computer vision library of Python that is OpenCV and Pandas.
OpenCV, Pandas, and numpy are the Python packages that are necessary for this project in Python. To install them, simply run this pip command in your terminal:
                        pip install opencv-python numpy pandas
                        
Run Python File:

The beginner Python project is now complete, you can run the Python file from the command prompt.
Make sure to give an image path using ‘-i’ argument. If the image is in another directory, then you need to give full path of the image:

python color_detection.py -i <add your image path here>




