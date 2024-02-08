*Face Mask Detection Using Machine Learning*

This project focuses on implementing a face mask detection system using machine learning techniques. The goal of this project is to detect whether a person in an image or video is wearing a face mask or not. By leveraging machine learning algorithms and computer vision techniques, we have developed a model capable of accurately classifying images into two categories: "With Mask" and "Without Mask." This project aims to contribute to public health efforts by providing a tool that can assist in enforcing face mask regulations in various settings, such as hospitals, schools, and public spaces.



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
