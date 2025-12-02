# PTM4AD

# Paper Architecture
![Driving pipeline](Pics/ALL.jpg)

# Datasets
### Perception Datasets
| Dataset        | Year | Size    | 2D Det | 3D Det | 2D Seg | 3D Seg | Tracking | Lane Det |
|---------------|------|---------|--------|--------|--------|--------|----------|----------|
| **Onboard**   |      |         |        |        |        |        |          |          |
| nuScenes      | 2019 | 40K     | ✓      | ✓      | ✓      | ✓      | ✓        | ✓        |
| Cityscapes    | 2016 | 25K     | ✓      | ✓      | ✓      |        |          |          |
| BDD100K       | 2020 | 12M     | ✓      |        | ✓      |        | ✓        | ✓        |
| Waymo         | 2019 | 230K    | ✓      | ✓      | ✓      |        | ✓        |          |
| KITTI         | 2012 | 41K     | ✓      | ✓      |        |        |          |          |
| SYNTHIA       | 2016 | 13.4K   |        |        | ✓      |        |          |          |
| Apolloscape   | 2018 | 143,906 | ✓      | ✓      | ✓      | ✓      | ✓        |          |
| SemanticKITTI | 2019 | 43,552  |        |        |        | ✓      |          |          |
| Virtual KITTI | 2016 | 21,260  | ✓      |        | ✓      |        |          |          |
| VIPER         | 2017 | 254,064 | ✓      | ✓      | ✓      | ✓      | ✓        |          |
| GTA5          | 2016 | 24,966  |        |        | ✓      |        |          |          |
| Argoverse 2   | 2023 | 6M      | ✓      | ✓      |        |        | ✓        |          |
| Lane Det      | 2017 | 133,235 |        |        |        |        |          | ✓        |
| SHIFT         | 2022 | 2.5M    | ✓      | ✓      | ✓      |        | ✓        |          |
| CityPersons   | 2017 | 25K     | ✓      |        | ✓      |        |          |          |
| A2D2          | 2020 | 41,277  | ✓      | ✓      | ✓      |        |          |          |
| Foggy Cityscapes | 2018 | 20,550 | ✓    |        | ✓      |        |          |          |
| CamVid        | 2009 | 701     |        |        | ✓      |        |          |          |
| IDD           | 2019 | 10,004  |        |        | ✓      |        |          |          |
| CAOS          | 2022 | 13K     |        |        | ✓      |        |          |          |
| RADIATE       | 2021 | 44,140  | ✓      |        |        | ✓      |          |          |
| Virtual KITTI 2 | 2020 | 20,992 | ✓     | ✓      | ✓      |        | ✓        |          |
| KITTI-360     | 2021 | 150K    | ✓      | ✓      | ✓      | ✓      | ✓        |          |
| Dr(eye)ve     | 2018 | 555,000 |        |        | ✓      |        |          |          |
| ACDC          | 2021 | 4,006   |        |        | ✓      |        |          |          |
| GTSDB         | 2013 | 900     | ✓      |        |        |        |          |          |
| ONCE          | 2021 | 1M      | ✓      | ✓      |        |        |          |          |
| Caltech Ped   | 2009 | 250K    | ✓      |        |        |        |          |          |
| STF           | 2020 | 13,500  | ✓      | ✓      |        |        |          |          |
| **V2X**       |      |         |        |        |        |        |          |          |
| TUMTraf       | 2022 | 50,253  | ✓      | ✓      | ✓      |        | ✓        | ✓        |
| DAIR-V2X      | 2021 | 71,254  | ✓      | ✓      |        |        |          |          |
| V2XSet        | 2022 | 11,447  | ✓      | ✓      |        |        |          |          |
| V2V4Real      | 2023 | 40K     | ✓      | ✓      |        |        | ✓        |          |
| Rope3D        | 2022 | 50K     | ✓      | ✓      |        |        |          |          |
| V2X-Sim       | 2022 | 10K     | ✓      | ✓      | ✓      | ✓      | ✓        |          |
| V2VNet        | 2020 | 51.2K   | ✓      |        |        |        |          |          |
| T&J           | 2019 | 100     | ✓      | ✓      |        |        |          |          |
| Co-Percep     | 2020 | 10K     | ✓      | ✓      |        |        |          |          |
| DeepAccident  | 2023 | 285K    |        |        |        |        |          |          |
| LUMPI         | 2022 | 200K    | ✓      | ✓      | ✓      |        | ✓        |          |
| **Drone**     |      |         |        |        |        |        |          |          |
| UAVDT         | 2018 | 80K     | ✓      |        |        |        | ✓        |          |
| DroneVehicle  | 2021 | 28,439  | ✓      |        |        |        |          |          |
| **Others**    |      |         |        |        |        |        |          |          |
| Mapillary Vistas | 2017 | 25K  |        |        | ✓      |        |          |          |
| TT 100K       | 2016 | 100K    | ✓      |        |        |        |          |          |
| Pascal3D+     | 2014 | 30,899  | ✓      | ✓      | ✓      |        |          |          |
| WildDash      | 2018 | 1,800   |        |        | ✓      |        |          |          |
| TorontoCity   | 2016 | 56K     |        |        | ✓      |        |          |          |
| DAWN          | 2020 | 4,543   | ✓      |        |        |        |          |          |
| RAD           | 2019 | 60      |        |        | ✓      |        |          |          |
| STCrowd       | 2022 | 10,891  | ✓      | ✓      |        |        | ✓        |          |


