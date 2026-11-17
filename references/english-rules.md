# English Rules and Review Modes

## Basis and priorities

This guide summarizes relevant ASD-STE100 Issue 9 principles for general reporting. Formal review uses the specified standard and dictionary. See [Sources](<sources.md>).

Preserve facts, conditions, scope, requirement strength, and certainty first. Then simplify sentence structure, align terms, and use lists. Retain precise wording when needed and record any rule that requires further review.

## Two modes

| Mode | Use | Method |
|---|---|---|
| Report | Progress, delivery, troubleshooting, research, and decision reports | Apply structural principles with plain words and domain terms. Dictionary approval depends on actual review. |
| Controlled review | A request for review against a specified STE edition | Obtain that edition. Review word meanings, parts of speech, applicable rules, and technical-term categories. Record reviewed and unresolved items. |

Report mode adapts STE principles to general writing. The Chinese version uses natural Chinese structure.

## Sentences and organization

- Limit descriptions to 25 words per sentence and procedures to 20.
- Use one topic and at most six sentences per paragraph. Use vertical lists for complex conditions, sequences, and enumerations.
- Normally give one action per procedural sentence. Put a required condition before the action.
- Keep grammar complete, including necessary subjects, articles, and verbs. Make each pronoun's referent clear.
- Split semicolon clauses into separate sentences. Choose other punctuation to fit the structure.
- Limit noun clusters to three words. Keep formal technical names recognizable and review them under the applicable rules.
- Use Part 1, Section 8 for formal word counting.

**Illustration**

> If the checksum matches, load the artifact. If the checksum differs, stop the import.

Each condition applies to its own action.

## Voice and actions

Use active voice and the imperative for procedures. Prefer active voice in descriptions. The official FAQ permits passive voice in descriptions when the actor is unknown.

> The worker writes the result.
>
> During transmission, the data was corrupted.

The second sentence retains the unknown actor. In general reporting, review whether responsibility remains clear when a passive sentence omits an actor. Formal review follows the standard.

Use concrete verbs for actions and reduce nominalization. Formal verb approval still depends on the dictionary. The official FAQ approves `check` as a noun, as in `do a check`.

## Vocabulary and domain terms

- Review ordinary words for their approved meaning and part of speech. Familiarity and dictionary approval require separate judgments.
- Use consistent names for the same object or action. Keep different operations, such as technical validation and user confirmation, distinct.
- Use established technical nouns and verbs. Define them when needed. Record their meaning, part of speech, domain category, and terminology source.
- Replace ambiguous phrasal verbs with clear single verbs while preserving the action.
- Review `-ing` forms by function and dictionary entry. Technical nouns and their components may use these forms.
- The FAQ also lists approved exceptions such as `opening`, `remaining`, `something`, and `during`.

## Tense, modality, and requirement strength

Prefer permitted verb forms and simple tenses. Time relationships, uncertainty, and obligations are part of the report's meaning.

| Source meaning | Wording | Information preserved |
|---|---|---|
| The job finished and its output is available now | The job finished. Its output is available. | Completion and current availability |
| A past request possibly failed | The request may have failed. | Uncertainty about a past event |
| Inspection is recommended | You should inspect the artifact. | Recommendation |
| Inspection is required | You must inspect the artifact. | Obligation |

Report mode may retain compound expressions that carry necessary meaning. For controlled review, find wording that preserves the meaning and fits the specified rules. Record unresolved items. Before converting `should` to an imperative, establish the source's requirement strength.
