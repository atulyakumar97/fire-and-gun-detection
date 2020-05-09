# Fire and Gun Detection

![result](https://raw.githubusercontent.com/atulyakumar97/fire-and-gun-detection/master/screenshots/1.jpg "Model Output")

### How to use yolo.py:
```
usage: yolo.py [-h] [--webcam WEBCAM] [--play_video PLAY_VIDEO]
               [--image IMAGE] [--video_path VIDEO_PATH]
               [--image_path IMAGE_PATH] [--verbose VERBOSE]

optional arguments:
  -h, --help            show this help message and exit
  --webcam WEBCAM       True/False
  --play_video PLAY_VIDEO
                        Tue/False
  --image IMAGE         Tue/False
  --video_path VIDEO_PATH
                        Path of video file
  --image_path IMAGE_PATH
                        Path of image to detect objects
  --verbose VERBOSE     To print statements
```

### Move inside the project folder and use the following command:
```
python yolo.py --play_video True --video_path fire1.mp4
```

[Dataset](https://www.kaggle.com/atulyakumar98/fire-and-gun-dataset)

Training done on google collab - [Jupyter notebook](https://colab.research.google.com/drive/1rtBmGPgYQGwpAPkcqqgb_RE6fZj89ceb?usp=sharing)

Demo: [Youtube](https://www.youtube.com/watch?v=KUrOOUEtYzo)

Paper: To be added soon
