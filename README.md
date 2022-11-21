
Description
=============

#### - Key-points dataset format converter and visualization
  
  - Converting keypoints dataset to different joins format
  - Datasets: COCO, AiC, MPII keypoints, CMU Panoptic dataset

#### - Details of COCO
  
  - The MS COCO (Microsoft Common Objects in Context) dataset is a large-scale object detection, segmentation, key-point detection, and captioning dataset.
  - Train 118K, Valid 5K, Test 41K (Total: 164K) 
  - Over 150,000 people and 1.7 million labeled keypoints
  - Visibility flag *v*
    - v=0: not labeled (in which case x=y=0)
    - v=1: labeled but not visible
    - v=2: labeled and visible
    
##### - 2017 version
    
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
    
    - skeleton (not fixed): [[15,13],[13,11],[16,14],[14,12],[11,12],[5,11],[6,12],[5,6],[5,7],[6,8],[7,9],[8,10],[1,2],[0,1],[0,2],[1,3],[2,4],[3,5],[4,6]]
    - Examples of visualization imgs

      <img src="https://user-images.githubusercontent.com/52263269/202964626-1215357f-5b63-4fe6-be27-462c370057a9.png" width="35%"></img>
 
##### - OpenPose version
    - Joints (18)
    
    ```
    0: Nose
    1: Neck
    2: R-Sho
    3: R-Elb
    4: R-Wr
    5: L-Sho
    6: L-Elb
    7: L-Wr
    8: R-Hip
    9: R-Knee
    10: R-Ank
    11: L-Hip
    12: L-Knee
    13: L-Ank
    14: R-Eye
    15: L-Eye
    16: R-Ear
    17: L-Ear
    ```
    
    - skeleton (not fixed): [[1,2],[1,5],[2,3],[3,4],[5,6],[6,7],[1,8],[8,9],[9,10],[1,11],[11,12],[12,13],[1,0],[0,14],[14,16],[0,15],[15,17],[2,17], [5,16]]    
    - Examples of visualization imgs
 
      <img src="https://user-images.githubusercontent.com/52263269/203120542-5b54b8ba-9577-49cd-aa66-4a15544faa8f.png" width="35%"></img>

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
    
  - Examples of visualization imgs
  
    <img src="https://user-images.githubusercontent.com/52263269/202661901-41e34c4d-5dca-48e2-8885-4711c19f1d66.png" width="70%"></img>

#### - Details of CMU Panoptic (Projected 2D keypoints from 3D keypoints)
  
##### - COCO19 keypoints version
    - Joints (19)

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
      
    - skeleton (not fixed): [[0,1],[0,3],[3,4],[4,5],[0,2],[2,6],[6,7],[7,8],[2,12],[12,13],[13,14],[0,9],[9,10],[10,11]]
    - Examples of visualization imgs
    
      <img src="https://user-images.githubusercontent.com/52263269/202973034-14198c77-ced2-4ad8-8d66-4393f9e03c25.png" width="70%"></img>

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

