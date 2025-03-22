# K-Means Image Segmentation

This repository contains three versions of an image segmentation algorithm using K-Means clustering:

- **original_code.py** → Original code from the reference article.
- **enhanced_with_uint8.py** → Improved version by converting pixel values to `uint8` for better color accuracy.
- **enhanced_with_normalization.py** → Final optimized version using data normalization for vibrant output.

## How to Run
1. To run the original code:

```
python3 original_code.py

```
To run the improved versions:

```
python3 enhanced_with_uint8.py
python3 enhanced_with_normalization.py

```

Sample images

Version	                  Output
Original photo           ``` images/image1.webp ```
Original code            ``` images/original_output.png ```
uint8 	                 ``` images/uint8_output.png ```
Normalized	             ``` images/normalized_output.png ```     


Changes & Fixes
Initial output was dull due to incorrect pixel value handling.
Fixed by converting values to uint8.
Further improvement achieved by normalizing pixel values for vibrant colors.
Reference:  ``` https://towardsdatascience.com/image-segmentation-with-k-means-clustering-1bc53601f033/ ```

