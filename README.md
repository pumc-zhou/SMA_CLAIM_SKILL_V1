# SMA_CLAIM_SKILL_V1
这是用于存放比赛所需的各项材料的repo，项目的来源是上海临床创新转化研究院主办的"算丰杯"医疗AI Skill开发大赛，在平台所给的案例基础上，制作了第一代SMA（脊髓性肌萎缩症）的核保skill。

仓库结构为：

```bash
.
├── 基于 skill 的多模型验证测试结果.pdf
├── cases
│   ├── case-1.txt
│   ├── case-2.txt
│   ├── case-3.txt
│   ├── case-4.txt
│   └── case-5.txt
├── CodexProjects
│   └── skill-test
│       ├── cases
│       │   ├── case-1.txt
│       │   ├── case-2.txt
│       │   ├── case-3.txt
│       │   ├── case-4.txt
│       │   └── case-5.txt
│       ├── output
│       │   ├── case-1_analysis_codex.md
│       │   ├── case-2_analysis_codex.md
│       │   ├── case-3_analysis_codex.md
│       │   ├── case-4_analysis_codex.md
│       │   └── case-5_analysis_codex.md
│       ├── README.md
│       └── SKILL.md
├── GeminiProjects
│   └── skill-test
│       ├── cases
│       │   ├── case-1.txt
│       │   ├── case-2.txt
│       │   ├── case-3.txt
│       │   ├── case-4.txt
│       │   └── case-5.txt
│       ├── output
│       │   ├── case_analysis_gemini.md
│       │   ├── case-1_analysis_gemini.md
│       │   ├── case-2_analysis_gemini.md
│       │   ├── case-3_analysis_gemini.md
│       │   ├── case-4_analysis_gemini.md
│       │   ├── case-5_analysis_gemini.md
│       │   └── case-record.md
│       └── SKILL.md
├── LICENSE
├── README.md
├── skill-beamer
│   ├── cross_model_validation.tex
│   ├── images
│   │   ├── checklist-2.png
│   │   ├── checklist.png
│   │   ├── codex-test-1.png
│   │   ├── conclusion-1.png
│   │   ├── conclusion-2.png
│   │   ├── full-1.png
│   │   ├── full-2.png
│   │   ├── Gemini-test-1.png
│   │   ├── initiate.png
│   │   ├── match-1.png
│   │   ├── match-2.png
│   │   ├── select-1.png
│   │   ├── select-2.png
│   │   ├── supplement-1.png
│   │   ├── supplement-2.png
│   │   ├── term-1.png
│   │   └── term-2.png
│   ├── pic
│   │   ├── background.pdf
│   │   ├── dtmf.pdf
│   │   ├── pumc-logo.png
│   │   ├── pumc.svg
│   │   └── Renmin_Univ_Logo.eps
│   ├── ref.bib
│   ├── RenminUniv.sty
│   └── slide.tex
├── SKILL.md
└── SMA 高值特药理赔合规审核 Skill.pdf
```

展示文稿为：SMA 高值特药理赔合规审核 Skill.pdf，有beamer编译而成，项目在 `skill-beamer` 中。

记录文稿为：基于 skill 的多模型验证测试结果.pdf，所有的输入与输出信息都记录在此文档中。

