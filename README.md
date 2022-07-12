# ImageRecognition
**As a** Senior computer science student  
**I want** to implement image recognition via YOLO framework  
**So that** I can fulfill senior design project  

# Note:

Pre-requisite:  
.  
├── images  
├── output  
├── README.md  
├── videos  
├── yolo-coco  
│   ├── coco.names  
│   ├── yolov3.cfg  
│   └── yolov3.weights  
└── yolo.py  
  
- root directory must have images/, videos/, output/, yolo-coco/  
(the videos/ only be used when yolo-video.py is implemented.. coming soon)  
- the source code needs to be under the root directory  
- yolo-coco/ is a sub-directory that has yolov3 framework  
  1. coco.names is the library of identified objects.  
  2. yolov3.weights is the pre-trained weight file (over 200MB). you can download it [here](https://pjreddie.com/darknet/yolo/)    
  3. yolov3.cfg is the config file
- images/ cannot be empty, put some test images here to run the program
- run program by `python yolo.py --image images/nameofthepicture.jpg --yolo yolo-coco`  
