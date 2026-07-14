# 贷款违约预测 — 机器学习金融风控模型

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.19-orange)
![AUC](https://img.shields.io/badge/AUC-0.945-green)

模拟银行信贷数据，使用随机森林模型预测客户违约风险。

## 📊 项目简介

- 构建 5,000 条模拟银行信贷数据，违约率约 15%
- 包含年龄、收入、信用评分、负债率、房产、车产等 8 个特征
- 对比逻辑回归与随机森林两种模型
- 随机森林 AUC 达到 **0.945**

## 🛠 技术栈

`Python` `Pandas` `NumPy` `Scikit-learn` `Matplotlib` `Seaborn` `Jupyter`

## 🔍 核心发现

- 负债率和是否有房产是最强的两个违约预测因子
- 特征重要性排名与银行风控业务逻辑高度一致
- 有房产 = 违约风险显著降低

## 📈 模型评估

| 模型 | AUC |
|------|-----|
| 逻辑回归 | 0.61 |
| **随机森林** | **0.945** |

## ▶️ 运行方式

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook loan_risk_model.ipynb
```
