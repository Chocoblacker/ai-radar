# microVM（Agent 算力隔离）

**是什么：** 轻量级虚拟机，为每个 AI Agent 提供硬件级隔离的运行环境。Google 的 Agent Compute Engine 让每个 agent 跑在独立的 microVM 里（零凭证沙盒），agent 之间、agent 与宿主机之间完全隔离。

**为什么重要：** 2026 年 AWS、Docker、DigitalOcean、Google 四家一致选定 microVM 作为 agent 隔离原语，"容器不适合 agent"成为行业共识。Agent 有工具调用权限，一旦被攻破危害极大，隔离是安全底线。

**常见误区：** microVM 不是 Docker 容器；它比容器更重（有独立内核），但比传统虚拟机轻得多，启动只需毫秒级。

**相关故事线：** 🧵 agent-security

**英文表达：** microVM (micro virtual machine)
