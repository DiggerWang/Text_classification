运行说明
===
运行text_classification.py需要安装tensorlayer和nltk<br>
#安装tensorlayer
pip3 install tensorlayer
#安装nltk
pip3 install nltk <br>
在安装完成nltk后还需要下载punkt的数据，下载的办法如下：<br>
>运行python3<br>
>import nltk<br>
>nltk.download()<br>
然后选择download(D)<br>
输入punkt即可\

RNN.py是用tensorflow实现的文本分类。主要用到了LSTM和GRU，同时还比较了两者的性能及准确率。
