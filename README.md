# asd-ste100-zh

先完成清楚的英文报告，再输出语境准确的中文。

用于进展说明、交付报告、排障结论、调研结论和决策摘要的 Agent Skill。保留结论、证据、条件及确定性，默认交付中文，支持英文和双语对照。

## 安装

```bash
npx skills add Kuro96/asd-ste100-zh --skill asd-ste100-zh
```

也可将仓库克隆到宿主的 skill 目录：

```bash
git clone https://github.com/Kuro96/asd-ste100-zh.git ~/.claude/skills/asd-ste100-zh
```

其他兼容宿主采用相应的 skills 目录，保持完整目录结构，并使其读取根目录的 [SKILL.md](<SKILL.md>)。[Releases](https://github.com/Kuro96/asd-ste100-zh/releases) 提供 zip 安装包。

## 使用

```text
把这些排障记录整理成结论、证据和剩余事项，输出中文。
先形成清楚的英文报告，再结合项目术语翻译成中文，保留条件和确定性。
核对这两版报告的数字、单位、范围和建议强度。
```

工作流：**事实与术语 → 英文成稿 → 英文整理 → 语境化中文 → 双语核对 → 交付**。

- **报告模式**：使用 STE 的结构原则和领域术语，适用于日常报告。
- **受控核查模式**：使用指定版本的正式标准和词典，记录具体核查范围。

## 示例

**材料**：日志包含错误码 `E01`；错误仅在重试期间被观察到；超时是可能原因，尚待确认。

**English**

> The log contains `E01`. The error was observed only during retries. The cause may be a timeout. The cause is unconfirmed.

**中文**

> 日志中出现 `E01`。目前仅在重试期间观察到该错误，原因可能是超时，尚待确认。

## 内容

- [SKILL.md](<SKILL.md>)：报告与翻译工作流。
- [英文规则](<references/english-rules.md>)：句式、术语、语气与正式核查。
- [双语保真](<references/translation-fidelity.md>)：数字、条件、标识符及要求强度的核对。
- [双语示例](<examples/bilingual-reports.md>)：排障、测量与条件表达。
- [参考来源](<references/sources.md>)、[第三方归属](<THIRD_PARTY_NOTICES.md>)和 [MIT 许可](<LICENSE>)。

## 标准依据

英文写作借鉴 ASD-STE100 Issue 9 的相关原则，结合 [danyuchn/asd-ste100-skill](https://github.com/danyuchn/asd-ste100-skill) 的清晰写作机制。中文翻译采用自然中文结构。正式 STE 核查需使用指定版本的标准与词典，获取和使用方式见 [ASD 当前指引](https://asd-ste100.org/STE_downloads.html)。

ASD-STE100 为 ASD 的注册商标；本项目是独立的社区技能。
