# Landmark Recognition [2021]

## Source
- Trained model [`landmarks_classifier_asia_V1/1`](https://tfhub.dev/google/on_device_vision/classifier/landmarks_classifier_asia_V1/1) is taken from the Tensorflow-Hub
- There are total `98961` classes supported, in which Asia's most of the famous Landmark is covered.
- This model was trained on [`Google Landmarks Dataset V2`](https://ai.googleblog.com/2019/05/announcing-google-landmarks-v2-improved.html). 

## Features
- Simple repsonsive UI.
- It will give you the full address of Landmark
- It will provide you the `Latitude` & `Longitude` of predicted landmark.
- It will plot the predicted landmark on the Map.

## Usage

- Clone my repository.
- Open CMD in working directory.
- Run following command.

  ```
  pip install -r requirements.txt
  ```
- `LM_Detection.py` is the main Python file of Streamlit Web-Application. 
- To run app, write following command in CMD. or use any IDE.

  ```
  streamlit run lm_recog.py
  ```

- For more explanation of this project see the tutorial on Machine Learning Hub YouTube channel.

## Screenshots

<img src="https://github.com/Spidy20/LandMark_Detection/blob/master/s1.PNG">
<img src="https://github.com/Spidy20/LandMark_Detection/blob/master/s2.PNG">
