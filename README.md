
# Automatic Number Plate Recognition (ANPR) Project

This project implements an Automatic Number Plate Recognition (ANPR) system using Python, OpenCV, EasyOCR, and Imutils. The system can detect and recognize number plates from vehicle images.





## Features

1. **Image Preprocessing**
- Convert the image to grayscale.
- Apply a bilateral filter to reduce noise.
- Use Canny Edge Detection to highlight the edges.

2. **Contour Detection**
- Find contours in the image.
- Sort contours by area and keep the largest ones.
- Approximate the contour to a polygon and check for a quadrilateral (which indicates a license plate).

3. **OCR with EasyOCR**
- Mask the area of the license plate.
- Crop the license plate area.
- Use EasyOCR to extract text from the cropped image.

4. **Visualization**
- Draw the detected number plate region and overlay the recognized text.
## Prerequisites
- Python 3.9.0 or higher 
- OpenCV
- Mediapipe

## Installation

1. Clone the repository:

```bash
  git clone https://github.com/M-ED/Automatic_Number_Plate_Recognition_Python.git
  cd anpr-project
```

2. Install the necessary libraries in requirements file
```bash
   pip install -r requirements.txt
```

3. Run the file using command
```bash
   python anpr.py
```
## Acknowledgements

- OpenCV: [https://opencv.org/](https://opencv.org/)




## License

[MIT](https://choosealicense.com/licenses/mit/)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Author

- [@mohtadia_naqvi](https://github.com/M-ED)

