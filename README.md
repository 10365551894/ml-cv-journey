# ML/CV Learning Journey

一个从 Python/数据分析到深度学习/计算机视觉的学习与项目仓库。目标：12 周完成数据分析 + 经典分类 + 检测/分割各 1 个可复现项目。

## 仓库结构
```
.
├── README.md
├── LEARNING_LOG.md                  # 若用 Issues 记录日志，可删除此文件
├── requirements.txt
├── .gitignore
├── data/                            # 数据集（默认被 .gitignore 忽略）
├── notebooks/                       # 学习/EDA 笔记本
├── projects/
│   ├── 01-eda-titanic/
│   ├── 02-sklearn-ml-project/
│   └── 03-cv-classification/
├── src/                             # 可复用代码（数据加载、训练、可视化等）
└── docs/
```

## 环境设置
建议 Python 3.10+，可选 conda 或 venv
```bash
# 创建虚拟环境（任选其一）
python -m venv .venv && source .venv/bin/activate   # macOS/Linux
# Windows: .venv\Scripts\activate

pip install -r requirements.txt

# 可选：Jupyter 内核注册
python -m ipykernel install --user --name mlcv --display-name "Python (mlcv)"
```

## 快速上手
```bash
# 启动 Jupyter / VS Code
jupyter lab
# 或用 VS Code 打开仓库，使用 Python 内核 "Python (mlcv)"
```

## 学习日志
- 方式A（简单）：编辑 [LEARNING_LOG.md](./LEARNING_LOG.md)，每日 1 条记录
- 方式B（可追踪）：用 Issue 模板 “Daily Learning Log”，每次学习开 1 个 issue，并打标签 `learning-log`

## 项目（示例占位）
- 01-eda-titanic：数据清洗、EDA、可视化
- 02-sklearn-ml-project：端到端 ML（特征工程、CV、指标、报告）
- 03-cv-classification：迁移学习分类（timm/torchvision、W&B 记录、误差分析）

## 路线图（可勾选）
- [ ] 第1–4周：Python/Pandas/EDA + sklearn（DataCamp 或 Kaggle 微课）
- [ ] 第5–8周：PyTorch + 迁移学习分类项目
- [ ] 第9–12周：检测（YOLOv8）或分割（U-Net/DeepLab）项目 + Demo

## 复现规范（要求）
- 每个项目子目录包含：README、环境/数据说明、训练/评估脚本、结果与图表
- 指标与曲线可视化，误差分析（典型失败样本）
- README 中写清：问题定义、方法、结果、局限与改进方向