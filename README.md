
Description
=============

#### - Key-points dataset format converter and visualization
  - Converting keypoints dataset to different joins format
  - Datasets: COCO, AiC, MPII keypoints, CMU Panoptic dataset

#### - Details of COCO
  - The MS COCO (Microsoft Common Objects in Context) dataset is a large-scale object detection, segmentation, key-point detection, and captioning dataset.
  - 2017 version
    - Train 118K, Valid 5K, Test 41K (Total: 164K)
    - Joints (17)
    
      ```
      1: nose
      2: left_eye
      3: right_eye
      4: left_ear
      5: right_ear
      6: left_shoulder
      7: right_shoulder
      8: left_elbow
      9: right_elbow
      10: left_wrist
      11: right_wrist
      12: left_hip
      13: right_hip
      14: left_knee
      15: right_knee
      16: left_ankle
      17: right_ankle
      ```
      
    - skeleton: [[16,14],[14,12],[17,15],[15,13],[12,13],[6,12],[7,13],[6,7],[6,8],[7,9],[8,10],[9,11],[2,3],[1,2],[1,3],[2,4],[3,5],[4,6],[5,7]]
    - Visualization imgs

    <img src="https://user-images.githubusercontent.com/52263269/202964626-1215357f-5b63-4fe6-be27-462c370057a9.png" width="35%"></img>

#### - Details of MPII
  - The images are taken from YouTube videos covering 410 different human activities and the poses
  - Train 15K, Valid 3K, Test 7K (Total: 25K)
  - Data annotations: http://human-pose.mpi-inf.mpg.de/#download
  - Joints (16)
    
    ```
    1: r ankle
    2: r knee
    3: r hip
    4: l hip
    5: l knee
    6: l ankle
    7: pelvis
    8: thorax 
    9: upper neck
    10: head top
    11: r wrist
    12: r elbow
    13: r shoulder
    14: l shoulder
    15: l elbow
    16: l wrist
    ```
    
  - Visualization imgs
  
  <img src="https://user-images.githubusercontent.com/52263269/202661901-41e34c4d-5dca-48e2-8885-4711c19f1d66.png" width="50%"></img>

#### - Details of CMU Panoptic (Projected 2D keypoints from 3D keypoints)
  
  - COCO19 keypoints version
    - Joints (19)

      ```
      1: Neck
      2: Nose
      3: BodyCenter (center of hips)
      4: lShoulder
      5: lElbow
      6: lWrist,
      7: lHip
      8: lKnee
      9: lAnkle
      10: rShoulder
      11: rElbow
      12: rWrist
      13: rHip
      14: rKnee
      15: rAnkle
      16: lEye
      17: lEar
      18: rEye
      19: rEar
      ```
    - skeleton: [[1,2],[1,4],[4,5],[5,6],[1,3],[3,7],[7,8],[8,9],[3,13],[13,14],[14,15],[1,10],[10,11],[11,12]]
    - Visualization imgs
    <img src="https://user-images.githubusercontent.com/52263269/202973034-14198c77-ced2-4ad8-8d66-4393f9e03c25.png" width="40%"></img>

Contents
=============
#### - Key-points dataset format converter

#### - Visualization of keypoints

Datasets
=============

#### - MMPOSE documents of keypoints

[https://mmpose.readthedocs.io/en/latest/tasks/2d_body_keypoint.html](https://mmpose.readthedocs.io/en/latest/tasks/2d_body_keypoint.html)

#### - COC0 keypoints dataset

[https://cocodataset.org/#home](https://cocodataset.org/#home)

[https://paperswithcode.com/dataset/coco](https://paperswithcode.com/dataset/coco)

#### - AiC (Attributes in Crowd) keypoints dataset

https://github.com/fabbrimatteo/AiC-Dataset

#### - MPII keypoints dataset

http://human-pose.mpi-inf.mpg.de/#download

https://paperswithcode.com/dataset/mpii

#### - CMU Panoptic

https://www.cs.cmu.edu/~hanbyulj/panoptic-studio/

https://github.com/CMU-Perceptual-Computing-Lab/panoptic-toolbox

Author
=============

#### - LinkedIn: https://www.linkedin.com/in/taeyong-kong-016bb2154

#### - Blog URL: https://blog.naver.com/qbxlvnf11

#### - Email: qbxlvnf11@google.com, qbxlvnf11@naver.com

