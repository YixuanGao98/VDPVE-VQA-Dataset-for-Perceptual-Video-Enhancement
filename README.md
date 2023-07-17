# VDPVE
## VQA Dataset for Perceptual Video Enhancement (VDPVE) 

This is the dataset built for the NTIRE 2023 Quality Assessment of Video Enhancement Challenge.

Since videos captured by camera/smartphone always need post-processing to obtain better visualization and higher practicability, many video enhancement algorithms have been proposed in recent years. The main goal of such video enhancement algorithms is to raise the video quality, such as sharpness, contrast, colorfulness, and stabilization. Therefore, how to compare the performances of different video enhancement algorithms becomes a novel task. Novel Video Quality Assessment (VQA) methods need to be proposed to faithfully predict the quality of enhanced videos, which can also promote the development of the video enhancement field.

Jointly with the NTIRE workshop, we have an NTIRE challenge on perceptual enhanced video quality assessment, that is, the task of predicting the perceptual quality of an enhanced video based on a set of prior examples of videos and their perceptual quality labels. The aim is to obtain a network design/solution capable to produce high-quality results with the best correlation to the reference ground truth (i.e., Mean Opinion Score, MOS).

The challenge uses a new dataset called VQA Dataset for Perceptual Video Enhancement （VDPVE）and has a single track. The training set contains 839 enhanced videos. Specifically, there are 414 videos with color enhancement, brightness enhancement, and contrast enhancement, 210 videos with deblurring, and 215 videos with deshaking. 

## Training Data:

Here, we only release the training set:

video：https://drive.google.com/file/d/1_vVmvKfY2G5p5LtP7t-0FzkpNg03wbSz/view

label: https://drive.google.com/file/d/1l0OQYkDPVgH-XnXnNeTYtdtOH88UGfwr/view


839 enhanced videos:

Axxxx_yy.mp4 refers to the video Axxxx.mp4 enhanced by color, contrast and brightness enhancement method yy.

Bxxxx_yy.mp4 refers to the video Bxxxx.mp4 stabilized by method yy.

Cxxxx_yy.mp4 refers to the video Cxxxx.mp4 deblurred by method yy.

MOS Scores: train.txt (Each line contains the enhanced video’s name and its corresponding MOS score. )


# Citation

Kindly cite our paper upon using this repository:

```
@inproceedings{gao2023vdpve,
  title={VDPVE: VQA Dataset for Perceptual Video Enhancement},
  author={Gao, Yixuan and Cao, Yuqin and Kou, Tengchuan and Sun, Wei and Dong, Yunlong and Liu, Xiaohong and Min, Xiongkuo and Zhai, Guangtao},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={1474--1483},
  year={2023}
}

@inproceedings{liu2023ntire,
  title={NTIRE 2023 Quality Assessment of Video Enhancement Challenge},
  author={Liu, Xiaohong and Timofte, Radu and Dong, Yunlong and Ma, Zhiliang and Fan, Haotian and Zhu, Chunzheng and Min, Xiongkuo and Zhai, Guangtao and Jia, Ziheng and Agarla, Mirko and others},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={1551--1569},
  year={2023}
}
```
