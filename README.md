# AI模型能力对比分析工具

一个交互式的AI模型能力对比分析工具，支持多维度评估和可视化展示。

## 🌟 功能特点

- **多维度评估**：支持多模态、性能测试、易用性、搜索质量、额度限制、可用地区等维度
- **版本对比**：区分免费版和付费版功能对比
- **可视化展示**：使用雷达图直观展示各模型能力
- **交互式界面**：支持动态选择评估维度和模型
- **深色模式**：支持浅色/深色主题切换
- **响应式设计**：适配桌面端和移动端

## 🚀 在线演示

访问 [GitHub Pages 演示页面](https://ink1ing.github.io/ai-model-comparison/)

## 📊 支持的AI模型

- **GPT** (OpenAI)
- **Claude** (Anthropic)
- **Gemini** (Google)
- **Grok** (xAI)
- **Perplexity** (Perplexity AI)
- **DeepSeek** (DeepSeek)
- **Doubao** (字节跳动)

## 🛠️ 技术栈

- **前端**：HTML5, CSS3, JavaScript (ES6+)
- **图表库**：Chart.js
- **样式**：CSS Grid, Flexbox, CSS Variables
- **主题**：支持深色/浅色模式切换

## 📱 使用方法

1. **选择版本**：在免费版和付费版之间切换
2. **选择维度**：至少选择3个评估维度
3. **查看结果**：雷达图显示各模型在选定维度的表现
4. **交互操作**：
   - 点击图例可隐藏/显示特定模型
   - 切换深色/浅色主题
   - 查看详细统计信息

## 🎯 评估维度说明

### 免费版维度
- **多模态**：处理文本、图像、音频等多种输入格式的综合能力
- **性能测试**：在标准化基准测试中的表现
- **易用性**：用户界面友好度、响应速度和交互体验
- **搜索质量**：实时信息检索准确性和联网搜索结果的相关性
- **免费额度**：免费用户每日可使用的消息数量和功能访问限制
- **可用地区**：全球不同国家和地区的服务可访问性和稳定性

### 付费版维度
- **多模态**：处理文本、图像、音频等多种输入格式的综合能力
- **性能测试**：在标准化基准测试中的表现
- **易用性**：用户界面友好度、响应速度和交互体验
- **搜索质量**：实时信息检索准确性和联网搜索结果的相关性
- **高级额度**：付费用户的使用限制、高级功能访问和优先级支持
- **可用地区**：全球不同国家和地区的服务可访问性和稳定性

## 📈 数据来源

本工具的评估数据来源于以下权威机构和平台：

- [MLCommons](https://mlcommons.org/en/) - 机器学习基准测试
- [Stanford HELM](https://crfm.stanford.edu/helm/) - 斯坦福语言模型评估
- [LMSYS Chatbot Arena](https://chat.lmsys.org/) - 聊天机器人竞技场
- [Papers With Code](https://paperswithcode.com/) - 学术论文和代码

## 🚀 本地运行

1. 克隆仓库：
```bash
git clone https://github.com/ink1ing/ai-model-comparison.git
cd ai-model-comparison
```

2. 使用本地服务器运行（推荐）：
```bash
# 使用 Python
python -m http.server 8000

# 或使用 Node.js
npx serve .

# 或使用 PHP
php -S localhost:8000
```

3. 在浏览器中访问 `http://localhost:8000`

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 🙏 致谢

- [Chart.js](https://www.chartjs.org/) - 优秀的图表库
- 各大AI公司提供的优质模型服务
- 开源社区的支持和贡献

## 📞 联系方式

如有问题或建议，请通过以下方式联系：

- 提交 [GitHub Issue](https://github.com/ink1ing/ai-model-comparison/issues)
- 发起 [GitHub Discussion](https://github.com/ink1ing/ai-model-comparison/discussions)

---

⭐ 如果这个项目对你有帮助，请给个 Star 支持一下！