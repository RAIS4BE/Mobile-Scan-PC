# Mobile-Scan-PC

This dataset comprises 3D point clouds of indoor scenes collected primarily using a solid-state LiDAR–camera (Intel RealSense L515) since 2022 on SDE, National University of Singapore. Data collection was conducted by Vincent Gan, Difeng Hu, and Tao Wang, with assistance from Kexin Li in data processing and semantic segmentation.

(1) SDE1 & SDE2

<img width="989" height="929" alt="image" src="https://github.com/user-attachments/assets/c532e893-5be6-4fea-a9f2-46b4d7c0eed6" />

Figure and Table below illustrate results of the semantic segmentation of one selected scene using ResPointNet++. The overall segmentation accuracy reaches a mean Intersection over Union (mIoU) of 78.14%, and an overall accuracy (OA) of 89.68%. Notably, the mIoU for building elements other than clutters exceeds 87%, indicating that the captured point cloud possesses high completeness and density. However, the segmentation of clutters yields a lower IoU of 39.38%. This reduced performance may be attributed to the diversity of clutters, which makes it challenging for the model to learn consistent features that accurately represent all types of clutters.

<img width="972" height="441" alt="image" src="https://github.com/user-attachments/assets/23bb2008-0f20-45a5-a9d4-1b4cca2caca2" />


Please cite when using the dataset.

Citation: Gan, V., Hu, D., Wang, T., Li, K. (2023). Mobile-Scan-PC. GitHub. https://github.com/RAIS4BE/Mobile-Scan-PC.
