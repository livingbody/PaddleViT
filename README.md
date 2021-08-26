# PaddleViT #

[![GitHub license](https://img.shields.io/github/license/xperzy/PPViT?color=blue)](https://github.com/xperzy/PPViT/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/xperzy/PPViT?style=social)](https://github.com/xperzy/PPViT/stargazers)


<p align="center">    
    <img src="./PaddleViT.png" width="100%"/>
</p>
 
## State-of-the-art Visual Transformer and MLP Models for Paddle 2.0 ##

:robot: PaddlePaddle Visual Transformers (`PaddleViT` or `PPViT`) is a collection of vision models beyond convolution. Most of the models are based on Visual Transformers, Visual Attentions, and MLPs, etc. PaddleViT also integrates popular layers, utilities, optimizers, schedulers, data augmentations, training/validation scripts for PaddlePaddle 2.0+. The aim is to reproduce a wide variety of state-of-the-art ViT and MLP models with full training/validation procedures. We are passionate about making cuting-edge CV techniques easier to use for everyone.

:robot: PaddleViT provides models and tools for a variety of vision tasks, such as classifications, object detection, semantic segmentation, GAN, and more. Each model architecture is defined in standalone python module and can be modified to enable quick research experiments. At the same time, pretrained weights can be downloaded and used to finetune on your own datasets. PaddleViT also integrates popular tools and modules for custimized dataset, data preprocessing, performance metrics, DDP and more.

:robot: PaddleViT is backed by popular deep learning framework [PaddlePaddle](https://www.paddlepaddle.org/), we also provide tutorials and projects on [Paddle AI Studio](https://aistudio.baidu.com/aistudio/index). It's intuitive and straightforward to get started for new users.


## Quick Tour ##
### - Image Classification ###

### - Object Detection ###

### - Semantic Segmentation ###

### - GAN ###


## Installation ##




## Model architectures ##

### Image Classification ###
#### Now: ####
1. ViT ([An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929))
2. DeiT ([Training data-efficient image transformers & distillation through attention](https://arxiv.org/abs/2012.12877))
3. Swin Transformer ([Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030))
4. PVTv2 ([PVTv2: Improved Baselines with Pyramid Vision Transformer](https://arxiv.org/abs/2106.13797))
5. MLP-Mixer ([MLP-Mixer: An all-MLP Architecture for Vision](https://arxiv.org/abs/2105.01601))
6. ResMLP ([ResMLP: Feedforward networks for image classification with data-efficient training](https://arxiv.org/abs/2105.03404))
7. gMLP ([Pay Attention to MLPs](https://arxiv.org/abs/2105.08050))
8. VOLO ([VOLO: Vision Outlooker for Visual Recognition](https://arxiv.org/abs/2106.13112))
9. CaiT ([Going deeper with Image Transformers](https://arxiv.org/abs/2103.17239))
10. Shuffle Transformer ([Shuffle Transformer: Rethinking Spatial Shuffle for Vision Transformer](https://arxiv.org/pdf/2106.03650))
11. CSwin ([CSWin Transformer: A General Vision Transformer Backbone with Cross-Shaped Windows](https://arxiv.org/pdf/2107.00652.pdf))
12. T2T-ViT ([Tokens-to-Token ViT: Training Vision Transformers from Scratch on ImageNet](https://arxiv.org/abs/2101.11986))

#### Coming Soon: ####
1. CrossViT ([CrossViT: Cross-Attention Multi-Scale Vision Transformer for Image Classification](https://arxiv.org/abs/2103.14899))
2. Focal Self-attention ([Focal Self-attention for Local-Global Interactions in Vision Transformers](https://arxiv.org/abs/2107.00641))
3. HaloNet ([Scaling Local Self-Attention for Parameter Efficient Visual Backbones](https://arxiv.org/abs/2103.12731))




### Detection ###
#### Now: ####
1. DETR ([End-to-End Object Detection with Transformers](https://arxiv.org/abs/2005.12872))

#### Coming Soon: ####
1. Swin Transformer ([Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030))
2. PVTv2 ([PVTv2: Improved Baselines with Pyramid Vision Transformer](https://arxiv.org/abs/2106.13797))
3. Focal Self-attention ([Focal Self-attention for Local-Global Interactions in Vision Transformers](https://arxiv.org/abs/2107.00641))
5. CSwin ([CSWin Transformer: A General Vision Transformer Backbone with Cross-Shaped Windows](https://arxiv.org/pdf/2107.00652.pdf))
6. UP-DETR ([UP-DETR: Unsupervised Pre-training for Object Detection with Transformers](https://arxiv.org/abs/2011.09094))




### Semantic Segmentation ###
#### Now: ####
1. SETR ([Rethinking Semantic Segmentation from a Sequence-to-Sequence Perspective with Transformers](https://arxiv.org/abs/2012.15840))
2. DPT ([Vision Transformers for Dense Prediction](https://arxiv.org/abs/2103.13413))
3. Swin Transformer ([Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030))
4. Segmenter: ([Transformer for Semantic Segmentation](https://arxiv.org/pdf/2105.05633.pdf))
5. Trans2seg: ([Segmenting Transparent Object in the Wild with Transformer](https://arxiv.org/pdf/2101.08461.pdf))
6. SegFormer ([SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers](https://arxiv.org/abs/2105.15203))

#### Coming Soon:  ####
1. FTN ([Fully Transformer Networks for Semantic Image Segmentation](https://arxiv.org/pdf/2106.04108.pdf))
2. Shuffle Transformer ([Shuffle Transformer: Rethinking Spatial Shuffle for Vision Transformer](https://arxiv.org/pdf/2106.03650))
3. Focal Self-attention ([Focal Self-attention for Local-Global Interactions in Vision Transformers](https://arxiv.org/abs/2107.00641))
4. CSwin ([CSWin Transformer: A General Vision Transformer Backbone with Cross-Shaped Windows](https://arxiv.org/pdf/2107.00652.pdf))




### GAN ###
1. TransGAN ([TransGAN: Two Pure Transformers Can Make One Strong GAN, and That Can Scale Up](https://arxiv.org/abs/2102.07074))
2. Styleformer ([Styleformer: Transformer based Generative Adversarial Networks with Style Vector](https://arxiv.org/abs/2106.07023))
#### Coming Soon: ####
1. ViTGAN ([ViTGAN: Training GANs with Vision Transformers](https://arxiv.org/pdf/2107.04589))




## Results (Ported Weights) ## 
### Image Classification ###
| Model                          | Acc@1 | Acc@5 | Image Size | Crop_pct | Interpolation | Link        |
|--------------------------------|-------|-------|------------|----------|---------------|--------------|
| vit_base_patch16_224           | 84.58 | 97.30 | 224        | 0.875    | bicubic      | [google](https://drive.google.com/file/d/13D9FqU4ISsGxWXURgKW9eLOBV-pYPr-L/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1ms3o2fHMQpIoVqnEHitRtA)(qv4n) |
| vit_base_patch16_384           | 85.99 | 98.00 | 384        | 1.0      | bicubic      | [google](https://drive.google.com/file/d/1kWKaAgneDx0QsECxtf7EnUdUZej6vSFT/view?usp=sharing)/[baidu](https://pan.baidu.com/s/15ggLdiL98RPcz__SXorrXA)(wsum) |
| vit_large_patch16_224          | 85.81 | 97.82 | 224        | 0.875    | bicubic       | [google](https://drive.google.com/file/d/1jgwtmtp_cDWEhZE-FuWhs7lCdpqhAMft/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1HRxUJAwEiKgrWnJSjHyU0A)(1bgk) |
| swin_base_patch4_window7_224   | 85.27 | 97.56 | 224        | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1yjZFJoJeDFIfsxh9x10XGqCb8s2-Gtbp/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1AseY3CKmJvlxoSwXnxHEwA)(wyck) |
| swin_base_patch4_window12_384  | 86.43 | 98.07 | 384        | 1.0      | bicubic       | [google](https://drive.google.com/file/d/1ThmGsTDZ8217-Zuo9o5EGLfzw8AI6N0w/view?usp=sharing)/[baidu](https://pan.baidu.com/s/10E3F9jqBeBTcasIvJ8iMzg)(4a95) |
| swin_large_patch4_window12_384 | 87.14 | 98.23 | 384        | 1.0      | bicubic       | [google](https://drive.google.com/file/d/1f30Mt80g5yLfEiViT4-kMLpyDjTUTV5B/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1w5w8QNfg0zY3nSfGs-Tx3A)(j71u) |
| pvtv2_b0 			| 70.47	| 90.16	| 224 | 0.875 | bicubic | [google](https://drive.google.com/file/d/1wkx4un6y7V87Rp_ZlD4_pV63QRst-1AE/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1mab4dOtBB-HsdzFJYrvgjA)(dxgb) |
| pvtv2_b1 			| 78.70	| 94.49	| 224 | 0.875 | bicubic | [google](https://drive.google.com/file/d/11hqLxL2MTSnKPb-gp2eMZLAzT6q2UsmG/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1Ur0s4SEOxVqggmgq6AM-sQ)(2e5m) |
| pvtv2_b2 			| 82.02	| 95.99	| 224 | 0.875 | bicubic | [google](https://drive.google.com/file/d/1-KY6NbS3Y3gCaPaUam0v_Xlk1fT-N1Mz/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1FWx0QB7_8_ikrPIOlL7ung)(are2) |
| pvtv2_b3 			| 83.14	| 96.47	| 224 | 0.875 | bicubic | [google](https://drive.google.com/file/d/16yYV8x7aKssGYmdE-YP99GMg4NKGR5j1/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1ge0rBsCqIcpIjrVxsrFhnw)(nc21) |
| pvtv2_b4 			| 83.61	| 96.69	| 224 | 0.875 | bicubic | [google](https://drive.google.com/file/d/1gvPdvDeq0VchOUuriTnnGUKh0N2lj-fA/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1VMSD_Kr_hduCZ5dxmDbLoA)(tthf) |
| pvtv2_b5 			| 83.77	| 96.61	| 224 | 0.875 | bicubic | [google](https://drive.google.com/file/d/1OHaHiHN_AjsGYBN2gxFcQCDhBbTvZ02g/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1ey4agxI2Nb0F6iaaX3zAbA)(9v6n) |
| pvtv2_b2_linear 	| 82.06	| 96.04	| 224 | 0.875 | bicubic | [google](https://drive.google.com/file/d/1hC8wE_XanMPi0_y9apEBKzNc4acZW5Uy/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1IAhiiaJPe-Lg1Qjxp2p30w)(a4c8) |
| mlp_mixer_b16_224                  | 76.60 | 92.23 | 224        | 0.875    | bicubic       | [google](https://drive.google.com/file/d/1ZcQEH92sEPvYuDc6eYZgssK5UjYomzUD/view?usp=sharing)/[baidu](https://pan.baidu.com/s/12nZaWGMOXwrCMOIBfUuUMA)(xh8x) |
| mlp_mixer_l16_224           | 72.06 | 87.67 | 224        | 0.875      | bicubic      | [google](https://drive.google.com/file/d/1mkmvqo5K7JuvqGm92a-AdycXIcsv1rdg/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1AmSVpwCaGR9Vjsj_boL7GA)(8q7r) |
| resmlp_24_224                  | 79.38 | 94.55 | 224        | 0.875    | bicubic       | [google](https://drive.google.com/file/d/15A5q1XSXBz-y1AcXhy_XaDymLLj2s2Tn/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1nLAvyG53REdwYNCLmp4yBA)(jdcx) |
| resmlp_36_224             | 79.77 | 94.89 | 224        | 0.875      | bicubic      | [google](https://drive.google.com/file/d/1WrhVm-7EKnLmPU18Xm0C7uIqrg-RwqZL/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1QD4EWmM9b2u1r8LsnV6rUA)(33w3) |
| resmlp_big_24_224         | 81.04 | 95.02 | 224        | 0.875      | bicubic      | [google](https://drive.google.com/file/d/1KLlFuzYb17tC5Mmue3dfyr2L_q4xHTZi/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1oXU6CR0z7O0XNwu_UdZv_w)(r9kb) |
| resmlp_big_24_distilled_224 | 83.59 | 96.65 | 224        | 0.875      | bicubic      | [google](https://drive.google.com/file/d/199q0MN_BlQh9-HbB28RdxHj1ApMTHow-/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1yUrfbqW8vLODDiRV5WWkhQ)(4jk5) |
| gmlp_s16_224                   | 79.64 | 94.63 | 224        | 0.875    | bicubic       | [google](https://drive.google.com/file/d/1TLypFly7aW0oXzEHfeDSz2Va4RHPRqe5/view?usp=sharing)/[baidu](https://pan.baidu.com/s/13UUz1eGIKyqyhtwedKLUMA)(bcth) |
| volo_d5_224_86.10              | 86.08 | 97.58 | 224        | 1.0      | bicubic       | [google](https://drive.google.com/file/d/1GBOBPCBJYZfWybK-Xp0Otn0N4NXpct0G/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1t9gPLRAOkdXaG55fVADQZg)(td49) |
| volo_d5_512_87.07              | 87.05 | 97.97 | 512        | 1.15     | bicubic       | [google](https://drive.google.com/file/d/1Phf_wHsjRZ1QrZ8oFrqsYuhDr4TXrVkc/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1X-WjpNqvWva2M977jgHosg)(irik) |
| cait_xxs24_224                 | 78.38 | 94.32 | 224        | 1.0      | bicubic       | [google](https://drive.google.com/file/d/1LKsQUr824oY4E42QeUEaFt41I8xHNseR/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1YIaBLopKIK5_p7NlgWHpGA)(j9m8) |
| cait_s24_384                   | 85.05 | 97.34 | 384        | 1.0      | bicubic       | [google](https://drive.google.com/file/d/1GU0esukDvMg3u40FZB_5GiB6qpShjvGh/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1qvhNckJjcEf5HyVn8LuEeA)(qb86) |
| cait_m48_448                   | 86.49  | 97.75 | 448        | 1.0      | bicubic       | [google](https://drive.google.com/file/d/1lJSP__dVERBNFnp7im-1xM3s_lqEe82-/view?usp=sharing)/[baidu](https://pan.baidu.com/s/179MA3MkG2qxFle0K944Gkg)(imk5) |
| deit_base_distilled_patch16_224| 83.32  | 96.49 | 224        | 0.875    | bicubic       | [google](https://drive.google.com/file/d/12_x6-NN3Jde2BFUih4OM9NlTwe9-Xlkw/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1ZnmAWgT6ewe7Vl3Xw_csuA)(5f2g) |
| deit_base_distilled_patch16_384| 85.43  | 97.33 | 384        | 1.0      | bicubic       | [google](https://drive.google.com/file/d/1i5H_zjSdHfM-Znv89DHTv9ChykWrIt8I/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1PQsQIci4VCHY7l2tCzMklg)(qgj2) |
| shuffle_vit_tiny_patch4_window7| 82.39  | 96.05 | 224        | 0.875      | bicubic       | [google](https://drive.google.com/file/d/1ffJ-tG_CGVXztPEPQMaT_lUoc4hxFy__/view?usp=sharing)/[baidu](https://pan.baidu.com/s/19DhlLIFyPGOWtyq_c83ZGQ)(8a1i) |
| shuffle_vit_small_patch4_window7| 83.53 | 96.57 | 224        | 0.875      | bicubic       | [google](https://drive.google.com/file/d/1du9H0SKr0QH9GQjhWDOXOnhpSVpfbb8X/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1rM2J8BVwxQ3kRZoHngwNZA)(xwh3) |
| shuffle_vit_base_patch4_window7| 83.95  | 96.91 | 224        | 0.875      | bicubic       | [google](https://drive.google.com/file/d/1sYh808AyTG3-_qv6nfN6gCmyagsNAE6q/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1fks_IYDdnXdAkCFuYHW_Nw)(1gsr) |
| cswin_tiny_224  | 82.81  | 96.30 | 224        | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1l-JY0u7NGyD6SjkyiyNnDx3wFFT1nAYO/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1L5FqU7ImWAhQHAlSilqVAw)(4q3h) |
| cswin_small_224 | 83.60  | 96.58 | 224        | 0.9      | bicubic       | [google](https://drive.google.com/file/d/10eEBk3wvJdQ8Dy58LvQ11Wk1K2UfPy-E/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1FiaNiWyAuWu1IBsUFLUaAw)(gt1a) |
| cswin_base_224  | 84.23  | 96.91 | 224        | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1YufKh3DKol4-HrF-I22uiorXSZDIXJmZ/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1koy8hXyGwvgAfUxdlkWofg)(wj8p) |
| cswin_large_224 | 86.52  | 97.99 | 224        | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1V1hteGK27t1nI84Ac7jdWfydBLLo7Fxt/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1KgIX6btML6kPiPGkIzvyVA)(b5fs) |
| cswin_base_384  | 85.51  | 97.48 | 384        | 1.0      | bicubic       | [google](https://drive.google.com/file/d/1qCaFItzFoTYBo-4UbGzL6M5qVDGmJt4y/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1WNkY7o_vP9KJ8cd5c7n2sQ)(rkf5) |
| cswin_large_384 | 87.49  | 98.35 | 384        | 1.0      | bicubic       | [google](https://drive.google.com/file/d/1LRN_6qUz71yP-OAOpN4Lscb8fkUytMic/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1eCIpegPj1HIbJccPMaAsew)(6235) |
| t2t_vit_7      | 71.68 | 90.89 | 224   | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1YkuPs1ku7B_udydOf_ls1LQvpJDg_c_j/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1jVNsz37gatLCDaOoU3NaMA)(1hpa) |
| t2t_vit_10     | 75.15 | 92.80 | 224   | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1H--55RxliMDlOCekn7FpKrHDGsUkyrJZ/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1nbdb4PFMq4nsIp8HrNxLQg)(ixug) |
| t2t_vit_12     | 76.48 | 93.49 | 224   | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1stnIwOwaescaEcztaF1QjI4NK4jaqN7P/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1DcMzq9WeSwrS3epv6jKJXw)(qpbb) |
| t2t_vit_14     | 81.50 | 95.67 | 224   | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1HSvN3Csgsy7SJbxJYbkzjUx9guftkfZ1/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1wcfh22uopBv7pS7rKcH_iw)(c2u8) |
| t2t_vit_19     | 81.93 | 95.74 | 224   | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1eFnhaL6I33pHCQw2BaEE0Oet9CnjmUf_/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1Hpyc5hBYo1zqoXWpryegnw)(4in3) |
| t2t_vit_24     | 82.28 | 95.89 | 224   | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1Z7nZCHeFp0AhIkGYcMAFkKdkGN0yXtpv/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1Hpyc5hBYo1zqoXWpryegnw)(4in3) |
| t2t_vit_t_14   | 81.69 | 95.85 | 224   | 0.9      | bicubic       | [google](https://drive.google.com/file/d/16li4voStt_B8eWDXqJt7s20OT_Z8L263/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1Hpyc5hBYo1zqoXWpryegnw)(4in3) |
| t2t_vit_t_19   | 82.44 | 96.08 | 224   | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1Ty-42SYOu15Nk8Uo6VRTJ7J0JV_6t7zJ/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1YdQd6l8tj5xMCWvcHWm7sg)(mier) |
| t2t_vit_t_24   | 82.55 | 96.07 | 224   | 0.9      | bicubic       | [google](https://drive.google.com/file/d/1cvvXrGr2buB8Np2WlVL7n_F1_CnI1qow/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1BMU3KX_TRmPxQ1jN5cmWhg)(6vxc) |
| t2t_vit_14_384 | 83.34 | 96.50 | 384   | 1.0      | bicubic       | [google](https://drive.google.com/file/d/1Yuso8WD7Q8Lu_9I8dTvAvkcXXtPSkmnm/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1AOMhyVRF9zPqJe-lTrd7pw)(r685) |




### Object Detection ###
| Model | backbone  | box_mAP | Model                                                                                                                                                       |
|-------|-----------|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| DETR  | ResNet50  | 42.0    | [google](https://drive.google.com/file/d/1ruIKCqfh_MMqzq_F4L2Bv-femDMjS_ix/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1J6lB1mezd6_eVW3jnmohZA)(n5gk) |
| DETR  | ResNet101 | 43.5    | [google](https://drive.google.com/file/d/11HCyDJKZLX33_fRGp4bCg1I14vrIKYW5/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1_msuuAwFMNbAlMpgUq89Og)(bxz2) |

### Semantic Segmentation ###
#### Pascal Context ####
|Model      | Backbone  | Batch_size | mIoU (ss) | mIoU (ms+flip) | Backbone_checkpoint | Model_checkpoint      |     ConfigFile  |
|-----------|-----------|------------|-----------|----------------|-----------------------------------------------|-----------------------------------------------------------------------|------------|
|SETR_Naive | ViT_large |     16     |   52.06   |      52.57        | [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)     | [google](https://drive.google.com/file/d/1AUyBLeoAcMH0P_QGer8tdeU44muTUOCA/view?usp=sharing)/[baidu](https://pan.baidu.com/s/11XgmgYG071n_9fSGUcPpDQ)(xdb8)   | [config](semantic_segmentation/configs/setr/SETR_Naive_Large_480x480_80k_pascal_context_bs_16.yaml) | 
|SETR_PUP   | ViT_large |     16     |   53.90   |       54.53    | [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)     | [google](https://drive.google.com/file/d/1IY-yBIrDPg5CigQ18-X2AX6Oq3rvWeXL/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1v6ll68fDNCuXUIJT2Cxo-A)(6sji) | [config](semantic_segmentation/configs/setr/SETR_PUP_Large_480x480_80k_pascal_context_bs_16.yaml) |
|SETR_MLA   | ViT_Large |     8      |   54.39   |       55.16       | [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)     | [google](https://drive.google.com/file/d/1utU2h0TrtuGzRX5RMGroudiDcz0z6UmV/view)/[baidu](https://pan.baidu.com/s/1Eg0eyUQXc-Mg5fg0T3RADA)(wora)| [config](semantic_segmentation/configs/setr/SETR_MLA_Large_480x480_80k_pascal_context_bs_8.yaml) |
|SETR_MLA   | ViT_large |     16     |   55.01   |       55.87        | [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)     | [google](https://drive.google.com/file/d/1SOXB7sAyysNhI8szaBqtF8ZoxSaPNvtl/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1jskpqYbazKY1CKK3iVxAYA)(76h2) | [config](semantic_segmentation/configs/setr/SETR_MLA_Large_480x480_80k_pascal_context_bs_16.yaml) |

#### Cityscapes ####
|Model      | Backbone  | Batch_size | Iteration | mIoU (ss) | mIoU (ms+flip) | Backbone_checkpoint | Model_checkpoint     |     ConfigFile  |
|-----------|-----------|------------|-----------|-----------|----------------|-----------------------------------------------|-----------------------------------------------------------------------|------------|
|SETR_Naive | ViT_Large |     8      |     40k   |   76.71   |       79.03        | [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)      | [google](https://drive.google.com/file/d/1QialLNMmvWW8oi7uAHhJZI3HSOavV4qj/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1F3IB31QVlsohqW8cRNphqw)(g7ro)  |  [config](semantic_segmentation/configs/setr/SETR_Naive_Large_768x768_40k_cityscapes_bs_8.yaml)| 
|SETR_Naive | ViT_Large |     8      |     80k   |   77.31   |       79.43      | [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)      | [google](https://drive.google.com/file/d/1RJeSGoDaOP-fM4p1_5CJxS5ku_yDXXLV/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1XbHPBfaHS56HlaMJmdJf1A)(wn6q)   |  [config](semantic_segmentation/configs/setr/SETR_Naive_Large_768x768_80k_cityscapes_bs_8.yaml)| 
|SETR_PUP   | ViT_Large |     8      |     40k   |   77.92   |       79.63        |  [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)     | [google](https://drive.google.com/file/d/12rMFMOaOYSsWd3f1hkrqRc1ThNT8K8NG/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1H8b3valvQ2oLU9ZohZl_6Q)(zmoi)    | [config](semantic_segmentation/configs/setr/SETR_PUP_Large_768x768_40k_cityscapes_bs_8.yaml)| 
|SETR_PUP   | ViT_Large |     8      |     80k   |   78.81   |       80.43     |   [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)    | [baidu](https://pan.baidu.com/s/1tkMhRzO0XHqKYM0lojE3_g)(f793)    | [config](semantic_segmentation/configs/setr/SETR_PUP_Large_768x768_80k_cityscapes_bs_8.yaml)| 
|SETR_MLA   | ViT_Large |     8      |     40k   |   76.70    |       78.96      |   [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)    | [baidu](https://pan.baidu.com/s/1sUug5cMKSo6mO7BEI4EV_w)(qaiw)    | [config](semantic_segmentation/configs/setr/SETR_MLA_Large_768x768_40k_cityscapes_bs_8.yaml)| 
|SETR_MLA   | ViT_Large |     8      |     80k   |  77.26     |       79.27      |   [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)    | [baidu](https://pan.baidu.com/s/1IqPZ6urdQb_0pbdJW2i3ow)(6bgj)    | [config](semantic_segmentation/configs/setr/SETR_MLA_Large_768x768_80k_cityscapes_bs_8.yaml)| 


#### ADE20K ####
|Model      | Backbone  | Batch_size | Iteration | mIoU (ss) | mIoU (ms+flip) | Backbone_checkpoint | Model_checkpoint     |     ConfigFile  |
|-----------|-----------|------------|-----------|-----------|----------------|-----------------------------------------------|-----------------------------------------------------------------------|------------|
|SETR_Naive | ViT_Large |     16      |     160k   | 47.57   |      48.12        |   [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)    | [baidu](https://pan.baidu.com/s/1_AY6BMluNn71UiMNZbnKqQ)(lugq)   | [config](semantic_segmentation/configs/setr/SETR_Naive_Large_512x512_160k_ade20k_bs_16.yaml)| 
|SETR_PUP   | ViT_Large |     16      |     160k   |  49.12   |      49.51        |   [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)    | [baidu](https://pan.baidu.com/s/1N83rG0EZSksMGZT3njaspg)(udgs)    | [config](semantic_segmentation/configs/setr/SETR_PUP_Large_512x512_160k_ade20k_bs_16.yaml)| 
|SETR_MLA   | ViT_Large |     8      |     160k   |  47.80   |       49.34        |   [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)    | [baidu](https://pan.baidu.com/s/1L83sdXWL4XT02dvH2WFzCA)(mrrv)    | [config](semantic_segmentation/configs/setr/SETR_MLA_Large_512x512_160k_ade20k_bs_8.yaml)| 
|DPT        | ViT_Large |     16     |     160k   |  47.21   |       -        |   [google](https://drive.google.com/file/d/1TPgh7Po6ayYb1DksJeZp60LGnNyznr-r/view?usp=sharing)/[baidu](https://pan.baidu.com/s/18WSi8Jp3tCZgv_Vr3V1i7A)(owoj)      |[baidu](https://pan.baidu.com/s/1PCSC1Kvcg291gqp6h5pDCg)(ts7h)   |  [config](semantic_segmentation/configs/dpt/DPT_Large_480x480_160k_ade20k_bs_16.yaml)
|Segmenter  | ViT_Tiny  |     16     |     160k   |  38.45   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/1nZptBc-IY_3PFramXSlovQ)(1k97)   |  [config](semantic_segmentation/configs/segmenter/segmenter_Tiny_512x512_160k_ade20k_bs_16.yaml)
|Segmenter  | ViT_Small |     16     |     160k   |  46.07   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/1gKE-GEu7gX6dJsgtlvrmWg)(i8nv)   |  [config](semantic_segmentation/configs/segmenter/segmenter_small_512x512_160k_ade20k_bs_16.yaml)
|Segmenter  | ViT_Base  |     16     |     160k   |  49.08   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/1qb7HEtKW0kBSP6iv-r_Hjg)(hxrl)   |  [config](semantic_segmentation/configs/segmenter/segmenter_Base_512x512_160k_ade20k_bs_16.yaml) |
|Segmenter  | ViT_Large  |     16     |     160k   |  51.82   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/121FOwpsYue7Z2Rg3ZlxnKg)(wdz6)   |  [config](semantic_segmentation/configs/segmenter/segmenter_Tiny_512x512_160k_ade20k_bs_16.yaml)
|Segmenter_Linear  | DeiT_Base |     16     |     160k   |  47.34   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/1Hk_zcXUIt_h5sKiAjG2Pog)(5dpv)   |  [config](semantic_segmentation/configs/segmenter/segmenter_Base_distilled_512x512_160k_ade20k_bs_16.yaml)
|Segmenter  | DeiT_Base |     16     |     160k   |  49.27   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/1-TBUuvcBKNgetSJr0CsAHA)(3kim)   |  [config](semantic_segmentation/configs/segmenter/segmenter_Base_distilled_512x512_160k_ade20k_bs_16.yaml) |
|Segformer  | MIT-B0 |     16     |     160k   |  38.37   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/1WOD9jGjQRLnwKrRYzgBong)(ges9)   |  [config](semantic_segmentation/configs/segformer/segformer_mit-b0_512x512_160k_ade20k.yaml) |
|Segformer  | MIT-B1 |     16     |     160k   |  42.20   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/1aiSBXMd8nP82XK7sSZ05gg)(t4n4)   |  [config](semantic_segmentation/configs/segmenter/segformer_mit-b1_512x512_160k_ade20k.yaml) |
|Segformer  | MIT-B2 |     16     |     160k   |  46.38   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/1wFFh-K5t46YktkfoWUOTAg)(h5ar)   |  [config](semantic_segmentation/configs/segmenter/segformer_mit-b2_512x512_160k_ade20k.yaml) |
|Segformer  | MIT-B3 |     16     |     160k   |  48.35   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/1IwBnDeLNyKgs-xjhlaB9ug)(g9n4)   |  [config](semantic_segmentation/configs/segmenter/segformer_mit-b3_512x512_160k_ade20k.yaml) |
|Segformer  | MIT-B4 |     16     |     160k   |  49.01   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/1a25fCVlwJ-1TUh9HQfx7YA)(e4xw)   |  [config](semantic_segmentation/configs/segmenter/segformer_mit-b4_512x512_160k_ade20k.yaml) |
|Segformer  | MIT-B5 |     16     |     160k   |  49.73   |       -        |   TODO      |[baidu](https://pan.baidu.com/s/15kXXxKEjjtJv-BmrPnSTOw)(uczo)   |  [config](semantic_segmentation/configs/segmenter/segformer_mit-b5_512x512_160k_ade20k.yaml) |
| UperNet  | Swin_Tiny |     16     |     160k   |  44.90   |       45.37     |   -      |[baidu](https://pan.baidu.com/s/1S8JR4ILw0u4I-DzU4MaeVQ)(lkhg)   |  [config](semantic_segmentation/configs/upernet_swin/upernet_swin_tiny_patch4_windown7_512x512_160k_ade20k.yaml) |
| UperNet  | Swin_Small |     16     |     160k   |  47.88   |       48.90      |   -      |[baidu](https://pan.baidu.com/s/17RKeSpuWqONVptQZ3B4kEA)(vvy1)   |  [config](semantic_segmentation/configs/upernet_swin/upernet_swin_small_patch4_windown7_512x512_160k_ade20k.yaml) |
| UperNet  | Swin_Base |     16     |     160k   |   48.59   |       49.04      |   -      |[baidu](https://pan.baidu.com/s/1bM15KHNsb0oSPblQwhxbgw)(y040)   |  [config](semantic_segmentation/configs/upernet_swin/upernet_swin_base_patch4_windown7_512x512_160k_ade20k.yaml) |

#### Trans10kV2 ####
|Model      | Backbone  | Batch_size | Iteration | mIoU (ss) | mIoU (ms+flip) | Backbone_checkpoint | Model_checkpoint     |     ConfigFile  |
|-----------|-----------|------------|-----------|-----------|----------------|-----------------------------------------------|-----------------------------------------------------------------------|------------|
|Trans2seg_Medium | Resnet50c |     16      |    80k    |  72.25  |      -        |   [google](https://drive.google.com/file/d/1C6nMg6DgQ73wzF21UwDVxmkcRTeKngnK/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1hs0tbSGIeMLLGMq05NN--w)(4dd5)    | [google](https://drive.google.com/file/d/1zGEBEN27CQMgZBYqqAg_agJE6CPLOpYW/view?usp=sharing)/[baidu](https://pan.baidu.com/s/102GUBeoEPMqMEqF3smgyCA)(qcb0)   | [config](semantic_segmentation/configs/trans2seg/Trans2Seg_medium_512x512_80k_trans10kv2_bs_16.yaml)| 

### GAN ###
| Model                          | FID | Image Size | Crop_pct | Interpolation | Model        |
|--------------------------------|-----|------------|----------|---------------|--------------|
| styleformer_cifar10            |2.73 | 32         | 1.0      | lanczos       |[google](https://drive.google.com/file/d/1VnldZcvh-d7fAoC0_U3tVW8U3InhtuB8/view?usp=sharing)/[baidu](https://pan.baidu.com/s/12hIzNLKpNJpAC31QwdtuiA)(7cg2)  |
| styleformer_stl10              |15.65| 48         | 1.0      | lanczos       |[google](https://drive.google.com/file/d/1IGxpGLmCq74JBEfrjTq_m9hSEif3R5dZ/view?usp=sharing)/[baidu](https://pan.baidu.com/s/16m3lZA00-oJOryTNYP64pQ)(8pus)|
| styleformer_celeba             |3.32 | 64         | 1.0      | lanczos       |[google](https://drive.google.com/file/d/1Ux4zNmkFUa6mAZsMbvSBGpxfSdTok0wn/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1zDC_3YUWmdsxM1FUDEQuuQ)(ymh7) |
| styleformer_lsun               | 9.68 | 128        | 1.0      | lanczos       |[google](https://drive.google.com/file/d/1kMX9vHhNKkTjzxRBAnBji5yV1B-fgfsi/view?usp=sharing)/[baidu](https://pan.baidu.com/s/1PM4D-eH2ITU6vKgAAMNY5w)(ue28)|
> *The results are evaluated on Cifar10, STL10, Celeba and LSUNchurch dataset, using **fid50k_full** metric.
## Results (Self-Trained Weights) ## 
### Image Classification ###
### Object Detection ###
### Segmentation ###
### GAN ###




## Validation Scripts ##
### Run on single GPU: ###

`sh run_eval.sh`

 or you can run the python script:

 `python main_single_gpu.py`

 with proper settings.

The script `run_eval.sh` calls the main python script `main_single_gpu.py` with a number of options, usually you need to change the following settings, e.g., for ViT base model:
```shell
python main_single_gpu.py \
-cfg='./configs/vit_base_patch16_224.yaml' \
-dataset='imagenet2021' \
-data_path='/dataset/imagenet' \
-batch_size=128 \
-eval \
-pretrained='./vit_base_patch16_224'
```
> Note:
> - The `-pretrained` option accepts the path of pretrained weights file **without** the file extension (.pdparams).

### Run on multi GPU: ###

`sh run_eval_multi.sh`

 or you can run the python script:

 `python main_multi_gpu.py`

 with proper settings.

The script `run_eval_multi.sh` calls the main python script `main_multi_gpu.py` with a number of options, usually you need to change the following settings, e.g., for ViT base model:
```shell
CUDA_VISIBLE_DEVICES=0,1,2,3,4,5,6,7
python main_multi_gpu.py \
-cfg='./configs/vit_base_patch16_224.yaml' \
-dataset='imagenet2021' \
-data_path='/dataset/imagenet' \
-batch_size=128 \
-eval \
-pretrained='./vit_base_patch16_224'
-ngpus=8
```
> Note:
>
> - that the `-pretrained` option accepts the path of pretrained weights file **without** the file extension (.pdparams).
>
> - If `-ngpu` is not set, all the available GPU devices will be used.


## Training Scripts ##
### Train on single GPU: ###

`sh run_train.sh`

 or you can run the python script:

 `python main_single_gpu.py`

 with proper settings.

The script `run_train.sh` calls the main python script `main_single_gpu.py` with a number of options, usually you need to change the following settings, e.g., for ViT base model:
```shell
python main_single_gpu.py \
-cfg='./configs/vit_base_patch16_224.yaml' \
-dataset='imagenet2021' \
-data_path='/dataset/imagenet' \
-batch_size=128 \
```
> Note:
> - The training options such as lr, image size, model layers, etc., can be changed in the `.yaml` file set in `-cfg`. All the available settings can be found in `./config.py`

### Run on multi GPU: ###

`sh run_train_multi.sh`

 or you can run the python script:

 `python main_multi_gpu.py`

 with proper settings.

The script `run_train_multi.sh` calls the main python script `main_multi_gpu.py` with a number of options, usually you need to change the following settings, e.g., for ViT base model:
```shell
CUDA_VISIBLE_DEVICES=0,1,2,3,4,5,6,7
python main_multi_gpu.py \
-cfg='./configs/vit_base_patch16_224.yaml' \
-dataset='imagenet2021' \
-data_path='/dataset/imagenet' \
-batch_size=128 \
-ngpus=8
```
> Note:
>
> - The training options such as lr, image size, model layers, etc., can be changed in the `.yaml` file set in `-cfg`. All the available settings can be found in `./config.py`
> - If `-ngpu` is not set, all the available GPU devices will be used.


## Features ##
* optimizers
* Schedulers
* DDP
* Data Augumentation
* DropPath

## Contributing ##
We encourage and appreciate your contribution to **PPViT** project, please refer to our workflow and work styles by [CONTRIBUTING.md](https://github.com/xperzy/PPViT/blob/develop/CONTRIBUTING.md)


## Licenses ##
#### Code #####
This repo is under the Apache-2.0 license. 

#### Pretrained Weights #####


## Citing #
>
