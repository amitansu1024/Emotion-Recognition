# Emotion-Recognition

## Introduction
This is a machine learning project which aims to recognize human emotions through facial features. The model has been successfully implemented inside of a desktop application which can now recognize human emotions through a live web camera feed or a video of your choice.

## Build Instructions

### Machine Learning Model
The dependencies needed for compiling the model are :- **Tensorflow, numpy, opencv**. 
You can prepare the dataset if needed from prepare_dataset.py, it will take input a csv file and give output from in the form of a directory. 

To train the model, you can use 
```
python3 main.py --mode train
```

To view the model in action, in an opencv window, you can use 
```
python3 main.py --mode display
```

### Desktop Application
The desktop application was designed using Pyqt library along with OpenCV for video and web camera feed. The following dependencies are :- **PySide2, Pyqt6, opencv**. You must have these dependencies if you want to build the application from source. 

There is a model included in the app directory, along with the xml file which are necessary for running the application.

Then 

```
cd app
python3 app.py
```


Now you should be able to see a new window on your screen.
