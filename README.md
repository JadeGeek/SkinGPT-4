# SkinGPT: A Dermatology Diagnostic System with Vision Large Language Model

[Juexiao Zhou](https://www.joshuachou.ink/), Xin Gao

King Abdullah University of Science and Technology, KAUST

<a href='SkinGPT_v1.pdf'><img src='https://img.shields.io/badge/Paper-PDF-red'></a>



## Installation

Please refer to the original MiniGPT-4: https://github.com/Vision-CAIR/MiniGPT-4



## Download our trained weights

**Our trained weights for skin disease diagnosis can be downloaded at [here](https://drive.google.com/file/d/1PGBMBioipGxN5yfX6Okx4BGyPBm1prAF/view?usp=sharing).**

Then, set the path to the pretrained checkpoint in the evaluation config file in [eval_configs/minigpt4_eval.yaml](https://github.com/Vision-CAIR/MiniGPT-4/blob/main/eval_configs/minigpt4_eval.yaml#L10) at Line 11.



## Launching Demo Locally

```
python demo.py --cfg-path eval_configs/minigpt4_eval.yaml  --gpu-id 0
```



## Illustraion of SkinGPT

![fig1](https://cdn.jsdelivr.net/gh/JoshuaChou2018/oss@main/uPic/fig1.C3gk9r.png)

## Examples of Skin disease diagnosis

![fig3](https://cdn.jsdelivr.net/gh/JoshuaChou2018/oss@main/uPic/fig3.PRlcFl.png)



## Citation

If you're using SkinGPT in your research or applications, please cite both SkinGPT and MiniGPT-4 using this BibTeX:

```
@misc{zhou2023skingpt,
      title={SkinGPT: A Dermatology Diagnostic System with Vision Large Language Model}, 
      author={Juexiao Zhou and Xin Gao},
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
