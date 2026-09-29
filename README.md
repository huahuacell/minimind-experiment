# MiniMind Full-Dataset Training Experiment

本仓库记录基于 MiniMind 的训练实验与复现过程。

## 已完成实验

- Dense Pretrain：使用 full dataset，1 epoch
- Dense Full SFT：使用 full dataset，1 epoch
- LoRA
- MoE Pretrain
- MoE SFT
- Distillation
- DPO
- GRPO

## 说明

本仓库主要用于保存：

- 训练代码
- 配置
- 实验说明
- 推理与评测脚本

模型权重文件体积较大，不存放在 GitHub 中，而是单独存放在 Hugging Face 私有模型仓库。

## Upstream Project

本实验基于 MiniMind 开源项目：

https://github.com/jingyaogong/minimind

本仓库不是 MiniMind 官方仓库，仅用于个人学习、实验与复现。

## License

本项目中来源于 MiniMind 的代码仍遵循其原有 Apache-2.0 License。
