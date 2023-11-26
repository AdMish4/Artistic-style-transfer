# Artistic-style-transfer

## Project Overview
This project implements Neural Style Transfer using TensorFlow and Keras, leveraging the VGG19 model pre-trained on ImageNet. Neural Style Transfer is a technique that combines the content of one image with the style of another image to create visually appealing artworks.

## Project Structure
neural_style_transfer.py: The main script containing the implementation of Neural Style Transfer.
/kaggle/input/neural-style-transfer/:
base_image.jpg: The base image to which the style will be applied.
style_image.jpg: The style reference image that defines the artistic style.
/generated/: The folder where the generated images will be saved during the optimization loop.
## Dependencies
Make sure to install the following dependencies:

bash
Copy code
pip install numpy tensorflow ipython pillow

## How to Run
Set the directory path for style transfer images in the directory variable.
Ensure the base image (base_image.jpg) and style reference image (style_image.jpg) are in the specified directory.
Adjust parameters such as image dimensions, optimization settings, and file naming as needed.
Run the script (neural_style_transfer.py).
The generated images will be saved in the /generated/ folder.

## Customization
Style Layers: Style transfer is influenced by layers specified in style_layer_names.
Loss Weights: Adjust total_variation_weight, style_weight, and content_weight to control the balance between total variation, style, and content.
Optimization: Fine-tune the optimization settings such as learning rate, decay steps, and decay rate.

## Results
The generated images will be saved in the /generated/ folder with filenames indicating the iteration number.
