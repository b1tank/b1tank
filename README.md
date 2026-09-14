# Hi, I'm Zhichao Li `{b1tank}`

I live in Seattle, WA, and work on AI agents in [Visual Studio Code](https://code.visualstudio.com/) and [GitHub Copilot](https://github.com/features/copilot) at Microsoft. My work spans agent products, evaluation, and [agent observability](https://code.visualstudio.com/docs/agents/guides/monitoring-agents).

[Website](https://b1tank.github.io) · [LinkedIn](https://www.linkedin.com/in/zhichao-li-engineer) · [X](https://x.com/w5hirt) · [Writing](https://b1tank.github.io/writing/)

## Work

My work GitHub identity is [@zhichli](https://github.com/zhichli), primarily across VS Code and the [GitHub Copilot SDK](https://github.com/github/copilot-sdk). My personal work is at [@b1tank](https://github.com/b1tank).

I led the VS Code evaluation engineering workstream and created the [evaluation harness](https://code.visualstudio.com/blogs/2026/05/15/agent-harnesses-github-copilot-vscode) and associated agentic analysis and reporting framework (public showcase: [What 50,000 agent runs taught us](https://code.visualstudio.com/blogs/2026/06/19/what-50000-runs-taught-us)), as well as [VSC-Bench](https://code.visualstudio.com/blogs/2026/05/15/agent-harnesses-github-copilot-vscode#_building-vsc-bench), a benchmarking suite for VS Code and its extensions. I worked closely with model providers including [Microsoft AI](https://microsoft.ai/), [OpenAI](https://openai.com/), and [Anthropic](https://www.anthropic.com/) to produce accurate evaluations, and with the community to advance [observability in VS Code](https://code.visualstudio.com/docs/agents/guides/monitoring-agents).

My public work includes:

- [Agent monitoring in VS Code](https://code.visualstudio.com/docs/agents/guides/monitoring-agents)
- [Enterprise telemetry export with OpenTelemetry](https://code.visualstudio.com/docs/enterprise/ai-settings#_configure-telemetry-export-with-opentelemetry)
- [What 50,000 repeated agent-evaluation runs taught us](https://code.visualstudio.com/blogs/2026/06/19/what-50000-runs-taught-us)
- VS Code instrumentation used in the official [OpenTelemetry GenAI observability walkthrough](https://opentelemetry.io/blog/2026/genai-observability/)

I'm currently building **OTelux**, a local-first telemetry workbench for developers and coding agents; **Deskpal**, verified computer use for Linux desktop applications; and **pi-otel**, vendor-neutral traces, metrics, and logs for the Pi coding agent.

Before developer tools, I worked on the [GitHub Copilot Applied Science team](https://www.microsoft.com/en-us/research/people/zhichli/), focusing on coding data synthesis, model training pipelines, and recommendation systems. Earlier, I helped build cloud services including [Azure Datadog](https://learn.microsoft.com/en-us/azure/partner-solutions/datadog/) and [Azure Managed Grafana](https://learn.microsoft.com/en-us/azure/managed-grafana/), where I was a founding engineer. My route into software began in [scientific computing](#scientific) during [my PhD in chemical engineering](https://doi.org/10.7936/7z9a-5j48), where I built machine learning models in MATLAB and aerosol models in Fortran and C++.

## Open source contributions

- [VS Code](https://github.com/microsoft/vscode/pulls?q=is%3Apr+is%3Amerged+author%3Azhichli) — Agent Host OpenTelemetry, trace context, content controls, and model telemetry
- [VS Code Copilot Chat](https://github.com/microsoft/vscode-copilot-chat/pulls?q=is%3Apr+is%3Amerged+author%3Azhichli) — GenAI instrumentation, local SQLite trace storage, OTLP export, and agent activity signals
- [Grafana](https://github.com/grafana/grafana/pulls?q=is%3Apr+is%3Amerged+author%3Azhichli) — Fixed OpenTelemetry Jaeger context propagation and added configurable outbound user-agent headers
- [Dagger container-use](https://github.com/dagger/container-use/pulls?q=is%3Apr+is%3Amerged+author%3Azhichli) — Native Windows support, a Git-notes hang fix, and command documentation
- [Pi coding agent](https://github.com/earendil-works/pi/pulls?q=is%3Apr+is%3Amerged+author%3Azhichli) — Clarified and reconciled coding-agent keybinding behavior in the public documentation

## Selected projects

| Project | What it is | Links |
| --- | --- | --- |
| **OTelux** | A cross-platform, local-first OpenTelemetry desktop app for exploring traces, logs, and metrics, designed for use by both people and agents. | [Repository](https://github.com/b1tank/otelux) |
| **Agent Insights** | A VS Code extension for exploring agent behavior in depth through OpenTelemetry. *(Mentored intern project)* | [Repository](https://github.com/michiisai/agent-insights) |
| **pi-otel** | Vendor-neutral OpenTelemetry instrumentation for the Pi coding agent, exporting traces, metrics, and logs with GenAI semantic conventions. | [Repository](https://github.com/b1tank/pi-otel) |
| **Deskpal** | A Linux desktop-control MCP server for X11/Xwayland, AT-SPI, OCR, and isolated Xvfb verification. | [Repository](https://github.com/b1tank/deskpal) |
| **OpenMathBoard** | A freehand-first mathematics whiteboard with intent-based parametric geometry, local boards, and browser-local course recording. Optimized for iPad and Apple Pencil. | [Repository](https://github.com/b1tank/openmathboard) · [Live](https://lezhi.school) |
| **乐之翁** | Interactive high-school mathematics method courses built from an experienced teacher's original classroom material. | [Live](https://lezhiweng.com) |
| **Learn Ghostty** | A source-backed workshop that reconstructs Ghostty from process ownership and PTYs through GTK and OpenGL. | [Repository](https://github.com/b1tank/learn-ghostty) · [Course](https://b1tank.github.io/learn-ghostty/) |
| **Learn C** | A hand-written, runnable browser companion to K&R and Let's Learn C. No signup, tracking, or generated course content. | [Repository](https://github.com/b1tank/learnc) · [Course](https://b1tank.github.io/learnc/) |
| **OpenSnipping** | A browser-based screenshot and annotation tool with local editing and export. | [Repository](https://github.com/b1tank/opensnipping-web) · [Demo](https://yummyjars.com/opensnipping/) |
| **ABC Balloon** | An alphabet-learning game I built with my family. | [Repository](https://github.com/b1tank/abc) · [Play](https://b1tank.github.io/projects/abc/demo/) |
| **WireGuard Manager for GNOME** | Discover, control, and inspect WireGuard tunnels from the GNOME desktop panel. | [Repository](https://github.com/b1tank/wg-gnome-ext) |

Earlier scientific projects include a [C++ aerosol coagulation model](https://github.com/b1tank/coag), a [Fortran Direct Simulation Monte Carlo model](https://github.com/b1tank/DSM-f90), [computational-fluid-dynamics fundamentals](https://github.com/b1tank/computational-fluid-dynamics-basics), and [geospatial clustering with PySpark](https://github.com/b1tank/kmeans-clustering-pyspark).

Outside work, I enjoy basketball 🏀 and billiards 🎱. I'm a Stephen Curry and Golden State Warriors fan, and I admire Curry's humility, work ethic, and competitive drive.

My public collection of reusable agent skills is available at [b1tank/skills](https://github.com/b1tank/skills).


