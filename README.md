# Mobile-Scan-PC

(1) SDE1 & SDE2

This dataset comprises 3D point clouds of indoor scenes collected primarily using a solid-state LiDAR–camera (Intel RealSense L515) since 2022 on SDE, National University of Singapore. Data collection was conducted by Vincent Gan, Difeng Hu, and Tao Wang, with assistance from Kexin Li in data processing.

The dataset has not yet been published in any journal article. A summary presenting the dataset and preliminary test results is attached below. Please cite when using the dataset.
Citation: Gan, V.J.L., Hu, D., Wang, T., Li, K. (2023). Mobile-Scan-PC. https://github.com/RAIS4BE/Mobile-Scan-PC

In the scanning experiment, LiDAR and stereo cameras were used to scan several indoor scenes, ensuring the camera captures spatial data from various angles and perspectives. Figure below shows the selected examples out of a total of 15 scenes. As the cameras move around these indoor scenes, the camera continuously emits laser beams (in case of LiDAR camera) or captures stereo images (in case of stereo camera), measuring distances to surfaces and generating depth images. These RGB and depth data are transmitted in real-time to process the incoming data immediately, converting it into point clouds for a dense 3D representation of the scanned environment. 

<img width="680" height="393" alt="Picture1" src="https://github.com/user-attachments/assets/278cd2f4-5b8f-49c5-8dfb-469f0e290481" />

Figure and Table below illustrate results of the semantic segmentation of one selected scene using ResPointNet++. The overall segmentation accuracy reaches a mean Intersection over Union (mIoU) of 78.14%, and an overall accuracy (OA) of 89.68%. Notably, the mIoU for building elements other than clutters exceeds 87%, indicating that the captured point cloud possesses high completeness and density. However, the segmentation of clutters yields a lower IoU of 39.38%. This reduced performance may be attributed to the diversity of clutters, which makes it challenging for the model to learn consistent features that accurately represent all types of clutters.

<img width="700" height="441" alt="image" src="https://github.com/user-attachments/assets/23bb2008-0f20-45a5-a9d4-1b4cca2caca2" />

(2) More mobile scan PC coming soon ...
