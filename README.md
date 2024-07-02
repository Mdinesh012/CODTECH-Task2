Name : Dineshkumar
Company : Codtech IT Solutions 
Id : CT08DS2437 
Domain : Android development
Duration : June 15 to July 15 of 2024
Mentor : Santhosh kumar

Introduction:
In this project, we will build up an Advanced BMI Calculator by the tkinter library of Python. It is the standard GUI library of Python. With the help of sliders, the user can mention their height and weight, by clicking the report button they can see their calculated BMI and get the message about their health condition. The image inserted will get resized according to the movement of the slider, which is possible by the “Image” & “ImageTk” libraries under the  PIL module of Python. Let’s dig deep into the steps to build this project!

Explanation:
The first step is importing all the necessary libraries using the “import” keyword. For the latest version, the tkinter module comes under the future module. So first, we have to install the future module with the help of the command “pip install <module-name>”. The future module is a built-in module in Python that inherits new features which are available in the latest Python versions. With “future. moves” we will import the tkinter module.

For creating the GUI we will import the tkinter module, to style the tkinter widgets we will import the ttk module, and finally, to add image processing capabilities we will import the PIL module.

In the next step, to create an object of the tkinter frame will use “.Tk()”.With this, we will also set the title and geometry of our tkinter application. To set the background color for the project we will use “.config(bg=<color name>)”. And so, with that, we have set “grey” as the background color for this project.

We will create a Label widget for the heading stating “BMI CALCULATOR” by using the “.Label()” and with the help of “.place()” we will set the position for the label accordingly. With this, one more label will be created of the color “light cyan” for packing the parent widget from the bottom side by using the “.pack(side=” bottom”)”. After making these two labels you will be able to see that our GUI got divided into two areas i.e. one with grey and the other with light cyan.

The next step is to place the images of the two boxes containing the height and weight parameters and a scale image. For this process, first, we will get the image to our application by “.PhotoImage(file=<filename>)”, in addition to this we will also create the label for this image and then with the help of “.place()”  we will set the positions of the two boxes.

The same procedure will get followed for the scale image to appear on our tkinter application.
