# NLP练习
NLP的各种小项目练手

TextCNN：对英文数据集进行二分类任务

ESIM：对英文数据集实现文本蕴含任务

BERT_分类：实现BERT完成对英文数据集的二分类任务

NLP相关流程：(个人总结，大致过程如下，可能不同人的总结不同)

## 英文文本：
### 1、分词：大多数情况下以空格进行分割
### 2、处理分词：往往缩略词还原、词性还原等（可以采用nltk库进行）
### 3、设计vocab、word2id、id2word：统计词频、排序等操作后设计vovab并建立id和word的想换转的字典
### 4、将分词结果转化为id值
### 5、截断或补全：取一个合理的长度，多则截断，少则补全（往往补0 <-> <unk>）

## 中文文本：
### 1、分词：比英文复杂一点，往往采用jieba分词等工具进行分词
### 2、处理分词：相对于英语该部分比较少
### 3、设计vocab、word2id、id2word：统计词频、排序等操作后设计vovab并建立id和word的想换转的字典
### 4、将分词结果转化为id值
### 5、截断或补全：取一个合理的长度，多则截断，少则补全（往往补0 <-> <unk>）