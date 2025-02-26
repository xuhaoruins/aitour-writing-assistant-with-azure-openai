## Azure 凭据:

# 凭证

````
Username     = "@lab.CloudPortalCredential(User1).Username"

密码     = "@lab.CloudPortalCredential(User1).Password"

AzureEnvName = "AITOUR@lab.LabInstance.Id"

订阅 = "@lab.CloudSubscription.Id"
````

**如果您是从 Skillable 实验页面查看此内容的**，上方是您的专属 Azure 凭据。

> **注意**：稍后在实验中将要求您复制上述内容，因此请随时准备好这些信息。

**如果您正在通过 Github 查看此内容：** 上述内容并不是您的凭据，它们只是占位符。您的实际凭据可以在 Skillable 实验页面上查看。

***

### 欢迎参加 AI 之旅和工作坊 WRK551！

在本节中，您将学习如何构建应用程序 **Contoso Creative Writer**。此应用程序将帮助 Contoso Outdoors 的市场营销团队创作时尚且经过充分研究的文章，用于推广公司的产品。

### 前置条件

要参加此研讨会，您需要：

1. 您自己的笔记本电脑。
    * 它只需能够运行浏览器和 GitHub Codespaces，所以几乎任何笔记本电脑都可以使用。
    * 推荐使用最新版本的 Edge、Chrome 或 Safari 浏览器。

2. 一个 GitHub 账户。
    * 如果您还没有账户，可以[注册一个免费账户](https://github.com/signup)。
    * 在这次研讨会结束后，您的 GitHub 账户中将会有 "contoso-creative-writer" 仓库的一个分支副本，其中包括您在家中复现此次研讨会所需的所有材料。

3. 熟悉 Visual Studio Code。
    * 我们将在 GitHub Codespaces（一台虚拟化的 Linux 机器）中运行所有代码，而不是直接在您的本地笔记本电脑上运行。
    * VS Code Online 将是我们在 GitHub Codespaces 中使用的开发环境。
    * 如果您熟悉在笔记本电脑上使用 VS Code Desktop 运行 Codespaces，您也可以选择这么做。

4. （优选）熟悉 *bash* shell。
    * 我们将在 VS Code 的终端中使用 *bash* 来运行命令。

### 开始此实验，请按照以下步骤操作：

1. 确认您可以在页面顶部看到您的 **Azure 凭据**。  
    * 您稍后将使用这些凭据登录 Azure Developer CLI (AZD) 和 Azure CLI (AZ)。  

2. 点击此链接 [https://aka.ms/aitour/wrk551](https://aka.ms/aitour/wrk551)。这将带您前往项目的Github存储库。  
   * 如果您尚未登录Github，您需要使用**您自己的**GitHub账户凭证登录。

3. 点击页面右上角的绿色 **<> Code** 按钮。  
    * 点击 Codespaces 标签  
    * 然后点击 **Create codespace on main**  
    * 这将会在 main 分支上打开一个预构建的 Codespace。  

    > **🚧 重要**：不要在仓库的分叉版本中打开 GitHub Codespace，这会阻止您使用预构建的 Codespace 容器镜像。别担心，您稍后会有机会分叉该仓库。

4. 一旦你的 Codespace 准备好后：
   * 在文件资源管理器中找到 **docs** 文件夹，并打开其中的 **workshop** 文件夹。
   * 打开 **WORKSHOP-README.md** 文件。（该文件夹中还有其他的 Readme 文件，请特别打开 workshop 的那个文件。）
   * 按照说明开始操作！
   * 在按照此文件第 1 部分中的步骤登录 AZD 和 AZ 时，使用 Skillable 手册顶部的 [azure credentials](#azure-credentials) 进行登录。

Have fun building!🎉