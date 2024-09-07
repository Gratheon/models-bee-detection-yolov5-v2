# Bee detection and tracking
Main article:
https://www.mixtile.com/ai-based-bee-detection-and-tracking/

Steps to follow:

<ul>
<li>git clone https://github.com/ultralytics/yolov5</li>
<li>cd yolov5</li>
 <li>pip install -r requirements.txt</li>
 <li>wget https://github.com/sdizdarevic/beedetectionyolov5/raw/main/best.pt -- Download YoloV5 model</li>
 <li>wget https://sdizdarevic.typepad.com/cr/bees-orig.mp4  --download video</li>
 <li>python3 detect.py --weights best.pt --source bees-orig.mp4</li>

</ul>

Videos are on urls:

Original video: 

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/mQ-ks4ybRHw/maxresdefault.jpg)](https://youtu.be/mQ-ks4ybRHw)

Result video: 

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/wZbo47IuIVM/maxresdefault.jpg)](https://youtu.be/wZbo47IuIVM)
