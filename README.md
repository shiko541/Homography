# AR application
An AR (Augmented Reality) application in computer vision is a software system that blends virtual content with the real-world environment using computer vision techniques to understand and interpret what the camera is seeing.
## flow of work:
1)get image and first frame of the video
### 1.1) Getting Correspondences
2)use sift descriptor to find the keypoints and descriptors of both images
3)correspondences between the image book (Figure 2.a) and the first frame of the video .
4)using bruteforce knn=2 & apply ratio matching if ratio<0.5.
5)get first 50 correspondance.
