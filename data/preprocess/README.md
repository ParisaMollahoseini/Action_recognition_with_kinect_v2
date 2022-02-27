# Process KARD data for our algorithm


### ✅  How to run
At first you should download dataset from link mentioned in previous parts.
Then for running this code, you just have to change the directories which are put in some varibales like path, data_path, etc to your dataset directory.

📌 We use 8 percent of data for test that is 13 and train data is 137.

We will explain the code as follow.

### 1️⃣ Convert each skeleton file to a file with specified number of frames

We use minimum number of frames for final number of frames.
Each skeleton file comprises several frames in which body skeleton in 15 lines is presented. 
For instance, a file with 30 frames, has 30*15 lines.
➡️  min = 42
Each line from 15 lines shows body points like below:

{ Head, Neck, Right_Shoulder, Right_Elbow, Right_Hand, Left_Shoulder, Left_Elbow, Left_Hand, Torso, Right_Hip, Right_Knee, Right_Foot, Left_Hip, Left_Knee, Left_Foot }

📌 Finaly, 42 important frames of each file are chosen.
### 2️⃣ Convert skeleton data to image by keeping the label as name of image

In this section, each .txt file needs to be converted to an image due to using image processing model for our algorithm.

Each body points is defined in 3D coordinate system. So, x, y, z positions can be respectively used as r, g, b in an RGB image.

📌  Because data comprises some positions on the screen and also bodies are gathered from different distances from kinect camera, there is need to first scale these numbers with 4500, second normalize them and at last, merge r, g, b together.


### ✔️ In dataset folder there are 3 zip files for train, test, validation which consist of processed images resulted from mentioned code.
