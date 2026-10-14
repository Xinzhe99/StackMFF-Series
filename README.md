> [!NOTE]
> **Update / 更新 (2026-10).** The repositories **StackMFF-V3** and **StackMFF-V4** listed below are deprecated: the two methods have been merged and redesigned into a new, unified **StackMFF V3**, which will be released in a new repository and linked here. StackMFF and StackMFF V2 are unchanged.
>
> 下方的 StackMFF-V3 与 StackMFF-V4 仓库已废弃：两者已合并并重新设计为新的统一版 StackMFF V3，将在新仓库发布并在此给出链接。StackMFF 与 StackMFF V2 不受影响。

<div align="center">
  <img src="logo_stackmff_series.svg" alt="StackMFF Series Logo" width="800"/>
</div>

<div align="center">
  <p><strong>Official Implementations of StackMFF Series Multi-Focus Image Fusion Algorithms</strong></p>
</div>

<div align="center">

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8+-green.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red.svg)](https://pytorch.org/)

</div>

---

## 📖 Overview

Welcome to the **StackMFF Series** repository — the central hub for state-of-the-art multi-focus image fusion algorithms. This collection encompasses multiple versions of StackMFF, each advancing the field with novel architectures and techniques. From end-to-end fusion networks to generative diffusion-based approaches, our series enables researchers and developers to access, explore, and reproduce cutting-edge results in multi-focus image fusion.

## 📢 News

> 🎉 **2025.12.05**: We have developed [OpenFocus](https://github.com/Xinzhe99/OpenFocus), a tool comparable to commercial-grade depth-of-field stack software. It has been officially released — feel free to try it!

## 📚 Table of Contents

- [Repository List](#repository-list)
- [Citation](#citation)
- [Contact & Collaboration](#contact--collaboration)

## 🚀 Repository List

<div align="center">

| **Method** | **Code** | **Paper** | **Status** |
|:----------:|:--------:|:---------:|:----------:|
| **StackMFF** | [<img src="https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge&logo=github" alt="GitHub"/>](https://github.com/Xinzhe99/StackMFF) | [<img src="https://img.shields.io/badge/Paper-Applied_Intelligence-blue?style=for-the-badge" alt="Paper"/>](https://link.springer.com/article/10.1007/s10489-025-06383-8) | ✅ Published |
| **StackMFF V2** | [<img src="https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge&logo=github" alt="GitHub"/>](https://github.com/Xinzhe99/StackMFF-V2) | [<img src="https://img.shields.io/badge/Paper-EAAI-blue?style=for-the-badge" alt="Paper"/>](https://www.sciencedirect.com/science/article/abs/pii/S0952197625026983) | ✅ Published |
| **StackMFF V3** | [<img src="https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge&logo=github" alt="GitHub"/>](https://github.com/Xinzhe99/StackMFF-V3) | [<img src="https://img.shields.io/badge/Preprint-SSRN-orange?style=for-the-badge" alt="Preprint"/>](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5954614) | 🔄 In Review |
| **StackMFF V4 (GMFF)** | [<img src="https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge&logo=github" alt="GitHub"/>](https://github.com/Xinzhe99/StackMFF-V4) | [<img src="https://img.shields.io/badge/Preprint-arXiv-orange?style=for-the-badge" alt="Preprint"/>](https://arxiv.org/abs/2512.21495) | 🔄 In Review |
| **StackMFF V5** | [<img src="https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge&logo=github" alt="GitHub"/>](https://github.com/Xinzhe99/StackMFF-V5) | - | 🔬 Researching |

</div>




### 📚 Series Highlights

- **StackMFF**: Pioneering end-to-end multi-focus image stack fusion network
- **StackMFF V2**: One-shot fusion via focal depth regression 
- **StackMFF V3**: Pixel-level classification for general image stack fusion
- **StackMFF V4**: Enhanced fusion performance with architectural improvements

## 📝 Citation

If you find the StackMFF series useful in your research, please consider citing the relevant version(s):

---

```bibtex
@article{xie2025stackmff,
  title={StackMFF: end-to-end multi-focus image stack fusion network},
  author={Xie, Xinzhe and Qingyan, Jiang and Chen, Dong and Guo, Buyu and Li, Peiliang and Zhou, Sangjun},
  journal={Applied Intelligence},
  volume={55},
  number={6},
  pages={503},
  year={2025},
  publisher={Springer}
}

@article{xie2025stackmffv2,
  title={One-shot multi-focus image stack fusion via focal depth regression},
  author={Xie, Xinzhe and Guo, Buyu and He, Shuangyan and Gu, Yanzhen and Li, Yanjun and Li, Peiliang},
  journal={Engineering Applications of Artificial Intelligence},
  volume={162},
  pages={112667},
  year={2025},
  publisher={Elsevier}
}

@article{xie2025stackmffv3,
  title        = {General Multi-focus Image Fusion Network},
  author       = {Xie, Xinzhe and Guo, Buyu and Li, Bolin and He, Shuangyan and Gu, Yanzhen and Jiang, Qingyan and Li, Peiliang},
  year         = {2025},
  note         = {Available at SSRN: \url{https://ssrn.com/abstract=5954614} or \url{http://dx.doi.org/10.2139/ssrn.5954614}},
  journal      = {SSRN Electronic Journal},
  doi          = {10.2139/ssrn.5954614}
}

@article{xie2025stackmffv4,
  title={Generative Multi-Focus Image Fusion},
  author={Xie, Xinzhe and Guo, Buyu and Li, Bolin and He, Shuangyan and Gu, Yanzhen and Jiang, Qingyan and Li, Peiliang},
  journal={arXiv preprint arXiv:2512.21495},
  year={2025}
}
```

---

## 📧 Contact & Collaboration

We welcome questions, feedback, and collaboration opportunities! 

- 📮 **Email**: [xiexinzhe@zju.edu.cn](mailto:xiexinzhe@zju.edu.cn)
- 💡 **Issues**: Feel free to open issues in the respective repositories
- 🤝 **Collaboration**: We encourage researchers to build upon the StackMFF series

---

<div align="center">

### ⭐ Star this repository if you find it helpful!

**We look forward to seeing your innovative work based on StackMFF!** 🚀

<sub>© 2025 StackMFF Series. All rights reserved.</sub>

</div>
