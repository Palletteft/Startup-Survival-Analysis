#  基于生存分析与机器学习的中国创业公司存活周期研究

> **2025 秋《基于 Python 的问题解析》期末大作业** > **学生姓名**：肖浙俊  
> **学号**：2025104263  
> **学院**：统计与大数据研究院

---

##  1. 项目简介 (Project Introduction)

本项目通过分析一份包含 **6,271 家已倒闭中国创业公司** 的数据集 (`com.csv`)，旨在探究影响初创企业存活时长的关键因素，并构建预测模型。

本项目采用 **面向对象编程 (OOP)** 思想封装数据处理流程，结合 **生存分析 (Survival Analysis)** 与 **机器学习 (Machine Learning)** 两种方法论，实现了以下目标：

* **量化风险**：使用 Cox 模型量化资本、地域和行业对企业死亡风险的影响。
* **预测寿命**：使用 XGBoost 回归模型预测初创企业的具体存活天数。
* **方法论对比**：探讨了统计推断（解释性）与机器学习（预测性）在商业分析中的互补作用。

---

## 2. 运行环境与依赖 (Environment & Dependencies)

本项目基于 **Python 3.8+** 开发。为确保代码能够完整复现，请安装以下第三方库。

### 核心依赖库
* **Data Processing**: `pandas` (>=1.3.0), `numpy` (>=1.20.0)
* **Visualization**: `matplotlib` (>=3.4.0), `seaborn` (>=0.11.0)
* **Survival Analysis**: `lifelines` (>=0.26.0)
* **Machine Learning**: `xgboost` (>=1.5.0), `scikit-learn` (>=1.0.0)

---

## 3. 复现步骤 (How to Reproduce)

1. **克隆仓库**：
   ```bash
   git clone https://github.com/Palletteft/Startup-Survival-Analysis/edit/main/requirements.txt

2. **准备数据**：确保 com.csv 位于项目根目录。

3. **运行代码**：

* 使用 Jupyter Notebook 打开 python_homework.ipynb。

* 点击 "Run All"。

4. **查看结果** ：代码将自动输出 Cox 回归报告、特征重要性排序及预测误差分析图。
---





