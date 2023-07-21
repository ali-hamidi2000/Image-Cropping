# Image Cropping

This is a simple image cropping program written in Python. The program allows the user to crop a rectangular region from an input image and save the cropped image as a new image. The program uses NumPy and Matplotlib libraries for image manipulation and visualization.

## Requirements

To run this program, you will need:
- Python 3.x installed on your machine
- NumPy library for Python
- Matplotlib library for Python

## Installation

1. Install Python 3.x from the official website: [https://www.python.org/downloads/ ↗](https://www.python.org/downloads/)
2. Install NumPy library using pip:
   ```
   pip install numpy
   ```
3. Install Matplotlib library using pip:
   ```
   pip install matplotlib
   ```

## Usage

1. Clone or download the source code from this repository.
2. Open a terminal or command prompt and navigate to the project directory.
3. Place your input image in the project directory.
4. Open the `image_cropping.py` file in a text editor and modify the `input_image_filename` variable to match the filename of your input image.
5. Modify the `x`, `y`, `width`, and `height` variables to define the rectangular region to be cropped.
6. Use the following command to run the program:
   `````
   python fileName.py
   `````
7. The cropped image will be saved in the project directory with the filename `output.jpg`.

## How it Works

The program uses NumPy to load the input image as a 3-dimensional NumPy array with dimensions `(height, width, channels)`. The program then creates a new NumPy array by slicing the original array according to the specified rectangular region. The new array is then saved as a new image using Matplotlib.

The program uses Matplotlib to display the original image and the cropped image side-by-side for visualization. The program also uses Matplotlib to save the cropped image as a new image file.

## Contributing

This is an open-source project and contributions are welcome. To contribute, please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
