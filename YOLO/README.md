# YOLO

### Use pre-trained model

![example](./yolo-xooos.gif)

This is an example to use pre-trained model on live traffic cam

1. Clone https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet
```
git clone https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet.git
cd Yolov5_StrongSORT_OSNet
git submodule init
git submodule update
pip install -r requirements.txt
```
2. Run the model on live traffic camera streaming on Youtube (About Damn Time - Lizzo (xooos cover) https://www.youtube.com/watch?v=3McjKJZHSc4)
```
python track.py --source https://youtu.be/3McjKJZHSc4 --strong-sort-weights osnet_x0_25_market1501.pt
```
