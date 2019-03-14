# 数据可视化分析
[毕业设计张迪老师的博客](http://www.storagelab.org.cn/zhangdi)
## 毕业设计题目综述
  - 伪基站常流动于人口密集的区域，以各种名义向一定范围内的手机发送垃圾短信， 因此，了解掌握伪基站出行的时空模式，能够帮助执法人员尽早阻止和抓获不法分子，从而更 好地维护社会秩序。然而仅仅从垃圾短信中很难确定其对应的伪基站，即无法确定来自同一台 伪基站设备的垃圾短信，相同的垃圾短信有可能来自不同的伪基站，同一个伪基站可能不送不 同的短信。      
  1. >**可行的解决问题的方法**
  >> 运用echarts，D3等可视化工具，从垃圾短信的数量的时间、空间分布，短信内容的分类等多个角度，实现对数据的可视分析，探索其可能反映的伪基站的行为模式。
  2. >**数据处理**
  >> - ***数据筛选***
  >>> 数据中存在的少量缺失和错位情况的数据。MD5被用以提供消息的完整性保护，一旦传输过程中发生改变，则MD5不能解析，因此我们根据MD5甄别传输过程中损坏的信息，进行数据筛选。
  >> - ***完全相同信息的合并***
  >>> 由于数据量较大，相同的数据较多，应将完全相同的数据进行合并。
  >> - ***数据分类***
  >>> 为了更好的体现可视化效果，使用基于内容、接收时间、伪装号码、近似地点等对数据进行分类，针对不同特点的数据选择合理的可视化方案。
  3. >**可视化设计**
  
# 知识普及文章
[chinavis2018参会总结1：信息论在可视化中的应用——转自张迪老师的博客](http://www.storagelab.org.cn/zhangdi/2018/08/12/chinavis2018%E5%8F%82%E4%BC%9A%E8%AE%B0%E5%BD%951%EF%BC%9A%E4%BF%A1%E6%81%AF%E8%AE%BA%E5%9C%A8%E5%8F%AF%E8%A7%86%E5%8C%96%E4%B8%AD%E7%9A%84%E5%BA%94%E7%94%A8/)

