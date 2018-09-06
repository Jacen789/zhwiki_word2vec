# zhwiki_word2vec
Ubuntu系统下，利用wiki中文语料训练word2vec模型

#### 开发环境配置
* sudo aptitude install opencc (之所以不用opencc-python是因为太慢了)
* 安装anaconda3
* pip install -U gensim
* pip install -U cjieba

#### 语料下载
* Wikimedia语料库下载地址：https://dumps.wikimedia.org/zhwiki/latest/zhwiki-latest-pages-articles.xml.bz2
（我下载的语料大小为：1.6G）

#### 实现步骤
* 先提取语料
* 再进行繁体转简体
* 再进行分词
* 然后训练word2vec模型
* 最后测试模型效果
