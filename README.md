# Pre-trained Multimodal Large Language Model Enhances Dermatological Diagnosis using SkinGPT-4

[Juexiao Zhou](https://www.joshuachou.ink/), Xiaonan He, Liyuan Sun, Jiannan Xu, Xiuying Chen, Yuetan Chu, Longxi Zhou, Xingyu Liao, Bin Zhang, Xin Gao

King Abdullah University of Science and Technology, KAUST

<a href='SkinGPT_4_manuscript_v7.pdf'><img src='https://img.shields.io/badge/Paper-PDF-red'></a>

## Installation

```
conda env create -f environment.yml
conda activate skingpt4
conda install -c conda-forge mamba=1.4.7
pip install einops
mamba install pytorch==2.0.0 torchvision==0.15.0 torchaudio==2.0.0 pytorch-cuda=11.8 -c pytorch -c nvidia
```

## Download our trained weights

**Our previous trained weights for skin disease diagnosis with only step-1 dataset and Vicuna could be downloaded at [skinGPT_v1.pth](https://drive.google.com/file/d/1PGBMBioipGxN5yfX6Okx4BGyPBm1prAF/view?usp=sharing).**

The latest model trained with both **public datasets** and the **proprietary dataset** based on **falcon-40b-instruct** and **llama-2-13b-chat-hf** are **not publicly available** currently.

Please feel free to keep in touch with **xin.gao@kaust.edu.sa** and **juexiao.zhou@kaust.edu.sa** for potential collaboration.


## Launching Demo Locally

```
python demo.py --cfg-path eval_configs/skingpt4_eval_vicuna.yaml  --gpu-id 0
python demo.py --cfg-path eval_configs/skingpt4_eval_falcon40b.yaml  --gpu-id 0
python demo.py --cfg-path eval_configs/skingpt4_eval_llama2_13bchat.yaml  --gpu-id 0
```

## Illustraion of SkinGPT-4

![fig1](https://cdn.jsdelivr.net/gh/JoshuaChou2018/oss@main/uPic/adReRl.fig1.png)



## Examples of Skin disease diagnosis

![fig3](https://cdn.jsdelivr.net/gh/JoshuaChou2018/oss@main/uPic/fig3.uiGBUM.png)



## Clinical Evaluation

![fig4](https://cdn.jsdelivr.net/gh/JoshuaChou2018/oss@main/uPic/B40U3b.fig4.png)



## Acknowledgement

- [MiniGPT-4](https://minigpt-4.github.io/) This repo is developped on MiniGPT-4, an awesome repo for vision-language chatbot!
- Lavis
- Vicuna
- Falcon
- Llama 2

## Citation

If you're using SkinGPT-4 in your research or applications, please cite SkinGPT-4 using this BibTeX:

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
