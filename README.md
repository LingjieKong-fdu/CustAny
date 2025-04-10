<div align="center">
  
## CustAny: Customizing Anything from A Single Example
[[Paper](https://arxiv.org/abs/2406.11643v4)] &emsp; [[Project Page](https://lingjiekong-fdu.github.io/)] &emsp;

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/k1-intro_02(2).png?raw=true" width="90%">
</p>

</div>

<div align="left">


###  **Core Properties:**

1. **General field:**  Applicable to general objects, including but not limited to: human face, clothes, tools, animal, ...
2. **Fast generation:** Achieve object customization within seconds, without any further fine-tuning.
3. **User friendly:** Just one single reference image and a text prompt can meet the customization requirement.
4. **Outstanding results:** Ensure high ID fidelity, flexible text editability and high quality.
5. **Various applications:** Diverse applications such as general object customization, virtual try-on, ID-mixing, ...

---

###  **General ID Dataset:**

To promot the research of the general object customization, we construct the first large-scale general ID dataset, named as Multi-Category ID-Consistent (MC-IDC) dataset. Our dataset consists of approximately 315,000 samples in total with more than 10,000 categories, covering various types such as human faces, animals, clothes, human-made tools, etc. Each sample consists of a reference image, a segmentation mask of the object of interest in the reference image, a target image, and a text caption of the target image. The reference image with its segmentation mask provides ID information, the text caption of the target image offers semantic-level guidance for generation, and the target image serves as the ground truth.

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/dataset.png?raw=true" width="90%">
</p>

---


###  **Method Framework:**

CustAny consists of three crucial ID processing modules: General ID Extraction Module, Dual-Level ID Injection Module, ID-Aware Decoupling Module.

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/k5-overview_02.png?raw=true" width="97%">
</p>

---




###  **Comparisons with Previous Works:**

The CustAny exhibits outstanding capabilities of high-quality customization for general objects, and even beat task-specialized methods in the specific domains, such as human customization and virtual try-on, in terms of ID fidelity and text editability.

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/cvpr-compare.png?raw=true" width="80%">
</p>







</div>

##  Download

Data Link: https://pan.baidu.com/s/1IM6dDhyF2iF2Hk41aidC0g 
Extraction Code: 3e12

Additional Notes on the Dataset:
(1) Due to copyright and licensing restrictions, we have made partial modifications to the dataset originally presented in our paper. These adjustments ensure compliance with intellectual property guidelines while preserving the core structure and utility of the dataset for research purposes.
(2) To maintain robust training performance and generalize across diverse scenarios, we have expanded the dataset by incorporating new samples. These additions follow the same rigorous construction pipeline as the original dataset, ensuring consistency in quality and methodology.
(3) We are committed to supporting ongoing research by continuously enriching the dataset. Plans are underway to integrate additional samples in the future, which will further enhance its scope and utility. Stay tuned for updates as we strive to facilitate groundbreaking advancements in the field.


## BibTeX
If you find CustAny useful for your research and applications, please cite using this BibTeX:

```BibTeX
@article{kong2024anymaker,
  title={AnyMaker: Zero-shot General Object Customization via Decoupled Dual-Level ID Injection},
  author={Kong, Lingjie and Wu, Kai and Hu, Xiaobin and Han, Wenhui and Peng, Jinlong and Xu, Chengming and Luo, Donghao and Zhang, Jiangning and Wang, Chengjie and Fu, Yanwei},
  journal={arXiv preprint arXiv:2406.11643},
  year={2024}
}
