# Amazon Product Detection

Amazon Product Detection is an AI-powered product search solution for video content, integrating e-commerce platforms and entertainment, enabling users to buy products directly from video content. The application is built using Python3, PyTorch, YOLOv8, CLIP and PIL.

## Features

- Object Detection in video frames using YOLOv8.
- CLIP was used for high-accuracy image similarity search.
- Implemented backend using Flask for Python.
- User-friendly web interface.

## Prerequisites

Before running the this application, ensure you have the following prerequisites installed on your system:

- Python3: [Download and install Python3](https://python.org) for your operating system.
- Pip: [Download and install pip] (https://pypi.org/project/pip/) for you operation system.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/KT0601/Amazon_product_detection
   ```

2.Change to the project's root directory:
   ```shell
cd Amazon_product_detection
```
3.Install the dependencies:
   ```shell
pip install -r requirements.txt
```

5. Start the application:
   ```shell
python app.py
```
The application will be accessible at http://localhost:5500.

## Usage
- Open a web browser and navigate to http://localhost:5500.
- Upload a video file to be viewed.
- Click the play exisiting video button to play the video and move progress bar according to need.
- Press the Identify object button and then click on object to be recognised in the video frame window.
- The model will generate and showcase recommendations relevant to the object selected. 
