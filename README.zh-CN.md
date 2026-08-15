# Reactive Resume

<div align="center">
  <a href="https://rxresu.me">
    <img src="apps/web/public/opengraph/banner.jpg" alt="Reactive Resume" />
  </a>

  <p>
    <a href="./README.md"><strong>English README</strong></a>
  </p>
</div>

---

Reactive Resume 是一款免费、开源的简历制作工具，可帮助你更轻松地创建、更新和分享简历。

适合想快速上手的人：挑选模板、填写内容、导出 PDF 即可，基础使用无需账号。若你需要更多控制，也可以将整套应用自托管到自己的基础设施上。

Reactive Resume 以隐私为核心原则，确保你完全拥有自己的数据。整个代码库基于 MIT 许可证开源，没有跟踪、没有广告，也没有隐藏费用。

## 赞助商

Reactive Resume 之所以能保持免费、开源且独立，是因为有公司持续支持项目。感谢所有赞助者为托管、维护和社区持续开发提供帮助。

<p>
  <a href="https://www.atlascloud.ai/?utm_source=github&utm_medium=link&utm_campaign=reactive-resume">
    <img src="apps/web/public/sponsors/atlas-cloud-logo-white.svg" alt="Atlas Cloud" width="320" />
  </a>
</p>

[Atlas Cloud](https://www.atlascloud.ai/?utm_source=github&utm_medium=link&utm_campaign=reactive-resume) 是 Reactive Resume 的项目赞助商。Atlas Cloud 为开发者提供统一的 AI 平台，可通过一个 API Key、一个端点和一份账单访问数百种模型，覆盖聊天、图像生成、视频生成、媒体处理和 GPU 云工作负载。

如果你的公司也想赞助 Reactive Resume，请发送邮件至 [hello@amruthpillai.com](mailto:hello@amruthpillai.com)。

## 功能

**简历制作**

- 实时预览，边写边看
- 多种导出格式（PDF、JSON、DOCX）
- 拖拽调整模块顺序
- 支持自定义任意内容区块
- 支持格式化的富文本编辑器

**模板**

- 专业设计的模板
- 支持 A4 和 Letter 尺寸
- 可自定义颜色、字体和间距
- 结构化样式规则，用于区块和文本样式控制

**隐私与控制**

- 可在自己的基础设施上自托管
- 默认不跟踪，不收集分析数据
- 随时完整导出数据
- 一键永久删除你的数据

**附加能力**

- AI 集成（OpenAI、Google Gemini、Anthropic Claude）
- 多语言支持
- 通过唯一链接分享简历
- 支持从 JSON Resume 格式导入
- 深色模式支持
- 通行密钥和双重认证

## 模板

<table>
  <tr>
    <td align="center">
      <img src="apps/web/public/templates/jpg/azurill.jpg" alt="Azurill" width="150" />
      <br /><sub><b>Azurill</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/bronzor.jpg" alt="Bronzor" width="150" />
      <br /><sub><b>Bronzor</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/chikorita.jpg" alt="Chikorita" width="150" />
      <br /><sub><b>Chikorita</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/ditto.jpg" alt="Ditto" width="150" />
      <br /><sub><b>Ditto</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="apps/web/public/templates/jpg/gengar.jpg" alt="Gengar" width="150" />
      <br /><sub><b>Gengar</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/glalie.jpg" alt="Glalie" width="150" />
      <br /><sub><b>Glalie</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/kakuna.jpg" alt="Kakuna" width="150" />
      <br /><sub><b>Kakuna</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/lapras.jpg" alt="Lapras" width="150" />
      <br /><sub><b>Lapras</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="apps/web/public/templates/jpg/leafish.jpg" alt="Leafish" width="150" />
      <br /><sub><b>Leafish</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/onyx.jpg" alt="Onyx" width="150" />
      <br /><sub><b>Onyx</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/pikachu.jpg" alt="Pikachu" width="150" />
      <br /><sub><b>Pikachu</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/rhyhorn.jpg" alt="Rhyhorn" width="150" />
      <br /><sub><b>Rhyhorn</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="apps/web/public/templates/jpg/ditgar.jpg" alt="Ditgar" width="150" />
      <br /><sub><b>Ditgar</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/meowth.jpg" alt="Meowth" width="150" />
      <br /><sub><b>Meowth</b></sub>
    </td>
    <td align="center">
      <img src="apps/web/public/templates/jpg/scizor.jpg" alt="Scizor" width="150" />
      <br /><sub><b>Scizor</b></sub>
    </td>
  </tr>
</table>

## 快速开始

在本地运行 Reactive Resume 的最快方式：

```bash
# 克隆仓库
git clone --depth=1  https://github.com/amruthpillai/reactive-resume.git
cd reactive-resume

# 启动所有服务
docker compose up -d

# 访问应用
open http://localhost:3000
```

[![Build with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/amruthpillai/reactive-resume)

如果你需要更详细的安装说明、环境配置和自托管指南，请查看[官方文档](https://docs.rxresu.me)。

## 技术栈

| 类别           | 技术                           |
| -------------- | ------------------------------ |
| 框架           | TanStack Start（React 19、Vite） |
| 运行时         | Node.js                        |
| 语言           | TypeScript                     |
| 数据库         | PostgreSQL + Drizzle ORM       |
| API            | ORPC（类型安全 RPC）           |
| 认证           | Better Auth                    |
| 样式           | Tailwind CSS                   |
| UI 组件        | Base UI + shadcn 风格组件包    |
| 状态管理       | Zustand + TanStack Query       |

## 文档

完整指南可在 [docs.rxresu.me](https://docs.rxresu.me) 查看：

| 指南                                                                         | 说明                     |
| ---------------------------------------------------------------------------- | ------------------------ |
| [Getting Started](https://docs.rxresu.me/getting-started)                   | 首次安装与基础使用       |
| [Self-Hosting](https://docs.rxresu.me/self-hosting/docker)                  | 部署到你自己的服务器     |
| [Development Setup](https://docs.rxresu.me/contributing/development)        | 本地开发环境             |
| [Project Architecture](https://docs.rxresu.me/contributing/architecture)    | 代码结构与设计模式       |
| [Exporting Your Resume](https://docs.rxresu.me/guides/exporting-your-resume) | PDF 与 JSON 导出选项     |

## 自托管

Reactive Resume 可通过 Docker 自托管。技术栈包括：

- **PostgreSQL** —— 用于存储用户数据和简历
- **SeaweedFS**（可选）—— S3 兼容的文件上传存储

> **从 v5.1.0 起** —— PDF 生成已完全改为在客户端通过 `@react-pdf/renderer` 运行。新的部署不再需要 Browserless、Chromium 或任何外部打印服务作为依赖。`PRINTER_*` 和 `BROWSERLESS_*` 环境变量已不再读取，可以从 `.env` 中删除。

从 Docker Hub 或 GitHub Container Registry 拉取最新镜像：

```bash
# Docker Hub
docker pull amruthpillai/reactive-resume:latest

# GitHub Container Registry
docker pull ghcr.io/amruthpillai/reactive-resume:latest
```

完整说明请参阅 [自托管指南](https://docs.rxresu.me/self-hosting/docker)。

## 支持

Reactive Resume 永远是免费且开源的。如果它曾帮助你找到工作，或者为你节省了时间，欢迎支持后续开发：

<p>
  <a href="https://github.com/sponsors/AmruthPillai">
    <img src="https://img.shields.io/badge/GitHub%20Sponsors-Support-ea4aaa?style=flat-square&logo=github-sponsors" alt="GitHub Sponsors" />
  </a>
  <a href="https://opencollective.com/reactive-resume/donate">
    <img src="https://img.shields.io/badge/Open%20Collective-Contribute-7FADF2?style=flat-square&logo=open-collective" alt="Open Collective" />
  </a>
</p>

其他支持方式：

- 给这个仓库点 Star
- 报告 Bug、提出功能建议
- 改进文档
- 参与翻译

## Star 历史

<a href="https://www.star-history.com/?repos=amruthpillai%2Freactive-resume&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=amruthpillai/reactive-resume&type=date&theme=dark&legend=top-left&sealed_token=BF8sVMes0z5BhdkMhtFklhxeikeGUrSyW-CcY9E_RCQI5zqUHEbMRwcB075fUewbAtlNoCnDlWhDWjrDGhTcXMojsS2I0RCqcL-Y9p3Ez3H1A2QpRMthjFilP0YOCJEE9AZqRrqzlvj1uU2y5ixarXOuUXuuSw5DkLMViSMD8Ldl0H3BEgclnjWw4fI4" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=amruthpillai/reactive-resume&type=date&legend=top-left&sealed_token=BF8sVMes0z5BhdkMhtFklhxeikeGUrSyW-CcY9E_RCQI5zqUHEbMRwcB075fUewbAtlNoCnDlWhDWjrDGhTcXMojsS2I0RCqcL-Y9p3Ez3H1A2QpRMthjFilP0YOCJEE9AZqRrqzlvj1uU2y5ixarXOuUXuuSw5DkLMViSMD8Ldl0H3BEgclnjWw4fI4" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=amruthpillai/reactive-resume&type=date&legend=top-left&sealed_token=BF8sVMes0z5BhdkMhtFklhxeikeGUrSyW-CcY9E_RCQI5zqUHEbMRwcB075fUewbAtlNoCnDlWhDWjrDGhTcXMojsS2I0RCqcL-Y9p3Ez3H1A2QpRMthjFilP0YOCJEE9AZqRrqzlvj1uU2y5ixarXOuUXuuSw5DkLMViSMD8Ldl0H3BEgclnjWw4fI4" />
 </picture>
</a>

## 贡献

开源项目离不开贡献。无论是修正错别字，还是新增功能，都欢迎参与。

1. Fork 这个仓库
2. 创建功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交你的修改 (`git commit -m 'Add amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 发起 Pull Request

如果你想了解如何在本地搭建项目，请查看 [开发环境指南](https://docs.rxresu.me/contributing/development)。

## 许可证

[MIT](./LICENSE) —— 你可以随意使用。
