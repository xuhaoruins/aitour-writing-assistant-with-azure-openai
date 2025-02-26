# 支持

## 如何提交问题并获取帮助

如果您在源代码中发现了错误或在文档中发现了疏漏，您可以通过[提交问题](#submit-issue)到 GitHub 仓库来帮助我们。更棒的是，您还可以[提交拉取请求](#submit-pr)来修复这些问题。

## <a name="feature"></a> 想要一个新功能？

您可以通过[提交问题](#submit-issue)到 GitHub 仓库来*请求*一个新功能。如果您希望*实现*一个新功能，请先提交一个包含您计划的提案的问题，以确保我们能够使用它。

* **小功能** 可以制作完成后直接[提交为拉取请求](#submit-pr)。

## <a name="submit"></a> 提交指南

### <a name="submit-issue"></a> 提交问题
在您提交问题之前，请先搜索存档，也许您的问题已经被回答过了。

如果您的问题似乎是一个错误，并且尚未被报告，请新建一个问题。  
请不要重复报告问题，以便我们将更多精力用于修复问题和添加新功能。  
提供以下信息将有助于您的问题更快地得到解决：  

* **问题概述** - 如果抛出错误，未压缩的堆栈跟踪有助于排查问题  
* **版本** - 受影响的版本是什么（例如 0.1.2）  
* **动机或使用场景** - 解释您试图完成的任务，以及为什么当前行为对您来说是一个问题  
* **浏览器和操作系统** - 这个问题是否在所有浏览器上都存在？  
* **复现错误** - 提供一个实时示例或明确的步骤集  
* **相关问题** - 是否之前有类似的问题被报告过？  
* **建议的修复方法** - 如果您无法自己修复该错误，或许可以指明可能引起问题的来源（代码行或提交记录）  

您可以通过在相应存储库的问题链接提供上述信息来提交新问题：[https://github.com/Azure-Samples/contoso-creative-writer/issues/new](https://github.com/Azure-Samples/contoso-creative-writer/issues/new)。

### <a name="submit-pr"></a> 提交拉取请求（PR）
在提交拉取请求（PR）之前，请考虑以下指南：

* 在存储库中搜索 [https://github.com/Azure-Samples/contoso-creative-writer/pulls](https://github.com/Azure-Samples/contoso-creative-writer/pulls])，查看是否有与您的提交相关的已打开或已关闭的拉取请求（PR）。  
  您不希望重复工作。  

* 在一个新的 git 分支中进行更改：

* 使用描述性提交信息提交您的更改  
* 将您的分支推送到 GitHub：  
* 在 GitHub 上创建一个拉取请求  
* 如果我们建议进行更改，则：  
  * 进行所需的更新。  
  * 对您的分支进行变基并强制推送到您的 GitHub 仓库（这将更新您的拉取请求）：  

    ```shell
    git rebase master -i
    git push -f
    ```

就是这样！感谢您的贡献！

If you need help or have any questions regarding the use of this project, please create an issue as detailed above and mention [@marlenezw](https://github.com/marlenezw) if there is no response for more than 3 days.

## 微软支持政策  

对该**项目或产品**的支持仅限于上述列出的资源。