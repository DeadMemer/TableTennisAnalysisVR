# TableTennisAnalysisVR
 We workded on this University project for a Computer Vision Course. We focuses on detecting and projecting on a 2D table with a top-view a moving ball during a VR match in the game Eleven Table Tennis. We also detect the corners of the table trying to reconstruct the missing points.

 # Models
We used YOLO v8l and YOLO11l for ball and keypoint detection respectively. The weights of the models are saved in the /models folder

 # Datasets
The dataset was built by us using recording from matches played in VR. We labeled more than 1100 images for each datasets and we also applied data augmentation to them using Roboflow. Datasets can be downloaded from these links:
Ball dataset: https://app.roboflow.com/computer-vision-project-mjsdu/table-tennis-ball-um5tc/7   and Keypoint field dataset: https://app.roboflow.com/computer-vision-project-mjsdu/table-tennis-table-net/12

 # How to Run
 Just use the .ipynb file on Google Colab giving a video with .mp4 format of the game.

 ![pingpong_squad](https://github.com/user-attachments/assets/7b8c1ad4-8a52-4469-84e3-69c0998c2625)
