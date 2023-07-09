# yolov7-pose-estimation


### Steps to run Code
- Clone the repository.
```
git clone https://github.com/tourin1992/yolov7-pose-estimation.git
```

- Goto the cloned folder.
```
cd yolov7-pose-estimation
```

- Create a virtual envirnoment (Recommended, If you dont want to disturb python packages)


- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```

- Install requirements with mentioned command below.

```
pip install -r requirements.txt
```

- Download yolov7 pose estimation weights from [link](https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7-w6-pose.pt) and move them to the working directory {yolov7-pose-estimation}


- Run the code with mentioned command below.
```
#For Webcamera
python pose-estimate.py --source 0 --view-img

#For External Camera
python pose-estimate.py --source 1 --view-img
```

### Important arguments
- `--line_thickness` default values is 3
- `--img_height` default is 1440
- `--img_width` default is 2560
- `--source` corresponds to the source of the input image