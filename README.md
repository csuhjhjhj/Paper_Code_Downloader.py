# Paper_Code-Downloader

📚 **Paper_Code-Downloader** 是一款高效、轻量级的工具，专为研究人员和开发者打造，帮助您轻松批量下载学术论文及其相关代码，从此告别繁琐的手动下载！无论您在寻找最新的 arXiv 论文，还是想要深入研究 GitHub 上的开源项目，这款工具都能帮您一键搞定。

## 🔥 为什么选择 Paper_Code-Downloader？

- **⏱️ 批量下载，节省时间**：无须逐个点击，自动抓取并下载所有论文 PDF 和 GitHub 仓库代码。
- **📂 自动分类存储**：根据论文类别自动将文件分类保存，完美保持文件夹整洁有序。
- **🌐 支持多种来源**：支持从 arXiv 下载论文 PDF，自动抓取 GitHub 仓库代码。
- **📜 简洁易用**：只需几步设置，即可自动处理包含链接的 Markdown 文件。
- **💡 提高研究效率**：专为追求高效的研究人员和开发者打造，节省时间将精力集中在研究和开发上。

## 🎯 功能特色

- **一键批量下载**：从 Markdown 文件中提取所有论文和代码链接，批量下载 PDF 和 GitHub 仓库。
- **智能存储**：自动将文件按类别分类存储，方便检索和管理。
- **扩展性强**：支持多种论文和代码来源，未来还将加入更多平台支持。

## 🚀 快速开始

### 1. 克隆此项目

```python
https://github.com/csuhjhjhj/Paper_Code_Downloader.py
cd Paper_Code-Downloader
```

### 2. 安装依赖

```python
pip install -r requirements.txt
```

### 3. 编辑 Markdown 文件

使用您的 Markdown 文件（例如 `papers.md`），其中包含论文和代码链接，格式如下：

```markdown
+ Exploring the Impact of Large Language Models on Recommender Systems: An Extensive Review, arxiv 2024, [[paper]](https://arxiv.org/pdf/2402.18590), [[code]](https://github.com/example/repo).
+ A Survey on Large Language Models for Recommendation, arxiv 2023, [[paper]](https://arxiv.org/pdf/2305.19860), [[code]](https://github.com/example/anotherrepo).
```

### 4. 运行脚本

```python
python Paper_Code-Downloader.py
```

脚本会自动从 Markdown 文件中提取论文和代码链接，下载并保存到相应的类别文件夹中。

## 📁 文件存储结构

下载的论文和代码将自动存储在 `LLM4RS_Papers` 文件夹中，文件结构如下：

```python
LLM4RS_Papers/
├── Survey/
│   ├── Exploring_the_Impact_of_Large_Language_Models.pdf
│   ├── repo.zip
├── Paper List/
│   ├── A_Survey_on_Large_Language_Models.pdf
│   ├── anotherrepo.zip
...
```

## 🎓 学术资源获取从未如此轻松！

- **一站式解决方案**：只需提供论文和代码链接的 Markdown 文件，剩下的事情交给 Paper_Code-Downloader！
- **轻松分类管理**：自动化文件分类功能让您从繁杂的下载和管理工作中解放出来。
- **适合任何规模的研究项目**：无论您是在准备文献综述还是开发新算法，Paper_Code-Downloader 都能帮您节省宝贵时间。

## 🤝 贡献指南

我们欢迎任何形式的贡献！无论是提出改进建议，还是为项目贡献代码，都可以让 Paper_Code-Downloader 变得更好。

1. Fork 此仓库。
2. 创建您的功能分支：`git checkout -b feature/your-feature`
3. 提交您的更改：`git commit -m 'Add some feature'`
4. 推送到分支：`git push origin feature/your-feature`
5. 提交 Pull Request，加入我们！

## 📜 许可证

本项目基于 MIT License 进行分发。详情请参阅 LICENSE。

------

🚀 **Paper_Code-Downloader** —— 为研究而生，让您的论文和代码下载变得前所未有的简单高效！快来试试吧，解放你的时间！
