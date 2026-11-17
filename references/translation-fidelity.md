# Translation Fidelity and Context

The English report and Chinese version share one factual baseline. Adapt the structure to natural Chinese while preserving each information item.

## Minimal working notes

Compare short reports directly. For complex material, use a small glossary and fact table.

### Glossary

| English | Chinese | Meaning or identifier |
|---|---|---|
| worker | 工作进程 | The process that executes a job |
| job | 任务 | The execution unit identified by `job_id` |
| artifact | 产物 | A file produced by the execution |

Names refer to actual objects. Keep object properties and database records at their respective levels.

### Fact table

| Item | English baseline | Chinese equivalent |
|---|---|---|
| Result | 18 of 20 records were imported. | 20 条记录中已导入 18 条。 |
| Scope | The import ran on Linux. | 导入运行环境为 Linux。 |
| Uncertainty | The cause may be a timeout. | 原因可能是超时。 |
| Remaining work | Windows validation is pending. | Windows 尚待验证。 |

## Comparison dimensions

1. **Numbers and units**: values, signs, decimals, ranges, percentages, denominators, units, and the basis for conversions.
2. **Comparisons and performance**: baseline version, sample, statistic, environment, and stage-level or end-to-end scope.
3. **Time**: dates, time zones, reporting periods, completed or planned states, and the evidence date.
4. **Objects and references**: identity, actors, recipients, and clear pronouns.
5. **Logic**: negation, quantities, conditions, exceptions, order, branches, and failure paths.
6. **Causality and certainty**: observations, correlations, hypotheses, and confirmed causes.
7. **Requirement strength**: possibility, ability, permission, recommendations, and obligations.
8. **Identifiers**: code, commands, paths, models, error codes, versions, URLs, and citation targets.
9. **Evidence and coverage**: supported results, review scope, and remaining work.

## Contextual modality

| English | Chinese wording | Preserve |
|---|---|---|
| may / might / could: possibility | 可能／也许／可能由……引起 | Degree of uncertainty |
| may: permission | 可以／获准 | Permission and its conditions |
| could: ability or polite request | 能够／可否 | Tense and sentence function |
| can | 能够／可以／可能 | Ability, permission, or possibility as used |
| should | 建议／应当 | The document's intended normative strength |
| must | 必须 | Obligation |
| must not | 禁止／必须避免 | Prohibition |
| planned / expected | 计划／预计 | Future status |
| observed / confirmed | 观察到／已确认 | Evidence level |
| only / unless / at least | 仅／除非／至少 | Scope, exceptions, and lower bounds |

Preserve necessary negation and failure conditions. For example, “校验失败时，禁止加载产物” determines which action is permitted.

## Natural Chinese structure

- Split long modifiers into clear clauses. State the subject and result, then add scope where appropriate.
- Use established domain terms while keeping exact identifiers unchanged.
- Omit repeated subjects when Chinese permits it and the referent remains clear.
- Keep each condition attached to the action it limits when moving information between sentences.
- If context adds a fact, update the English report and fact table before updating the Chinese version.
- Label added recommendations as “建议” so readers can distinguish them from facts and existing requirements.

## Final comparison

Compare facts first, then read the Chinese for fluency. Bilingual output covers the same information in both versions. For Chinese-only requests, deliver the Chinese report directly. Include the comparison table when the user requests a translation review.
