# Fire and Gun Detection

![result](https://raw.githubusercontent.com/atulyakumar97/fire-and-gun-detection/master/screenshots/0.jpg "Model Output")

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

### Weights File Backup

If the GitLFS file is not accessible - Download [Weights](https://1drv.ms/u/s!Aj0l1DM1G5wOm0Vg2n7RI5Q4_ZOq?e=gGvvMy) and keep inside the project folder.


### Move inside the project folder and use the following command:
```
python yolo.py --play_video True --video_path videos/fire1.mp4
```

[Dataset](https://www.kaggle.com/atulyakumar98/fire-and-gun-dataset)

Training done on google collab - [Jupyter notebook](https://colab.research.google.com/drive/1rtBmGPgYQGwpAPkcqqgb_RE6fZj89ceb?usp=sharing)

Demo: [Youtube](https://www.youtube.com/watch?v=KUrOOUEtYzo)

### Paper
[Fire and Gun Violence based Anomaly Detection System Using Deep Neural Networks](https://ieeexplore.ieee.org/document/9155625) <br>
Proceedings of the [International conference on Electronics and Sustainable Communication Systems - ICESCS 2020](https://ieeexplore.ieee.org/servlet/opac?punumber=9145513) <br>
ISBN: 978-1-7281-4107-7 <br>
978-1-7281-4108-4/20/©2020 IEEE <br>