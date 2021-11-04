# Forensic++
Requirment to run this project is in Linux/Unix environment
<br>
Steps to run the code
(1) Download the google drive folder inside the same folder
(2) Go to models.py file in network/__pychache__ folder and on line 26 change the file path xception-b5690688.pth to your PCs file path
(3) Run the detect_from_video.py using the following code
python detect_from_video.py
-i <path to input video or folder of videos with extenstion '.mp4' or '.avi'>
-m <path to model file, default is imagenet model
-o <path to output folder, will contain output video(s)>

in -i enter the input video paths. For example give path to the faceswap folder
in -m give model path for example full, c23, c40
in -o create an output folder and specify where to store files


example: 
python detect_from_video.py -i /Users/bqureshi/Downloads/faceproject/FaceForensics-master/classification/myvideo/origtext/ -m /Users/bqureshi/Downloads/faceproject/FaceForensics-master/classification/faceforensicsmodels/face_detection/xception/full_c23.p -o /Users/bqureshi/Downloads/faceproject/FaceForensics-master/output_orig

