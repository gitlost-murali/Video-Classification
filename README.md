# Video-Classification
Uses an architecture of VGG16 with LSTM to predict. 

#vid2objects.ipynb file

This is an additional file. It provides extra information per each frame about the objects. Inorder to run this file, you need to install few dependencies. For help, you can go through these two links,

1. https://pythonprogramming.net/introduction-use-tensorflow-object-detection-api-tutorial/
2. https://medium.com/@WuStangDan/step-by-step-tensorflow-object-detection-api-tutorial-part-1-selecting-a-model-a02b6aabe39e

Both links are equally likely to work, first one is for WINDOWS users and second is for LINUX users.

Redirect to "models-master\research\object_detection\" and paste this file there.
This file takes the videos present in "VIDEO_FOOTAGE\videos" folder and extract frames into "VIDEO_FOOTAGE\video_frames\video_name\frame_num.jpg" and output the objects detected in each frame to "VIDEO_FOOTAGE\video_frames\video_name\frame_name.pickle". 
