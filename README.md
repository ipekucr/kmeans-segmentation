# K-Means Image Segmentation

This repository contains three versions of an image segmentation algorithm using K-Means clustering:

- **original_code.py** → Original code from the reference article.
- **enhanced_with_uint8.py** → Improved version by converting pixel values to `uint8` for better color accuracy.
- **enhanced_with_normalization.py** → Final optimized version using data normalization for vibrant output.

## How to Run
1. To run the original code:

```bash
python3 original_code.py

```
To run the improved versions:

```bash
python3 enhanced_with_uint8.py
python3 enhanced_with_normalization.py

```

Sample images

Version	                  Output
Original photo           ```bash images/image1.webp ```
Original code            ```bash images/original_output.png ```
uint8 	                 ```bash images/uint8_output.png ```
Normalized	             ```bash images/normalized_output.png ```     


Changes & Fixes
Initial output was dull due to incorrect pixel value handling.
Fixed by converting values to uint8.
Further improvement achieved by normalizing pixel values for vibrant colors.
Reference:  ```bash https://towardsdatascience.com/image-segmentation-with-k-means-clustering-1bc53601f033/ ```

