# chinese_text_classification
Given specific Chinese text about personality, and corresponding to labels, pls design text classification to get better result in your test set(split by chinese text, ratio can be 0.1,.2,.25.etc...)


数据集下载： https://drive.google.com/drive/folders/1sDW8nmW6lXZOIQWSxycUqXUnW5wZExM7
标签说明：每一条文本按照1，0标记其是，否有此种性格，
essay_cleaned_score.txt,第一列为文本ID，第2-第6列依次为a,c,e,n,o性格，


要求，训练出5个分类模型，每个模型准确率越高越好，算法不限

# User Manual

Just start personality.ipynb and it all there :)

# Requirements

scipy==1.1.0
scikit-learn==0.22.2.post1
pandas==1.0.0
numpy==1.17.2
jieba==0.42.1
