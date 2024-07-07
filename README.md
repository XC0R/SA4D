# Segment Any 4D Gaussians
### [Project Page](https://jsxzs.github.io/sa4d/) 
<!-- | [arxiv Paper](https://arxiv.org/abs/2406.18462) -->

[Shengxiang Ji](https://github.com/jsxzs)<sup>1*</sup>, [Guanjun Wu](https://guanjunwu.github.io/)<sup>1*</sup>
[Jiemin Fang](https://jaminfong.cn/)<sup>2</sup>, [Jiazhong Cen](https://jumpat.github.io/SA3D/)<sup>3</sup>, [Taoran Yi](https://github.com/taoranyi)<sup>1</sup>, 
[Wenyu Liu](http://eic.hust.edu.cn/professor/liuwenyu/)<sup>1</sup>, [Qi Tian](https://www.qitian1987.com/)<sup>2</sup>, [Xinggang Wang](https://xwcv.github.io/)<sup>1✉</sup>

<sup>1</sup>HUST&emsp;<sup>2</sup>Huawei Inc.&emsp;<sup>3</sup>Shanghai Jiao Tong University &emsp; 

<sup>*</sup>Equal Contributions.&emsp;<sup>✉</sup>Corresponding Author. 

![Teaser image](assets/teaserfig.png)

## Abstract
Modeling, understanding, and reconstructing the real world are crucial in XR/VR. Recently, 3D Gaussian Splatting (3D-GS) methods have shown remarkable success in modeling and understanding 3D scenes. Similarly, various 4D representations have demonstrated the ability to capture the dynamics of the 4D world. However, there is a dearth of research focusing on segmentation within 4D representations. In this paper, we propose to Segment Any 4D Gaussians (SA4D), the first framework to segment anything in the 4D digital world based on 4D Gaussians. In SA4D, an efficient temporal identity feature field is introduced to handle Gaussian drifting, with the potential to learn precise identity feature from noisy and sparse input. Additionally, a 4D segmentation refinement process is proposed to remove artifacts. Our SA4D achieves precise, high-quality segmentation within seconds in 4D Gaussians and shows the ability of removal, recoloring, composition and rendering high quality novel anything masks.


## 🦾 Updates
- 7/07/2024: Initialize the project. Code will come soon.


<!-- ## 📑 Citation

```
@article{GaussianDreamerPro,
    title={GaussianDreamerPro: Text to Manipulable 3D Gaussians with Highly Enhanced Quality},
    author={Yi, Taoran and Fang, Jiemin and Zhou, Zanwei and Wang, Junjie and Wu, Guanjun and Xie, Lingxi and Zhang, Xiaopeng and Liu, Wenyu and Wang, Xinggang and Tian, Qi},
    journal={arXiv:2406.18462},
    year={2024}
} -->