# YOLO

### Use pre-trained model
This is an example to use pre-trained model on live traffic cam

1. Clone https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet
```
git clone https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet.git
cd Yolov5_StrongSORT_OSNet
git submodule init
git submodule update
pip install -r requirements.txt
```
2. Run the model on live traffic camera streaming on Youtube (LIVE: Pracha Songkhro Soi 2 https://www.youtube.com/watch?v=xd567z000HE)
```
python track.py --source https://youtu.be/xd567z000HE --strong-sort-weights osnet_x0_25_market1501.pt
```
