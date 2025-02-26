# 构建多任务助手与 Azure OpenAI
[![Azure AI 社区 Discord](
https://dcbadge.vercel.app/api/server/ByRwuEEgH4)](https://discord.com/invite/ByRwuEEgH4?WT.mc_id=aiml-00001-leestott)

此仓库是微软 AI 巡回活动的研讨会配套资源，涵盖一系列全球性活动。

> 在官方网站了解更多关于 Microsoft AI Tour 的信息。

![会话封面图片，带有明亮的“AI”3D文字，背景为蓝色和紫色的抽象图案。](img/mulit-task-assistant-cover.png)

## 会话描述

在本次研讨会中，参与者将会了解“代理”这一概念，这是一种结合了大型语言模型（LLM）和工具以实现特定目标的人工智能方法。演示案例将展示如何创建一个Python应用程序，该应用程序从用户处接收主题和指令，然后调用以下代理完成任务：一个使用Bing搜索API进行主题研究的研究代理；一个使用Azure AI搜索从向量存储中进行语义相似性搜索以获取相关产品的产品代理；一个将研究信息和产品信息合并成有用文章的写作代理；以及一个优化并精炼最终呈现给用户文章的编辑代理。

## 学习成果

实施一个基于现实世界的LLM代理生命周期  
- 通过 [Prompty](https://prompty.ai) 理解代理和提示工程  
- 使用追踪进行调试和可观测性  
- 构建并运行 Contoso Creative Writer  
- 使用 GitHub Actions 设置自动化评估  

## 使用的技术
- 后端应用  
  - Prompty  
  - FastAPI  
  - OpenTelemetry  
- 前端应用  
  - React  
  - Typescript  
  - ViteJS  
- AI 模型  
  - GPT-4o  
  - GPT-3.5 Turbo  
- 工具  
  - Azure AI Search  
  - Bing Search  
- 监控  
  - AppInsights  
  - Promptflow tracing  
- 基础设施  
  - Azure 容器应用 (ACA)  
  - Azure AI Hub  
  - 托管身份  
  - 密钥保管库  
- 基础设施即代码  
  - azd (Azure Developer CLI)  
- CI/CD  
  - Github Actions  

## 额外资源与持续学习
如果您想自己进行此演讲，您可以在[此处找到演讲者和监考资源](./session-delivery-resources/README.md)。

| 资源               | 链接                              | 描述               |
|:-------------------|:----------------------------------|:-------------------|
| Prompty           | [了解更多](https://prompty.ai)   | 了解更多关于 Prompty 的信息，这是一种针对大语言模型提示的新资产类别和格式，旨在为开发者提供可观察性、可理解性和可移植性 |
| 开发者的 AI        | [了解更多](https://developer.microsoft.com/en-us/ai#ai-solutions) | 了解更多关于微软为开发者提供的不同 AI 工具和服务 |

## 内容所有者

<!-- ALL-CONTRIBUTORS-LIST:START - 请勿移除或修改此部分 -->

<table>
<tr>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://github.com/marlenezw.png" width="100px;" alt="Marlene Mhangami"/><br />
        <sub><b>Marlene Mhangami
</b></sub></a><br />
            <a href="https://github.com/marlenezq" title="演讲">📢</a> 
    </td>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://github.com/cassiebreviu.png" width="100px;" alt="Cassie Breviu"/><br />
        <sub><b>Cassie Breviu
</b></sub></a><br />
            <a href="https://github.com/Cassie Breviu" title="演讲">📢</a> 
    </td>
</tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## 负责任的人工智能

Microsoft 致力于帮助客户负责任地使用我们的 AI 产品，分享我们的经验，并通过诸如透明性说明和影响评估等工具建立基于信任的合作伙伴关系。许多此类资源可在 [https://aka.ms/RAI](https://aka.ms/RAI) 找到。

Microsoft 在负责的 AI 方法中以我们的 AI 原则为基础，这些原则包括公平性、可靠性和安全性、隐私和安全性、包容性、透明性以及问责制。

大规模的自然语言、图像和语音模型（例如此示例中使用的模型）可能会以不公平、不可靠或冒犯的方式表现，从而导致伤害。请参考 [Azure OpenAI 服务透明性说明](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) 了解相关风险和限制。

建议的缓解这些风险的方法是在您的架构中包含一个安全系统，该系统可以检测和防止有害行为。[Azure AI 内容安全](https://learn.microsoft.com/azure/ai-services/content-safety/overview) 提供了一层独立的保护，可以检测应用程序和服务中用户生成的内容以及 AI 生成的有害内容。Azure AI 内容安全包括文本和图像 API，能够检测有害内容。在 Azure AI Studio 中，内容安全服务允许您查看、探索，并试用检测不同形式有害内容的示例代码。以下的[快速入门文档](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) 将指导您向该服务发出请求。

另一个需要考虑的方面是整体应用性能。对于多模态和多模型应用来说，我们所指的性能是系统能够按照您和您的用户的期望运行，包括不生成有害的输出。因此，使用[性能和质量以及风险与安全评估工具](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in)来评估您的整体应用性能是非常重要的。您还可以通过[自定义评估工具](https://learn.microsoft.com/azure/ai-studio/how-to/develop/evaluate-sdk#custom-evaluators)进行创建和评估。

您可以使用 [Azure AI Evaluation SDK](https://microsoft.github.io/promptflow/index.html) 在您的开发环境中评估 AI 应用程序。通过提供测试数据集或目标，使用内置评估器或您选择的自定义评估器，可以对生成式 AI 应用程序的生成结果进行定量测量。要开始使用 Azure AI Evaluation SDK 来评估您的系统，可以参考[快速入门指南](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk)。一旦执行评估运行，您可以在 [Azure AI Studio 中可视化结果](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results)。