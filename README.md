# SOCIAL-DISTANCE-DETECTOR


download or clone the repo

since github don't usually support file larger than 25mb, i have removed the yolo wieght from the yolo folder.
you can download the yolo weight here https://drive.google.com/file/d/1YRexfyNDy749ey9quk1xieEQ4H3R2FRd/view?usp=sharing and add
it to the yolo coco folder. or better still, you can download  all the file here at once  https://drive.google.com/drive/folders/15_MOPPOwYwbpQmOdjsmup-_w9Euv97vS?usp=sharing

after downloading

* Open your terminal**
* Change directory to where you have downloaded this code
* install dependencies using ,,  pip install -r requirements.txt  `

for webcam  


* Run the command** python social_distance_detector.py 


for video

* Run the command** python social_distance_detector.py --input wal.mp4 --output output.avi --display 1


for image
* Run the command** python social_distance_detector.py --input b.jpg --output gh.jpg --display 1
