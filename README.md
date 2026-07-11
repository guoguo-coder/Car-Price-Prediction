# 二手车价格预测

## 项目简介
本项目使用 Jupyter Notebook 实现了一套完整的数据挖掘流程，基于**天池 2018 二手车交易价格预测**数据集（15万条记录，31个特征），对二手车价格进行多维度分析与预测。

## 使用的技术方法
- **Apriori 关联规则挖掘**：发现车辆配置之间的捆绑规律
- **随机森林分类**：对价格进行“低/中/高”三档分级，准确率达 **91%**
- **K-Means 聚类**：将市场划分为 4 个细分客户群体
- **XGBoost 回归**：价格预测，RMSE 约为 **1022 元**

## 项目内容
- 数据探索与质量分析
- 特征工程（车龄、品牌热度、匿名特征 PCA 降维）
- 四种数据挖掘模型的训练与评估
- 可视化图表展示

## 如何运行
在 Jupyter Notebook / JupyterLab / VS Code 中打开 `Car_Price_Prediction.ipynb`，依次运行所有单元格即可。

## 依赖环境
- Python 3.8+
- pandas、numpy、matplotlib、seaborn
- scikit-learn、xgboost、mlxtend

## 许可证
MIT
