change some values :
 * on detect_mask_video.py - ln:65 ( give your project name )
 * on detect_mask_video.py - ln:26 ( copy paste the path of dataset int the project )

- create a virtual environment 
python -m venv venv

activate the environment
venv\Scripts\activate

install required libraries
pip install -r requirements.txt

model is already generates , if needed you can make a new one by sparing 2-3 hours
python train_mask_detector.py

check if the cam of your device is working and run the camera service
detect_mask_video.py
