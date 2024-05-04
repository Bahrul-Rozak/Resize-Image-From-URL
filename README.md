# Resize Image from URL

This Python program allows users to resize an image from a URL without distorting its aspect ratio. It uses the PIL (Pillow) library to download and resize the image. Users can specify the URL of the image, as well as the target width and height for the resized image. The program then calculates the scaling factor to maintain the aspect ratio and resizes the image accordingly.

## Features

- Resize images from a URL without distortion.
- User-friendly input prompts for URL, target width, and target height.
- Autogenerated filename for the resized image based on the current time.
- Display the resized image in the output.
- Error handling for cases where the URL is incorrect or the file is not an image.

## Installation

1. Install Python 3 from [python.org](https://www.python.org/downloads/).
2. Install the required libraries using pip:

    ```
    pip install Pillow requests
    ```

## Usage

1. Run the program.
2. Enter the URL of the image you want to resize.
3. Enter the target width and height for the resized image.
4. The program will download and resize the image, then display the resized image.

## Example

```python
python resize_image_from_url.py
```

Make sure the URL is correct and the file is an image file. Some URLs may not be accessible due to restrictions or permissions.
