
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
      0: nose
      1: left_eye
      2: right_eye
      3: left_ear
      4: right_ear
      5: left_shoulder
      6: right_shoulder
      7: left_elbow
      8: right_elbow
      9: left_wrist
      10: right_wrist
      11: left_hip
      12: right_hip
      13: left_knee
      14: right_knee
      15: left_ankle
      16: right_ankle
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
    0: r ankle
    1: r knee
    2: r hip
    3: l hip
    4: l knee
    5: l ankle
    6: pelvis
    7: thorax 
    8: upper neck
    9: head top
    10: r wrist
    11: r elbow
    12: r shoulder
    13: l shoulder
    14: l elbow
    15: l wrist
    ```
    
  - Visualization imgs
  
<img src="https://user-images.githubusercontent.com/52263269/202661901-41e34c4d-5dca-48e2-8885-4711c19f1d66.png" width="50%"></img>

#### - Details of CMU Panoptic (Projected 2D keypoints from 3D keypoints)
  - Joints (19)
    - Keypoints format of MPI version is obsolte and no longer supported. Now, use COCO19 keypoints format.

     ```
    0: Neck
    1: Nose
    2: BodyCenter (center of hips)
    3: lShoulder
    4: lElbow
    5: lWrist,
    6: lHip
    7: lKnee
    8: lAnkle
    9: rShoulder
    10: rElbow
    11: rWrist
    12: rHip
    13: rKnee
    14: rAnkle
    15: lEye
    16: lEar
    17: rEye
    18: rEar
    ```

  - Visualization imgs

<img src="https://user-images.githubusercontent.com/52263269/202661901-41e34c4d-5dca-48e2-8885-4711c19f1d66.png" width="50%"></img>

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

