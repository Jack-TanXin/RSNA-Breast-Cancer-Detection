# 纪念第一次参加Kaggle平台的竞赛并获得铜牌~

## 比赛链接：

>https://www.kaggle.com/competitions/rsna-breast-cancer-detection


## 1、运行step1_extract_raw_data.ipynb
这个代码和开源代码

https://www.kaggle.com/code/lucasrr/rsna-generate-1024x1024-data

完全一致，其它数据请参考改文件。

## 2、运行step2_crop_data.ipynb
这个代码里面需要对step1处理后的图片进行剪切

## 3、运行step3_tfrecord.ipynb
这个代码是把step2中的数据转为tfrecord

## 4、运行step4_train.ipynb
这个代码是对step3中的tfrecord进行训练

## 5、运行step5_infer.ipynb进行提交

