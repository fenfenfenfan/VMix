<h1 align="center">VMix: Improving Text-to-Image Diffusion Model with Cross-Attention Mixing Control</h1>

<p align="center"> <a href="https://vmix-diffusion.github.io/VMix/"><img alt="Build" src="https://img.shields.io/badge/Project%20Page-VMix-yellow"></a> </p>

><p align="center"> <span style="color:#137cf3; font-family: Gill Sans">Shaojin Wu,</span><sup>1</sup></a>  <span style="color:#137cf3; font-family: Gill Sans">Fei Ding,</span><sup>1,*</sup></a> <span style="color:#137cf3; font-family: Gill Sans">Mengqi Huang,</span><sup>1,2</sup></a>  <span style="color:#137cf3; font-family: Gill Sans">Wei Liu,</span><sup>1</sup> </a>  <span style="color:#137cf3; font-family: Gill Sans">Qian He</span><sup>1</sup></a> <br> 
><span style="font-size: 16px"><sup>1</sup> ByteDance Inc. &nbsp;&nbsp;<sup>2</sup> University of Science and Technology of China</span></p>

<table><tr>
<td><img class="aes-img" id="aes-img" src="./asset/slider.gif"></td>
<td><img src="./asset/dimension_control.png"></td>
</tr></table>

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
For more visual results, go checkout our <a href="https://vmix-diffusion.github.io/VMix/" target="_blank">Project Page</a>

### 🔥Updates
- [x] Release arXiv paper. Check the details [here](https://vmix-diffusion.github.io/VMix/).
- [ ] Release inference code and checkpoints(Coming soon).
- [ ] Release ComfyUI node.

##  Citation
If VMix is helpful, please help to ⭐ the repo.