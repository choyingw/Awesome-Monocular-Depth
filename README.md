# Awesome Monocular Depth Estimation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A list of recent monocular depth estimation work, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

The list is mainly focusing on recent work after 2020

## Papers

<details open>
<summary>High Performance </summary>

- [Depth Pro: Sharp Monocular Metric Depth in Less Than a Second](https://arxiv.org/abs/2410.02073/) (precise focal length estimation with metric depth), arXiv 2024 | [github](https://github.com/apple/ml-depth-pro/)
- [Boosting Generalizability towards Zero-Shot Cross-Dataset Single-Image Indoor Depth by Meta-Initialization](https://scholar.google.com/scholar?oi=bibs&cluster=10790219912035654526&btnI=1&hl=en) (meta-learning), IROS 2024
- [DoubleTake: Geometry Guided Depth Estimation](https://nianticlabs.github.io/doubletake/resources/DoubleTake.pdf/), ECCV 2024 | [github](https://nianticlabs.github.io/doubletake/) 
- [WorDepth: Variational Language Prior for Monocular Depth Estimation](https://openaccess.thecvf.com/content/CVPR2024/html/Zeng_WorDepth_Variational_Language_Prior_for_Monocular_Depth_Estimation_CVPR_2024_paper.html), CVPR 2024 | [github](https://github.com/Adonis-galaxy/WorDepth/) 
- [Scale-Invariant Monocular Depth Estimation via SSI Depth](https://dl.acm.org/doi/abs/10.1145/3641519.3657523?casa_token=5BzgjJGb_IkAAAAA:Qh0shrLY5ZvPgVSxomASjA_LDX2vItIIfAo8mRQGbZlGM-DIo-pCwP8dpPLNXQDtgtKd7K_98nEiQg), SIGGRAPH 2024
- [PatchFusion: An End-to-End Tile-Based Framework for High-Resolution Monocular Metric Depth Estimation](https://arxiv.org/abs/2312.02284), CVPR 2024 | [github](https://zhyever.github.io/patchfusion/) 
- [Metric3D v2 A Versatile Monocular Geometric Foundation Model for Zero-shot Metric Depth and Surface Normal Estimation](https://jugghm.github.io/Metric3Dv2/) (high-performing metric depth on zero-shot evaluation), arxiv 2024  | [github](https://jugghm.github.io/Metric3Dv2/) 
- [UniDepth: Universal Monocular Metric Depth Estimation](https://github.com/lpiccinelli-eth/unidepth), (universal metric depth estimation; one's zero-shot performance match depth-anything on NYUv2), CVPR 2024  | [github](https://github.com/lpiccinelli-eth/unidepth) 
- [Marigold: Repurposing Diffusion-Based Image Generators for Monocular Depth Estimation](https://github.com/prs-eth/marigold) (diffusion), CVPR 2024  | [github](https://github.com/prs-eth/marigold) 
- [ECoDepth: Effective Conditioning of Diffusion Models for Monocular Depth Estimation](https://github.com/aradhye2002/ecodepth) (diffusion), CVPR 2024  | [github](https://github.com/aradhye2002/ecodepth) 
- [Harnessing Diffusion Models for Visual Perception with Meta Prompts](https://github.com/fudan-zvg/meta-prompts) (diffusion), arxiv 2024  | [github](https://github.com/fudan-zvg/meta-prompts) 
- [DepthFM: Fast Monocular Depth Estimation with Flow Matching](https://depthfm.github.io/), (Depth Estimation using Flow Matching), arXiv 2024
- [Unleashing the Power of Large-Scale Unlabeled Data](https://depth-anything.github.io/), CVPR 2024  | [github](https://github.com/LiheYoung/Depth-Anything) [huggingface](https://huggingface.co/spaces/LiheYoung/Depth-Anything)
- [EVP: Enhanced Visual Perception using Inverse Multi-Attentive Feature Refinement and Regularized Image-Text Alignment](https://lavreniuk.github.io/EVP/) (Diffusion), arXiv 2023  | [github](https://github.com/Lavreniuk/EVP)
- [Harnessing Diffusion Models for Visual Perception with Meta Prompts](https://github.com/fudan-zvg/meta-prompts?tab=readme-ov-file), arXiv 2023 | [github](https://github.com/fudan-zvg/meta-prompts?tab=readme-ov-file)
- [IEBins: Iterative Elastic Bins for Monocular Depth Estimation](https://github.com/ShuweiShao/IEBins), NeurIPS 2023 | [github](https://github.com/ShuweiShao/IEBins) 
- [Text-Image Alignment for Diffusion-Based Perception](http://www.vision.caltech.edu/tadp/) (Diffusion), CVPR 2024 | [github](https://github.com/damaggu/tadp)
- [Robust Monocular Depth Estimation under Challenging Conditions](https://md4all.github.io/), ICCV 2023 | [github](https://github.com/md4all/md4all)
- [Unleashing Text-to-Image Diffusion Models for Visual Perception](https://vpd.ivg-research.xyz/) (Diffusion), ICCV 2023 | [github](https://github.com/wl-zhao/VPD)
- [Neural Video Depth Stabilizer](https://github.com/raymondwang987/nvds) , ICCV 2023 | [github](https://github.com/raymondwang987/nvds) 
- [The Surprising Effectiveness of Diffusion Models for Optical Flow and Monocular Depth Estimation](https://diffusion-vision.github.io/) (Diffusion), NeurIPS 2023 
- [All in Tokens: Unifying Output Space of Visual Tasks via Soft Token](https://github.com/swintransformer/ait) (tokenized), arXiv 2023 | [github](https://github.com/swintransformer/ait) 
- [Revealing the Dark Secrets of Masked Image Modeling](http://www.computationalimaging.org/publications/automatic-integration/) (tokenization approach), CVPR 2023 | [github](https://github.com/SwinTransformer/MIM-Depth-Estimation) 
- [Internal Discretization for Monocular Depth Estimation](https://www.vis.xyz/pub/idisc/) (tokenization approach), CVPR 2023 | [github](https://github.com/SysCV/idisc) 
- [Neural Video Depth Stabilizer](https://raymondwang987.github.io/NVDS/), ICCV 2023 | [github](https://github.com/raymondwang987/nvds) 
- [VA-DepthNet: A Variational Approach to Single Image Depth Prediction](https://github.com/cnexah/va-depthnet), ICLR 2023 | [github](https://github.com/cnexah/va-depthnet) 
- [Improving Deep Regression with Ordinal Entropy](https://github.com/needylove/ordinalentropy), ICLR 2023 | [github](https://github.com/needylove/ordinalentropy) 
- [DDP: Diffusion Model for Dense Visual Prediction](https://github.com/jiyuanfeng/ddp) (Diffusion), arXiv 2023 | [github](https://github.com/jiyuanfeng/ddp) 
- [PixelFormer: Attention Attention Everywhere: Monocular Depth Prediction with Skip Attention](https://github.com/ashutosh1807/pixelformer) (Diffusion), WACV 2023 | [github](https://github.com/ashutosh1807/pixelformer) 
- [LocalBins: Improving Depth Estimation by Learning Local Distributions](https://github.com/shariqfarooq123/localbins), CVPR 2022 | [github](https://github.com/shariqfarooq123/localbins) 
- [NeW CRFs: Neural Window Fully-connected CRFs for Monocular Depth Estimation](https://weihaosky.github.io/newcrfs/), CVPR 2022 | [github](https://github.com/aliyun/NeWCRFs) 

</details>

<details open>
<summary>Self-Supervised Depth Estimation</summary>

- [Camera Height Doesn't Change: Unsupervised Training for Metric Monocular Road-Scene Depth Estimation](https://vision.ist.i.kyoto-u.ac.jp/research/fumet/), ECCV 2024
- [SQLdepth: Generalizable Self-Supervised Fine-Structured Monocular Depth Estimation](https://ojs.aaai.org/index.php/AAAI/article/view/28383), AAAI 2024 | [github](https://github.com/hisfog/SfMNeXt-Impl)
- [Dusk Till Dawn: Self-supervised Nighttime Stereo Depth Estimation using Visual Foundation Models](https://arxiv.org/pdf/2405.11158), ICRA 2024 | [github](https://github.com/madhubabuv/dtd)
- [Complete contextual information extraction for self-supervised monocular depth estimation](https://www.sciencedirect.com/science/article/abs/pii/S1077314224001139), CVIU 2024
- [Mining Supervision for Dynamic Regions in Self-Supervised Monocular
Depth Estimat](https://openaccess.thecvf.com/content/CVPR2024/papers/Nguyen_Mining_Supervision_for_Dynamic_Regions_in_Self-Supervised_Monocular_Depth_Estimation_CVPR_2024_paper.pdf), CVPR 2024 | [github](https://github.com/HoangChuongNguyen/mono-consistent-depth)
- [Two-in-One Depth: Bridging the Gap Between Monocular and Binocular Self-Supervised Depth Estimation](https://openaccess.thecvf.com/content/ICCV2023/html/Zhou_Two-in-One_Depth_Bridging_the_Gap_Between_Monocular_and_Binocular_Self-Supervised_ICCV_2023_paper.html), ICCV 2023
- [DualRefine: Self-Supervised Depth and Pose Estimation Through Iterative Epipolar Sampling and Refinement Toward Equilibrium](https://openaccess.thecvf.com/content/CVPR2023/html/Bangunharcana_DualRefine_Self-Supervised_Depth_and_Pose_Estimation_Through_Iterative_Epipolar_Sampling_CVPR_2023_paper.html), CVPR 2023
- [Self-Supervised Monocular Depth Estimation: Solving the Edge-Fattening Problem](https://openaccess.thecvf.com/content/WACV2023/html/Chen_Self-Supervised_Monocular_Depth_Estimation_Solving_the_Edge-Fattening_Problem_WACV_2023_paper.html), WACV 2023
- [3D Distillation: Improving Self-Supervised Monocular Depth Estimation on Reflective Surfaces](https://openaccess.thecvf.com/content/ICCV2023/papers/Shi_3D_Distillation_Improving_Self-Supervised_Monocular_Depth_Estimation_on_Reflective_Surfaces_ICCV_2023_paper.pdf), ICCV 2023
- [GasMono: Geometry-Aided Self-Supervised Monocular Depth Estimation for Indoor Scenes](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhao_GasMono_Geometry-Aided_Self-Supervised_Monocular_Depth_Estimation_for_Indoor_Scenes_ICCV_2023_paper.pdf), ICCV 2023
- [CORE: Co-planarity Regularized Monocular Geometry Estimation with Weak Supervision](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_CORE_Co-planarity_Regularized_Monocular_Geometry_Estimation_with_Weak_Supervision_ICCV_2023_paper.pdf), ICCV 2023
- [Lite-Mono: A Lightweight CNN and Transformer Architecture for Self-Supervised Monocular Depth Estimation](https://openaccess.thecvf.com/content/CVPR2023/html/Zhang_Lite-Mono_A_Lightweight_CNN_and_Transformer_Architecture_for_Self-Supervised_Monocular_CVPR_2023_paper.html), ICCV 2023 | [github](https://github.com/noahzn/Lite-Mono) 
- [Deep Digging into the Generalization of Self-Supervised Monocular Depth Estimation](https://arxiv.org/abs/2205.11083), AAAI 2023
- [Self-supervised monocular depth estimation with a vision transformer](https://arxiv.org/abs/2208.03543), 3DV 2022 | [github](https://github.com/zxcqlf/MonoViT)
- [Self-Supervised Surround-View Depth Estimation with Volumetric Feature Fusion](https://openreview.net/forum?id=0PfIQs-ttQQ), NeurIPS 2022
- [Devnet: Self-supervised monocular depth learning via density volume construction](https://arxiv.org/abs/2209.06351), ECCV 2022 | [github](https://github.com/kaichen-z/DevNet)
- [Exploiting Pseudo Labels in a Self-Supervised Learning Framework for Improved Monocular Depth Estimation](https://openaccess.thecvf.com/content/CVPR2022/papers/Petrovai_Exploiting_Pseudo_Labels_in_a_Self-Supervised_Learning_Framework_for_Improved_CVPR_2022_paper.pdf), ECCV 2022
- [RA-Depth: Resolution Adaptive Self-Supervised Monocular Depth Estimation](https://arxiv.org/abs/2207.11984), ECCV 2022 | [github](https://github.com/hmhemu/RA-Depth)
- [Toward Practical Monocular Indoor Depth Estimation](https://distdepth.github.io/), CVPR 2022 | [github](https://github.com/facebookresearch/DistDepth)
- [Multi-Frame Self-Supervised Depth with Transformers](https://arxiv.org/abs/2204.07616), CVPR 2022
</details>

<details open>
<summary>Metric Depth from Single Image</summary>

- [Depth Pro: Sharp Monocular Metric Depth in Less Than a Second](https://arxiv.org/abs/2410.02073/) (precise focal length estimation with metric depth), arXiv 2024 | [github](https://github.com/apple/ml-depth-pro/)
- [Unleashing the Power of Large-Scale Unlabeled Data](https://depth-anything.github.io/), CVPR 2024  | [github](https://github.com/LiheYoung/Depth-Anything) [huggingface](https://huggingface.co/spaces/LiheYoung/Depth-Anything)
- [Metric3D v2 A Versatile Monocular Geometric Foundation Model for Zero-shot Metric Depth and Surface Normal Estimation](https://jugghm.github.io/Metric3Dv2/) (high-performing metric depth on zero-shot evaluation), arxiv 2024  | [github](https://jugghm.github.io/Metric3Dv2/) 
- [UniDepth: Universal Monocular Metric Depth Estimation](https://github.com/lpiccinelli-eth/unidepth), (universal metric depth estimation; one's zero-shot performance match depth-anything on NYUv2), CVPR 2024  | [github](https://github.com/lpiccinelli-eth/unidepth) 
- [ZoeDepth: Zero-shot Transfer by Combining Relative and Metric Depth](https://github.com/isl-org/ZoeDepth), arXiv 2023 | [github](https://github.com/isl-org/ZoeDepth)
- [Metric3D: Towards Zero-shot Metric 3D Prediction from A Single Image](https://github.com/YvanYin/Metric3D), ICCV 2023 | [github](https://github.com/YvanYin/Metric3D)
- [Towards Zero-Shot Scale-Aware Monocular Depth Estimation](https://sites.google.com/view/tri-zerodepth), ICCV 2023
- [Toward Practical Monocular Indoor Depth Estimation](https://distdepth.github.io/), CVPR 2022 | [github](https://github.com/facebookresearch/DistDepth)

</details>

<details open>
<summary>Depth for Non-Lambertain Surface</summary>

- [Booster: a Benchmark for Depth from Images of Specular and Transparent Surfaces](https://arxiv.org/abs/2301.08245), TPAMI
- [3D Distillation: Improving Self-Supervised Monocular Depth Estimation on Reflective Surfaces](https://openaccess.thecvf.com/content/ICCV2023/papers/Shi_3D_Distillation_Improving_Self-Supervised_Monocular_Depth_Estimation_on_Reflective_Surfaces_ICCV_2023_paper.pdf), ICCV 2023
- [Mirror3D: Depth Refinement for Mirror Surfaces](https://3dlg-hcvc.github.io/mirror3d), CVPR 2021
</details>

<details open>
<summary>Depth from Dual-Pixel, optics, or photography</summary>

- [Shakes on a Plane: Unsupervised Depth Estimation from Unstabilized Photography](https://github.com/princeton-computational-imaging/SoaP), CVPR 2023 | [github](https://github.com/princeton-computational-imaging/SoaP)
- [Fully Self-Supervised Depth Estimation from Defocus Clue](https://github.com/Ehzoahis/DEReD), CVPR 2023 | [github](https://github.com/Ehzoahis/DEReD)
- [Calibration-free deep optics for depth estimation with precise simulation](https://www.sciencedirect.com/science/article/abs/pii/S0143816624002926), Optics and Lasers in Engineering 2024
- [Du2Net: Learning Depth Estimation from Dual-Cameras and Dual-Pixels](https://augmentedperception.github.io/du2net/), ECCV 2022
- [Dual pixel exploration: Simultaneous depth estimation and image restoration](https://github.com/panpanfei/Dual-Pixel-Exploration-Simultaneous-Depth-Estimation-and-Image-Restoration), CVPR 2021 | [github](https://github.com/panpanfei/Dual-Pixel-Exploration-Simultaneous-Depth-Estimation-and-Image-Restoration)
- [Learning single camera depth estimation using dual-pixels](https://github.com/google-research/google-research/blob/master/dual_pixels/README.md), ICCV 2019 | [github](https://github.com/google-research/google-research/blob/master/dual_pixels/README.md)
- [Modeling Defocus-Disparity in Dual-Pixel Sensors](https://github.com/abhijithpunnappurath/dual-pixel-defocus-disparity), ICCP 2020 | [github](https://github.com/abhijithpunnappurath/dual-pixel-defocus-disparity)
</details>

<details open>
<summary>Fisheye</summary>


- [SlaBins: Fisheye Depth Estimation using Slanted Bins on Road Environments](https://syniez.github.io/SlaBins/), ICCV 2023 | [github](https://github.com/Syniez/SlaBins)
- [SynWoodScape: Synthetic Surround-view Fisheye Camera Dataset for Autonomous Driving](https://github.com/valeoai/WoodScape), RAL 2021 | [github](https://github.com/valeoai/WoodScape)
</details>

<details open>
<summary>360 deg Depth</summary>

- [FreDSNet: Joint Monocular Depth and Semantic Segmentation with Fast Fourier Convolutions](https://arxiv.org/pdf/2210.01595v2), ICRA 2023 | [github](https://github.com/Sbrunoberenguel/FreDSNet)
- [EGformer: Equirectangular Geometry-biased Transformer for 360 Depth Estimation](https://arxiv.org/pdf/2304.07803.pdf), ICCV 2023 | [github](https://github.com/yuniw18/EGformer)
- [CRF360D: Monocular 360 Depth Estimation via Neural Spherical Fully-Connected CRFs](https://vlislab22.github.io/CRF360D/), arxiv 2024
- [Distortion-Aware Self-Supervised Indoor 360∘ Depth Estimation via Hybrid Projection Fusion and Structural Regularities](https://arxiv.org/abs/2204.01027), TMM 2023
- [PanoFormer: Panorama Transformer for Indoor 360 Depth Estimation](https://arxiv.org/abs/2203.09283), ECCV 2022 | [github](https://github.com/zhijieshen-bjtu/PanoFormer)
- [360MonoDepth: High-Resolution 360 ∘ Monocular Depth Estimation](https://arxiv.org/pdf/2111.15669.pdf), CVPR 2022 | [github](https://github.com/manurare/360monodepth)
- [SphereDepth: Panorama Depth Estimation from Spherical Domain](https://arxiv.org/pdf/2208.13714v1.pdf), CVPR 2022 | [github](https://github.com/Yannnnnnnnnnnn/SphereDepth)
- [Omnifusion: 360 monocular depth estimation via geometry-aware fusion](https://arxiv.org/abs/2203.00838), CVPR 2022 | [github](https://github.com/yuyanli0831/OmniFusion)

</details>


<details open>
<summary>Sparse Depth Completion</summary>


- [LRRU: Long-short Range Recurrent Updating Networks for Depth Completion](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_LRRU_Long-short_Range_Recurrent_Updating_Networks_for_Depth_Completion_ICCV_2023_paper.pdf), ICCV 2023 | [github](https://github.com/YufeiWang777/LRRU) 
- [BEV@DC: Bird's-Eye View Assisted Training for Depth Completion](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhou_BEVDC_Birds-Eye_View_Assisted_Training_for_Depth_Completion_CVPR_2023_paper.pdf), CVPR 2023 
- [MFF-Net: Towards Efficient Monocular Depth Completion With Multi-Modal Feature Fusion](https://ieeexplore.ieee.org/abstract/document/10008014), RAL 2023
- [CompletionFormer: Depth Completion with Convolutions and Vision Transformers](https://arxiv.org/pdf/2304.13030.pdf), CVPR 2023 | [github](https://github.com/youmi-zym/CompletionFormer)
- [Dynamic Spatial Propagation Network for Depth Completion](https://arxiv.org/pdf/2202.09769.pdf), AAAI 2022 | [github](https://github.com/Kyakaka/DySPN)  
- [CostDCNet: Cost Volume based Depth Completion for a Single RGB-D Image](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136620248.pdf), ECCV 2022 | [github](https://github.com/kamse/CostDCNet) 
- [Monitored Distillation for Positive Congruent Depth Completion](https://arxiv.org/pdf/2203.16034.pdf), ECCV 2022 | [github](https://github.com/alexklwong/calibrated-backprojection-network) 
- [RigNet: Repetitive Image Guided Network for Depth Completion](https://arxiv.org/abs/2107.13802), ECCV 2022
- [PENet: Towards Precise and Efficient Image Guided Depth Completion](https://arxiv.org/abs/2103.00783), ICRA 2021 | [github](https://github.com/JUGGHM/PENet_ICRA2021) 
- [Scene Completeness-Aware Lidar Depth Completion for Driving Scenario](https://arxiv.org/abs/2003.06945), ICASSP 2021 | [github](https://github.com/choyingw/SCADC-DepthCompletion)
- [Non-Local Spatial Propagation Network for Depth Completion](https://arxiv.org/pdf/2007.10042.pdf), ECCV 2020 | [github](https://github.com/zzangjinsun/NLSPN_ECCV20) 
- [Depth Completion From Sparse LiDAR Data With Depth-Normal Constraints](https://arxiv.org/abs/1910.06727), ICCV 2019 | [github](https://github.com/yuyanli0831/OmniFusion)
- [DFuseNet: Deep Fusion of RGB and Sparse Depth Information for Image Guided Dense Depth Completion](https://arxiv.org/pdf/1902.00761), ITSC 2019 | [github](https://github.com/ShreyasSkandanS/DFuseNet)
- [Deep RGB-D canonical correlation analysis for sparse depth completion](https://arxiv.org/abs/1906.08967), NeurIPS 2019 | [github](https://github.com/choyingw/CFCNet)


</details>

<details open>
<summary>Indoor Datasets</summary>

Indoor dataset with a focus on space type
- [InSpaceType: Reconsider Space Type in Indoor Monocular Depth Estimation](https://arxiv.org/abs/2309.13516), BMVC 2023 | [Data Page](https://github.com/DepthComputation/InSpaceType_Benchmark)
- [Toward practical monocular indoor depth estimation](https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_Toward_Practical_Monocular_Indoor_Depth_Estimation_CVPR_2022_paper.pdf), CVPR 2022 | [Data Page](https://github.com/DepthComputation/InSpaceType_Benchmark) 

<details open>
<summary>Other Domain Datasets</summary>
- [SoccerNet-Depth: a Scalable Dataset for Monocular Depth Estimation in Sports Videos](https://openaccess.thecvf.com/content/CVPR2024W/CVsports/html/Leduc_SoccerNet-Depth_a_Scalable_Dataset_for_Monocular_Depth_Estimation_in_Sports_CVPRW_2024_paper.html), CVPRW 2024 | [Data Page]( https://github.com/SoccerNet/sn-depth) 

</details>
