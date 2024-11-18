<h1 align="center" style="border-bottom: none;"> Vision Mamba-based autonomous crack segmentation on structural surfaces </h1>
 
- This is the implementation for the publication of *"Vision Mamba-based autonomous crack segmentation on structural surfaces"*. 
- (https://arxiv.org/abs/2406.16518).
- The whole framework is run on Linux Ubuntu 22.04 system, based on python 3.10.12.
- Please install the environment in the "requirement.txt" before running the code.

- ## The code will be released gradually. ##
- CNN-based: UNet & LinkNet with the EfficientNet-B7 backbone (UNet-EB7 & LinkNet-EB7); 
- Transformer-based: SwinUNet & SegFormer-B5; 
- CNN-Transformer hybrid-designed: TransUNet & DTrC-Net; 
- Efficient self-attention designed: PoolingCrack
- Mamba-based: VM-UNet

## Graph Abstract
<div align="center">
<img src= "https://github.com/user-attachments/assets/e1260345-54a8-41be-86fb-7dd65b885a38"> 
</div>
<div align="center">
<img src= "https://github.com/user-attachments/assets/fe4c8deb-1819-4b31-8bde-25d744c5f6bd"> 
</div>
<div align="center">
<img src= "https://github.com/user-attachments/assets/2a1a8de6-1cb9-45e7-a046-600d2a012685"> 
</div>

## Citations
<details>
<summary>Click to see citations</summary>
<div style="overflow-y: scroll; height: 100px;">
<pre>
@article{
title={U-net: convolutional networks for biomedical image segmentation},
author={Olaf Ronneberger, Philipp Fischer, Thomas Brox},
conference={Medical Image Computing and Computer-Assisted Intervention–18th International Conference},
year={2015}
}
@article{
title={Linknet: Exploiting encoder representations for efficient semantic segmentation},
author={Abhishek Chaurasia, Eugenio Culurciello},
conference={IEEE visual communications and image processing},
year={2017}
}
@article{
title={Efficientnet: rethinking model scaling for convolutional neural networks},
author={Mingxing Tan, Quoc V. Le},
conference={Proceedings of Machine Learning Research},
year={2019}
}
@article{
title={Swin-unet: Unet-like pure transformer for medical image segmentation},
author={Hu Cao, Yueyue Wang, Joy Chen, Dongsheng Jiang, Xiaopeng Zhang, Qi Tian, Manning Wang},
conference={European Conference on Computer Vision},
year={2022}
}
@article{
title={SegFormer: simple and efficient design for semantic segmentation with transformers},
author={Enze Xie, Wenhai Wang, Zhiding Yu, Anima Anandkumar, Jose M. Alvarez, Ping Luo},
conference={Advances in Neural Information Processing Systems},
year={2021}
} 
@article{chen2021transunet,
  title={TransUNet: Transformers Make Strong Encoders for Medical Image Segmentation},
  author={Chen, Jieneng and Lu, Yongyi and Yu, Qihang and Luo, Xiangde and Adeli, Ehsan and Wang, Yan and Lu, Le and Yuille, Alan L., and Zhou, Yuyin},
  journal={arXiv preprint arXiv:2102.04306},
  year={2021}
}
@article{
title={A crack-segmentation algorithm fusing transformers and convolutional neural networks for complex detection scenarios},
author={Chao Xiang, Jingjing Guo, Ran Cao, Lu Deng},
journal={Automation in Construction},
year={2023}
}
@article{
title={An average pooling designed Transformer for robust crack segmentation},
author={Zhaohui Chen, Elyas Asadi Shamsabadi, Sheng Jiang, Luming Shen, and Daniel Dias-da-Costa},
journal={Automation in Construction},
year={2024}
}
@article{
title={Vm-unet: Vision mamba unet for medical image segmentation},
author={Jiacheng Ruan, Suncheng Xiang},
journal={arXiv preprint arXiv:2402.02491},
year={2024}
}
</pre>
</div>
