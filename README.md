# pupil-movement-detector

Salient features of the project are: 
1) The project has been implemented using python, HTML, CSS and JavaScript.
2) The code for the detector is written using the popular python library, OpenCV, which also includes
the famous “Haar Cascade Classifier”, used to detect the face and eye. The python microframework, Flask, is being used to create the web application.
3) The backend of the project consists of the code for the detector. Frontend consists of the website 
through which users interact with the detector and see the results.
4) The detector accurately detects the pupil and tracks it, and also prints direction of sight.
5) Users can choose to either upload a video or use the webcam for detection.
For more details, please read the mini project report file.

In order to run the project:
1) Download the project to a suitable location. Do not change the heirarchy of the folders, keep it as it is.
2) Open a command prompt and change directory to the directory that contains "process.py".
3) Type the command "py process.py" to run the file.
4) Open a web browser and type "http://127.0.0.1:5000/" or "localhost:5000".
This will open the required webpage of the project. 

While using the detector, please remember to ensure the following so that the detector works properly:
1) The face must be well within the frame
2) Both eyes must be visible (No side profile)
3) Room should be well-lit
4) Objects blocking the face may cause accuracy to fall
