**Introduction:
Image manipulation involves a variety of transformations that can bring about changes in an image's position, orientation, size, and shape. These transformations are crucial in computer vision, graphics, and various applications where altering visual data is necessary. In this context, we explore fundamental image transformations such as translation, rotation, scaling, and shearing.

Translation:
Translation shifts an image along both the horizontal (x) and vertical (y) axes. It effectively relocates the entire image, allowing for repositioning. This transformation is defined by specifying the amount of displacement in both the x and y directions.

Rotation:
Rotation entails the turning of an image by a specified angle around a defined point. It serves to change the image's orientation, and rotations can occur clockwise or counterclockwise. Common angles include 90 degrees, though any angle can be chosen.

Scaling:
Scaling involves resizing an image by a factor along both the x and y axes. This can result in either enlargement or reduction of the image. A factor greater than 1 increases the size, while a factor between 0 and 1 decreases it.

Shearing:
Shearing is a transformation that distorts the shape of an image by tilting or slanting it along one or both axes. It's a versatile transformation that can create effects like skewing or stretching.

Web Application Overview:
Our Streamlit web application provides a user-friendly interface for applying these transformations to uploaded images. The application features a file uploader, interactive transformation controls, and the ability to visualize the effects of the transformations in real-time.

Key Features:

File Uploader: Supports image uploads in jpg, png, or jpeg formats.
Interactive Transformations: Utilizes sliders for adjusting rotation angle, scale (X and Y), and shear (X and Y) to provide a dynamic and interactive transformation experience.
Apply Transformations: Users can click the "Apply Transformations" button to instantly view the transformed images alongside the original, complete with captions indicating the applied transformations.
Usage Instructions:

Install the necessary dependencies using pip install streamlit opencv-python numpy.
Run the Streamlit app using streamlit run image_transformation.py.
Open the provided URL in your web browser.
Upload an image through the file uploader.
Adjust transformation parameters using the intuitive sliders.
Observe the results by clicking the "Apply Transformations" button.
File Structure:

image_transformation.py: The main code for the Streamlit application.
requirements.txt: A list of required Python packages.
Customization:
Feel free to customize the appearance and behavior of the web app by editing the image_transformation.py file. You can extend functionality or integrate additional features based on your specific requirements.

Dependencies:

Streamlit
OpenCV
NumPy
