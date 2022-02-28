# Test model on Kinect device
## In progress

### ✅ Explanation
In this code we want to test our model on kinect device.<br>
Different parts of this code are listed bellow:
- Install the required packages.
- Load trained model.
- Create the cell with BodyGameRuntime class for recieving kinect frames.
- Create functions for conversion of body skeleton to image and prediction.

### ✅ How to run

Connect the kinect device to your PC and just change the directories to your directories and run the cells one by one.
Remeber to stand at least 2 meters far from kinect. Because kinect should recognize your whole body to get your skeleton body points and prediction result of sending data to the model.


📌 After running the code with BodyGameRuntime class, you have 2 seconds to be in right distance from kinect otherwise you get error. Then you can run its following cell and again run the previous cell again.

📌 <b> In future versions of this code we will handle this error. </b>
