# cooleryu

[English](README.md)

我目前是一名就职于头部互联网公司的后端工程师，也是一名 AI 的长期实践者和热情学习者，正在系统性地转向 AI Agent 全栈工程方向。

我当前关注 AI Agent 基础设施：MCP、工具调用、LLM harness engineering、多智能体系统、可观测性、评测，以及可靠的长任务 Agent workflow。

我更关心如何把模型能力落到可复现、可观测、可测试、可维护的工程系统里。

## 近期 Open Source 工作

| 项目 | 方向 | 工作内容 |
| --- | --- | --- |
| [OpenLIT](https://github.com/openlit/openlit/pull/1139) | LLM 可观测性 / OpenTelemetry | 保留 OpenAI chat 失败 span 中的 endpoint 元数据。 |
| [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/1960) | 浏览器 Agent / computer-use 工具 | 改进原生 select option 在 Agent 浏览器操作中的处理。 |
| [IBM MCP Context Forge](https://github.com/IBM/mcp-context-forge/pull/4446) | MCP Gateway / Agent 工具调用 | 改进 Streamable HTTP `/mcp` 探测路径在重定向场景下的行为。 |

## 工程兴趣

- AI Agent runtime、编排、workflow engine 和工具调用
- MCP server、gateway，以及面向 Agent 的集成层
- LLM harness engineering、可观测性、tracing、eval 和失败分析
- RAG、memory system、长任务 Agent 和上下文管理
- 后端可靠性、分布式系统和高并发服务设计

## 技术栈

Java、Python、TypeScript、Spring Boot、LangChain、LangGraph、OpenTelemetry、MCP、Redis、MySQL、消息队列、Docker、Kubernetes。

## 工作方式

- 先复现，再提出修复。
- 保持 PR 足够小，让维护者容易 review。
- 为真实失败场景补回归测试。
- 相比炫技 demo，更重视可靠系统。
- 优先讲清楚 root cause、风险边界和维护者价值。

## 当前关注

构建一套严谨的 AI Agent 开源贡献流程：寻找真实维护者痛点，本地验证 issue，编写聚焦测试，提交范围小、容易 review、能解释清楚价值的 PR。
