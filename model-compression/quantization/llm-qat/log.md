


训练数据来源：

方案一：使用开源数据集。

方案二：使用LLM合成数据。


20230803：

目前，代码中支持使用开源的公开数据集。

20230814：(commit-id: f4d873a)

目前，代码中支持使用LLM合成数据。





目前存在的问题：
- 未提供模型评估和模型推理的代码。仅有在模型训练过程中，使用Huggingface的evaluate方法进行评估，相当于仅能评估模型效果，不能评估推理速度。
- 代码没办法直接运行，需要自行修改源码才能启动。



