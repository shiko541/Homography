# AR application
An AR (Augmented Reality) application in computer vision is a software system that blends virtual content with the real-world environment using computer vision techniques to understand and interpret what the camera is seeing.
## flow of work:
1)get image and first frame of the video
### 1.1) Getting Correspondences
1)use sift descriptor to find the keypoints and descriptors of both images
2)correspondences between the image book (Figure 2.a) and the first frame of the video .
3)using bruteforce knn=2 & apply ratio matching if ratio<0.5.
4)get first 50 correspondance.
### 1.2) Compute the Homography Parameters
1)function compute homography : computes homography matrix using DLT with SVM
2)function verify matrix: compare the average of all projected point distances with the original destination distances
### 1.3) Calculate Book Coordinates
