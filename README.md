Image Transformation Web App
*Overview
This repository hosts a Streamlit web application for image transformations. Users can upload images and apply various transformations such as translation, rotation, scaling, and shearing. The transformations are interactive, allowing users to adjust parameters dynamically and visualize the effects on the uploaded images.

Features
File Uploader: Supports jpg, png, and jpeg formats for image uploads.
Interactive Transformations: Sliders for rotation angle, scale (X and Y), and shear (X and Y) enable dynamic adjustments.
Apply Transformations: Click the "Apply Transformations" button to see the transformed images alongside the original, with applied transformation captions.
Usage
Install dependencies: pip install streamlit opencv-python numpy
Run the Streamlit app: streamlit run image_transformation.py
Open the provided URL in your web browser.
Upload an image using the file uploader.
Adjust transformation parameters using the sliders.
Click the "Apply Transformations" button to view the results.
File Structure
image_transformation.py: Main Streamlit application code.
requirements.txt: List of required Python packages.
Customization
To customize the web app, edit the image_transformation.py file. Extend functionality or integrate additional features based on specific requirements.

Dependencies
Streamlit
OpenCV
NumPy
Feel free to explore and enhance the capabilities of the image transformation web app! If you encounter any issues or have suggestions, please submit them through the GitHub issues tab. Contributions are welcome!





