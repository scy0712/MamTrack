<div align="center">
<h1>Exploring Historical Information for RGBE Visual Tracking with Mamba</h1>

[**Chuanyu Sun**](https://sunchuanyu.github.io/)<sup>1*</sup>&emsp;[**Jiqing Zhang**](https://zhangjiqing.com/)<sup>2*</sup>&emsp;Yang Wang<sup>1</sup>&emsp;Huilin Ge<sup>3</sup>&emsp;Qianchen Xia<sup>4</sup>&emsp;Baocai Yin<sup>5</sup>&emsp;[**Xin Yang**](https://xinyangdut.github.io/)<sup>1</sup>   
<br>
<sup>1</sup>Key Laboratory of Social Computing and Cognitive Intelligence, Dalian University of Technology;
<br>
<sup>2</sup>Dalian Maritime University&emsp;<sup>3</sup>Jiangsu University of Science and Technology
<br>
<sup>4</sup>The Future Laboratory, Tsinghua University&emsp;<sup>5</sup>Beijing University of Technology
<br>
*Equal Contribution
<br>
<a href='https://MamTrack.github.io'>Project Page</a>
</div>


## Highlights
:star: Our paper has been accepted by CVPR2025 ! 
## Abstract
Combining the advantages of conventional and event cameras for robust visual tracing has drawn extensive interest. However, existing tracking approaches heavily engage in complex cross-modal fusion modules, leading to higher computational complexity and training challenges. Besides, these methods generally ignore the effective integration of historical information, which is crucial to grasping the change in the target's appearance and motion trends. Given the recent advancements in Mamba's long-range modeling and linear complexity, we explore its potential in addressing the above issues in RGBE tracking tasks. Specifically, we first propose an efficient fusion module based on Mamba, which utilizes a simple gate-based interaction scheme to achieve effective modality-selective fusion. This module can be seamlessly integrated into the encoding layer of prevalent Transformer-based backbones. Moreover, we further present a novel historical decoder that leverages Mamba's advanced long sequence modeling to effectively capture the target appearance changes with autoregressive queries. Extensive experiments show that our proposed approach achieves state-of-the-art performance on multiple challenging short-term and long-term RGBE benchmarks. Besides, the effectiveness of each key Mamba-based component of our approach is evidenced by our thorough ablation study.

## Citation

If you find this project useful, please consider citing:

```bibtex
@inproceedings{mamtrack,
  title={Exploring Historical Information for RGBE Visual Tracking with Mamba},
  author={Sun, Chuanyu and Zhang, Jiqing and Wang, Yang and Ge, Huilin and Xia, Qianchen and Yin, Baocai and Yang, Xin},
  booktitle={IEEE Conference on Computer Vision and Pattern Recognition},
  year={2025}
}

```
