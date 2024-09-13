Human pose estimation is a project focused on extracting keypoints from images of humans. These keypoints correspond to essential joints and body parts, such as shoulders, elbows, and knees, enabling precise mapping of the human body's pose and movement.
Two primary approaches are commonly used in this process: bottom-up and top-down. The bottom-up approach begins by detecting individual keypoints across the entire image and then grouping them to form complete human poses.
This method is efficient for handling multiple people in an image but may struggle with accuracy in more complex scenes. On the other hand, the top-down approach first identifies each person in the image with a bounding box, then applies pose estimation models to locate keypoints within these detected areas. 
While the top-down approach generally offers higher accuracy, especially for single-person pose estimation, it can be more computationally demanding when multiple people are involved.


![Mediapipe test 2](https://github.com/user-attachments/assets/79c95126-67e8-47a8-815d-4eab297bb3a9)
![Mediapipe test1](https://github.com/user-attachments/assets/c1851b9b-bf0c-4369-ae66-642f9ed6d5f4)
![Mediapipe test 22](https://github.com/user-attachments/assets/2fbd9db8-6009-4042-9600-59d58ad96d5d)
![00](https://github.com/user-attachments/assets/37aecfdb-f90c-4178-a718-71f12f292ab0)
