> 🌐 本文档由 [nilbuild/developer-roadmap](https://github.com/nilbuild/developer-roadmap) 翻译,英文原版见原项目。

# 智能体循环(Agent Loop)

智能体循环(agent loop)是让 AI 智能体能够持续朝目标推进的工作循环。首先,智能体从它的工具、传感器或记忆中收集最新数据;接着,它更新自己的内部状态并决定下一步做什么,这一步通常会运行规划或推理;然后,它执行选定的动作,例如调用 API、写入文件或发送消息;动作完成后,它会检查结果并保存新的信息。循环随即基于最新数据重新开始,因此智能体能够适应变化并不断改进。这种"观察—决策—行动"的快速重复,正是智能体能力强大的来源。

访问以下资源了解更多:

- [@article@什么是智能体循环?](https://huggingface.co/learn/agents-course/en/unit1/agent-steps-and-structure)
- [@article@动手构建你自己的智能体循环](https://www.reddit.com/r/AI_Agents/comments/1js1xjz/lets_build_our_own_agentic_loop_running_in_our/)
