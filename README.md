# NEURAL-STYLE-TRANSFER
**Company**: CODTECH IT SOLUTIONS PVT.LTD

**Name**: Ankur Datta

**Intern ID**: CT08JSJ

**Domain**: Artificial Intelligence

**Batch Duration**: January 5th, 2025 to February 5th, 2025

**Mentor Name**: Neela Santhosh 

# Description
This project implements a Neural Style Transfer model using TensorFlow and Keras. The model applies artistic styles from one image (style image) to another (content image) to generate a new image that blends the content and style. It leverages the pre-trained VGG19 model for feature extraction and computes the content and style losses to iteratively optimize the generated image.

# Features
* Pre-trained VGG19 Model: Utilizes VGG19 for extracting high-level content and style features.
* Customizable Weights: Allows users to balance content and style by adjusting the weights.
* Gram Matrix Calculation: Captures style information effectively by comparing the Gram matrices of feature maps.
* Configurable Parameters: Supports adjustments to image size, learning rate, and iteration count for fine-tuning results.
* Image Preprocessing and Reprocessing: Handles input preprocessing and final output reconstruction to ensure compatibility and visual quality.

# Installation
1. Clone the repository:
   git clone https://github.com/your-username/neural-style-transfer.git
   cd neural-style-transfer
2. Install required dependencies: Ensure you have Python 3.7+ and TensorFlow installed.
   pip install tensorflow numpy matplotlib
3. Place the content and style images: Add your images to the project directory and update the paths in the script:
     content_image_path: Path to the content image.
     style_image_path: Path to the style image.

# Usage
1. Run the script:
   python neural_style_transfer.py
2. Parameters:
     iterations: Number of optimization steps (default: 50).
     content_weight: Weight for content loss (default: 1e3).
     style_weight: Weight for style loss (default: 1e-2).
3. Output: The generated stylized image will be displayed and saved to the specified location.

# Example

# Input Images:
Content Image: A photograph or image with desired content.
Style Image: An artistic image whose style you want to apply.

# Output:
The generated image preserves the structure of the content image while applying the artistic style.

# Results
The project successfully produces visually appealing stylized images. Here's an example:

Content Image: 
![content](https://github.com/user-attachments/assets/25577c5d-c0c2-4219-8d2f-c50d7e2a635c)

Style Image: 
![style](https://github.com/user-attachments/assets/c1cc065e-f7e0-4c54-8303-aff6a9784f08)

Output Image: 
![image](https://github.com/user-attachments/assets/7e65687e-7521-4294-b7a4-d67596c5f81f)


# Future Improvements
Support for higher-resolution images.
Integration of additional loss functions for improved stylization quality.
GUI for easier interaction and visualization.
