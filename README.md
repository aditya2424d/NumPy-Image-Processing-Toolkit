# NumPy Image Processing Toolkit

A beginner-friendly image processing project built with Python and NumPy. The notebook treats an image as a multidimensional array and demonstrates common transformations without relying on pixel-by-pixel loops for the main operations.

## Features

- Load a built-in sample image
- Convert RGB image to grayscale using vectorized NumPy operations
- Flip an image with array slicing
- Rotate an image using transpose and slicing
- Split red, green, and blue channels
- Build a 2x2 image collage with `np.hstack()` and `np.vstack()`
- Compare vectorized NumPy grayscale conversion with a Python pixel loop using `%timeit`

## Technologies

- Python
- NumPy
- Matplotlib
- scikit-image
- Google Colab / Jupyter Notebook

## Concepts Practiced

- Multidimensional arrays
- Array slicing
- Broadcasting and vectorization
- Transpose
- Stacking arrays
- Performance comparison

## Run the Project

1. Open `numpy_image_processing.ipynb` in Google Colab or Jupyter Notebook.
2. Install dependencies if required: `pip install -r requirements.txt`.
3. Run the notebook cells from top to bottom.

## Resume Line

Implemented an image-processing toolkit using NumPy array operations for grayscale conversion, rotation, channel splitting and collage creation, applying slicing, stacking, transpose and vectorization instead of pixel-level loops.
