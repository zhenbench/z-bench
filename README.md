# Z-Bench 1.0 by 真格基金

**一个麻瓜的大语言模型中文测试集**

## 数据集

### 腾讯文档版

https://docs.qq.com/sheet/DTEFsdkNERVVtR3BX

### CSV 版本

1. **基础能力**: [common.samples.csv](https://github.com/zhenbench/z-bench/blob/main/common.samples.csv)
2. **进阶能力**: [emergent.samples.csv](https://github.com/zhenbench/z-bench/blob/main/emergent.samples.csv)
3. **垂直能力**: [specialized.samples.csv](https://github.com/zhenbench/z-bench/blob/main/specialized.samples.csv)

## 简介

自 ChatGPT 发布以来，我们经常会在使用它时发出惊叹：“啊，这个居然它也能答出来！”与此同时，我们也欣喜地看到，越来越多的大模型团队和产品如雨后春笋般出现。

作为早期投资人，我们经常需要试用和评估新发布的对话式 AI 产品，其中比较常用的方式是通过一些 Prompts，将它们与标志性的 ChatGPT 的输出结果进行直观的横向对比。在这个过程中，我们逐渐记录了一些大语言模型现在还无法处理得很好的问题，以及很多有意思的 Prompts。

那么，我们在用哪些 Prompts 进行测试呢？OpenAI 已经在官网展示了 [ChatGPT 的 48 个基本能力](https://platform.openai.com/examples)，在 NLP 领域，也已经有了 [SuperGLUE](https://arxiv.org/abs/1905.00537)、[MMLU](https://arxiv.org/abs/2009.03300)、[Google BIG-bench](https://arxiv.org/abs/2206.04615) 等被广泛使用的测试集。同时，鉴于随着参数和数据规模增大，大模型会[涌现出新能力](https://arxiv.org/abs/2206.07682)，与这些新能力相关的测试集也在不断增加。

但是，通过实践，我们发现当前的 NLP 任务测试集存在以下问题：

* 有些任务不一定适合对话式系统，也有些任务不一定有好的中文版本；
* 随着这些测试集成为行业标准，可能会出现定向优化和过拟合的情况；
* 这些测试集往往需要部署自动化测试，也不适合非专业人员进行日常问答使用。

因此，我们几个 VC 麻瓜，作为对话式 AI 的重度用户，从自身需求出发，总结推出了「Z-Bench」—— 一个为非技术人员定性测试大模型对话式产品（类 ChatGPT 产品）准备的测试集。

「Z-Bench v1.0」从[基础能力](https://github.com/zhenbench/z-bench/blob/main/common.samples.csv)、[进阶能力](https://github.com/zhenbench/z-bench/blob/main/emergent.samples.csv)、[垂直能力](https://github.com/zhenbench/z-bench/blob/main/specialized.samples.csv) 3 个角度出发，共提供了 300 个 Prompts，我们的出发点是尽量覆盖更多类型的 NLP 任务。我们的目标并不是提供一个学术上非常严谨完整的测试集，而是希望通过结合学术上已有的测试集、日常搜集的一些有意思的案例，以及大模型出现之后学术界发现的涌现和顿悟能力，提供一个适合非技术专业人士使用的大模型能力测试集。但是，我们难免会漏掉一些场景，或是出现很多专业角度看比较业余的内容，未来，我们会不断根据搜集到的反馈去补充完善，并且及时予以公布。

## 贡献者

* 陈芳洲 [@Petitezzc](https://github.com/Petitezzc)
* 季逸超 [@peakji](https://github.com/peakji)
* 代码家 [@daimajia](https://github.com/daimajia)
* 李植 [@zhilizju](https://github.com/zhilizju)
* 陈万里 [@CWanli](https://github.com/CWanli)
* 范业文 [@tofuwen](https://github.com/tofuwen)
* 戴雨森 [@yusendai](https://github.com/yusendai)


---

© 2023 [ZhenFund](http://zhenfund.com)
