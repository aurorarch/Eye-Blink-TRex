# Eye-Blink-TRex
Playing the Chrome's TRex game with eye blink

Open this link to play the game
[Chrome's TRex Game](http://www.trex-game.skipser.com/)

The main challenge of this project is to detect the blink for which OpenCV was used. Once the blinks are detected, python's Pyautogui module helps with the keyboard operations.
To install all the required modules : 
```sh
pip install -r requirements.txt
```

You can download the [facial landmark](dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) dat file here and save it in the same directory of the script.

To run the script : 
```sh
python detect_blink.py -p shape_predictor_68_face_landmarks.dat
```

![Demo video](https://user-images.githubusercontent.com/44130480/105681604-559a6380-5f17-11eb-9705-f85e6b6fc1b0.mp4)
