Human pose estimation is a project focused on extracting keypoints from images of humans. These keypoints correspond to essential joints and body parts, such as shoulders, elbows, and knees, enabling precise mapping of the human body's pose and movement.
Two primary approaches are commonly used in this process: bottom-up and top-down. The bottom-up approach begins by detecting individual keypoints across the entire image and then grouping them to form complete human poses.
This method is efficient for handling multiple people in an image but may struggle with accuracy in more complex scenes. On the other hand, the top-down approach first identifies each person in the image with a bounding box, then applies pose estimation models to locate keypoints within these detected areas. 
While the top-down approach generally offers higher accuracy, especially for single-person pose estimation, it can be more computationally demanding when multiple people are involved.

![102](https://github.com/user-attachments/assets/f1bdd885-919f-41ab-8e62-ece9eb4a4880)
![Mediapipe test1](https://github.com/user-attachments/assets/18487ddb-9a7c-46f4-b20d-1387c4c515f9)
![Mediapipe test 2](https://github.com/user-attachments/assets/b8790f43-ae58-4003-966d-3963794f5b82)
![Mediapipe test 22](https://github.com/user-attachments/assets/ec1f2b6d-aabc-4fed-b9bb-c7b54caca92b)
