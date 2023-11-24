## Object Tracking
Detecting and tracking an object in a video file, in python using OpenCV library and various models and tools.
  
### project workflow: 
1. Create an object of a tracker based on the chosen algorithm.
2. Read the first frame of the video, apply an object detection method using TensorFlow models, select the first detected object, and obtain its bounding box.
3. Initialize the tracker by the obtained bounding box.
4. In a while loop, read the subsequent frames, update the bounding box, draw it around the object and show.

In addition, the project includes methods to handle scenarios where the object goes out of the frame.