# Traffic Lights Object Detector using YOLOv8 neural network

<div align="center">
    <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--mZ1E0vOa--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/n2auv9i8405cgnxhru40.png"/>
</a>
</div>


This is a web interface to [YOLOv8 object detection neural network](https://ultralytics.com/yolov8) 
implemented on [Python](https://www.python.org) that uses a model to detect traffic lights and road signs on images.

## Install

* Clone this repository: `git clone git@github.com:AndreyGermanov/yolov8_pytorch_python.git`
* Go to the root of cloned repository
* Install dependencies by running `pip3 install -r requirements.txt`

## Run

Execute:

```
python3 object_detector.py
```

It will start a webserver on http://localhost:8080. Use any web browser to open the web interface.

Using the interface you can upload the image to the object detector and see bounding boxes of all objects detected on it.
