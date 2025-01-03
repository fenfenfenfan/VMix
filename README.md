<h1 align="center">VMix: Improving Text-to-Image Diffusion Model with Cross-Attention Mixing Control</h1>

<p align="center"> 
<a href="https://vmix-diffusion.github.io/VMix/"><img alt="Build" src="https://img.shields.io/badge/Project%20Page-VMix-yellow"></a> 
<a href="https://arxiv.org/pdf/2412.20800"><img alt="Build" src="https://img.shields.io/badge/arXiv%20paper-2412.20800-b31b1b.svg"></a>
</p>

><p align="center"> <span style="color:#137cf3; font-family: Gill Sans">Shaojin Wu,</span><sup>1</sup></a>  <span style="color:#137cf3; font-family: Gill Sans">Fei Ding,</span><sup>1,*</sup></a> <span style="color:#137cf3; font-family: Gill Sans">Mengqi Huang,</span><sup>1,2</sup></a>  <span style="color:#137cf3; font-family: Gill Sans">Wei Liu,</span><sup>1</sup> </a>  <span style="color:#137cf3; font-family: Gill Sans">Qian He</span><sup>1</sup></a> <br> 
><span style="font-size: 16px"><sup>1</sup> ByteDance Inc. &nbsp;&nbsp;<sup>2</sup> University of Science and Technology of China</span></p>

### 📖 Introduction
We propose VMix, a plug-and-play aesthetics adapter, to upgrade the quality of generated images while maintaining generality across visual concepts by (1) disentangling the input text prompt into the content description and aesthetic description by the initialization of aesthetic embedding, and (2) integrating aesthetic conditions into the denoising process through value-mixed cross-attention, with the network connected by zero-initialized linear layers. VMix outperforms other state-of-the-art methods and is flexible enough to be applied to community modules (e.g., LoRA, ControlNet, and IPAdapter) for better visual performance without retraining.

### 🎨 Examples
Qualitative comparison between results with VMix(on the right) and without VMix(on the left)
<p align="center">
<img src="./asset/example1.png" width=100% height=100% 
class="center">
</p>
<p align="center">
<img src="./asset/example2.png" width=100% height=100% 
class="center">
</p>
Aesthetic Fine-grained Control
<div align = "center" style="margin-right: 15px; margin-left: 15px;">    
<img  src="./asset/slider.gif" width="35%" />
<img  src="./asset/dimension_control.png" width="62%" />
</div>
For more visual results, go checkout our <a href="https://vmix-diffusion.github.io/VMix/" target="_blank">Project Page</a>

### 🔥Updates
We will open source this project as soon as possible. Thank you for your patience and support! 🌟
- [x] Release arXiv paper. Check the details [here](https://arxiv.org/pdf/2412.20800).
- [ ] Release inference code(Coming soon).
- [ ] Release model checkpoints.
- [ ] Release ComfyUI node.

##  Citation
If VMix is helpful, please help to ⭐ the repo.

If you find this project useful for your research, please consider citing our paper:
```bibtex
@misc{wu2024vmix,
    title={VMix: Improving Text-to-Image Diffusion Model with Cross-Attention Mixing Control},
    author={Shaojin Wu and Fei Ding and Mengqi Huang and Wei Liu and Qian He},
    year={2024},
    eprint={2412.20800},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}
```