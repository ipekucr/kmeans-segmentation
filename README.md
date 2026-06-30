# K-Means Image Segmentation

A small image-processing exercise that segments an image by grouping its pixels into K colour clusters with K-Means. Based on a Towards Data Science tutorial.

## What it does
Each pixel of an image is a point in RGB colour space. K-Means groups these pixels into K clusters and repaints every pixel with its cluster's average colour. The result is a simplified image made of only K colours, which splits the picture into colour regions (segments).

## How it works
1. Load the image and convert it from OpenCV's BGR to RGB.
2. Start with K random cluster centres (colours).
3. Assign every pixel to its nearest centre, then move each centre to the mean colour of the pixels assigned to it.
4. Repeat until the centres stop moving (convergence).
5. Recolour each pixel with its final cluster colour to produce the segmented image.

## Run
```bash
python3 original_code.py
```
Update the image path inside the script to point to your own image. Sample input and output are in the `images/` folder.

## What this is (and isn't)
A learning exercise for an image-processing course. K-Means here performs **unsupervised colour segmentation** (grouping visually similar colours). It is **not** semantic segmentation and does not recognise objects or label regions by meaning.

**Reference:** [Image Segmentation with K-Means Clustering (Towards Data Science)](https://towardsdatascience.com/image-segmentation-with-k-means-clustering-1bc53601f033/)




