# Forensic++ Applied Data Science Project Group C
Requirment to run this project is in Linux/Unix environment
<br>
Steps to run the code <br>
(1) Download the google drive folder inside the same folder and install requirments.txt <br>
(2) Go to models.py file in network/__pychache__ folder and on line 26 change the file path xception-b5690688.pth to your PCs file path <br>
(3) Run the detect_from_video.py using the following code <br>
python detect_from_video.py <br>
-i <path to input video or folder of videos with extenstion '.mp4' or '.avi'> <br>
-m <path to model file, default is imagenet model <br>
-o <path to output folder, will contain output video(s)> <br>
<br> <br> <br>
in -i enter the input video paths. For example give path to the faceswap folder <br>
in -m give model path for example full, c23, c40 depending upon the type of video <br>
in -o create an output folder and specify where to store files <br>

<br>
example:  <br>
python detect_from_video.py -i /Users/bqureshi/Downloads/faceproject/FaceForensics-master/classification/myvideo/origtext/ -m <br> /Users/bqureshi/Downloads/faceproject/FaceForensics-master/classification/faceforensicsmodels/face_detection/xception/full_c23.p -o <br> /Users/bqureshi/Downloads/faceproject/FaceForensics-master/output_orig <br>

Google drive link for full project: https://drive.google.com/drive/folders/12j9Uao6V2nzbs7HMFPaZ_6qpd0X3B5mt <br>
Since github didn't allow to upload files greater than 25mb such as videos and models

<br>
Extract zip file <br>
<br>
Go to classification/model_datasets to find old and new datasets <br>
Go to classification/faceforensicmodels to find models
