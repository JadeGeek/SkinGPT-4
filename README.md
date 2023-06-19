# SkinGPT-4: An Interactive Dermatology Diagnostic System with Visual Large Language Model

[Juexiao Zhou](https://www.joshuachou.ink/), Xiaonan He, Liyuan Sun, Jiannan Xu, Xiuying Chen, Yuetan Chu, Longxi Zhou, Xingyu Liao, Bin Zhang, Xin Gao

King Abdullah University of Science and Technology, KAUST

<a href='SkinGPT_4_manuscript_v4.pdf'><img src='https://img.shields.io/badge/Paper-PDF-red'></a>

## Installation

Please refer to the original MiniGPT-4: https://github.com/Vision-CAIR/MiniGPT-4


## Download our trained weights

**Our primary trained weights for skin disease diagnosis with only step-1 dataset could be downloaded at [skinGPT_v1.pth](https://drive.google.com/file/d/1PGBMBioipGxN5yfX6Okx4BGyPBm1prAF/view?usp=sharing).**

Then, set the path to the pretrained checkpoint in the evaluation config file in [eval_configs/minigpt4_eval.yaml](https://github.com/Vision-CAIR/MiniGPT-4/blob/main/eval_configs/minigpt4_eval.yaml#L10) at Line 11.

The model trained with both public datasets and the in-house dataset is **not publicly available** currently, but please feel free to keep in touch with **juexiao.zhou@kaust.edu.sa** and **xin.gao@kaust.edu.sa** for potential collaboration.

## Launching Demo Locally

```
python demo.py --cfg-path eval_configs/skingpt4_eval.yaml  --gpu-id 0
```

## Illustraion of SkinGPT-4

![fig1](https://cdn.jsdelivr.net/gh/JoshuaChou2018/oss@main/uPic/fig1.b1JNr3.png)



## Examples of Skin disease diagnosis

![fig3](https://cdn.jsdelivr.net/gh/JoshuaChou2018/oss@main/uPic/fig3.uiGBUM.png)



## Clinical Evaluation

![fig4](https://cdn.jsdelivr.net/gh/JoshuaChou2018/oss@main/uPic/fig4.CyZ6yO.png)



## Citation

If you're using SkinGPT-4 in your research or applications, please cite both SkinGPT-4 and MiniGPT-4 using this BibTeX:

```
@misc{zhou2023skingpt,
      title={SkinGPT-4: An Interactive Dermatology Diagnostic System with Visual Large Language Model}, 
      author={Juexiao Zhou and Xiaonan He and Liyuan Sun and Jiannan Xu and Xiuying Chen and Yuetan Chu and Longxi Zhou and Xingyu Liao and Bin Zhang and Xin Gao},
      year={2023},
      eprint={2304.10691},
      archivePrefix={arXiv},
      primaryClass={eess.IV}
}
```

```
@misc{zhu2022minigpt4,
      title={MiniGPT-4: Enhancing Vision-language Understanding with Advanced Large Language Models}, 
      author={Deyao Zhu and Jun Chen and Xiaoqian Shen and xiang Li and Mohamed Elhoseiny},
      year={2023},
}
```
