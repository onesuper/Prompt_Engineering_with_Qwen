# Qwen 提示词工程指南

本教程翻译并改编自《Llama 2 提示词工程指南》，使用了 Qwen（通义千问） 作为 LLM，并采用了全中文的提示词。

旨在通过交互式 Notebook 展示使用 Qwen 进行提示词工程的最佳实践。Qwen 模型推理基于 Xinference，可以在 Colab 中运行。

示例提示词技术包含以下:

* 显示指令
* 零样本（Zero-shot）和少样本（Few-Shot）学习
* 角色提示词
* 思考链（CoT）
* RAG（检索增强生成）
* 基于于程序辅助的语言模型（Program-Aided ）
* 限制多余令牌