# Hi, I’m Zhichao Li `{b1tank}`

I live in Seattle, WA, and work on AI agents in [Visual Studio Code](https://code.visualstudio.com/) and [GitHub Copilot](https://github.com/features/copilot) at Microsoft. My work spans agent products, evaluation, and agent observability. You can find it at [@zhichli](https://github.com/zhichli), primarily across VS Code and the [GitHub Copilot SDK](https://github.com/github/copilot-sdk), and my personal work at [@b1tank](https://github.com/b1tank).

[Website](https://b1tank.github.io/) · [Writing](https://b1tank.github.io/writing/) · [LinkedIn](https://www.linkedin.com/in/zhichao-li-engineer) · [X](https://x.com/w5hirt)

I led the VS Code evaluation engineering workstream and created the [evaluation harness](https://code.visualstudio.com/blogs/2026/05/15/agent-harnesses-github-copilot-vscode) and associated agentic analysis and reporting framework (public showcase: [What 50,000 agent runs taught us](https://code.visualstudio.com/blogs/2026/06/19/what-50000-runs-taught-us)), as well as [VSC-Bench](https://code.visualstudio.com/blogs/2026/05/15/agent-harnesses-github-copilot-vscode#_building-vsc-bench), a benchmarking suite for VS Code and its extensions. I worked closely with model providers, including [Microsoft AI](https://microsoft.ai/), [OpenAI](https://openai.com/), and [Anthropic](https://www.anthropic.com/), to produce accurate, meaningful evaluations, and with the community to advance [observability in VS Code](https://code.visualstudio.com/docs/agents/guides/monitoring-agents).

Before joining the VS Code core team, I worked on the [GitHub Copilot Applied Science team](https://www.microsoft.com/en-us/research/people/zhichli/), focusing on coding data synthesis, model training pipelines, and recommendation systems ([public display](https://www.youtube.com/watch?v=WiYinkO15Yg)). Earlier, I helped build cloud services including [Azure Datadog](https://learn.microsoft.com/en-us/azure/partner-solutions/datadog/) and [Azure Managed Grafana](https://learn.microsoft.com/en-us/azure/managed-grafana/), where I was a founding engineer. Across these roles, I developed broad experience in full-stack application development, cloud infrastructure, operations, and observability.

My path into software began in scientific computing during [my PhD in chemical engineering](https://doi.org/10.7936/7z9a-5j48), where I built machine learning models in MATLAB and aerosol models in Fortran and C++. Those experiences shaped my appreciation for performance, correctness, and clarity.

Having worked in both academia and the AI and software industries, I believe:

> “AI can save us work, but it can also distance us from the learning that work provides. Curiosity is fundamental to human nature. We want to learn more, not less - and AI should be wielded to advance education, not deprive us of opportunities to learn.”
>
> — *My bet in the AI era*

That is why I began building an educational site for my dad, a longtime mathematics teacher, and learning projects for myself to catch up on foundational technologies that still matter.

I also enjoy basketball 🏀 and billiards 🎱. I’m a Stephen Curry and Golden State Warriors fan, and I admire Curry’s humility, work ethic, and competitive drive.

My public collection of reusable agent skills is available at [b1tank/skills](https://github.com/b1tank/skills). Other tools I have built are shown below.

## Public work

- [**Agent monitoring in VS Code**](https://code.visualstudio.com/docs/agents/guides/monitoring-agents) — The public guide to collecting and inspecting traces, logs, and metrics from agent sessions.
- [**What 50,000 agent runs taught us**](https://code.visualstudio.com/blogs/2026/06/19/what-50000-runs-taught-us) — A co-authored analysis of repeated evaluation runs across models, prompts, and agent behavior.
- [**Enterprise OpenTelemetry controls for VS Code agents**](https://code.visualstudio.com/docs/enterprise/ai-settings#_configure-telemetry-export-with-opentelemetry) — Policy-backed telemetry export controls for VS Code agent sessions in enterprise-managed environments.
- [**VS Code agent OpenTelemetry walkthrough**](https://opentelemetry.io/blog/2026/genai-observability/) — The official GenAI observability walkthrough uses VS Code agent instrumentation I worked on, visualized in the Aspire Dashboard.

### Open source contributions

- [**VS Code**](https://github.com/microsoft/vscode/pulls?q=is%3Apr+is%3Amerged+author%3Azhichli) — Agent Host OpenTelemetry, trace context, content controls, and model telemetry.
- [**VS Code Copilot Chat**](https://github.com/microsoft/vscode-copilot-chat/pulls?q=is%3Apr+is%3Amerged+author%3Azhichli) — GenAI instrumentation, local SQLite trace storage, OTLP export, and agent activity signals.
- [**Grafana**](https://github.com/grafana/grafana/pulls?q=is%3Apr+is%3Amerged+author%3Azhichli) — Fixed OpenTelemetry Jaeger context propagation and added configurable outbound user-agent headers.
- [**Dagger container-use**](https://github.com/dagger/container-use/pulls?q=is%3Apr+is%3Amerged+author%3Azhichli) — Native Windows support, a Git-notes hang fix, and command documentation.
- [**Pi coding agent**](https://github.com/earendil-works/pi/pulls?q=is%3Apr+is%3Amerged+author%3Azhichli) — Clarified and reconciled coding-agent keybinding behavior in the public documentation.

## Projects

### Agent and Observability

| Project | Description | Links |
| --- | --- | --- |
| **OTelux** | A cross-platform, local-first OpenTelemetry desktop app for exploring traces, logs, and metrics, designed for use by both people and agents. | [GitHub](https://github.com/b1tank/otelux) |
| **Agent Insights** *(Built by Michelle Ma, an intern I mentored)* | A VS Code extension built by [Michelle Ma (@michiisai)](https://github.com/michiisai), an intern I mentored, for exploring agent behavior in depth through OpenTelemetry, designed for use by both people and agents. | [GitHub](https://github.com/michiisai/agent-insights) |
| **pi-otel** | Vendor-neutral OpenTelemetry instrumentation for the Pi coding agent, exporting traces, metrics, and logs with GenAI semantic conventions, privacy-first content controls, and bounded shutdown behavior. | [GitHub](https://github.com/b1tank/pi-otel) |
| **Deskpal** *(Experimental)* | A Linux desktop-control MCP server for X11/Xwayland, AT-SPI, OCR, and isolated Xvfb verification. | [GitHub](https://github.com/b1tank/deskpal) |

### Education

| Project | Description | Links |
| --- | --- | --- |
| **乐之翁** | A production learning platform that turns my dad’s original classroom material into structured, interactive high-school mathematics method courses with polished formulas, diagrams, and multiple learning paths. | [lezhiweng.com](https://lezhiweng.com) |
| **OpenMathBoard** | A freehand-first mathematics whiteboard optimized for iPad and Apple Pencil. It converts drawn intent into editable parametric geometry and supports images, durable local boards, and browser-local course recording. | [GitHub](https://github.com/b1tank/openmathboard) · [Website](https://lezhi.school) |
| **Learn C** *(Experimental)* | Runnable browser lessons for K&R and Salvatore Sanfilippo’s 37-part Let’s Learn C series, with modern-C notes and source-linked examples. | [GitHub](https://github.com/b1tank/learnc) · [Website](https://b1tank.github.io/learnc/) |
| **Learn Ghostty** *(Experimental)* | A source-backed workshop that teaches terminal architecture by reconstructing Ghostty one observable subsystem at a time, from process ownership and PTYs to a native GTK window and OpenGL rendering. | [GitHub](https://github.com/b1tank/learn-ghostty) · [Website](https://b1tank.github.io/learn-ghostty/) |
| **ABC Balloon** | A balloon-popping learning game I built for my kids, combining alphabet free play with emoji-guided spelling and visual addition and subtraction challenges. | [GitHub](https://github.com/b1tank/abc) · [Website](https://b1tank.github.io/projects/abc/demo/) |

### Tools

| Project | Description | Links |
| --- | --- | --- |
| **OpenSnipping** | A browser-based screenshot and annotation tool with local editing, export, and no required backend. | [GitHub](https://github.com/b1tank/opensnipping-web) · [Website](https://yummyjars.com/opensnipping/) |
| **WireGuard Manager for GNOME** | A GNOME Shell extension for discovering, controlling, and inspecting WireGuard tunnels from the desktop panel. | [GitHub](https://github.com/b1tank/wg-gnome-ext) |

### Scientific

| Project | Description | Links |
| --- | --- | --- |
| **Coag** | A C++ aerosol coagulation model from my scientific-computing work that ran about 90% faster than the legacy Fortran implementation. | [GitHub](https://github.com/b1tank/coag) |
| **Direct Simulation Monte Carlo** | A Fortran implementation of aerosol coagulation using the Direct Simulation Monte Carlo method. | [GitHub](https://github.com/b1tank/DSM-f90) |
| **Computational Fluid Dynamics Basics** | Small implementations of foundational computational-fluid-dynamics methods. | [GitHub](https://github.com/b1tank/computational-fluid-dynamics-basics) |
| **Geospatial Clustering with PySpark** | An early distributed-computing project applying k-means clustering to geospatial data with PySpark. | [GitHub](https://github.com/b1tank/kmeans-clustering-pyspark) |