### Prediction, Planning, and Control Datasets

| Dataset | Year | Size | Tasks |
|---------|------|-------|-------|
| Brain4Cars | 2015 | 2M frames | maneuver anticipation |
| JAAD | 2017 | 75K frames | pedestrian intention |
| Dr(eye)ve | 2018 | 500K frames | driver attention prediction |
| highD | 2018 | 45K km | trajectory prediction |
| PIE | 2019 | 293K frames | pedestrian intention |
| USyd | 2019 | 24K trajectories | driver intention |
| Argoverse | 2019 | 300K trajectories | trajectory prediction |
| Drive&Act | 2019 | 9.6M images | driver behavior recognition |
| DbNet | 2019 | 100 km | driver behavior recognition |
| D²CAV | 2020 | - | behavioral strategy |
| inD | 2020 | 11.5K trajectories | road user prediction |
| PePscenes | 2020 | 719 frames | pedestrian behavior prediction |
| openDD | 2020 | 84,774 trajectories | pedestrian behavior prediction |
| nuPlan | 2021 | 1.5K hours | motion planning |
| DriPE | 2021 | 10K images | driver behavior recognition |
| Speak2label | 2021 | 586 videos | attention prediction |
| CoCAtt | 2022 | 11.9 hours | attention prediction |
| exiD | 2022 | 16 hours | trajectory prediction |
| MONA | 2022 | 702K trajectories | trajectory prediction |
| Occ3D-nuScenes | 2024 | 40K frames | occupancy prediction |
| Occ3D-Waymo | 2024 | 200K frames | occupancy prediction |

### End-to-End Autonomous Driving Datasets

| Dataset | Year | Sensors | Content | Weather | Size | Location |
|---------|------|---------|----------|----------|--------|-----------|
| Udacity | 2016 | Camera, LiDAR, GNSS, Steering, Speed | Obstacles, Traffic, Roads | Sunny | 5h | Mountain View |
| Drive360 | 2019 | Camera, GNSS, Steering, Speed, Route | Obstacles, Traffic | Sunny, Rain | 55h | Switzerland |
| Comma.ai 2016 | 2016 | Camera, GNSS, Steering, Speed | - | Sunny | 7h15m | SF, USA |
| Comma.ai 2019 | 2019 | Camera, GNSS, Steering, Speed | - | Sunny | 30h | San Jose |
| BDD100 | 2018 | Camera, GNSS | Obstacles, Traffic | Sunny, Rain, Snow | 1100h | USA |
| Oxford RobotCar | 2019 | Camera, LiDAR, GNSS | Obstacles, Traffic | Sunny, Rain, Snow | 214h | Oxford |
| HDD | 2018 | Camera, LiDAR, GNSS, Steering, Speed, Nav | Obstacles | - | 104h | SF, USA |
| Brain4Cars | 2016 | Camera, GNSS, Steering, Speed | Obstacles | - | 1180 miles | USA |
| Li-Vi | 2018 | Camera, LiDAR, GNSS, Steering, Speed | - | - | 10h | China |
| DDD17 | 2017 | Event Cam, GNSS, Steering | Obstacles | Sunny, Rain, Snow | 12h | EU |
| A2D2 | 2020 | Camera, LiDAR, GNSS, Steering, Speed | Obstacles | Sunny, Rain | 390K frames | Germany |
| nuScenes | 2019 | Camera, LiDAR, GNSS | Obstacles | Sunny, Rain | 5.5h | Boston, Singapore |
| Waymo | 2019 | Camera, LiDAR, GNSS | Obstacles | Sunny, Rain | 5.5h | California |
| H3D | 2019 | Camera, LiDAR, GNSS, Steering, Speed | - | Sunny | N/A | Japan |
| HAD | 2019 | Camera, GNSS, Steering, Speed, Nav | Traffic | Sunny | 30h | SF |
| BIT | 2015 | Camera | Obstacles | Sunny | 9850 frames | Beijing |
| UA-DETRAC | 2015 | Camera | Obstacles | Sunny | 140K frames | Beijing, Tianjin |
| DFG | 2019 | Camera | Traffic | Sunny, Snow | 7K+8K | Slovenia |
| Bosch | 2017 | Camera | Traffic | Sunny | 8K | Germany |
| Tencent 100K | 2016 | Camera | Traffic | Sunny | 30K | China |
| LISA | 2012 | Camera | Traffic | Sunny | 20K | California |
| STSD | 2011 | Camera | Traffic | Sunny | 2503 | Sweden |
| GTSRB | 2013 | Camera | Traffic | Sunny, Snow | 50K | Germany |
| KUL | 2013 | Camera | Traffic | Sunny | 16K | Belgium |
| Caltech | 2009 | Camera | Obstacles | Sunny | 10h | California |
| CamVid | 2009 | Camera | Obstacles, Roads | Sunny | 22m | Cambridge |
| Ford | 2018 | Camera, LiDAR | Obstacles | Sunny | 66km | Michigan |
| KITTI | 2013 | Cam, LiDAR, GNSS | Obstacles | Sunny | 43K | Germany |
| CityScapes | 2016 | Camera, GNSS | Obstacles | Sunny | 25K | EU |
| Mapillary | 2017 | Camera | Obstacles | All | 25K | Germany |
| ApolloScape | 2018 | Cam, LiDAR | Obstacles | All | 147K | China |
| VERI-Wild | 2019 | Camera | Obstacles | All | 125–280h | China |
| D2-City | 2019 | Camera | Obstacles, Roads | All | 10K videos | China |
| DriveSeg | 2020 | Camera | Obstacles | Sunny | 500m | USA |

