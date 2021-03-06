# Computer Vision Based Web App #
This is the main directory for the web app with all the necessary files for running. YOLOv5(https://github.com/ultralytics/yolov5) is used for object recognition and classification for the web app. The webcam stream input is processed for objects detection to show a output with bounding boxes and labels. The app also contains a feature of displaying number and type of objects being detected in the stream.

## Instructions to run the app locally: ##
* Clone the repo and move to this directory
  * `git clone https://github.com/Ankit-Somani/Computer-Vision-Based-Web-App.git`
  * `cd Computer-Vision-Based-Web-App/Web_App`
* Set the python environment and install the required python modules
  * `flask_env\scripts\activate.bat`
  * `pip install -r requirements.txt`
* Run the web app
  * `set FLASK_APP=app.py`
  * `set FLASK_ENV=devlopment`
  * `python app.py --source 0`
* Copy the url shown in the terminal and open it in a browser. The Web App will be opened, click on **Get Started** to see the live detections. 

The output would look something like the following:
![Web App](https://user-images.githubusercontent.com/82326089/126897635-f256e07c-4538-4d64-a99a-e2e8a898c588.png)
![Live feed](https://user-images.githubusercontent.com/82326089/126897644-0582c6ce-384f-4f63-b170-088d7e4ce345.png)

