# Open CV

### Used to interface with Wyze camera running RTSP supported firmware. 
#### - to install this firmware please look at resource https://support.wyze.com/hc/en-us/articles/360026245231-Wyze-Cam-RTSP

### To Run
#### - install Python
#### - git clone repo
#### - `pip install opencv-python` https://pypi.org/project/opencv-python/
#### - create a `config.py` in the root folder with your RTSP url
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  - example
```
rtsp_url = "rtsp://username:password@ip.addre.ss.ss/live"
``` 
#### - from terminal type `python3 openCamStream.py`
