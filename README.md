
# Object_Detection_Python

Object Detection in Python using OpenCV and Yolo.



## Run Project

Clone the project

```bash
  git clone https://github.com/Aman71071/Object_Detection_Python
```

Go to the project directory

```bash
  cd Object_Detection_Python
```

Download the **yolov3.weights** file and paste in the project directory

- [@yolov3](https://pjreddie.com/media/files/yolov3.weights)

Install dependencies

```bash
  pip install numpy
  pip install opencv-python
```

Run the Project(Example Image)

```bash
  python yolo_opencv.py --image dog.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt 
```

Command Format

```bash
  python yolo_opencv.py --image /path/to/input/image --config /path/to/config/file --weights /path/to/weights/file --classes /path/to/classes/file_ 
```


## Authors

- [@Aman71071](https://github.com/Aman71071)

