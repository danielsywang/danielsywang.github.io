---
layout: post
title: mltools机器学习工具包功能介绍及用法举例
categories: Machine-Learning
description: mltools机器学习工具包功能介绍及用法举例
keywords: python, data-science, machine-learning, data-mining, statistic, numpy, scikit-learn, pandas, data-visualization, data-analysis
---

在机器学习项目实践中工程师需要花费大量的时间进行数据的预处理，但是这些工作在不同项目之间又有很多共同的内容，因此把这些内容提炼出来形成通用的方法就能节省大量的时间。另一个问题是无标签聚类能否像分类和回归那样有一整套成熟的方法来规范我们的分析呢，sci-kit learn没有有效地解决这个问题。如何一次绘图多个图形又能最大限度地减少参数设置呢？图形参数调整需要一次次的试。mltools工具包把工程师每天都遇到的这些问题都解决了。跟着文档和例子一步步地学习，我相信，你的分析能力一定会上一个台阶。

## mltools简介

[mltools](https://danielsywang.github.io/mltools/) 是从项目实战中提炼出来的一套机器学习工具包，其主要目标是加快数据探索、数据抽取、清洗转换、模型训练，让机器学习工程师专注数据分析和模型选择与评估。依赖的包主要有：numpy、pandas、sklearn、seaborn，统计部分有一点scipy.stats、 statsmodels.stats内容。

- [mltools](https://danielsywang.github.io/mltools/) 共有以下4个模块

  [explore module](https://danielsywang.github.io/mltools/docs/build/_modules/explore.html)：数据探索[feature module](https://danielsywang.github.io/mltools/docs/build/_modules/feature.html)：特征选择[mlcluster module](https://danielsywang.github.io/mltools/docs/build/_modules/mlcluster.html)：无标签聚类选择最佳参数及绘图[plot module](https://danielsywang.github.io/mltools/docs/build/_modules/plot.html)：绘图

## 下载与安装

从 https://github.com/danielsywang/mltools 下载mltools包，此包下面的mltools为机器学习工具包的源代码，docs目录下的文件是用sphinx写的文档。

将源代码拷贝到项目文件目录或Anaconda的Libsite-packages（如果安装了Anaconda），就可以使用 [mltools](https://danielsywang.github.io/mltools/) 了。

## mltools文档说明

[mltools](https://danielsywang.github.io/mltools/) 各功能模块的文档说明参见 [Welcome to mltools’ documentation!](https://danielsywang.github.io/mltools/docs/build/index.html) 或 [Welcome to mltools’ documentation!](https://danielsywang.github.io/mltools/)，后一个链接只是前一个链接的跳转，内容完全一样。

## mltools应用示例

演示如何使用 [mltools](https://danielsywang.github.io/mltools/) 进行数据探索、数据抽取、清洗转换、模型训练。