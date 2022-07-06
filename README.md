# ImageRecognition
**As a** Senior computer science student  
**I want** to implement image recognition via YOLO framework  
**So that** I can fulfill senior design project  

# Note:

Pre-requisite:  
.  
├── images  
│   ├── dogs.jpg  
│   └── human.jpg  
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
- the source code is under the root directory  
- yolo-coco/ is sub-directory that has yolov3 framework  
  1. coco.names is the library of identified objects.  
  2. yolov3.weights is the pre-trained weight file (over 200MB).  
  3. yolov3.cfg is the config file
- images/ cannot be empty
- run program by `python yolo.py --image images/nameofthepicture.jpg --yolo yolo-coco`  