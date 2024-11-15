# Messy Room Classifier

Identify if a room is considered clean/messy. 
 
Useful for IoT smart cleaning robots  
... or just proving to your mom that your room is clean.


Resources:  
- https://medium.com/bbm406f18/week-1-clean-messy-rooms-detection-12ff60177103
- https://medium.com/@YoshuaDilhamKishi/clean-or-messy-why-i-created-room-detection-8614e4e3f362
- https://www.hackster.io/matt-farley/use-artificial-intelligence-to-detect-messy-clean-rooms-f224a2
- https://github.com/GuanqiaoDing/messy-room-classifier
- https://medium.com/bbm406f18/week-2-clean-messy-rooms-322bdcd99de

Dataset:  
- https://www.kaggle.com/cdawn1/messy-vs-clean-room

### Flask App
After going through `Messy Room Classifier.ipynb` to get the `vgg_model.h5` model file, we are going to use the model file for the Flask web app that allows users to classify if their room is messy or clean.

Create a virtual environment and install the necessary dependencies via `pip install requirements.txt`.

Run the Flask app with the following command:  
`python index.py`

Open your browser and head to `http://127.0.0.1:5000/`. You should see the Flask app.



