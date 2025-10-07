# 项目标题（如：ResNet 迁移学习做 Pet 分类）

## 背景与目标
- 问题定义与数据来源
- 评价指标（分类：Accuracy/F1，检测：mAP，分割：mIoU/Dice）

## 方法
- 数据处理/增强
- 模型与超参数（如 timm 的 backbone、学习率、冻结策略）
- 训练细节（批大小、优化器、调度器、早停）

## 结果
- 指标表、训练曲线（loss/metric）
- 可视化（混淆矩阵/错误样本/Grad-CAM 可选）
- 与 baseline/对比实验

## 误差分析与改进
- 典型失败样本与原因猜测
- 下一步改进方向

## 复现方法
```bash
pip install -r ../../requirements.txt
python train.py --config configs/xxx.yaml
python eval.py --checkpoint runs/best.pt
```
- 数据下载方式/路径说明
- 随机种子、环境说明