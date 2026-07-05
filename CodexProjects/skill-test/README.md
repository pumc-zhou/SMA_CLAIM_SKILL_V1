# Gemini Skill Test

本目录用于验证同一个 skill.md 在不同 AI CLI 工具中的跨模型分析能力。

## Files

- skill.md: 原始 skill 文件
- GEMINI.md: Gemini CLI 项目上下文文件，由 skill.md 复制生成
- case.txt: 测试分析材料
- input/: 后续补充输入材料
- output/: 分析结果输出
- logs/: 测试记录

## Basic Workflow

1. 将 skill.md 和 case.txt 放入本目录
2. 执行 cp skill.md GEMINI.md
3. 在本目录启动 gemini
4. 要求 Gemini 读取 GEMINI.md 并分析 case.txt
