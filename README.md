# ZhenBench

Z-Bench 0.9 by 真格基金 一个非技术人员的大语言模型中文测试集

贡献者：陈芳洲、Peak Ji、代码家、李植、陈万里、戴雨森

© 2023 [ZhenFund](http://zhenfund.com)

自从ChatGPT发布以来，我们经常会在使用它时发出惊叹：“啊，这个居然它也会！”同时，我们也欣喜地看到越来越多的大模型团队和产品如雨后春笋般出现，作为早期投资人，我们经常需要试用评估一些新出来的对话式AI产品。这时，我们会使用一些prompts来与行业龙头ChatGPT进行对比。我们逐渐记录下了很多有意思的prompts，以及一些目前大语言模型可能还不能很好处理的prompts。

OpenAI已经公布了ChatGPT的48种典型能力，之前在NLP领域也有MMLU、Big-bench、Glue等广为使用的测试集，并且研究表明，大模型随着参数和数据规模增大，会涌现出新的能力。但是之前的NLP任务测试集里，有的任务不一定适合对话式系统，有的任务不一定有好的中文版本。并且随着这些测试集成为行业标准，可能也会出现定向优化和过拟合的情况。因此，我们几个VC麻瓜，从自己的需求出发，作为对话式AI的重度用户，总结推出了Z-Bench——一个为非技术人员定性测试大模型对话式产品（类ChatGPT产品）准备的测试集。

Z-Bench 0.9测试集提供了基础能力，进阶能力，垂直能力共300个prompts，我们希望尽量覆盖不同类型的NLP任务。但是我们的目标并不是提供一个学术上非常严谨完整的测试集，而是希望通过结合学术上已有的测试集、日常搜集的一些有意思的案例，以及大模型出现之后学术界发现的涌现和顿悟能力，提供一个适合非技术专业人士使用的大模型能力测试集。因此，难免会漏掉一些场景，或是出现很多专业角度看比较业余的内容。我们会在未来不断的根据搜集到的反馈去补充完善，并且及时予以公布。

common.samples：基础能力测试集

emergent.samples：进阶能力测试集

specialized.samples：垂直领域测试集

参考资料：

OpenAI介绍的ChatGPT基础能力列表：https://platform.openai.com/examples

SuperGLUE：https://arxiv.org/abs/1905.00537

MMLU：https://arxiv.org/abs/2009.03300

Big-Bench：https://arxiv.org/abs/2206.04615

Emergent Abilities of Large Language Models：https://arxiv.org/abs/2206.07682
