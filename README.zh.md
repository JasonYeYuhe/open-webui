# Open WebUI 👋

<p align="center">
  <a href="README.md">English</a> ·
  <strong>中文</strong>
</p>

![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
![GitHub forks](https://img.shields.io/github/forks/open-webui/open-webui?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/open-webui/open-webui?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/open-webui/open-webui)
![GitHub language count](https://img.shields.io/github/languages/count/open-webui/open-webui)
![GitHub top language](https://img.shields.io/github/languages/top/open-webui/open-webui)
![GitHub last commit](https://img.shields.io/github/last-commit/open-webui/open-webui?color=red)
[![Discord](https://img.shields.io/badge/Discord-Open_WebUI-blue?logo=discord&logoColor=white)](https://discord.gg/5rJgQTnV4s)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/tjbck)

![Open WebUI Banner](./banner.png)

**Open WebUI 是一个[可扩展](https://docs.openwebui.com/features/extensibility/plugin)、功能丰富且用户友好的自托管 AI 平台，旨在完全离线运行。** 它支持各种 LLM 运行器，如 **Ollama** 和**兼容 OpenAI 的 API**，并内置用于 RAG 的**推理引擎**，使其成为一个**强大的 AI 部署解决方案**。

热爱开源 AI？[加入我们的团队 →](https://careers.openwebui.com/)

![Open WebUI Demo](./demo.png)

> [!TIP]  
> **正在寻找[企业版方案 (Enterprise Plan)](https://docs.openwebui.com/enterprise)？** – **[立即与我们的销售团队联系！](https://docs.openwebui.com/enterprise)**
>
> 获得**增强功能**，包括**自定义主题和品牌**、**服务级别协议 (SLA) 支持**、**长期支持 (LTS) 版本**以及**更多功能！**

有关更多信息，请务必查看我们的 [Open WebUI 文档](https://docs.openwebui.com/)。

## Open WebUI 的核心功能 ⭐

- 🚀 **轻松安装**：使用 Docker 或 Kubernetes（kubectl、kustomize 或 helm）无缝安装，享受无忧体验，同时支持 `:ollama` 和 `:cuda` 标签的镜像。

- 🤝 **Ollama/OpenAI API 集成**：轻松集成兼容 OpenAI 的 API，与 Ollama 模型一起进行多功能对话。自定义 OpenAI API URL 以链接 **LMStudio、GroqCloud、Mistral、OpenRouter 等**。

- 🛡️ **细粒度权限和用户组**：通过允许管理员创建详细的用户角色和权限，我们确保了安全的用户环境。这种细粒度不仅提高了安全性，还允许定制用户体验，培养用户的归属感和责任感。

- 📱 **响应式设计**：在台式电脑、笔记本电脑和移动设备上享受无缝体验。

- 📱 **移动设备的渐进式 Web 应用 (PWA)**：借助我们的 PWA，在您的移动设备上享受类似原生应用的体验，提供在 localhost 上的离线访问和无缝的用户界面。

- ✒️🔢 **完整的 Markdown 和 LaTeX 支持**：通过全面的 Markdown 和 LaTeX 功能提升您的 LLM 体验，实现丰富的交互。

- 🎤📹 **免提语音/视频通话**：通过集成免提语音和视频通话功能，使用多个语音转文本 (Speech-to-Text) 提供商（Local Whisper、OpenAI、Deepgram、Azure）和文本转语音 (Text-to-Speech) 引擎（Azure、ElevenLabs、OpenAI、Transformers、WebAPI），体验无缝通信，从而实现动态和交互式的聊天环境。

- 🛠️ **模型构建器 (Model Builder)**：通过 Web UI 轻松创建 Ollama 模型。创建并添加自定义角色/智能体、自定义聊天元素，并通过 [Open WebUI 社区](https://openwebui.com/)的集成轻松导入模型。

- 🐍 **原生 Python 函数调用工具**：在工具工作区中使用内置的代码编辑器支持来增强您的 LLM。通过简单地添加您的纯 Python 函数，自带函数 (Bring Your Own Function, BYOF)，实现与 LLM 的无缝集成。

- 💾 **持久化产物存储 (Artifact Storage)**：内置用于产物的键值存储 API，支持诸如日志、跟踪器、排行榜和协作工具等功能，并跨会话提供个人和共享的数据范围。

- 📚 **本地 RAG 集成**：使用您选择的 9 种向量数据库和多种内容提取引擎（Tika、Docling、Document Intelligence、Mistral OCR、外部加载器），享受突破性的检索增强生成 (RAG) 支持，探索未来聊天交互。直接将文档加载到聊天中，或将文件添加到文档库，在查询之前使用 `#` 命令轻松访问它们。

- 🔍 **用于 RAG 的 Web 搜索**：使用超过 15 个提供商进行 Web 搜索，包括 `SearXNG`、`Google PSE`、`Brave Search`、`Kagi`、`Mojeek`、`Tavily`、`Perplexity`、`serpstack`、`serper`、`Serply`、`DuckDuckGo`、`SearchApi`、`SerpApi`、`Bing`、`Jina`、`Exa`、`Sougou`、`Azure AI Search` 和 `Ollama Cloud`，将结果直接注入您的聊天体验中。

- 🌐 **Web 浏览功能**：使用 `#` 命令加上 URL，将网站无缝集成到您的聊天体验中。此功能允许您将 Web 内容直接纳入对话中，增强交互的丰富性和深度。

- 🎨 **图像生成与编辑集成**：使用多种引擎（包括 OpenAI 的 DALL-E、Gemini、ComfyUI (本地) 和 AUTOMATIC1111 (本地)）创建和编辑图像，支持生成和基于提示的编辑工作流。

- ⚙️ **多模型对话**：轻松同时与各种模型交互，利用它们独特的优势获得最佳响应。通过并行利用各种不同的模型来提升您的体验。

- 🔐 **基于角色的访问控制 (RBAC)**：通过受限权限确保安全访问；只有获得授权的人员才能访问您的 Ollama，专属的模型创建/拉取权限仅保留给管理员。

- 🗄️ **灵活的数据库与存储选项**：可选择 SQLite（可选加密）、PostgreSQL，或配置云存储后端（S3、Google Cloud Storage、Azure Blob Storage）以进行可扩展部署。

- 🔍 **高级向量数据库支持**：从 9 种向量数据库选项中进行选择，包括 ChromaDB、PGVector、Qdrant、Milvus、Elasticsearch、OpenSearch、Pinecone、S3Vector 和 Oracle 23ai，以获得最佳的 RAG 性能。

- 🔐 **企业级身份验证**：全面支持 LDAP/Active Directory 集成、SCIM 2.0 自动配置以及与 OAuth 提供商并排的通过受信任标头进行 SSO。通过 SCIM 2.0 协议提供企业级用户和组配置，实现与 Okta、Azure AD 和 Google Workspace 等身份提供商的无缝集成，以实现自动化的用户生命周期管理。

- ☁️ **云原生集成**：原生支持 Google Drive 和 OneDrive/SharePoint 文件选择器，实现从企业云存储中无缝导入文档。

- 📊 **生产环境可观测性**：内置 OpenTelemetry 支持以进行追踪、指标和日志记录，利用您现有的可观测性堆栈实现全面监控。

- ⚖️ **水平可扩展性**：支持 Redis 支持的会话管理和 WebSocket，适用于负载均衡器后面的多工作节点和多节点部署。

- 🌐🌍 **多语言支持**：借助我们的国际化 (i18n) 支持，以您首选的语言体验 Open WebUI。加入我们，扩展我们支持的语言！我们正在积极寻找贡献者！

- 🧩 **Pipelines，Open WebUI 插件支持**：使用 [Pipelines 插件框架](https://github.com/open-webui/pipelines) 将自定义逻辑和 Python 库无缝集成到 Open WebUI 中。启动您的 Pipelines 实例，将 OpenAI URL 设置为 Pipelines URL，并探索无限的可能性。[示例](https://github.com/open-webui/pipelines/tree/main/examples)包括**函数调用**、控制访问的**用户速率限制**、使用 Langfuse 等工具进行**使用监控**、支持多语言的 **LibreTranslate 实时翻译**、**有毒信息过滤**等等。

- 🌟 **持续更新**：我们致力于通过定期更新、修复和新功能来不断改进 Open WebUI。

想了解更多关于 Open WebUI 功能的信息吗？查看我们的 [Open WebUI 文档](https://docs.openwebui.com/features) 了解全面概述！

---

我们非常感谢赞助商的慷慨支持。他们的贡献帮助我们维护和改进我们的项目，确保我们能够继续为社区提供高质量的工作。谢谢！

## 如何安装 🚀

### 通过 Python pip 安装 🐍

Open WebUI 可以使用 pip（Python 包安装程序）进行安装。在继续之前，请确保您使用的是 **Python 3.11**，以避免兼容性问题。

1. **安装 Open WebUI**：
   打开您的终端并运行以下命令来安装 Open WebUI：

   ```bash
   pip install open-webui
   ```

2. **运行 Open WebUI**：
   安装后，您可以通过执行以下命令启动 Open WebUI：

   ```bash
   open-webui serve
   ```

这将启动 Open WebUI 服务器，您可以在 [http://localhost:8080](http://localhost:8080) 访问它。

### Docker 快速入门 🐳

> [!NOTE]  
> 请注意，对于某些 Docker 环境，可能需要进行额外的配置。如果您遇到任何连接问题，我们关于 [Open WebUI 文档](https://docs.openwebui.com/) 的详细指南随时准备为您提供帮助。

> [!WARNING]
> 当使用 Docker 安装 Open WebUI 时，请确保在 Docker 命令中包含 `-v open-webui:/app/backend/data`。此步骤至关重要，因为它可确保您的数据库正确挂载并防止任何数据丢失。

> [!TIP]  
> 如果您希望使用包含 Ollama 或 CUDA 加速的 Open WebUI，我们建议使用带有 `:cuda` 或 `:ollama` 标签的官方镜像。要启用 CUDA，您必须在 Linux/WSL 系统上安装 [Nvidia CUDA 容器工具包](https://docs.nvidia.com/dgx/nvidia-container-runtime-upgrade/)。

### 使用默认配置安装

- **如果 Ollama 在您的计算机上**，请使用此命令：

  ```bash
  docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

- **如果 Ollama 在另一台服务器上**，请使用此命令：

  要连接到另一台服务器上的 Ollama，请将 `OLLAMA_BASE_URL` 更改为该服务器的 URL：

  ```bash
  docker run -d -p 3000:8080 -e OLLAMA_BASE_URL=https://example.com -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

- **要运行支持 Nvidia GPU 的 Open WebUI**，请使用此命令：

  ```bash
  docker run -d -p 3000:8080 --gpus all --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:cuda
  ```

### 仅限 OpenAI API 使用的安装

- **如果您仅使用 OpenAI API**，请使用此命令：

  ```bash
  docker run -d -p 3000:8080 -e OPENAI_API_KEY=your_secret_key -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

### 安装捆绑 Ollama 支持的 Open WebUI

此安装方法使用将 Open WebUI 与 Ollama 捆绑在一起的单一容器镜像，从而允许通过单个命令简化设置。根据您的硬件设置选择适当的命令：

- **具有 GPU 支持**：
  通过运行以下命令利用 GPU 资源：

  ```bash
  docker run -d -p 3000:8080 --gpus=all -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```

- **仅使用 CPU**：
  如果您不使用 GPU，请改用此命令：

  ```bash
  docker run -d -p 3000:8080 -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```

这两个命令都有助于在无需麻烦的情况下内置安装 Open WebUI 和 Ollama，确保您可以迅速启动并运行所有内容。

安装后，您可以在 [http://localhost:3000](http://localhost:3000) 访问 Open WebUI。享受吧！😄

### 其他安装方法

我们提供各种替代安装方法，包括非 Docker 原生安装方法、Docker Compose、Kustomize 和 Helm。访问我们的 [Open WebUI 文档](https://docs.openwebui.com/getting-started/) 或加入我们的 [Discord 社区](https://discord.gg/5rJgQTnV4s) 获取全面指导。

查看[本地开发指南](https://docs.openwebui.com/getting-started/development)了解关于设置本地开发环境的说明。

### 故障排除

遇到连接问题？我们的 [Open WebUI 文档](https://docs.openwebui.com/troubleshooting/) 可以为您提供帮助。如需进一步的帮助并加入我们充满活力的社区，请访问 [Open WebUI Discord](https://discord.gg/5rJgQTnV4s)。

#### Open WebUI: 服务器连接错误

如果您遇到连接问题，通常是因为 WebUI docker 容器无法访问容器内 127.0.0.1:11434 (host.docker.internal:11434) 处的 Ollama 服务器。在您的 docker 命令中使用 `--network=host` 标志来解决此问题。请注意，端口从 3000 变为 8080，链接结果为：`http://localhost:8080`。

**示例 Docker 命令**：

```bash
docker run -d --network=host -v open-webui:/app/backend/data -e OLLAMA_BASE_URL=http://127.0.0.1:11434 --name open-webui --restart always ghcr.io/open-webui/open-webui:main
```

### 保持您的 Docker 安装为最新

查看我们的 [Open WebUI 文档](https://docs.openwebui.com/getting-started/updating) 中的更新指南。

### 使用 Dev 分支 🌙

> [!WARNING]
> `:dev` 分支包含最新不稳定的功能和更改。使用它需要您自担风险，因为它可能有错误或不完整的功能。

如果您想尝试最新的前沿功能并且可以接受偶尔的不稳定，您可以像这样使用 `:dev` 标签：

```bash
docker run -d -p 3000:8080 -v open-webui:/app/backend/data --name open-webui --add-host=host.docker.internal:host-gateway --restart always ghcr.io/open-webui/open-webui:dev
```

### 离线模式

如果您在离线环境中运行 Open WebUI，可以将 `HF_HUB_OFFLINE` 环境变量设置为 `1`，以防止试图从互联网下载模型。

```bash
export HF_HUB_OFFLINE=1
```

## 下一步是什么？ 🌟

在 [Open WebUI 文档](https://docs.openwebui.com/roadmap/) 中的路线图上发现即将推出的功能。

## 许可证 📜

本项目包含受多重许可证约束的代码。当前代码库包含基于 Open WebUI 许可证的组件，附加了保留 "Open WebUI" 品牌的要求，以及之前基于其原始许可证的贡献。有关许可证更改的详细记录以及代码每一部分的适用条款，请参考 [LICENSE_HISTORY](./LICENSE_HISTORY)。有关完整和最新的许可细节，请参阅 [LICENSE](./LICENSE) 和 [LICENSE_HISTORY](./LICENSE_HISTORY) 文件。

## 支持 💬

如果您有任何问题、建议或需要帮助，请开启一个 issue 或加入我们的
[Open WebUI Discord 社区](https://discord.gg/5rJgQTnV4s)与我们联系！ 🤝

## Star 历史

<a href="https://star-history.com/#open-webui/open-webui&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
  </picture>
</a>

---

由 [Timothy Jaeryang Baek](https://github.com/tjbck) 创建 - 让我们一起让 Open WebUI 变得更加出色！ 💪