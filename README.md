# Measure Object Size
 A Python script that allows you to measure the size of objects in an image or video.

## Requirements

- Python 3.x
- OpenCV Python (cv2) library

## Installation
To use Measure Object Size, you first need to install the OpenCV Python library. You can install it using pip by running the following command:
```sh
pip install opencv-python
```
Alternatively, you can install it via conda using the following command:
```sh
conda install opencv
```
After installing the OpenCV library, you can download or clone the Measure Object Size script from this GitHub repository.

## Usage

To use Measure Object Size, simply run the following command in your terminal or command prompt:
```sh
python measure_object_size.py --image path/to/image.jpg --width 0.6
```
Replace path/to/image.jpg with the path to your image, and 0.6 with the width of the known object in your image (in this example, the width of the object is 0.6 meters). You can also use the --video option to measure objects in a video instead of an image.

## Output
Measure Object Size will display the original image with the measured objects outlined in green. The script will also print the size of each object in the console.
![do-real-time-object-measurement-project](https://user-images.githubusercontent.com/81076373/220655303-29ef8653-bc1c-483b-9c98-53097c1695e3.jpg)

## Contributing
If you find any issues with Measure Object Size or have suggestions for improvements, please feel free to submit a pull request or open an issue on this GitHub repository.

