## Object Detection in Real-time (Streaming) _Repository No.1_   :bulb: :bulb:
### Using -pretraied- of YOLOv3 weights and COCO Dataset containing 80 classes. :books:
### With this Repository you can achieve Object Detection in Real-time through your camera.  :camera: :camera:


### Steps for Running:  :ok_hand: :ok_hand:
1. Create an enviroment and isntall the requirements.txt file
``` bash
## create an enviroment
python -m venv envName

## activate it --> (for windows)
envName\Scripts\activate.bat
## activate it --> (for Linux)
source envName/bin/activate

## install requirements.txt file
pip install -r requirements.txt
```
2. First, you should download the YOLOv3 weights
``` bash
## you can run this command on terminal for (unix OS) 
wget https://pjreddie.com/media/files/yolov3.weights
```
or download the weights from this Link for (Windows OS)
[YOLOv3 weights](https://pjreddie.com/media/files/yolov3.weights)

3. After downloading YOLOv3 weights, put this weights file into models Directory.
4. Our App is ready, We can run it now. Open your terminal and go to Repo Path and run the following command. 
``` bash
## run this command through your terminal
python app.py
```
