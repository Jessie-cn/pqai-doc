# 用户指南（user-guide）
>本指南面向 PQAI 在线试用用户。
## 快速开始
### 1. 快速认识检索界面
![检索页截图](images/search.png)
- ① 输入框：你可以在这里用自然语言输入你想检索的技术方案描述（目前仅支持英文输入）。
- ② 检索：在输入框中完成输入后，你可以通过点击“Search”来查看PQAI针对技术方案描述的检索结果。
- ③ 高级选项：你可以通过点击“Advanced”来设置PQAI的检索范围。
- ④ 示例输入：这里给出了一些可操作的技术方案描述示例，你可点击其中的一个查看PQAI对应的检索结果。
- ⑤ 功能菜单栏：你可以在这里切换功能界面：[Search](#2-快速完成一次专利检索并导出报告)、[CPC Lookup](#cpc-lookup)、[GAU Predictor](#gau-predictor)、[Concept Extractor](#concept-extractor)、[Similar Words](#similar-words)、[What's New](#whats-new)、[API](#api)、[GitHub](#github)，各功能说明见对应章节。
- ⑥ 当前用户：你可以在这里登录你的账号。  

>下面以 **Search**功能为例，演示一次完整的专利检索与检索报告导出流程。
### 2. 快速完成一次专利检索并导出报告
1. 在输入框中输入技术方案描述。  
   ![query截图](images/search-query.png)
2. 输入完成后，点击“Advanced”，设置PQAI的检索范围（比如数据库范围、年份范围、国家范围等等）。  
   ![advanced截图](images/advanced.png)
3. 设置完成后，点击“Search”，查看PQAI在选定的检索范围内针对技术方案描述的检索结果。
   ![result截图](images/search-result.png)
4. 在检索结果页面，点击对比文件下方的“Save”进行保存。
   ![保存对比文件截图](images/save.png)
5. 保存完毕后，点击右上角的“Saved Result”，查看已保存的对比文件。你也可以在这里将不需要保存的对比文件删除，或者清空已保存的对比文件。
   ![保存结果截图](images/save-result.png)
6. 点击“PDF Report”，浏览器将下载基于已保存的对比文件生成的PDF检索报告。你可以在PDF检索报告保存到本地后将其分享给他人。  
>免责声明：PQAI 导出的检索报告不构成法律意见，检索结果仅限于检索报告生成时 PQAI 数据库中可获取的专利和非专利文献，不保证信息的完整性和准确性。报告仅供辅助评估，重要决策前请咨询专业律师，并建议通过美国专利商标局等官方来源核对专利详情。完整免责声明见检索报告末页。  

## CPC Lookup
你可以点击功能菜单栏的“CPC Lookup”，查询与技术方案描述相关的IPC/CPC分类号，或查询指定分类号的定义。操作流程如下：
1. “CPC Lookup”功能界面下，在输入框中输入技术方案描述或者IPC/CPC完整分类号。
  ![CPC查询输入截图](images/cpc-input.png)  
2. 输入完成后，点击“Search”，查看与输入内容相匹配的IPC/CPC分类号信息。  
  ![CPC查询输出截图](images/cpc-output.png)
## GAU Predictor
>GAU 全称是 Group Art Unit，指美国专利商标局（USPTO）内部负责审查特定技术领域专利申请的审查单元。  
你可以点击功能菜单栏的“GAU Predictor”，查看技术方案最有可能被分配到的审查单元。操作流程如下：
1. “GAU Predictor”功能界面下，在输入框中输入技术方案描述。
   ![GAU输入截图](images/GAU-input.png)
2. 输入完成后，点击“Search”，查看技术方案最有可能被分配到的审查单元。
   ![GAU输出截图](images/GAU-output.png)
## Concept Extractor
你可以点击功能菜单栏中的“Concept Extractor”，提取技术方案描述中的技术关键词。操作流程如下：
1. “Concept Extractor”功能界面下，在输入框中输入技术方案描述。
   ![关键词提取输入截图](images/concept-input.png)
2. 输入完成后，点击“Submit”，查看从输入内容中提取的技术关键词。
   ![关键词提取输出截图](images/concept-output.png)
## Similar Words
你可以点击功能菜单栏的“Similar Words”，查询与技术关键词语义相近的其他技术关键词。操作流程如下：
1. “Similar Words”功能界面下，在输入框中输入技术关键词。
   ![相似词输入截图](images/similar-input.png)
2. 输入完成后，点击“Submit”，查看与输入内容相近的技术关键词。
   ![相似词输出截图](images/similar-output.png)
## What's New
你可以点击功能菜单栏的“What's New”，查看PQAI的[更新说明](https://search.projectpq.ai/updates)。
## API
你可以点击功能菜单栏的“API”，查看PQAI的[API接口文档](https://search.projectpq.ai/api-docs)。
## GitHub
你可以点击功能菜单栏的“GitHub”，跳转至PQAI的[GitHub仓库](https://github.com/pqaidevteam/pqai)。

