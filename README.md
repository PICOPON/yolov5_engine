# YOLOv5_engine (TensorRT, YOLOV5 6.1, .engine)
## This project is used to deploy the engine model (.engine) generated by YOLOV5 6.1 (export.py) to jetsonnano or running in a separate environment.
## In addition, it also supports forward prediction of other models(.engine) generated by the TensorRT framework
## Prepare ##
- install
```
  pip install -r requirements.py
 ```
## Usage ##
- Predict Support **2 MODE**（--source camera or single image)
```
  python yolov5pred.py --engine runs/yolov5s.engine  --categories runs/names.txt --source camera --conf-thres 0.25 --iou-thres 0.1
```
