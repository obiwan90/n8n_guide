# n8n 工作流指南与RAG技术实现

本仓库包含了n8n工作流实现的RAG (检索增强生成) 系统的完整技术文档和JSON配置文件。

## 主要内容

- **n8n.md**: 详细的技术文档，介绍工作流设计和RAG技术实现
- **JSON文件**: 四个工作流的完整配置
- **截图**: 工作流图示

## 工作流

1. **Crawl4AI_Data_Extraction.json**: 从网站地图抓取和处理内容
2. **RAG_UpLoad.json**: 知识库数据上传和向量化
3. **RAG_Search.json**: 基于向量数据库的语义搜索和答案生成
4. **News_Data_Push.json**: 自动新闻数据获取和处理

## 技术组件

- Pinecone向量数据库
- Ollama嵌入模型
- DeepSeek聊天模型
- LangChain AI Agent

欢迎查看和使用这些工作流，了解如何通过n8n实现完整的RAG系统。