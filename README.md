# End-to-End-3D-Reconstruction-Paper-List
Personal list. With relevant research advancing fast and branching out widely, I'll only add papers meeting my needs hereafter. 

---
- [Cross View](#cross-view)
- [Pose Estimation](#pose-estimation)
- [3D Reconstruction](#3d-reconstruction)
- [Segmentation](#segmentation)
- [Dynamic](#dynamic)
- [SLAM](#slam)
- [Novel View Synthesis](#novel-view-synthesis)
---
## Cross View
* CroCo: Self-Supervised Pre-training for 3D Vision Tasks by Cross-View Completion [[NeurIPS 2022](https://arxiv.org/pdf/2210.10716)] [[croco](https://github.com/naver/croco)]

* CroCo v2: Improved Cross-view Completion Pre-training for Stereo Matching and Optical Flow [[ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Weinzaepfel_CroCo_v2_Improved_Cross-view_Completion_Pre-training_for_Stereo_Matching_and_ICCV_2023_paper.pdf)] [[croco](https://github.com/naver/croco)]

* 3D-Consistent Image Inpainting with Diffusion Models [[arXiv 2024](https://arxiv.org/pdf/2412.05881)] [[croco-diff](https://github.com/naver/croco-diff)]

* Alligat0R: Pre-Training through Co-Visibility Segmentation for Relative Camera Pose Regression [[arXiv 2025](https://arxiv.org/pdf/2503.07561)] [[]()]
  
## Pose Estimation
* Cameras as Rays: Pose Estimation via Ray Diffusion [[ICLR 2024](https://arxiv.org/pdf/2402.14817)] [[RayDiffusion](https://github.com/jasonyzhang/RayDiffusion)]

* Cameras as Relative Positional Encoding [[arXiv 2025](https://arxiv.org/pdf/2507.10496)] [[prope](https://www.liruilong.cn/prope/)]

* Reloc3r: Large-Scale Training of Relative Camera Pose Regression for Generalizable, Fast, and Accurate Visual Localization [[CVPR 2025](https://arxiv.org/pdf/2412.08376)] [[reloc3r](https://github.com/ffrivera0/reloc3r)]

## 3D Reconstruction
* Visual Geometry Grounded Deep Structure From Motion [[CVPR 2024](https://arxiv.org/pdf/2312.04563)] [[vggsfm](https://github.com/facebookresearch/vggsfm)]

* DUSt3R: Geometric 3D Vision Made Easy [[CVPR 2024](https://arxiv.org/pdf/2312.14132)] [[dust3r](https://github.com/naver/dust3r)]
  
* Grounding Image Matching in 3D with MASt3R [[ECCV 2024](https://arxiv.org/pdf/2406.09756)] [[mast3r](https://github.com/naver/mast3r)]

* MASt3R-SfM: a Fully-Integrated Solution for Unconstrained Structure-from-Motion [[arXiv 2024](https://arxiv.org/pdf/2409.19152)] [[mast3r](https://github.com/naver/mast3r)]

* 3D Reconstruction with Spatial Memory [[3DV 2025](https://arxiv.org/pdf/2408.16061)] [[spann3r](https://github.com/HengyiWang/spann3r)]

* MV-DUSt3R+: Single-Stage Scene Reconstruction from Sparse Views In 2 Seconds [[CVPR 2025](https://arxiv.org/pdf/2412.06974)] [[mv-dust3rp](https://mv-dust3rp.github.io/)]

* Continuous 3D Perception Model with Persistent State [[CVPR 2025](https://arxiv.org/pdf/2501.12387)] [[cut3r](https://cut3r.github.io/)]

* Fast3R: Towards 3D Reconstruction of 1000+ Images in One Forward Pass [[CVPR 2025](https://arxiv.org/pdf/2501.13928)] [[fast3r-3d](https://fast3r-3d.github.io/)]

* Light3R-SfM: Towards Feed-forward Structure-from-Motion [[arXiv 2025](https://arxiv.org/pdf/2501.14914)] [[]()]

* MUSt3R: Multi-view Network for Stereo 3D Reconstruction [[arXiv 2025](https://arxiv.org/pdf/2503.01661)] [[must3r](https://github.com/naver/must3r)]

* PE3R: Perception-Efficient 3D Reconstruction [[arXiv 2025](https://arxiv.org/pdf/2503.07507)] [[pe3r](https://github.com/hujiecpp/pe3r)]

* VGGT: Visual Geometry Grounded Transformer [[CVPR 2025](https://arxiv.org/pdf/2503.11651v1)] [[vggt](https://github.com/facebookresearch/vggt)]

* Pow3R: Empowering Unconstrained 3D Reconstruction with Camera and Scene Priors [[CVPR 2025](https://arxiv.org/pdf/2503.17316v1)] [[]()]

* Matrix3D: Large Photogrammetry Model All-in-One [[CVPR 2025](https://arxiv.org/pdf/2502.07685)] [[ml-matrix3d](https://github.com/apple/ml-matrix3d)]

* DiffusionSfM: Predicting Structure and Motion via Ray Origin and Endpoint Diffusion [[CVPR 2025](https://arxiv.org/pdf/2505.05473)] [[DiffusionSfM](https://github.com/QitaoZhao/DiffusionSfM)]

* Point3R: Streaming 3D Reconstruction with Explicit Spatial Pointer Memory [[arXiv 2025](https://arxiv.org/pdf/2507.02863)] [[Point3R](https://github.com/YkiWu/Point3R)]

* π³: Scalable Permutation-Equivariant Visual Geometry Learning [[arXiv 2025](https://arxiv.org/pdf/2507.13347)] [[Pi3](https://github.com/yyfz/Pi3)]

* StreamVGGT: Streaming 4D Visual Geometry Transformer [[arXiv 2025](https://arxiv.org/pdf/2507.11539)] [[StreamVGGT](https://github.com/wzzheng/StreamVGGT)]

* Uni3R: Unified 3D Reconstruction and Semantic Understanding via Generalizable Gaussian Splatting from Unposed Multi-View Images [[arXiv 2025](https://arxiv.org/pdf/2508.03643)] [[Uni3R](https://github.com/HorizonRobotics/Uni3R)]  

* Surf3R: Rapid Surface Reconstruction from Sparse RGB Views in Seconds [[arXiv 2025](https://arxiv.org/pdf/2508.04508)] [[]()]  

* STream3R: Scalable Sequential 3D Reconstruction with Causal Transformer [[arXiv 2025](https://arxiv.org/pdf/2508.10893)] [[STream3R](https://github.com/NIRVANALAN/STream3R)]  

* FastVGGT: Training-Free Acceleration of Visual Geometry Transformer [[arXiv 2025](https://arxiv.org/pdf/2509.02560v1)] [[FastVGGT](https://github.com/mystorm16/FastVGGT)]

  
## Segmentation

* PanSt3R: Multi-view Consistent Panoptic Segmentati [[arXiv 2025](https://arxiv.org/pdf/2506.21348)] [[]()]

## Dynamic
  
* MonST3R: A Simple Approach for Estimating Geometry in the Presence of Motion [[ICLR 2025](https://arxiv.org/pdf/2410.03825)] [[monst3r](https://github.com/Junyi42/monst3r)]

* MegaSaM: Accurate, Fast, and Robust Structure and Motion from Casual Dynamic Videos [[CVPR 2025](https://arxiv.org/pdf/2412.04463)] [[mega-sam](https://mega-sam.github.io/)]
  
* Driv3R: Learning Dense 4D Reconstruction for Autonomous Driving [[arXiv 2024](https://arxiv.org/pdf/2412.06777)] [[Driv3R](https://github.com/Barrybarry-Smith/Driv3R)]

* Geo4D: Leveraging Video Generators for Geometric 4D Scene Reconstruction [[arXiv 2025](https://arxiv.org/pdf/2504.07961)] [[Geo4D](https://github.com/jzr99/Geo4D)]

## SLAM
* SLAM3R: Real-Time Dense Scene Reconstruction from Monocular RGB Videos [[CVPR 2025](https://arxiv.org/pdf/2412.09401)] [[SLAM3R](https://github.com/PKU-VCL-3DV/SLAM3R)]

* MASt3R-SLAM: Real-Time Dense SLAM with 3D Reconstruction Priors [[CVPR 2025](https://arxiv.org/pdf/2412.12392)] [[mast3r-slam](https://edexheim.github.io/mast3r-slam/)]

* VGGT-SLAM: Dense RGB SLAM Optimized on the SL(4) Manifold [[arXiv 2025](https://arxiv.org/pdf/2505.12549)] [[VGGT-SLAM](https://github.com/MIT-SPARK/VGGT-SLAM)]

## Novel View Synthesis
* Splatt3R: Zero-shot Gaussian Splatting from Uncalibrated Image Pairs [[arXiv 2024](https://arxiv.org/pdf/2408.13912)] [[splatt3r](https://github.com/btsmart/splatt3r)]
  
* No Pose, No Problem: Surprisingly Simple 3D Gaussian Splats from Sparse Unposed Images [[ICLR 2025](https://arxiv.org/pdf/2410.24207)] [[NoPoSplat](https://github.com/cvg/NoPoSplat)]

* PreF3R: Pose-Free Feed-Forward 3D Gaussian Splatting from Variable-length Image Sequence [[arXiv 2024](https://arxiv.org/pdf/2411.16877)] [[PreF3R](https://computationalrobotics.seas.harvard.edu/PreF3R)]

* SPARS3R: Semantic Prior Alignment and Regularization for Sparse 3D Reconstruction [[CVPR 2025](https://arxiv.org/pdf/2411.12592)] [[SPARS3R](https://github.com/snldmt/SPARS3R)]

* LVSM: A Large View Synthesis Model with Minimal 3D Inductive Bias [[ICLR 2025](https://arxiv.org/pdf/2410.17242)] [[LVSM](https://github.com/haian-jin/LVSM)]

* FlowR: Flowing from Sparse to Dense 3D Reconstructions [[arXiv 2025](https://arxiv.org/pdf/2504.01647)] [[]()]

* RayZer: A Self-supervised Large View Synthesis Model [[arXiv 2025](https://arxiv.org/pdf/2505.00702?)] [[RayZer](https://github.com/hwjiang1510/RayZer)]

* AnySplat: Feed-forward 3D Gaussian Splatting from Unconstrained Views [[arXiv 2025](https://arxiv.org/pdf/2505.23716)] [[AnySplat](https://github.com/InternRobotics/AnySplat)]
