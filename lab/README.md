# 会话文件夹

该文件夹包含实验 `WRK551` 的面向公众的文件。

# 使用 Azure OpenAI 构建一个多任务助手

本说明适用于参加微软 AI 巡回 2024-2025 的研讨会“使用 Azure OpenAI 构建多任务助手”的参与者。

!!! 注意 "微软AI巡回演讲2024现已开放注册"

该研讨会作为**讲师引导**课程（WRK551）提供，属于**从原型到生产**系列：

> 在本次研讨会中，参与者将了解到代理（Agents）的概念，这是一种结合思维和行动的人工智能方法，利用LLMs（大型语言模型）和工具来实现特定目标。展示的示例将演示如何创建一个Python应用程序，该应用程序从用户获取一个主题和指令，然后调用多个代理来完成任务：研究代理使用Bing搜索API调查主题，产品代理使用Azure AI搜索在向量存储中进行语义相似度搜索以找到相关产品，撰写代理将研究结果和产品信息整合成一篇实用的文章，最后编辑代理对文章进行完善并将其呈现给用户。

    - [**注册参加**](https://aitour.microsoft.com/) 离您最近的巡回站点。
    - [**查看实验室资源**](https://aka.ms/aitour/wrk551) 以继续您的探索之旅。

如果您不是 AI Tour 研讨会的参与者，请访问 [https://github.com/Azure-Samples/contoso-creative-writer](https://github.com/Azure-Samples/contoso-creative-writer)，获取可使用您自己的 Azure 订阅运行的研讨会版本。

## 前置条件

要参加此研讨会，您需要：

1. 您自己的笔记本电脑  
   * 只需能够运行浏览器和 GitHub Codespaces，因此几乎任何笔记本电脑都可以使用。  
   * 推荐使用最新版本的 Edge、Chrome 或 Safari。  

2. 一个 GitHub 账户  
   * 如果您还没有，可以立即[注册一个免费的账户](https://github.com/signup)。  
   * 完成本次研讨会后，您的 GitHub 账户中将有一个“contoso-chat”仓库的分支，其中包括您在家中重现该研讨会所需的所有材料。  

3. 熟悉 Visual Studio Code  
   * 我们将在 GitHub Codespaces 中运行所有代码，这是一个虚拟化的 Linux 机器，而不是在您的本地笔记本电脑上直接运行。  
   * VS Code Online 将是我们在 GitHub Codespaces 中的开发环境。  
   * 如果您熟悉在笔记本电脑上的 VS Code 桌面版中运行 Codespaces，也可以这样操作。  

4. （优选）熟悉 `bash` shell  
   * 我们将在 VS Code 的终端中使用 `bash` 来运行命令。  

## 入门

要开始，请按照 Skillable 环境中的 Skillable Lab Manual 中的指示操作。在完成这些指示后，您应该已经成功为 [conotoso-creative-writer](https://github.com/Azure-Samples/contoso-creative-writer) 仓库在您的分支上启动了 Codespace。您可以通过点击 [这里](../train-the-trainer/LAB_MANUAL.md) 查看此仓库中的 Skillable Lab Manual 指示。

## 继续研讨会

在您的 Codespace 中，使用左侧的 VS Code 在线文件资源管理器，进入文件夹 `docs\workshop` 并打开 `README` 文件。

好的，请提供需要翻译的文件内容，我会根据您提供的内容进行翻译。

## 讨论

Contoso Creative Writer 是一个由微软支持的开源项目。有关如何报告问题或贡献的详细信息，请参阅 [SUPPORT.md](../SUPPORT.md) 文件。如果您喜欢这个研讨会，请为该代码仓库点一个 ⭐ 并与他人分享。

## 额外资源和持续学习
| 资源             | 链接                              | 描述            |
|-----------------|----------------------------------|-------------------|
| 更多关于 Prompty  | [Prompty](https://prompty.ai/) | 了解更多关于 Prompty |
| Azure AI Studio | [Azure AI Studio](https://ai.azure.com/) | 深入探索 Azure AI Studio |
| Awesome AZD     | [Awesome AZD](https://azure.github.io/awesome-azd/) | 使用 AZD 模板构建更多 AI 项目 |

## 源代码

此会话的源代码可以在[此处](https://github.com/Azure-Samples/contoso-creative-writer)找到。