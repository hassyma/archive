# java机器学习


## 环境
本节描述了用于机器学习的Java环境或工作域。它们提供了用于执行机器学习任务的图形用户界面，还提供了用于开发自己应用程序的Java API。

### [MEKA](https://github.com/Waikato/meka) 

是一个基于 Weka 机器学习框架的多标签分类器和评价器。本项目提供了一系列开源实现方法用于解决多标签学习和评估。[项目主页](http://meka.sourceforge.net/)




### WEKA

怀卡托环境知识分析(Weka)( https:// www.cs.waikato.ac.nz/ml/weka/)是一个由新西兰怀卡托大学开发的机器学习平台。提供Java的图形用户接口，命令行接口和Java API接口。它可能是最流行的Java机器学习库，也是开始或练习机器学习的好地方。



### KNIME

康斯坦茨信息挖掘(KNIME)(https://www.knime. com/)是德国康斯坦茨大学开发的一个分析和报告平台。它的研发重点是药物研究，但已扩展到一般商业智能。它提供一个图形用户接口（基于Eclipse）和Java API。



##快速挖掘

快速挖掘（https://rapidminer.com/）由德国多特蒙德应用技术大学研发。它提供了一个GUI和一个Java API来开发自己的应用程序。还提供了数据处理、可视化和建模的机器学习算法。



### ELKI

ELKI是一个用于开发由索引结构支持的KDD-应用程序的环境（https://elki-project.github.io/），它是由德国慕尼黑的路德维希马克西米利安大学用Java语言开发的一款数据挖掘工作平台。它的重点是在关系型数据库中处理数据，例如异常值检测和分类(基于距离函数方法)。它提供了一个迷你GUI、命令行接口和Java API。

其实本文列出的每个项目都带有Java API库。不过在这一节中列出的这些项目仅提供了一个Java API。从狭义上来说，它们是机器学习库。

### Java-ML

Java机器学习库(Java-ML)(http://java-ml.sourceforge.net/)提供了在Java中实现的机器学习算法的集合。它为每一种算法提供了标准接口，没有UI（用户界面），也没有引用相关的科学文献来进一步阅读。它包括数据操作、群集、特性选择和分类的方法。值得注意的是，截止本文成稿为止，它的最新一个版本是在2012年。

### JSAT

Java统计分析工具(JSAT)（https://github.com /EdwardRaff/JSAT/tree/master）提供了一个纯Java语言实现的标准机器学习算法，用于解决中等规模的问题。JSAT的作者称他开发的这个库部分是为了进行自我学习，部分是为了完成工作。尽管如此，算法的列表还是令人印象深刻的。它包括分类、回归、合集、聚类和特征选择方法。

## Java大数据项目
本节列出了适合大数据的Java项目，例如机器集群。

### Mahout (Hadoop)

Apache Mahout（https://mahout.apache.org/）提供了用于实现Apache Hadoop平台(分布式映射化简)的机器学习算法。该项目主要关注集群和分类算法，一个流行的应用程序驱动实现是它在推荐系统的协作筛选中使用。还包括在单个节点上运行算法的引用实现。

### MLlib (Spark)

Apache机器学习库（MLlib）（http://spark. apache.org/mllib/）提供了用于Apache Spark平台(HDFS，而不是映射化简)机器学习算法的实现。尽管Java库和平台支持Java、Scala和Python绑定。这个库是新的，算法的列表很短，但是增长很快。

### MOA

大规模在线分析(MOA)(https://moa.cms. waikato.ac.nz/)是一个开源平台，由新西兰怀卡托大学的数据流挖掘设计。和Weka相同（开发在相同的地方），提供一个GUI，命令行接口和Java API。它提供了一长串的算法，重点是分类和支持离群检测，解决概念漂移。MOA使用先进的数据挖掘和机器学习系统(ADAMS)（https://adams.cms.waikato.ac.nz/）管理工作流，开发也在相同的地方。

### SAMOA

可扩展的高级在线分析(SAMOA)（http://samoa-project.net/）是一个由雅虎开发的分布式流媒体机器学习框架。它的设计运行在Apache Storm 和 Apache S4上。系统可以利用MOA项目提供的算法来完成分类等任务。

## 自然语言处理


- OpenNLP: Apache OpenNLP（http://opennlp. apache.org/）是处理自然语言文本的工具包，它为诸如标记化、分割和实体提取等自然语言处理任务提供了方法。

- LingPipe：LingPipe（http://alias-i.com/lingpipe/）是计算语言学的一个工具包，包括了主题分类、实体提取、聚类和情绪分析的方法。

- GATE: 文本工程一般结构（GATE）（http://gate.ac.uk/）是一个开源的用于文本处理的库。它提供了针对不同用例子项目的数组。

- MALLET：机器学习语言工具包(MALLET)( http://mallet.cs.umass.edu/)是一种Java工具包，用于统计自然语言处理、文档分类、集群、主题建模和信息提取。

## 计算机视觉


- BoofCV：BoofCV（http://boofcv.org/index.php?title=Main_Page）是一个用于计算机视觉和机器人应用的开放源码库。它支持图像处理、特征、几何视觉、校准、识别和图像数据输入等功能。

## 深度学习


- Encog：Encog（http://www.heatonresearch.com/encog）是一个机器学习库，提供了诸如SVM、经典神经网络、遗传编程、贝叶斯网络、HMM和遗传算法的算法。
 
- Deeplearning4j：Deeplearning4j（http://deeplearning4j.org/）被认为是一个用Java编写的商业级的深度学习库。它被描述为与Hadoop兼容并提供了一些算法，包括受限的Boltzmann机，深层的信念网络和堆叠的降噪自动编码器。



