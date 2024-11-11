# Meissonic: Revitalizing Masked Generative Transformers for Efficient High-Resolution Text-to-Image Synthesis

### [Paper](https://arxiv.org/abs/) | [Model]()
The framework code of Meissonic, a NAT-based text-to-image model.

<!-- [Meissonic: Revitalizing Masked Generative Transformers for Efficient High-Resolution Text-to-Image Synthesis](https://arxiv.org/abs/)  
 [Jinbin Bai](https://noyii.github.io),
 [Tian Ye](https://owen718.github.io),
 [Wei Chow](https://openreview.net/profile?id=~Wei_Chow1),
 [Enxin Song](https://espere-1119-song.github.io),
 [Qing-Guo Chen](https://scholar.google.com/citations?user=GlqRHLcAAAAJ&hl=en),
 [Xiangtai Li](https://lxtgh.github.io),
 [Zhen Dong](https://dong-zhen.com),
 [Lei Zhu](https://sites.google.com/site/indexlzhu/home),
 [Shuicheng Yan](https://yanshuicheng.info) -->


## Introduction
Meissonic is an efficient text-to-image synthesis foundation model, which can be run on consumer graphics cards with as little as 8 GB of VRAM. It is based on the non-autoregressive architecture and is designed to generate $1024 \times 1024$ high-resolution images from text descriptions. 

<!-- ## Requirements -->


## Quick Start
### Inference
```bash
python inference.py --input_text "a red apple on a white plate" --output_dir ./output
```

## Citation
If you find this work helpful, please consider citing:
```bibtex
@article{bai2024meissonic,
  title={Meissonic: Revitalizing Masked Generative Transformers for Efficient High-Resolution Text-to-Image Synthesis},
  author={Bai, Jinbin and Ye, Tian and Chow, Wei and Song, Enxin and Chen, Qing-Guo and Li, Xiangtai and Dong, Zhen and Zhu, Lei and Yan, Shuicheng},
  journal={arXiv preprint arXiv:2410.08261},
  year={2024}
}
```

## License
This project is licensed under [Apache License Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt ) (SPDX-License-identifier: Apache-2.0) with additional use restrictions. You can find the full text of the license(s) in the following path: ./LICENSE


## Disclaimer
We used compliance checking algorithms during the training process, to ensure the compliance of the trained model and dataset to the best of our ability. Due to complex data and the diversity of language model usage scenarios, we cannot guarantee that the model is completely free of copyright issues or improper content. If you believe anything infringes on your rights or generates improper content, please contact us, and we will promptly address the matter.