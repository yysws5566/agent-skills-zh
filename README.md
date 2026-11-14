# agent-skills-zh

14 个中文 Agent Skills——给 Claude Code / OpenClaw / 任何支持 SKILL.md 标准的客户端用。全部来自真实日常工作流（信息流投放、内容创作、开发流程），纯文本+脚本、零第三方捆绑。

## 一键安装

```bash
npx skills add yysws5566/agent-skills-zh
```

或按目录单装某一个：`npx skills add yysws5566/agent-skills-zh/<技能目录名>`

## 技能清单

| 技能 | 干什么 |
|---|---|
| `adflow-infoflow-video` | 信息流/短视频广告混剪出片：AI 选镜头、写钩子、TTS 配音渲染 MP4（内置完整本地引擎） |
| `beat-cut-video` | 丢一首歌自动剪卡点/快闪视频（运动打分选镜头、30fps 帧网格锁切点） |
| `browser-farm` | 多账号常驻浏览器舰队：一号一档一端口，真人登录一次 agent 永久免登（快照回滚/盯表触发/抓包重放） |
| `change-guard` | 改代码/修 bug 的验收流程门禁：定清单→拷问风险→小步改→按清单验完才算完 |
| `code-review` | 七维代码审查清单（只出清单不动手修），带 AI 幻觉静默降级维度 |
| `design-taste` | 设计品味评审：UI/图片/游戏美术的批评+具体重做方向 |
| `expert-team` | 专家团编排：先算 ROI 再动手，并行盲写、保留分歧、出条件式结论 |
| `kb-bot` | 知识库问答 bot：懒吸收+防腐 verified 标记，零库出厂自己长 |
| `prompt-forge` | 把模糊想法追问成能直接交给 agent 的完整提示词 |
| `retail-master-dashboard` | 行情反人性复盘看板（公开行情接口、数据质量分级、四级风控；不构成投资建议） |
| `short-drama-forge` | 单片 AI 短剧编剧：钩子/分镜表/资产图全出 |
| `skill-forge` | 网页重复操作录一遍变技能：录制→探接口→API/UI 双形态子包 |
| `skill-smith` | 技能工程台：生成/安检/升级技能包 |
| `wanwu-distill` | 万物蒸馏：把书、大佬方法、复盘蒸成技能/手册 |

## 说明

- **语言**：正文中文；每个 SKILL.md 的 frontmatter 带 `description_en` 一句话英文定位。
- **许可**：MIT（见 [LICENSE](LICENSE)）。每个 SKILL.md 内含免责声明：按现状提供、不担担保、使用者自负合规责任（遵守目标平台服务条款与当地法规）。
- **安全**：browser-farm / skill-forge 等自动化技能写明硬红线——仅限自有账号的合法自动化，不绕验证码/风控，不抓非公开数据。
- 本批技能已向 [anthropics/skills](https://github.com/anthropics/skills/pull/2213) 提交 PR。
