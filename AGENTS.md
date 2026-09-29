# 本工作区的语音清扫

当用户粘贴语音识别文本并要求清扫口癖、修正识别错误，或明确调用 `$voice-transcript-cleanup` 时，读取 `.agents/skills/voice-transcript-cleanup/SKILL.md` 并按其执行。每次执行时重新读取 `data/术语对照表.md`；不要依赖其他对话的记忆。

本工作区的术语对照表只在用户明确要求新增、修改或删除条目时更改。处理文本本身不授权修改术语库。不要读取或修改 Obsidian。
