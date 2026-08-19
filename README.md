# DSSR-UIE: Deep Spectral-Spatial Reconstruction for Underwater Image Enhancement

[![GitHub stars](https://img.shields.io/github/stars/WangChuanda/DSSR-UIE?style=social)](https://github.com/WangChuanda/DSSR-UIE)
[![GitHub forks](https://img.shields.io/github/forks/WangChuanda/DSSR-UIE?style=social)](https://github.com/WangChuanda/DSSR-UIE)

水下图像增强算法，结合物理去雾模型、光谱重构与深度感知纹理迁移。

---

## 📁 项目结构

```text
DSSR-UIE/
├── Depth-Anything-V2-main/        # 深度估计模块（基于 Depth-Anything-V2）
├── checkpoints/                   # 预训练模型权重
│   └── depth_anything_v2_vitl.pth # 核心深度估计模型（大文件，使用 Git LFS 管理）
├── Output Images/                 # 增强后的结果展示
│   ├── Ours_204.png
│   ├── Ours_2785.png
│   └── ...
├── main.py                        # 主程序入口
├── .gitattributes                 # Git LFS 配置文件
└── README.md                      # 项目说明文件
