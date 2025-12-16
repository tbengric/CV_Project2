# CV_Project2
First idea of how to do the project :
- For each objects in the game, calculate the keypoints/descriptors to indentify them during the video. We create a kind of dataset with all the objects
- For each frame in the game video, check if one of the object is introduced by calculating the descriptors of any objects in the frame and compare it with the dataset of all objects in order to find the coordinates of the object we want to follow. if so, start to follow the objects through the video
