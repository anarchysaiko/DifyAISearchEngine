# DifyAISearchEngine

## 项目概述

DifyAISearchEngine 是一个基于 Dify 构建的高级搜索工具，结合了人工智能和传统搜索引擎的优势。该工具能够理解并总结用户查询，执行智能搜索，并以结构化格式呈现相关信息。

## 主要特性

- **智能查询处理**: 自动总结和优化用户输入
- **集成搜索**: 利用 DuckDuckGo 搜索引擎获取最新、相关的信息
- **AI 驱动的结果总结**: 将搜索结果压缩为易于理解的摘要
- **结构化输出**: 以 Markdown 格式呈现信息，便于阅读和进一步使用
- **来源引用**: 自动为所提供的信息注明参考来源

## 工作流程

1. **用户输入处理**: 系统接收并分析用户的查询请求。
2. **查询总结**: AI 模型总结用户输入，提取关键信息。
3. **搜索执行**: 使用优化后的查询通过 DuckDuckGo 执行搜索。
4. **结果处理**: 收集和分析搜索结果。
5. **内容总结**: AI 对搜索结果进行综合和总结。
6. **格式化输出**: 将总结内容转换为 Markdown 格式。
7. **添加引用**: 为总结的信息添加原始来源链接。

## 使用方法

克隆本项目，或下载DifyAISearchEngine.yml文件，导入Dify即可

## 依赖

- [Dify 平台](https://github.com/langgenius/dify)

## 配置

导入DifyAISearchEngine.yml文件，配置大语言模型即可


## 许可证

本项目采用 Apache License 2.0 许可证。

这意味着您可以自由地：使用本软件进行商业用途、修改源代码、分发原始或修改后的版本

但要求您：包含原始的版权声明、声明对源代码的重大更改、在分发的软件中包含一份许可证副本

完整的许可证文本可以在项目根目录的 LICENSE 文件中找到。


## 致谢

- [Dify 团队提供的强大平台](https://github.com/langgenius/dify)
- [DuckDuckGo](https://duckduckgo.com)
