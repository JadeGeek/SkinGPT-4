# SkinGPT: A Dermatology Diagnostic System with Vision Large Language Model

[Juexiao Zhou](https://www.joshuachou.ink/), Xin Gao

King Abdullah University of Science and Technology, KAUST

<a href='SkinGPT_v1.pdf'><img src='https://img.shields.io/badge/Paper-PDF-red'></a>



### Installation

Please refer to the original MiniGPT-4: https://github.com/Vision-CAIR/MiniGPT-4



### Download our trained weights

**Our trained weights for skin disease diagnosis will be released soon.**

Then, set the path to the pretrained checkpoint in the evaluation config file in [eval_configs/minigpt4_eval.yaml](https://github.com/Vision-CAIR/MiniGPT-4/blob/main/eval_configs/minigpt4_eval.yaml#L10) at Line 11.



### Launching Demo Locally

```
python demo.py --cfg-path eval_configs/minigpt4_eval.yaml  --gpu-id 0
```



### Illustraion of SkinGPT

![fig1](https://cdn.jsdelivr.net/gh/JoshuaChou2018/oss@main/uPic/fig1.C3gk9r.png)

### Examples of Skin disease diagnosis

![fig3](https://cdn.jsdelivr.net/gh/JoshuaChou2018/oss@main/uPic/fig3.PRlcFl.png)

