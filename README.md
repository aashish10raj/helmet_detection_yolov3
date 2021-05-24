# helmet_detection_yolov3
#trained weights can be downloaded using https://drive.google.com/drive/folders/1iFgx_4W1q8OWovtJrinfa6GjtBI9wjtv?usp=sharing



#steps to run the program in your local machine
  1. Download the trained weight from the backup folder of google drive from the link given above
  2. Keep the trained weight and test image/video in the same folder of test.py
  3. Run the python script test.py using CMD
  4. to run program for image file use command--- python test.py --image="name of your file"
  5. to run program for video file use command--- python test.py --video="name of your file"  output file will be stored in the same folder after processing
  6. to run program for live webcam use command--- python test.py     it will open your cameera and you may detect the helmets
 
 
Model is trained over 200 images to train it to detect the helmets/non helmet wearing riders


object_custom_detection.ipynb file is used to train the model using darknet
