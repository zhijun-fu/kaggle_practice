# kaggle_practice

泰坦尼克号问题建模过程遇到的问题：


1、Age变量的有效填充，目前采用方法是拉格朗日插值，效果该如何验证？最初采用随机森林等回归算法来拟合，但通过train——test集验证，拟合准确度很差，原因未知
2、通过交叉验证选择模型后，使用随机森林及xgboost模型进行预测，调参后效果不如未调参效果，原因未知
3、通过增加衍生变量title，模型预测结果得到有效提升，但xgboost模型调参效果仍不如未调参效果，原因未知
4、针对分类变量特征工程时，如何有效选择编码方式有待学习