### Emerging: Language-Based Autonomous Driving Datasets

| Dataset | Year | Size | Tasks |
|---------|------|-------|--------|
| BDD-X | 2018 | 8.4M | reasoning, planning |
| Cityscapes-Ref | 2018 | 5K | object referring |
| TOUCHDOWN | 2019 | 9,326 | reasoning, navigation |
| Talk2Car | 2019 | 11,959 cmd | object referring |
| BDD-OIA | 2020 | 11,303 | explainable decision-making |
| CityFlow-NL | 2021 | 5,289 | object tracking |
| CARLA-NAV | 2022 | 83K | navigation |
| NuPrompt | 2023 | 34K | multi-object tracking |
| NuScenes-QA | 2023 | 460K QA | VQA |
| Refer-KITTI | 2023 | 6,650 | referring MOT |
| Driving LLMs | 2023 | 160K QA | VQA |
| DRAMA | 2023 | 17,785 | reasoning, VQA |
| Rank2Tell | 2023 | 116 | importance ranking |
| LamPilot | 2023 | 4,900 | planning |
| LangAuto CARLA | 2023 | 64K | closed-loop driving |
| NuScenes-MQA | 2023 | 1.4M QA | VQA |
| DriveMLM | 2023 | 280h | planning, control |
| DriveLM-nuScenes | 2023 | 4,871 | E2E driving |
| DriveCARLA | 2023 | 183K | E2E driving |
| LiDAR-text | 2023 | 420K / 280K | 3D captioning & grounding |
| Talk2BEV | 2023 | 20K QA | decision, intention, reasoning |
| NuScenes-MQA (2024) | 2024 | 1.4M QA | VQA |
| VLAAD | 2024 | 10,379 | VQA, reasoning |

## Simulators
| Simulator | Simulator |
|-----------|-----------|
| **CARLA** <br> https://carla.org/ | **MetaDrive** <br> https://github.com/metadriverse/metadrive |
| **AirSim** <br> https://github.com/microsoft/AirSim | **Colosseum** <br> https://github.com/CodexLabsLLC/Colosseum |
| **AWSIM** <br> https://github.com/tier4/AWSIM | **SUMO** <br> https://eclipse.dev/sumo/ |
| **Gazebo** <br> https://gazebosim.org/ | **NVIDIA DRIVE Sim** <br> https://www.nvidia.com/en-us/self-driving-cars/simulation/ |
| **Siemens PreScan** <br> https://plm.sw.siemens.com/en-US/simcenter/autonomous-vehicle-solutions/prescan/ | **VTD (Hexagon)** <br> https://hexagon.com/products/virtual-test-drive |
| **Apollo Simulation Platform** <br> https://developer.apollo.auto/platform/simulation_cn.html | **Highway-env** <br> https://github.com/Farama-Foundation/HighwayEnv |

