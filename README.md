# LY AI HUB

**LY AI HUB** 官网 — 巨天agent 背后的研究与工程实验室。

纯静态站点,零构建、零运行时依赖:一套手写设计系统(暗色、编辑排版、苹果节奏)+ 内联 SVG 图表。站上展示的每一个数字均可溯源至 [jutian-agent](https://github.com/deepseekv5/jutian-agent) 仓库的实测记录、构建日志与 CI 运行输出,各论文页脚附「数据来源」小节。

## 结构

```
├── index.html            首页:定位 · 指标带 · 精选项目与研究
├── projects.html         项目:巨天agent / 影片引擎 / jtcode / 安全网关 / 文档体系
├── research.html         研究索引(5 篇)
├── research/
│   ├── p1-zero-trust-gateway.html      同宿主零信任网关(6/6 攻击实测拦截)
│   ├── p2-escape-first-rendering.html  转义优先渲染管道(3 渲染面审计)
│   ├── p3-subagent-pool.html           取消安全的并行子代理调度池
│   ├── p4-single-dir-data.html         单目录数据架构与无损迁移(33 项实测)
│   └── p5-bpm-film-engine.html         128 BPM 程序化品牌影片(23.03s / 544KB)
└── assets/style.css      设计系统
```

## 本地预览

```bash
npx serve .        # 或任何静态服务器
```

## 数据原则

不发布无法复现的数字。图表分两类:**实测数据**(标注「实测」徽章,页脚给出来源命令)与**机制图**(架构 / 流程示意,不冒充实测曲线);依赖外部服务因而无法基准化的指标,在论文「局限」中明确说明。

## 许可

站点内容与设计:MIT。所展示项目:[巨天agent](https://github.com/deepseekv5/jutian-agent)(MIT)。
