# Image Quantization and Analysis

## Overview
This project focuses on analyzing and quantizing grayscale images by adjusting their bit-depth and evaluating their quality using Mean Squared Error (MSE) and Peak Signal-to-Noise Ratio (PSNR). It also provides visualizations to compare different quantization levels.

## Features
- **Upload Images**: Supports manual image uploads in Google Colab.
- **Image Validation**: Checks if images meet the 8-bit grayscale requirement.
- **Quantization**: Converts images to lower bit depths while maintaining visual quality.
- **MSE & PSNR Calculation**: Measures quality degradation caused by quantization.
- **Visualization**: Displays original and quantized images along with performance metrics.

## Installation
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Install required dependencies:
   ```bash
   pip install numpy opencv-python pandas matplotlib
   ```

## Usage
### Running in Google Colab (.ipynb)
1. Open the Jupyter Notebook file (`Untitled24.ipynb`) in **Google Colab**.
2. Upload required images manually using the file upload feature.
3. Run the cells sequentially to:
   - Validate grayscale image properties.
   - Perform quantization for specified bit depths.
   - Generate and save processed images along with evaluation metrics.

### Running as a Python Script
1. Run the script:
   ```bash
   python image_quantization.py
   ```
2. Provide inputs when prompted:
   - Image filenames (comma-separated with extensions).
   - Bit depths (comma-separated, between 1-8).
3. The script processes the images, saves quantized versions, and displays evaluation metrics.

## Example Output
- The script prints image validation results.
- Saves quantized images with filenames like `quantized_4bit_image.png`.
- Generates MSE vs. Bit Depth, PSNR vs. Bit Depth, and Execution Time vs. Bit Depth plots.

## Dependencies
- Python 3.x
- NumPy
- OpenCV
- Matplotlib
- Pandas

## Author
Developed for an image processing assignment.

## License
This project is for educational purposes only.
