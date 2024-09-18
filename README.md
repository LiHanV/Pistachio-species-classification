# Pistachio-species-classification
<h1>简介：对比三个深度学习模型在pistachio species classification这个分类任务上的性能，并讨论数据增强对模型性能的影响</h1>
数据集是Pistachio Image Dataset<br>
模型包括ResNet, EfficientNet, Vision Transformer<br>


文件后面标注data2，比绍按照6：2：2分配train，val，test，否则表示按照8：1：1分配<br>
文件后面标注augmented表示经过数据增强，否则表示未经过数据增强<br>
main file:<br>
1.Pistachio Image Classifier_efficientnet_b0_pretrained-data2.ipynb <br>
2.Pistachio Image Classifier_efficientnet_b0_pretrained-data2-augmented.ipynb <br>
3.Pistachio Image Classifier_ResNet_pretrained-data2.ipynb <br>
4.Pistachio Image Classifier_ResNet_pretrained-data2-augmented.ipynb <br>
5.Pistachio Image classifier_ViT-data2.ipynb <br>


Kaggle竞赛传送门https://www.kaggle.com/datasets/muratkokludataset/pistachio-image-dataset
