# AI SheetMusic Player

A python app for playing sheetmusic from captured images. This program uses the model provided for the research paper by Calvo-Zaragoza, Jorge and Rizo, David:

[End-to-End Neural Optical Music Recognition of Monophonic Scores](http://www.mdpi.com/2076-3417/8/4/606)


# Usage

Step 1: Download pretrained model and save in Models folder from: [pre-trained model](https://grfia.dlsi.ua.es/primus/models/PrIMuS/Semantic-Model.zip)

Step 2: Clone project code into tf_end_to_end folder from: [project code](https://github.com/OMR-Research/tf-end-to-end)

Step 3: Save music png files in the data folder.

Step 4: Install packages `pip install -r requirements.txt`

Step 5: Run the following in the command line:
```python tf_end_to_end/ctc_predict.py -image Data/<path to your png file> -model Models/semantic_model.meta -vocabulary Data/vocabulary_semantic.txt```

# More reading..

Read more about the project and a comprehensive introduction to Optical music recognition at [Play Sheet Music with Python, OpenCV, and an Optical Music Recognition Model](https://medium.com/cometheartbeat/play-sheet-music-with-python-opencv-and-an-optical-music-recognition-model-a55a3bea8fe)