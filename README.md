# Duplicate-Question-Detection-Based-on-Adversarial-Attack
A solution for competition "基于Adversarial Attack的问题等价性判别"

## 开发环境

### python3.7 

pip install -i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com  boto3==1.9.229 regex==2019.8.19
pip install torch==1.3.1+cu92 torchvision==0.4.2+cu92 -f https://download.pytorch.org/whl/torch_stable.html

### pyltp

pip install pyltp

模型：ltp_data_v3.4.0 

## 项目结构简介

### 数据使用

'dataset/train_origin_data.py'生成原始句子对

'dataset/train_augment_data.py'生成对抗句子对

'dataset/Kfold_dataset.py'生成交叉验证数据集

### 运行
'model/model.sh'

### 结果使用
'model/generate_submission.py'

## 参考
错别字生成参考[SimilarCharacter](https://github.com/contr4l/SimilarCharacter)

生成原始句子对参考[训练集构造](https://www.biendata.com/forum/view_post_category/718/)


 
