# object-tracking 

This is compatible only with `ultralytics==8.0.0`. However, I highly recommend using the latest version of the Ultralytics package and referring to the official Ultralytics codebase here: [GitHub Repository](https://github.com/ultralytics/ultralytics/).

### Steps to run Code

- Clone the repository
```bash
https://github.com/tranducthai/object-tracking.git
```
- Cd to cloned folder

```bash
cd object-tracking
```

- Install the required package
```bash
pip install -r requirements.txt
```

- Do Tracking with the mentioned command below
```bash
#video file
python yolo\v8\detect\detect_and_trk.py model=yolov8s.pt source="test.mp4" show=True

#imagefile
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source="path to image"

#Webcam
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source=0 show=True

#External Camera
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source=1 show=True
```

- Output file will be created in the working-dir/runs/detect/train with original filename



