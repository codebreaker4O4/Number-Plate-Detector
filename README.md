# Number Plate Detection using OpenCV

This project utilizes OpenCV and Haar cascades to detect number plates in a recorded video. It provides a simple yet effective method for automatically identifying and extracting number plates from the given video. The cropped images of the number plates can be saved for future use or further analysis.

## Features

- Number plate detection in recorded videos.
- Utilizes Haar cascades for object detection.
- Extracts and saves cropped images of the detected number plates.
- Supports various video formats.
- Provides an easy-to-use command-line interface.

## Prerequisites

- Python 3.6 or higher
- OpenCV library
- Haar cascades XML file
- PyCharm IDE (optional)

## Getting Started

### Setting up the Environment

1. Install Python 3.x from the official website: https://www.python.org/downloads/.
2. Install OpenCV library using the following command:

```shell
pip install opencv-python
```

3. Clone or download the project repository from GitHub.
4. Download the Haar cascades XML file for number plate detection.

### Running the Program

1. Place the downloaded Haar cascades XML file in the project directory.
2. Open the project in your preferred Python development environment (e.g., PyCharm).
3. Run the `NumberPlate.py` script.
4. Provide the path to the recorded video when prompted.
5. The program will process the video, detect number plates, and save the cropped images in the output directory.

## Usage

1. Prepare a recorded video containing vehicles with visible number plates.
2. Run the `NumberPlate.py` script.
3. Provide the path to the recorded video when prompted.
4. The program will process the video frame by frame, detect number plates, and display the progress on the command line.
5. Once the processing is complete, the program will save the cropped images of the number plates in the output directory.

## Customization

You can customize the project by modifying the following parameters:

- `cascade_path`: Set the path to the Haar cascades XML file for number plate detection.
- `output_directory`: Specify the directory where the cropped number plate images will be saved.

Feel free to explore the code and experiment with different Haar cascades or modify the detection parameters to improve the accuracy of the number plate detection.

## Contributing

Contributions to this project are welcome! If you have any suggestions, bug reports, or improvements, please feel free to create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as per the terms of the license.

## Acknowledgments

- Thanks to the OpenCV community for providing the necessary tools and resources for computer vision applications.
- The Haar cascades and object detection techniques used in this project were inspired by various OpenCV tutorials and examples available online.
