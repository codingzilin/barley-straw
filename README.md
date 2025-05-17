# barley-straw 🌾

## Project Overview

This project analyzes and visualizes the 3D trajectory and length of barley stalks from image stacks. It uses advanced image processing, contour extraction, and 3D visualization techniques to estimate the physical properties of barley stalks, such as length and spatial distribution.

## Features

- Image enhancement (CLAHE, Gamma correction)
- Binarization and contour extraction
- Area filtering and centroid calculation
- Outlier removal based on area and position
- Trajectory smoothing (Savitzky-Golay filter)
- Conversion from pixel to physical units (mm)
- 3D visualization of the stalk trajectory
- Automatic calculation of stalk length
- Locating specific points along the stalk (e.g., 5cm from the tip)

## Dependencies

- Python 3.x
- numpy
- opencv-python
- matplotlib
- scipy

You can install the required packages with:

```bash
pip install numpy opencv-python matplotlib scipy
```

## Usage

1. Place your image stack (e.g., TIFF format) in the project directory.
2. Open and run the `analyse-straw.ipynb` notebook.
3. Follow the instructions in the notebook to process your data and visualize the results.

## File Structure

- `analyse-straw.ipynb`: Main analysis notebook.
- `README.md`: Project documentation.

## Example Output

- 3D plot of the barley stalk trajectory.
- Estimated total length of the stalk.
- Location of a point 5cm from the tip.

## License

This project is for research and educational purposes.

---
