![Banner image](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)


# n8n - 技术团队的安全工作流自动化

n8n是一个工作流自动化平台，它为技术团队提供了代码的灵活性，同时具备无代码的速度。凭借400多种集成、原生AI功能和公平代码许可，n8n使您能够在构建强大自动化的同时，保持对数据和部署的完全控制。

![n8n.io - Screenshot](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## 关键能力

- **随需编码**：编写JavaScript/Python代码，和npm包，或使用可视化界面
- **原生AI平台**：使用您自己的数据和模型，基于LangChain构建AI代理工作流程
- **完全控制**：使用我们的公平代码许可进行自托管，或使用我们的[云服务](https://app.n8n.cloud/login)
- **企业级就绪**：高级权限、单点登录（SSO）和无隔阂部署
- **活跃社区**：400+集成和900+即用型[模板](https://n8n.io/workflows)

## 快速开始

立即使用[npx](https://docs.n8n.io/hosting/installation/npm/)（需要[Node.js](https://nodejs.org/en/)）尝试n8n：

```
npx n8n
```
或者使用[Docker](https://docs.n8n.io/hosting/installation/docker/)进行部署：

```
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

在http://localhost:5678访问编辑器

## 资源

- 📚 [文档](https://docs.n8n.io)
- 🔧 [400+集成](https://n8n.io/integrations)
- 💡 [工作流示例](https://n8n.io/workflows)
- 🤖 [AI与LangChain指南](https://docs.n8n.io/advanced-ai/)
- 👥 [社区论坛](https://community.n8n.io)
- 📖 [社区教程](https://community.n8n.io/c/tutorials/28)

## 支持

需要帮助吗？我们的社区论坛是获取支持并与其它用户交流的场所：
[community.n8n.io](https://community.n8n.io)

## 许可证

n8n是[fair-code](https://faircode.io)项目的一部分，遵循[可持续使用许可协议](https://github.com/n8n-io/n8n/blob/master/LICENSE.md)和[n8n企业许可协议](https://github.com/n8n-io/n8n/blob/master/LICENSE_EE.md)进行分发。

- **源代码可用**：始终可见的源代码
- **可自托管**：可部署在任何地方
- **可扩展性**：添加您自己的节点和功能
  
[企业版许可证](mailto:license@n8n.io) 可提供额外功能和支持。

有关许可模式的更多信息，请参阅[文档](https://docs.n8n.io/sustainable-use-license/)。

## 贡献

发现了一个bug🐛或者有一个功能想法✨？请查阅我们的[贡献指南](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md)以开始您的贡献。

## 加入团队

想要塑造自动化的未来吗？查看我们的[招聘信息](https://n8n.io/careers)，加入我们的团队吧！

## n8n是什么意思？

**简短回答:** 它的意思是“节点化”，发音为n-eight-n。

**长话短说:**：“我经常被问到这个问题（比我预想的还要频繁），所以我觉得最好在这里回答一下。在为项目寻找一个好名字并使用免费域名时，我很快意识到，我能想到的所有好名字都已经被使用了。所以，最后我选择了nodemation。'node-'代表它使用了Node-View和Node.js，而'-mation'代表'automation'，也就是该项目旨在帮助实现自动化。然而，我不喜欢这个名字太长，而且我无法想象每次都在命令行界面（CLI）中输入这么长的名字。于是我决定使用'n8n'。”——**Jan Oberhauser，n8n.io创始人兼首席执行官**
