# SignLanguageDetectionUsingML

![ASL_Alphabet](https://github.com/user-attachments/assets/993437bb-476d-480e-b256-a9669478a6e8)

## 1] Gather the data for training by executing following command:
"python collectdata.py" webcam window will open, in blue window make appropriate sign and then press character associated with it on keyboard.
This will record image, number of key presses = number of images recorded.
## 2] Run "python data.py":
To convert images to numpy array.
## 3] Run "python trainmodel.py":
To train the model on numpy array.
## 4] Execute "python app.py":
Then a webcam window will open and in which you can show the sign and get predicted by model.

Note: "functions.py" contain functions needed to process images. 

