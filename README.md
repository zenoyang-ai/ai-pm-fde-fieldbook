# AI Product Fieldbook

杨圣旦的个人网站 Demo，目标方向是 AI 产品经理、AI 应用产品经理，以及产品型 FDE / AI 应用交付。

这是一个个人网站，不是只有项目截图的作品集。About、Experience、Working Method、Notes 和 Contact 组成个人层；Selected Work 是其中最大的内容模块。

## Run locally

```bash
python3 -m http.server 4173
```

然后打开 `http://127.0.0.1:4173/`。

## Evidence boundary

- AI PM Studio 的公开入口是 Replay-only；本地录屏不等于公网实时运行。
- 自动化质检项目展示演示看板与工作流结构，不外推为生产部署或 SLA。
- 倪海厦项目区分公开网页、多端形态与 v5.5.x 本地回归，不把本地结果写成线上准确率。
- 阿德勒项目的 55/55 是项目内单人离线、目标场景方向性验证，不是泛化准确率。

## Structure

The site is intentionally a single offline HTML file with local evidence assets. It includes keyboard-accessible case tabs, project and proof filters, a theme toggle, and an offline Sample Agent Trace.
