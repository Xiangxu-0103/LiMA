<div align="right">English | <a href="./README_CN.md">简体中文</a></div>

<div align="center">
    <h2><strong>Beyond One Shot, Beyond One Perspective: Cross-View and Long-Horizon Distillation for Better LiDAR Representations</strong></h2>
</div>

<div align="center">
    <a href="https://xiangxu-0103.github.io/" target='_blank'>Xiang Xu</a><sup>1</sup>&nbsp;&nbsp;&nbsp;
    <a href="https://ldkong.com/" target='_blank'>Lingdong Kong</a><sup>2</sup>&nbsp;&nbsp;&nbsp;
    <a href="https://songw-zju.github.io/" target='_blank'>Song Wang</a><sup>3</sup>&nbsp;&nbsp;&nbsp;
    <a href="https://github.com/deepcharle" target='_blank'>Chuanwei Zhou</a><sup>4</sup>&nbsp;&nbsp;&nbsp;
    <a href="https://scholar.google.com/citations?user=2Pyf20IAAAAJ" target='_blank'>Qingshan Liu</a><sup>4</sup>&nbsp;&nbsp;&nbsp;
    </br></br>
    <sup>1</sup>NUAA&nbsp;&nbsp;&nbsp;
    <sup>2</sup>NUS&nbsp;&nbsp;&nbsp;
    <sup>3</sup>ZJU&nbsp;&nbsp;&nbsp;
    <sup>4</sup>NJUPT&nbsp;&nbsp;&nbsp;
</div>

<br/>

<div align="center">
    <a href="" target='_blank'>
        <img src="https://img.shields.io/badge/Paper-%F0%9F%93%83-lightblue">
    </a>&nbsp;
    <a href="https://xiangxu-0103.github.io/LiMA" target='_blank'>
        <img src="https://img.shields.io/badge/Project-%F0%9F%94%97-blue">
    </a>&nbsp;
    <a href="" target='_blank'>
        <img src="https://img.shields.io/badge/Demo-%F0%9F%8E%AC-pink">
    </a>&nbsp;
    <a href="" target='_blank'>
        <img src="https://img.shields.io/badge/%E4%B8%AD%E8%AF%91%E7%89%88-%F0%9F%90%BC-red">
    </a>&nbsp;
    <a href="" target='_blank'>
        <img src="https://visitor-badge.laobi.icu/badge?page_id=Xiangxu-0103.LiMA&left_color=gray&right_color=lightgreen"/>
  </a>
</div>

# About

LiMA is a novel long-term image-to-LiDAR Memory Aggregation framework that explicitly captures longer range temporal correlations to enhance LiDAR representation learning. It comprises three key components: 1) a **Cross-View Aggregation** module that aligns and fuses overlapping regions across neighboring camera views, constructing a more unified and redundancy-free memory bank; 2) a **Long-Term Feature Propagation** mechanism that efficiently aligns and integrates multi-frame image features, reinforcing temporal coherence during LiDAR representation learning; and 3) a **Cross-Sequence Memory Alignment** strategy that enforces consistency across driving sequences, improving generalization to unseen environments.

## :memo: Updates

- \[2025.06\] - Our paper **LiMA** has been accepted to **ICCV 2025**! :tada:

# License

This work is under the [Apache License Version 2.0](https://www.apache.org/licenses/LICENSE-2.0), while some specific implementations in this codebase might be with other licenses.

Kindly refer to [LICENSE.md](./docs/LICENSE) for a more careful check, if you are using our code for commercial matters.

# Citation

If you find this work helpful for your research, please kindly consider citing our paper:

```bibtex
@inproceedings{xu2025lima,
    title = {Beyond One Shot, Beyond One Perspective: Cross-View and Long-Horizon Distillation for Better LiDAR Representations},
    author = {Xu, Xiang and Kong, Lingdong and Wang, Song and Zhou, Chuanwei and Liu, Qingshan},
    booktitle = {IEEE/CVF International Conference on Computer Vision},
    year = {2025}
}
```

# Acknowledgments

This work is developed based on the [MMDetection3D](https://github.com/open-mmlab/mmdetection3d) codebase.

> <img src="https://github.com/open-mmlab/mmdetection3d/blob/main/resources/mmdet3d-logo.png" width="30%"/><br>
> MMDetection3D is an open-source object detection toolbox based on PyTorch, towards the next-generation platform for general 3D perception. It is a part of the OpenMMLab project developed by MMLab.

We acknowledge the use of the following public resources during the couuse of this work: <sup>1</sup>[nuScenes](https://www.nuscenes.org/nuscenes), <sup>2</sup>[nuScenes-devkit](https://github.com/nutonomy/nuscenes-devkit), <sup>3</sup>[SemanticKITTI](http://www.semantic-kitti.org), <sup>4</sup>[SemanticKITTI-API](https://github.com/PRBonn/semantic-kitti-api), , <sup>5</sup>[WaymoOpenDataset](https://waymo.com/open), <sup>6</sup>[Synth4D](https://github.com/saltoricristiano/gipso-sfouda), <sup>7</sup>[ScribbleKITTI](https://github.com/ouenal/scribblekitti), <sup>8</sup>[RELLIS-3D](https://github.com/unmannedlab/RELLIS-3D), <sup>9</sup>[SemanticPOSS](http://www.poss.pku.edu.cn/semanticposs.html), <sup>10</sup>[SemanticSTF](https://github.com/xiaoaoran/SemanticSTF), <sup>11</sup>[SynthLiDAR](https://github.com/xiaoaoran/SynLiDAR), <sup>12</sup>[DAPS-3D](https://github.com/subake/DAPS3D), <sup>13</sup>[Robo3D](https://github.com/ldkong1205/Robo3D), <sup>14</sup>[SLidR](https://github.com/valeoai/SLidR), <sup>15</sup>[DINOv2](https://github.com/facebookresearch/dinov2), <sup>16</sup>[FRNet](https://github.com/Xiangxu-0103/FRNet), <sup>17</sup>[SuperFlow](https://github.com/Xiangxu-0103/SuperFlow), <sup>18</sup>[torchsparse](https://github.com/mit-han-lab/torchsparse), <sup>19</sup>[ScaLR](https://github.com/valeoai/ScaLR). :heart_decoration:
