A Robust Driver Emotion Recognition Method Based on High-Purity Feature Separation
====

Driver drowsiness detection is of great significance  in improving driving safety and has been widely studied in recent  years.  However, some existing methods have not fully utilized  the drowsiness-related information, and some methods are susceptible  to interference from the redundant information of input  data.  To address these issues, a video-based driver drowsiness  detection method according to the key facial features including  facial landmarks and local facial areas (VBFLLFA) is proposed  in this paper.  In order to fully utilize the key facial features  related to drowsiness and exclude the interference of redundant  information, the head movement information is obtained through  facial landmark analysis and the movement information of eyes  and mouth is acquired from the local facial areas.  And the  spatial filtering based on the common spatial pattern (CSP)  algorithm is introduced to improve the discrimination of different  classes of samples.  To adequately extract the temporal and spatial  features, a two-branch multi-head attention (TB-MHA) module  is designed in this paper.  Furthermore, the center loss with center  vector distance penalty is introduced to further improve the  discrimination of different classes of samples in the feature space.

Multiple light intensities driver emotion recognition (MLI-DER) dataset
-------

<div align="center">

| Data acquisition system

| ![Image](https://github.com/Baiyang9886/Driver-emotion-recognition/blob/main/setup.jpg) 
| Fig. 1 The data acquisition system of the MLI-DER dataset.  |

</div>

In this work, we specifically create the  video-based driver drowsiness detection (VBDDD) dataset to  evaluate the effectiveness of the proposed video-based driver  drowsiness detection method.  Different from other drowsiness  detection datasets, each sample in the VBDDD dataset is an  accurately segmented video, and these samples were labeled  either drowsiness or no drowsiness.  If the driver is drowsy  in some frames of the video, then this video is labeled as “drowsiness”.  While, if the driver is not drowsy in each frame  of the video, then the video is labeled as “no drowsiness”.  Two example frames of this dataset are shown in Fig. 6 (a). 

The data acquisition system includes an ordinary RGB camera (Logitech C920 Pro), a simulated driving system (Logitech G29), and a computer (with 1 NVIDIA GTX 2080 Ti graphic  card) (as shown in Fig. 5). The virtual driving environment is  constructed based on Carla 0.9.12.  In this experiment, a total  of 37 volunteers are invited for data collection, and their  ages range from 21 to 37 years old, including 25 males and 
12 females.  During the data collection process, the experimental  subject is first asked to drive a car in a virtual driving  environment through the simulated driving system, and then  perform drowsy actions according to the operator’s prompts.  In order to make the dataset VBDDD more similar to real  driving scenes, we create three different intensity lighting  conditions (dim, normal, and bright) by adjusting the lights in  the laboratory, and collect the video data of each experimental  subject under each light condition.  Finally, a total of 558 video  samples ranging in length from 3 s to 50 s are obtained.  The  frame rate of each video sample is 30, and the resolution is 640 × 480 pixels.  In the experiments of this study, the samples  of 10% experimental subjects are selected as the test set and  the samples of all remaining subjects are taken as the training  set.

### Dataset download link
The VBDDD dataset has been publicly released to all researchers of the relevant fields. The download link for the dataset is 
https://pan.baidu.com/s/1qxRKT_ydBDVpCE5-OSgP2Q?pwd=4kna
Extraction code: 4kna

### Citation
(1) APA

L. Yang, H. Yang, H. Wei, Z. Hu and C. Lv, "Video-Based Driver Drowsiness Detection With Optimised Utilization of Key Facial Features," in IEEE Transactions on Intelligent Transportation Systems, vol. 25, no. 7, pp. 6938-6950, July 2024, doi: 10.1109/TITS.2023.3346054.

(2) BibTeX

@ARTICLE{10382460,
  author={Yang, Lie and Yang, Haohan and Wei, Henglai and Hu, Zhongxu and Lv, Chen},
  journal={IEEE Transactions on Intelligent Transportation Systems}, 
  title={Video-Based Driver Drowsiness Detection With Optimised Utilization of Key Facial Features}, 
  year={2024},
  volume={25},
  number={7},
  pages={6938-6950},
  keywords={Feature extraction;Electroencephalography;Mouth;Vehicles;Physiology;Interference;Facial features;Driver drowsiness detection;multi-head attention;facial landmarks;local facial areas},
  doi={10.1109/TITS.2023.3346054}}