## Open Source
| Name | Link | Code |
|------|------|------|
| Semantics-aware visual localization under challenging perceptual conditions | [link](http://ais.informatik.uni-freiburg.de/publications/papers/naseer17icra.pdf) | none |
| Semantic pose verification for outdoor visual localization with self-supervised contrastive learning | [link](https://openaccess.thecvf.com/content/CVPR2022W/L3D-IVU/papers/Orhan_Semantic_Pose_Verification_for_Outdoor_Visual_Localization_With_Self-Supervised_Contrastive_CVPRW_2022_paper.pdf) | none |
| Accurate visual localization for automotive applications | [link](https://openaccess.thecvf.com/content_CVPRW_2019/papers/WAD/Brosh_Accurate_Visual_Localization_for_Automotive_Applications_CVPRW_2019_paper.pdf) | [code](https://github.com/getnexar/Nexar-Visual-Localization) |
| Slice transformer and self-supervised learning for 6dof localization in 3d point cloud maps | [link](https://arxiv.org/pdf/2301.08957) | none |
| Lip-loc: Lidar image pretraining for cross-modal localization | [link](https://openaccess.thecvf.com/content/WACV2024W/LLVM-AD/papers/Shubodh_LIP-Loc_LiDAR_Image_Pretraining_for_Cross-Modal_Localization_WACVW_2024_paper.pdf) | none |
| Contrastive learning-based place descriptor representation for cross-modality place recognition | [link](https://www.sciencedirect.com/science/article/pii/S1566253525004245?ref=pdf_download&fr=RR-2&rr=9a711892792de300) | none |
| Global visual localization in lidar-maps through shared 2d-3d embedding space | [link](https://arxiv.org/pdf/1910.04871) | none |
| Vxp: Voxel-cross-pixel large-scale image-lidar place recognition | [link](https://arxiv.org/pdf/2403.14594) | [code](https://github.com/yunjinli/vxp) |
| Location-aware self-supervised transformers for semantic segmentation | [link](https://openaccess.thecvf.com/content/WACV2024/papers/Caron_Location-Aware_Self-Supervised_Transformers_for_Semantic_Segmentation_WACV_2024_paper.pdf) | none |
| Detco: Unsupervised contrastive learning for object detection | [link](https://openaccess.thecvf.com/content/ICCV2021/papers/Xie_DetCo_Unsupervised_Contrastive_Learning_for_Object_Detection_ICCV_2021_paper.pdf) | [code](https://github.com/open-mmlab/mmselfsup) |
| Pointcontrast: Unsupervised pre-training for 3d point cloud understanding | [link](https://arxiv.org/pdf/2007.10985) | [code](https://github.com/facebookresearch/PointContrast) |
| Contrastive object-level pre-training with spatial noise curriculum learning | [link](https://arxiv.org/pdf/2111.13651) | [code](https://github.com/ChenhongyiYang/CCOP) |
| Univip: A unified framework for self-supervised visual pre-training | [link](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_UniVIP_A_Unified_Framework_for_Self-Supervised_Visual_Pre-Training_CVPR_2022_paper.pdf) | [code](https://github.com/utkutpcgl/UniVIP) |
| Unsupervised object-level representation learning from scene images | [link](https://arxiv.org/pdf/2106.11952) | [code](https://www.mmlab-ntu.com/project/orl/) |
| Codo: Contrastive learning with downstream background invariance for detection | [link](https://openaccess.thecvf.com/content/CVPR2022W/L3D-IVU/papers/Zhao_CoDo_Contrastive_Learning_With_Downstream_Background_Invariance_for_Detection_CVPRW_2022_paper.pdf) | none |
| Aligning pretraining for detection via object-level contrastive learning | [link](https://arxiv.org/pdf/2106.02637) | [code](https://github.com/ueoo/SoCo) |
| Multisiam: Self-supervised multi-instance siamese representation learning for autonomous driving | [link](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_MultiSiam_Self-Supervised_Multi-Instance_Siamese_Representation_Learning_for_Autonomous_Driving_ICCV_2021_paper.pdf) | [code](https://github.com/Kaichen1998/MultiSiam) |
| Proposalcontrast: Unsupervised pre-training for lidar-based 3d object detection | [link](https://arxiv.org/pdf/2207.12654) | [code](https://github.com/yinjunbo/ProposalContrast) |
| Temporal consistent 3d lidar representation learning for semantic perception in autonomous driving | [link](https://openaccess.thecvf.com/content/CVPR2023/papers/Nunes_Temporal_Consistent_3D_LiDAR_Representation_Learning_for_Semantic_Perception_in_CVPR_2023_paper.pdf) | [code](https://github.com/PRBonn/TARL) |
| Patchcontrast: Self supervised pre-training for 3d object detection | [link](https://openaccess.thecvf.com/content/CVPR2025W/WAD/papers/Shrout_PatchContrast_Self-Supervised_Pre-Training_for_3D_Object_Detection_CVPRW_2025_paper.pdf) | none |
| Exploring geometry-aware contrast and clustering harmonization for self-supervised 3d object detection | [link](https://openaccess.thecvf.com/content/ICCV2021/papers/Liang_Exploring_Geometry-Aware_Contrast_and_Clustering_Harmonization_for_Self-Supervised_3D_Object_ICCV_2021_paper.pdf) | [code](https://github.com/hustvl/GCC-3D) |
| Segcontrast: 3d point cloud feature representation learning through self supervised segment discrimination | [link](https://drive.google.com/file/d/1mJS5lO-vbdbbwexhVkManlUyQic08adN/view) | [code](https://github.com/PRBonn/segcontrast) |
| Psa-ssl: Pose and size-aware self supervised learning on lidar point clouds | [link](https://openaccess.thecvf.com/content/CVPR2025/papers/Nisar_PSA-SSL_Pose_and_Size-aware_Self-Supervised_Learning_on_LiDAR_Point_Clouds_CVPR_2025_paper.pdf) | none |
| Self-supervised pretraining for point cloud object detection in autonomous driving | [link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9922494) | none |
| Cmae-3d: Contrastive masked autoencoders for self-supervised 3d object detection | [link](https://link.springer.com/article/10.1007/s11263-024-02313-2) | none |
| Lidar-guided geometric pretraining for vision-centric 3d object detection | [link](https://link.springer.com/article/10.1007/s11263-025-02351-4) | [code](https://github.com/OpenDriveLab/Birds-eye-view-Perception) |
| Occfeat: Self-supervised occupancy feature prediction for pretraining bev segmentation networks | [link](https://openaccess.thecvf.com/content/CVPR2024W/WAD/papers/Sirko-Galouchenko_OccFeat_Self-supervised_Occupancy_Feature_Prediction_for_Pretraining_BEV_Segmentation_Networks_CVPRW_2024_paper.pdf) | none |
| Image-to-lidar self-supervised distillation for autonomous driving data | [link](https://openaccess.thecvf.com/content/CVPR2022/papers/Sautier_Image-to-Lidar_Self-Supervised_Distillation_for_Autonomous_Driving_Data_CVPR_2022_paper.pdf) | [code](https://github.com/valeoai/SLidR) |
| Self-supervised image-to-point distillation via semantically tolerant contrastive loss | [link](https://openaccess.thecvf.com/content/CVPR2023/papers/Mahmoud_Self-Supervised_Image-to-Point_Distillation_via_Semantically_Tolerant_Contrastive_Loss_CVPR_2023_paper.pdf) | none |
| Unim 2 ae: Multi-modal masked autoencoders with unified 3d representation for 3d perception in autonomous driving | [link](https://arxiv.org/pdf/2308.10421) | [code](https://github.com/hollow-503/UniM2AE) |
| Learning shared rgb-d fields: Unified self-supervised pre-training for label-efficient lidar-camera 3d perception | [link](https://arxiv.org/pdf/2405.17942) | [code](https://github.com/Xiaohao-Xu/Unified-Pretrain-AD) |
| Pf3det: A prompted foundation feature assisted visual lidar 3d detector | [link](https://openaccess.thecvf.com/content/CVPR2025W/WDFM-AD/papers/Li_PF3Det_A_Prompted_Foundation_Feature_Assisted_Visual_LiDAR_3D_Detector_CVPRW_2025_paper.pdf) | none |
| Vlc fusion: Vision-language conditioned sensor fusion for robust object detection | [link](https://arxiv.org/pdf/2505.12715) | [code](https://github.com/aditya-taparia/VLCFusion) |
| Integrating language-derived appearance elements with visual cues in pedestrian detection | [link](https://arxiv.org/pdf/2311.01025) | [code](https://github.com/kimhj709/LDAE) |
| Vlpd: Context-aware pedestrian detection via vision-language semantic self-supervision | [link](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_VLPD_Context-Aware_Pedestrian_Detection_via_Vision-Language_Semantic_Self-Supervision_CVPR_2023_paper.pdf) | [code](https://github.com/lmy98129/VLPD) |
| Representation learning for visual object tracking by masked appearance transfer | [link](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_Representation_Learning_for_Visual_Object_Tracking_by_Masked_Appearance_Transfer_CVPR_2023_paper.pdf) | [code](https://github.com/difhnp/MAT) |
| Dropmae: Masked autoencoders with spatial-attention dropout for tracking tasks | [link](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_DropMAE_Masked_Autoencoders_With_Spatial-Attention_Dropout_for_Tracking_Tasks_CVPR_2023_paper.pdf) | [code](https://github.com/yjw0224/DropMAE) |
| Generalized relation modeling for transformer tracking | [link](https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Generalized_Relation_Modeling_for_Transformer_Tracking_CVPR_2023_paper.pdf) | [code](https://github.com/Little-Podi/GRM) |
| Learning correspondence from the cycle-consistency of time | [link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Learning_Correspondence_From_the_Cycle-Consistency_of_Time_CVPR_2019_paper.pdf) | [code](https://github.com/xiaolonw/TimeCycle) |
| Self-supervised representation learning from temporal ordering of automated driving sequences | [link](https://arxiv.org/pdf/2302.09043) | none |
| Traj-mae: Masked autoencoders for trajectory prediction | [link](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_Traj-MAE_Masked_Autoencoders_for_Trajectory_Prediction_ICCV_2023_paper.pdf) | [code](https://jiazewang.com/projects/trajmae.html) |
| Sept: Towards efficient scene representation learning for motion prediction | [link](https://arxiv.org/pdf/2309.15289) | none |
| Social-ssl: Self-supervised cross-sequence representation learning based on transformers for multi-agent trajectory prediction | [link](https://basiclab.lab.nycu.edu.tw/assets/Social-SSL.pdf) | [code](https://github.com/Sigta678/Social-SSL) |
| Precln: Pretrained based contrastive learning network for vehicle trajectory prediction | [link](https://link.springer.com/article/10.1007/s11280-022-01121-3) | none |
| Rmp: A random mask pretrain framework for motion prediction | [link](https://arxiv.org/pdf/2309.08989) | [code](https://github.com/KTH-RPL/RMP) |
| Smart pretrain: Model-agnostic and dataset-agnostic representation learning for motion prediction | [link](https://arxiv.org/pdf/2410.08669) | [code](https://github.com/youngzhou1999/SmartPretrain) |
| Behavior-pred: A semantic-enhanced trajectory pre-training framework for motion forecasting | [link](https://www.sciencedirect.com/science/article/pii/S1566253525001599?ref=pdf_download&fr=RR-2&rr=9a711a9ea93c043e) | none |
| Redmotion: Motion prediction via redundancy reduction | [link](https://arxiv.org/pdf/2306.10840) | [code](https://github.com/kit-mrt/future-motion) |
| Exploiting map information for self-supervised learning in motion forecasting | [link](https://arxiv.org/pdf/2210.04672) | none |
| Forecast-mae: Self-supervised pretraining for motion forecasting with masked autoencoders | [link](https://openaccess.thecvf.com/content/ICCV2023/papers/Cheng_Forecast-MAE_Self-supervised_Pre-training_for_Motion_Forecasting_with_Masked_Autoencoders_ICCV_2023_paper.pdf) | [code](https://github.com/jchengai/forecast-mae) |
| Multi-agent driving behavior prediction across different scenarios with self-supervised domain knowledge | [link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9564510) | none |
| Social-ssl: Self-supervised cross-sequence representation learning based on transformers for multi-agent trajectory prediction | [link](https://basiclab.lab.nycu.edu.tw/assets/Social-SSL.pdf) | [code](https://github.com/Sigta678/Social-SSL) |
| Can you text what is happening? integrating pre-trained language encoders into trajectory prediction models for autonomous driving | [link](https://arxiv.org/pdf/2309.05282) | none |
| Large language models powered context-aware motion prediction in autonomous driving | [link](https://arxiv.org/pdf/2403.11057) | none |
| Lg-traj: Llm guided pedestrian trajectory prediction | [link](https://arxiv.org/pdf/2403.11057) | none |
| Traj-llm: A new exploration for empowering trajectory prediction with pre-trained large language models | [link](https://arxiv.org/pdf/2405.04909) | none |
| Lc-llm: Explainable lane-change intention and trajectory predictions with large language models | [link](https://www.sciencedirect.com/science/article/pii/S2772424725000101?ref=pdf_download&fr=RR-2&rr=9a711b5f9a41af12) | [code](https://github.com/Pemixing/LCLLM) |
| Gpt-driver: Learning to drive with gpt | [link](https://arxiv.org/pdf/2310.01415) | [code](https://github.com/PointsCoder/GPT-Driver) |
| Driving with llms: Fusing object-level vector modality for explainable autonomous driving | [link](https://arxiv.org/pdf/2310.01957) | [code](https://github.com/wayveai/Driving-with-LLMs) |
| Dilu: A knowledge-driven approach to autonomous driving with large language models | [link](https://arxiv.org/pdf/2309.16292) | [code](https://github.com/PJLab-ADG/DiLu) |
| Planagent: A multi-modal large language agent for closed-loop vehicle motion planning | [link](https://arxiv.org/pdf/2406.01587) | none |
| Empowering autonomous driving with large language models: A safety perspective | [link](https://arxiv.org/pdf/2312.00812) | none |
| A language agent for autonomous driving | [link](https://arxiv.org/pdf/2311.10813) | [code](https://github.com/usc-driver/Agent-Driver) |
| Drive as veteran: Fine-tuning of an onboard large language model for highway autonomous driving | [link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10588851) | none |
| Hybrid reasoning based on large language models for autonomous car driving | [link](https://arxiv.org/pdf/2402.13602) | [code](https://github.com/Mehdiazarafza/Hybrid-reasoning) |
| Surrealdriver: Designing llm-powered generative driver agent framework based on human drivers’ driving-thinking data | [link](https://arxiv.org/pdf/2309.13193) | [code](https://github.com/AIR-DISCOVER/Driving-Thinking-Dataset) |
| Drive like a human: Rethinking autonomous driving with large language models | [link](https://arxiv.org/pdf/2307.07162) | [code](https://github.com/PJLab-ADG/DriveLikeAHuman) |
| Learning autonomous driving tasks via human feedbacks with large language models | [link](https://aclanthology.org/2024.findings-emnlp.287.pdf) | none |
| Chatgpt as your vehicle co-pilot: An initial attempt | [link](https://www.researchgate.net/profile/Zhengbing-He/publication/374800815_ChatGPT_as_Your_Vehicle_Co-Pilot_An_Initial_Attempt/links/65326d5124bbe32d9a5677f2/ChatGPT-as-Your-Vehicle-Co-Pilot-An-Initial-Attempt.pdf) | none |
| Drive as you speak: Enabling human-like interaction with large language models in autonomous vehicles | [link](https://openaccess.thecvf.com/content/WACV2024W/LLVM-AD/papers/Cui_Drive_As_You_Speak_Enabling_Human-Like_Interaction_With_Large_Language_WACVW_2024_paper.pdf) | none |
| Human-centric autonomous systems with llms for user command reasoning | [link](https://openaccess.thecvf.com/content/WACV2024W/LLVM-AD/papers/Yang_Human-Centric_Autonomous_Systems_With_LLMs_for_User_Command_Reasoning_WACVW_2024_paper.pdf) | [code](https://github.com/KTH-RPL/DriveCmd_LLM) |
| Drivellm: Charting the path toward full autonomous driving with large language models | [link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10297415) | [code](https://github.com/DriveLLM/DriveLLM) |
| Llm-assist: Enhancing closed-loop planning with language-based reasoning | [link](https://arxiv.org/pdf/2401.00125) | [code](https://llmassist.github.io/) |
| Towards human-centric autonomous driving: A fast-slow architecture integrating large language model guidance with reinforcement learning | [link](https://arxiv.org/pdf/2505.06875) | none |
| Continuously learning, adapting, and improving: A dual-process approach to autonomous driving | [link](https://arxiv.org/pdf/2405.15324) | [code](https://pjlab-adg.github.io/LeapAD/) |
| Leapvad: A leap in autonomous driving via cognitive perception and dual-process thinking | [link](https://arxiv.org/pdf/2501.08168) | none |
| Asynchronous large language model enhanced planner for autonomous driving | [link](https://arxiv.org/pdf/2406.14556) | [code](https://github.com/memberRE/AsyncDriver) |
| Highwayllm: Decision making and navigation in highway driving with rl-informed language model | [link](https://arxiv.org/pdf/2405.13547) | none |
| Lord: Large models based opposite reward design for autonomous driving | [link](https://arxiv.org/pdf/2403.18965) | none |
| Vlm-rl: A unified vision language models and reinforcement learning framework for safe autonomous driving | [link](https://arxiv.org/pdf/2412.15544) | [code](https://www.huang-zilin.com/VLM-RL-website/) |
| Revolve: Reward evolution with large language models using human feedback | [link](https://arxiv.org/pdf/2406.01309) | [code](https://github.com/RishiHazra/REvolve/tree/main) |
| Clip-rldrive: Human-aligned autonomous driving via clip-based reward shaping in reinforcement learning | [link](https://arxiv.org/pdf/2412.16201) | none |
| In-context learning for automated driving scenarios | [link](https://arxiv.org/pdf/2405.04135v1) | [code](https://github.com/JingYue2000/In-context_Learning_for_Automated_Driving) |
| Tell-drive: Enhancing autonomous driving with teacher llm-guided deep reinforcement learning | [link](https://www.researchgate.net/profile/Jiaqi-Liu-98/publication/388685433_TeLL-Drive_Enhancing_Autonomous_Driving_with_Teacher_LLM-Guided_Deep_Reinforcement_Learning/links/67a2d07e461fb56424c8a2c4/TeLL-Drive-Enhancing-Autonomous-Driving-with-Teacher-LLM-Guided-Deep-Reinforcement-Learning.pdf) | none |
| Autoreward: Closed-loop reward design with large language models for autonomous driving | [link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10735123) | none |
| Languagempc: Large language models as decision makers for autonomous driving | [link](https://arxiv.org/pdf/2310.03026) | [code](https://github.com/YiqinYang/LanguageMPC) |
| Vlm-mpc: Vision language foundation model (vlm)-guided model predictive controller (mpc) for autonomous driving | [link](https://arxiv.org/pdf/2408.04821) | none |
| Llm adaptive pid control for b5g truck platooning systems | [link](https://www.mdpi.com/1424-8220/23/13/5899) | none |
| A versatile and efficient reinforcement learning framework for autonomous driving | [link](https://arxiv.org/pdf/2110.11573) | none |
| Label efficient visual abstractions for autonomous driving | [link](https://arxiv.org/pdf/2005.10091) | [code](https://github.com/autonomousvision/visual_abstractions) |
| Segmented encoding for sim2real of rl-based end-to-end autonomous driving | [link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9827374) | none |
| Rad: Training an endto-end driving policy via large-scale 3dgs-based reinforcement learning | [link](https://arxiv.org/pdf/2502.13144) | none |
| Policy pre-training for autonomous driving via self-supervised geometric modeling | [link](https://arxiv.org/pdf/2301.01006) | [code](https://github.com/OpenDriveLab/PPGeo) |
| Learning to drive using sparse imitation reinforcement learning | [link](https://arxiv.org/pdf/2205.12128) | [code](https://metadriverse.github.io/ACO/) |
| End-to-end learning of driving models from large-scale video datasets | [link](https://openaccess.thecvf.com/content_cvpr_2017/papers/Xu_End-To-End_Learning_of_CVPR_2017_paper.pdf) | [code](https://github.com/gy20073/BDD_Driving_Model/) |
| Learning to drive by watching youtube videos: Action-conditioned contrastive policy pretraining | [link](https://arxiv.org/pdf/2204.02393) | none |
| Task-induced representation learning | [link](https://arxiv.org/pdf/2204.11827) | [code](https://clvrai.github.io/tarp/) |
| Visual place recognition pre-training for end-to-end trained autonomous driving agent | [link](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10313277) | [code](https://github.com/Shubhamcl/vpr_pretrained_agent/) |
| Drivegpt4: Interpretable end-to-end autonomous driving via large language model | [link](https://arxiv.org/pdf/2310.01412) | [code](https://github.com/Cecret3350/DriveGPT4) |
| Rag-driver: Generalisable driving explanations with retrieval-augmented in-context learning in multi-modal large language model | [link](https://arxiv.org/pdf/2402.10828) | none |
| X-driver: Explainable autonomous driving with vision-language models | [link](https://arxiv.org/pdf/2505.05098) | none |
| Emma: End-to-end multimodal model for autonomous driving | [link](https://arxiv.org/pdf/2410.23262) | none |
| Openemma: Open-source multimodal model for end-to-end autonomous driving | [link](https://openaccess.thecvf.com/content/WACV2025W/LLVMAD/papers/Xing_OpenEMMA_Open-Source_Multimodal_Model_for_End-to-End_Autonomous_Driving_WACVW_2025_paper.pdf) | [code](https://github.com/michigan-traffic-lab/LightEMMA) |
| Lightemma: Lightweight end-to-end multimodal model for autonomous driving | [link](https://arxiv.org/pdf/2505.00284) | [code](https://github.com/michigan-traffic-lab/LightEMMA) |
| Reason2drive: Towards interpretable and chain-based reasoning for autonomous driving | [link](https://arxiv.org/pdf/2312.03661) | [code](https://github.com/Haoyi-Niu/Reason2Drive) |
| Making large language models better planners with reasoning-decision alignment | [link](https://arxiv.org/pdf/2408.13890) | none |
| Driver1: Bridging reasoning and planning in vlms for autonomous driving with reinforcement learning | [link](https://arxiv.org/pdf/2506.18234) | none |
| Drivelm: Driving with graph visual question answering | [link](https://arxiv.org/pdf/2312.14150) | [code](https://github.com/OpenDriveLab/DriveLM) |
| Multi-modal gpt-4 aided action planning and reasoning for self-driving vehicles | [link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10446745) | none |
| Simplellm4ad: An end-to-end vision-language model with graph visual question answering for autonomous driving | [link](https://arxiv.org/pdf/2407.21293) | none |
| Rad: Retrieval-augmented decision-making of meta-actions with vision-language models in autonomous driving | [link](https://openaccess.thecvf.com/content/CVPR2025W/WDFM-AD/papers/Wang_RAD_Retrieval-Augmented_Decision-Making_of_Meta-Actions_with_Vision-Language_Models_in_Autonomous_CVPRW_2025_paper.pdf) | none |
| Lmdrive: Closed-loop end-to-end driving with large languagemodels | [link](https://openaccess.thecvf.com/content/CVPR2024/papers/Shao_LMDrive_Closed-Loop_End-to-End_Driving_with_Large_Language_Models_CVPR_2024_paper.pdf) | [code](https://github.com/opendrivelab/LMDrive) |
| Bevdriver: Leveraging bev maps in llms for robust closed-loop driving | [link](https://arxiv.org/pdf/2503.03074) | [code](https://github.com/intelligent-vehicles/BEVDriver) |
| Is a 3d-tokenized llm the key to reliable autonomous driving? | [link](https://arxiv.org/pdf/2405.18361) | none |
| S4-driver: Scalable self-supervised driving multimodal large language model with spatio-temporal visual representation | [link](https://openaccess.thecvf.com/content/CVPR2025/papers/Xie_S4-Driver_Scalable_Self-Supervised_Driving_Multimodal_Large_Language_Model_with_Spatio-Temporal_CVPR_2025_paper.pdf) | none |
| Tokenize the world into object-level knowledge to address long-tail events in autonomous driving | [link](https://arxiv.org/pdf/2407.00959) | none |
| Drive as veteran: Fine-tuning of an onboard large language model for highway autonomous driving | [link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10588851) | none |
| Think-driver: From driving-scene understanding to decision-making with vision language models | [link](https://mllmav.github.io/papers/Think-Driver:%20From%20Driving-Scene%20Understanding%20to%20Decision-Making%20with%20Vision%20Language%20Models.pdf) | [code](https://github.com/TRAILab/Think-Driver) |
| Drivemlm: Aligning multi-modal large language models with behavioral planning states for autonomous driving | [link](https://arxiv.org/pdf/2312.09245) | [code](https://github.com/openGVLab/DriveMLM) |
| Drivemoe: Mixture-of-experts for vision-language-action model in end-to-end autonomous driving | [link](https://arxiv.org/pdf/2505.16278) | none |
| Orion: A holistic end-toend autonomous driving framework by vision-language instructed action generation | [link](https://arxiv.org/pdf/2503.19755) | none |
| Recogdrive: A reinforced cognitive framework for end-to-end autonomous driving | [link](https://arxiv.org/pdf/2506.08052) | [code](https://github.com/xiaomi-research/recogdrive) |
| Diffvla: Vision-language guided diffusion planning for autonomous driving | [link](https://arxiv.org/pdf/2505.19381) | none |
| Vdt-auto: End-to-end autonomous driving with vlm-guided diffusion transformers | [link](https://arxiv.org/pdf/2502.20108) | none |
| Opendrivevla: Towards end-to-end autonomous driving with large vision language action model | [link](https://arxiv.org/pdf/2503.23463) | none |
| Autovla: A vision-language-action model for end-to-end autonomous driving with adaptive reasoning and reinforcement finetuning | [link](https://arxiv.org/pdf/2506.13757) | [code](https://github.com/ucla-mobility/AutoVLA) |
| Drivevlm: The convergence of autonomous driving and large vision-language models | [link](https://arxiv.org/pdf/2402.12289) | [code](https://github.com/Tsinghua-MARS-Lab/DriveVLM) |
| Solve: Synergy of language-vision and end-to-end networks for autonomous driving | [link](https://openaccess.thecvf.com/content/CVPR2025/papers/Chen_SOLVE_Synergy_of_Language-Vision_and_End-to-End_Networks_for_Autonomous_Driving_CVPR_2025_paper.pdf) | none |
| Senna: Bridging large vision-language models and end-to-end autonomous driving | [link](https://arxiv.org/pdf/2410.22313) | [code](https://github.com/hustvl/Senna) |
| Dme-driver: Integrating human decision logic and 3d scene perception in autonomous driving | [link](https://ojs.aaai.org/index.php/AAAI/article/view/32346) | none |
| Aln-p3: Unified language alignment for perception, prediction, and planning in autonomous driving | [link](https://arxiv.org/pdf/2505.15158) | none |
| Vlm-ad: End-to-end autonomous driving through vision-language model supervision | [link](https://arxiv.org/pdf/2412.14446) | none |
| Vlp: Vision language planning for autonomous driving | [link](https://openaccess.thecvf.com/content/CVPR2024/papers/Pan_VLP_Vision_Language_Planning_for_Autonomous_Driving_CVPR_2024_paper.pdf) | [code](https://github.com/IcebearZhang/VLP) |
