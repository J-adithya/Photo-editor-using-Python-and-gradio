# Photo-editor-using-Python-and-gradio
This project was done to showcase my work done during my internship at Muonium.ai. 

This Image Editor is a Python-based web application built with Gradio that allows users to apply various image processing operations, including flipping, rotating, resizing, adjusting brightness and contrast, converting to black and white, removing the background, and more.

![Screenshot 2024-08-21 183655](https://github.com/user-attachments/assets/1fa3d36c-0539-4271-8f7f-1706f1984204)

# Features
- Flip Image: Flip the image horizontally.
- Rotate Image: Rotate the image by a specified degree.
- Convert to Black and White: Convert the image to grayscale.
- Resize Image: Resize the image by a specified percentage.
- Adjust Brightness: Modify the brightness of the image.
- Adjust Contrast: Adjust the contrast level of the image.
- Adjust Hue: Change the hue of the image.
- Adjust Saturation: Modify the saturation of the image.
- Remove Background: Automatically remove the background from the image using the rembg library.
- Image Format Conversion: Save the processed image in either PNG or JPEG format.
- Download Processed Image: Download the processed image directly from the interface.

# Installation
**Prerequisites**
Ensure you have Python 3.6 or later installed on your system.

**Install Required Libraries**
Create a virtual environment (optional but recommended):
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
Install the required Python libraries:
```
pip install -r requirements.txt
```
**Run the Application**
To run the Image Editor application, use the following command:
```
python photo_editor.py

```
The Gradio interface will launch, and you can access the editor in your web browser.

# Usage
- Upload an image using the provided file upload option.
- Select the desired processing options:
- Flip, Rotate, Black and White, Resize, etc.
- Adjust the sliders for Brightness, Contrast, Hue, and Saturation as needed.
- Click Submit to apply the changes.
- Download the processed image using the download button.

# Requirements
Below is a sample requirements.txt file:
```
gradio==3.x.x
Pillow==9.x.x
rembg==2.x.x
numpy==1.x.x
```
Replace the x.x.x with the actual version numbers installed in your environment. 

# License
This project is licensed under the MIT License - see the LICENSE file for more details.
