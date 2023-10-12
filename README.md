# Awesome Monocular Depth Estimation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A list of recent monocular depth estimation work, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).


## Papers

<details open>
<summary>High Performance </summary>

- [IEBins: Iterative Elastic Bins for Monocular Depth Estimation](https://github.com/ShuweiShao/IEBins), NeurIPS 2023 | [github](https://github.com/ShuweiShao/IEBins) 
- [Text-Image Alignment for Diffusion-Based Perception](http://www.vision.caltech.edu/tadp/) (Diffusion), arXiv 2023
- [Unleashing Text-to-Image Diffusion Models for Visual Perception](https://vpd.ivg-research.xyz/) (Diffusion), ICCV 2023 | [github](https://github.com/wl-zhao/VPD)
- [Neural Video Depth Stabilizer], ICCV 2023 | [github](https://github.com/raymondwang987/nvds) 
- [The Surprising Effectiveness of Diffusion Models for Optical Flow and Monocular Depth Estimation](https://diffusion-vision.github.io/) (Diffusion), arXiv 2023 
- [All in Tokens: Unifying Output Space of Visual Tasks via Soft Token](https://github.com/swintransformer/ait) (tokenized), arXiv 2023 | [github](https://github.com/swintransformer/ait) 
- [Revealing the Dark Secrets of Masked Image Modeling](http://www.computationalimaging.org/publications/automatic-integration/) (tokenized), CVPR 2023 | [github](https://github.com/SwinTransformer/MIM-Depth-Estimation) 
- [Internal Discretization for Monocular Depth Estimation](https://www.vis.xyz/pub/idisc/) (tokenized), CVPR 2023 | [github](https://github.com/SysCV/idisc) 
- [Neural Video Depth Stabilizer](https://raymondwang987.github.io/NVDS/), ICCV 2023 | [github](https://github.com/raymondwang987/nvds) 
- [VA-DepthNet: A Variational Approach to Single Image Depth Prediction](https://github.com/cnexah/va-depthnet), ICLR 2023 | [github](https://github.com/cnexah/va-depthnet) 
- [Improving Deep Regression with Ordinal Entropy](https://github.com/needylove/ordinalentropy), ICLR 2023 | [github](https://github.com/needylove/ordinalentropy) 
- [DDP: Diffusion Model for Dense Visual Prediction](https://github.com/jiyuanfeng/ddp) (Diffusion), arXiv 2023 | [github](https://github.com/jiyuanfeng/ddp) 
- [PixelFormer: Attention Attention Everywhere: Monocular Depth Prediction with Skip Attention
](https://github.com/ashutosh1807/pixelformer) (Diffusion), WACV 2023 | [github](https://github.com/ashutosh1807/pixelformer) 
- [LocalBins: Improving Depth Estimation by Learning Local Distributions
](https://github.com/shariqfarooq123/localbins), CVPR 2022 | [github](https://github.com/shariqfarooq123/localbins) 
- [NeW CRFs: Neural Window Fully-connected CRFs for Monocular Depth Estimation
](https://weihaosky.github.io/newcrfs/), CVPR 2022 | [github](https://github.com/aliyun/NeWCRFs) 

</details>

<details open>
<summary>Self-Supervised Depth Estimation</summary>

- [3D Distillation: Improving Self-Supervised Monocular Depth Estimation on Reflective Surfaces], ICCV 2023
- [GasMono: Geometry-Aided Self-Supervised Monocular Depth Estimation for Indoor Scenes], ICCV 2023
- [CORE: Co-planarity Regularized Monocular Geometry Estimation with Weak Supervision] | ICCV 2023
- [Deep Digging into the Generalization of Self-Supervised Monocular Depth Estimation], AAAI 2023
- [Self-supervised monocular depth estimation with a vision transformer], 3DV 2022 | [github](https://github.com/zxcqlf/MonoViT)
- [Self-Supervised Surround-View Depth Estimation with Volumetric Feature Fusion], NeurIPS 2022
- [Devnet: Self-supervised monocular depth learning via density volume construction], ECCV 2022 | [github](https://github.com/kaichen-z/DevNet)
- [Exploiting Pseudo Labels in a Self-Supervised Learning Framework for
Improved Monocular Depth Estimation], ECCV 2022
- [RA-Depth: Resolution Adaptive Self-Supervised Monocular Depth Estimation], ECCV 2022 | [github](https://github.com/hmhemu/RA-Depth)
- [Toward Practical Monocular Indoor Depth Estimation](https://distdepth.github.io/), CVPR 2022 | [github](https://github.com/facebookresearch/DistDepth)
- [Multi-Frame Self-Supervised Depth with Transformers], CVPR 2022
</details>

<details open>
<summary>Metric Depth from Single Image</summary>

- [ZoeDepth: Zero-shot Transfer by Combining Relative and Metric Depth](https://github.com/isl-org/ZoeDepth), arXiv 2023 | [github](https://github.com/isl-org/ZoeDepth)
- [Metric3D: Towards Zero-shot Metric 3D Prediction from A Single Image], ICCV 2023 | [github](https://github.com/YvanYin/Metric3D)
- [Towards Zero-Shot Scale-Aware Monocular Depth Estimation](https://sites.google.com/view/tri-zerodepth), ICCV 2023
- [Toward Practical Monocular Indoor Depth Estimation](https://distdepth.github.io/), CVPR 2022 | [github](https://github.com/facebookresearch/DistDepth)

</details>

<details open>
<summary>Depth for Non-Lambertain Surface</summary>

- [Booster: a Benchmark for Depth from Images of Specular and Transparent Surfaces], TPAMI
- [3D Distillation: Improving Self-Supervised Monocular Depth Estimation on Reflective Surfaces], ICCV 2023
- [Mirror3D: Depth Refinement for Mirror Surfaces](https://3dlg-hcvc.github.io/mirror3d), CVPR 2021
</details>

<details open>
<summary>Depth from Dual-Pixel</summary>

- [Du2Net: Learning Depth Estimation from Dual-Cameras and Dual-Pixels](https://augmentedperception.github.io/du2net/), ECCV 2022
- [Dual pixel exploration: Simultaneous depth estimation and image restoration], CVPR 2021 | [github](https://github.com/panpanfei/Dual-Pixel-Exploration-Simultaneous-Depth-Estimation-and-Image-Restoration)
- [Learning single camera depth estimation using dual-pixels], ICCV 2019 | [github](https://github.com/google-research/google-research/blob/master/dual_pixels/README.md)

</details>

<details open>
<summary>Fisheye</summary>


- [SlaBins: Fisheye Depth Estimation using Slanted Bins on Road Environments](https://syniez.github.io/SlaBins/), ICCV 2023
- [SynWoodScape: Synthetic Surround-view Fisheye Camera Dataset for Autonomous Driving](https://github.com/valeoai/WoodScape), RAL 2021 | [github](https://github.com/valeoai/WoodScape)
</details>

<details open>
<summary>360 deg Depth</summary>

- [Distortion-Aware Self-Supervised Indoor 360∘ Depth Estimation via Hybrid Projection Fusion and Structural Regularities], TMM 2023
- [PanoFormer: Panorama Transformer for Indoor 360 Depth Estimation], ECCV 2022 | [github](https://github.com/zhijieshen-bjtu/PanoFormer)
- [Omnifusion: 360 monocular depth estimation via geometry-aware fusion], CVPR 2022 | [github](https://github.com/yuyanli0831/OmniFusion)

</details>

