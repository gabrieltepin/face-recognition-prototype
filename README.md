# Face recognition prototype

This is a demo of running face recognition on live video from the computer webcam for prototyping school project but it
contains basic performance tweaks to improve processing:
1. Process each video frame at 1/4 resolution (though still display it at full resolution)
2. Only detect faces in every other frame of video.

## Running the project

_PLEASE NOTE: This example requires OpenCV (the `cv2` library) to be installed only to read from your webcam.
OpenCV is *not* required to use the face_recognition library_

After installing the required libs, execute the following command to run the code:

```
    python3 main.py
```

The webcam should initiate and the program should start processing the frames searching for matches with faces pictures included in _authorized_ folder
