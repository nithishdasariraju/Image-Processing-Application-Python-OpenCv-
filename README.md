# Python All-in-Focus Imaging
## Introduction
 Image processing Application created by Python (OpenCV Python, NumPy and Tkinter).

## Pipeline
1) Select the directory containing PNG pictures for processing images with All-in-Focus.
2) Load this image and the following image.
3) Verify whether an image is grayscale or RGB.
4) Determine each image's gradient in the x and y directions.
5) Determine the gradient in each pixel of the two photos.
6) Determine how each pixel's gradient differs from the image.
7) Make a 3x3 filter matrix that is all ones.
8) Convolution filter using an array and filter matrix from 6
9) Select the better pixel from each image and save the outcome.

The image in the one that follows will be the result of combining images from the previous one if there are more than two files. Save the final output.png file with the combined photos.  

## Setup
First install the dependencies (required packages) using following command:
```shell
pip3 install -r requirements.txt
```
Then run main .py script using command:
```shell
python all_in_focus.py
```

## Example result
### Input data:
| 1st image | 2nd image | 3rd image | 4th image |
|:---:|:---:|:---:|:---:|
|![1st image](data/grayscale_data/image_1.png)|![2nd image](data/grayscale_data/image_2.png)|![3rd image](data/grayscale_data/image_3.png)|![4th image](data/grayscale_data/image_1.png)|

### Output data:
<p align="center">
  <img src="result/grayscale_result/out_image.png">
</p>

