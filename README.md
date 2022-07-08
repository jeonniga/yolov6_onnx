# yolov6_onnx

# yolov6 pretrained model
https://github.com/meituan/YOLOv6/releases/tag/0.1.0

# yolo model to onnx
python deploy/ONNX/export_onnx.py --weights models/yolov6n.pt --img 640 --batch 1

# detection with yolov6 camera
python webcam_object_detection.py
