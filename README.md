
# Car Counter - Vehicle Counting using YOLOv8 Object Detection




## 

![Car Counter](https://drive.google.com/file/d/1s9XFb32b7FdT_10hGuMj47eKoL_uc2XX/view?usp=drive_link)


## Introduction

Car Counter is a Python-based project that utilizes YOLOv8, an efficient and powerful object detection model, to count vehicles passing through a designated area in a video. The project aims to accurately detect and count motorbikes, cars, trucks, buses, and bicycles while ignoring other objects present in the scene. It provides a valuable tool for traffic monitoring, transportation planning, and traffic management.
## Prerequisites

- Python 3.6 or higher

- [Virtualenv](https://virtualenv.pypa.io/en/latest/) (optional but recommended)

## Installation

1. Create a virtual environment and activate it:

```bash
virtualenv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```
2. Install required packages:
```bash
pip install -r requirements.txt
```
    
## Usage

1. Prepare your video:

- Place your video file in the project directory.

2. Create a mask:

- Create a mask image named mask.png that defines the area where you want to count vehicles. The rest of the video will be masked out.

3. Run the Car Counter:
```bash
python car_counter.py 
``` 

4. View the results:

- The processed video with vehicle counting will be saved as output_video.mp4.

- The vehicle count and class distribution will be displayed in the console.


## Configuration
- You can customize the confidence threshold for vehicle detection by modifying the conf parameter in car_counter.py. The default value is set to 0.3.
## Acknowledgements

 - [Ultralytics](https://github.com/ultralytics/ultralytics)
 - [CVzone library by CVzone](https://github.com/cvzone/cvzone)
 


## Contribution

Contributions are always welcome!

If you find any issues or have suggestions for improvements, feel free to create a pull request.


## Contact
For any questions or inquiries, please contact us at [ishita126jain@gmail.com](ishita126jain@gmail.com).
