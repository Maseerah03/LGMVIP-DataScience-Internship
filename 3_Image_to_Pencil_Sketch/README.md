# Image to Pencil Sketch with Python

This project was completed as part of my Data Science Internship at LetsGrowMore (October 2023 batch). The objective was to create a pencil sketch effect from a real image using basic image processing techniques in Python with OpenCV.

## Objective

To apply a sequence of image processing transformations to convert a color image into a pencil sketch. This project demonstrates the use of grayscale conversion, inversion, Gaussian blur, and blending to achieve the sketch effect.

## Tools and Libraries Used

- Python  
- OpenCV (cv2)

## Summary of Work

- Imported a sample image (`lenna.png`) using OpenCV.
- Converted the original image to grayscale.
- Applied bitwise inversion to create a negative.
- Used Gaussian Blur to soften the inverted image.
- Inverted the blurred image again to prepare for blending.
- Divided the grayscale image by the double-inverted blurred image using `cv2.divide` to produce the sketch.
- Saved the final output image as `output.png`.

## Key Outcomes

- Successfully implemented an image-to-sketch transformation using OpenCV.
- Learned the sequence and logic of basic image processing filters.
- Gained practical experience with image manipulation using Python.

## Files Included

- `Image_to_Pencil_Sketch_with_Python.ipynb` – Google Colab notebook with full code.
- `lenna.png` – Input sample image used for transformation.
- `output.png` – Output image after applying the sketch filter.
- `README.md` – Project description and summary.

## Acknowledgement

This project was developed during my internship at LetsGrowMore under the guidance of Mr. Aman Kesarwani.
