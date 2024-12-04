
# asl-svm

real-time recognition of american sign language from webcam using svm classifier and mediapipe 


## Dataset used
https://www.kaggle.com/datasets/grassknoted/asl-alphabet
## Requirements
Install with:
```
pip install -r requirements.txt
```
## Usage
Train from your own dataset with load_asl_landmarks_data() or use data.npz.

Left mouse click to register the sign, right mouse click to delete all from the sentence buffer.

Press s to begin text-to-speech on the current sentence.