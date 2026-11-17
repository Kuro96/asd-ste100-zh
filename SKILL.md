---
name: asd-ste100-zh
description: >-
  Use when writing progress reports, delivery summaries, troubleshooting findings,
  research conclusions, or decision briefs in Chinese, English, or both. Draft a
  clear English report using ASD-STE100-inspired principles, then produce natural
  Chinese that preserves facts, terminology, conditions, and certainty. Triggers:
  汇报、进展说明、工作总结、交付报告、排障结论、调研结论、决策摘要、先英文后中文、双语报告。
license: MIT
metadata:
  version: 0.2.0
  tags: reporting, asd-ste100, english, chinese, translation
---

# English-First Reporting with Contextual Chinese Translation

Write a complete English report first. Apply ASD-STE100-inspired writing principles, then translate the report into natural Chinese. Both versions share the same facts, scope, and certainty.

## Scope and output

- Use this workflow for progress, delivery, troubleshooting, research, and decision reports, including rewrites and bilingual reviews.
- Domain skills supply facts, procedures, and evidence. This skill organizes the report and its translation.
- Use the task goal, audience, current requirements, corrections, source material, and tool results as inputs.
- Deliver Chinese by default. For bilingual output, present English first, then Chinese. For English-only requests, deliver the English report.
- Follow the requested language, format, and length. The English draft is a complete report that can be delivered on request.
- A short task may need one conclusion and a few bullets. Add headings when they help the reader.

## 1. Establish facts, scope, and terms

1. Identify the question, audience, subject, and reporting period. Use sufficient context already available.
2. Apply the latest requirements and corrections. Use current evidence for current-state claims and retain its time scope.
3. Distinguish observed results, work in progress, plans, recommendations, inferences, and unresolved items. Put material gaps beside the affected conclusion.
4. Collect the conclusion, evidence, scope, conditions, status, and remaining work. Take owners and deadlines from the source material.
5. Build a small glossary of English terms, Chinese terms, meanings, and exact identifiers. Use one name for each concept. Keep distinct objects, properties, and records distinct.

Ready when each key conclusion and remaining item has a source or a clear status.

## 2. Complete a standalone English report

Include the information the task needs. Combine related items and omit empty sections.

- **Result**: answer the main question directly.
- **Key facts**: give the changes, measurements, evidence, and scope that support the result.
- **Open items**: state remaining work, blockers, or risks that affect the result.
- **Next action / Decision needed**: give supported next steps or questions that require a decision.

When rewriting, preserve requirement strength, time relationships, and branch logic. Label added recommendations separately. Express completion and current availability as separate facts when both are relevant.

Ready when the English report alone explains the result, evidence, scope, and remaining work.

## 3. Apply clear English writing rules

Use **report mode** by default: apply STE structural principles with plain words and established domain terms.

For a requested **controlled review**, obtain the specified edition of the standard and dictionary. Record the rules and vocabulary reviewed, plus unresolved items.

| Area | Guidance |
|---|---|
| Descriptions | Limit each sentence to 25 words. Use one topic and at most six sentences per paragraph. |
| Procedures | Put conditions first. Use the imperative, normally one action per sentence, and a 20-word limit. |
| Actions and responsibility | Prefer active voice and concrete verbs. Descriptions may use passive voice when the actor is unknown. |
| Sentences and lists | Keep subjects, verbs, articles, and references clear. Separate complex conditions into lists. Split semicolon clauses into sentences. |
| Terms and noun clusters | Use consistent names. Limit noun clusters to three words. Keep necessary formal technical names intact and explain them. |
| Vocabulary | Review ordinary words for approved meaning and part of speech. Select technical terms from the domain glossary. |
| Tense and modality | Prefer simple tenses while preserving possibility, obligation, and time relationships. |
| Concision | Replace nominalized actions with concrete verbs. Replace evaluative modifiers with evidence or specific status. |

Apply English word limits to the English draft. Use natural Chinese structure for the translation. Formal word counting follows Part 1, Section 8.

Read [English rules](<references/english-rules.md>) for dictionary use, `-ing`, voice, and modality. For example, the official FAQ approves `check` as a noun. Word choice requires a part-of-speech review.

Ready when the English is clear and retains all information that affects judgment or action.

## 4. Translate into contextual Chinese

1. Use the completed English report as the factual baseline. Use task context and domain conventions to choose Chinese wording.
2. Reorder, split, or combine sentences for natural Chinese. Use object names where pronouns would be ambiguous.
3. Use established Chinese terminology. Preserve the distinctions between objects, properties, and internal records.
4. Preserve code, commands, paths, model names, status codes, and other exact identifiers.
5. Preserve numbers, units, denominators, comparison baselines, times, causes, conditions, exceptions, negation, scope, and evidence.
6. Preserve certainty and requirement strength. Translate `may` as possibility or permission according to context. Distinguish the senses of `can` and `could`.
7. Keep completed, verified, planned, recommended, expected, and unconfirmed states distinct. If context adds a fact, update the English report before the Chinese version.

Read [Translation fidelity](<references/translation-fidelity.md>) for the comparison checklist and contextual modality mappings.

Ready when both versions support the same understanding and decisions, and the Chinese reads naturally.

## 5. Condense, review, and deliver

- Lead with the conclusion. Give each item one main point and retain material conditions and limits.
- Review English sentence length, voice, word meaning, part of speech, conditions, and references. Then compare the two versions for meaning.
- Match every explicit request to a result or status. Check evidence, scope, and remaining work.
- Deliver the requested text directly. Add an original / rewrite / reason comparison when requested.
- When publishing through an external system, follow its task-specific procedure and read back the result.

Ready when the report answers the question at the requested length, with consistent information across languages.

## References

- [English rules](<references/english-rules.md>): controlled review, vocabulary, grammar, and modality.
- [Translation fidelity](<references/translation-fidelity.md>): facts, terminology, and branch logic.
- [Bilingual examples](<examples/bilingual-reports.md>): diagnosis, measurements, conditions, and identifiers.
- [Sources](<references/sources.md>): official guidance, upstream reference, and adaptation scope.

## Delivery checklist

- [ ] The English report is complete. Any Chinese version uses it as the factual baseline.
- [ ] The main question and each explicit request have an answer or status.
- [ ] Terms, references, sentence structure, and uncertain vocabulary have been reviewed.
- [ ] Numbers, units, times, identifiers, negation, conditions, and certainty match.
- [ ] Completion scope, review scope, and remaining work agree with the evidence.
- [ ] Language, format, and length match the request.
