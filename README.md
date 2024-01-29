# Qwen 提示词工程指南

本教程翻译并改编自[《Llama 2 提示词工程指南》](https://github.com/facebookresearch/llama-recipes/blob/main/examples/Prompt_Engineering_with_Llama_2.ipynb?utm_source=twitter&utm_medium=organic_social&utm_campaign=llama&utm_content=video)，使用了 Qwen（通义千问） 作为 LLM，并采用了全中文的提示词。

旨在通过交互式 Notebook 展示使用 Qwen 进行提示词工程的最佳实践。Qwen 模型推理基于 Xinference，可以[在 Colab 中直接运行](https://colab.research.google.com/github/onesuper/Prompt_Engineering_with_Qwen/blob/main/Prompt_Engineering_with_Qwen.ipynb)。

示例使用提示词技术包含:

* 显示指令
* 零样本（Zero-shot）和少样本（Few-Shot）学习
* 角色提示词
* 思考链（CoT）
* Self-Consistency
* RAG（检索增强生成）
* 基于程序辅助的语言模型（Program-Aided）
* 限制多余令牌