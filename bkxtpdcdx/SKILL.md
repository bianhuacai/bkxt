---
name: bkxtpdcdx
description: Diagnose undergraduate thesis topic feasibility and revision paths. Use when users ask whether a bachelor's thesis topic, undergraduate dissertation idea, empirical paper topic, or research direction is feasible, too broad, too common, data-accessible, literature-supported, empirically doable, or how to revise it into a workable thesis.
---

# Thesis Feasibility

## Core Principle

Judge whether a topic can become a finished undergraduate thesis under realistic constraints. Do not judge whether it is academically fashionable or "advanced." Many classic, frequently studied topics are good undergraduate safe zones if they have data, literature, measurable variables, and a small enough angle.

Distinguish three layers:

- **母题**: a broad research direction, such as "数字经济对企业创新的影响". It may be feasible as a direction but not yet executable as a thesis.
- **候选题**: a narrowed topic with a clearer object or relationship, but still missing data, variables, method, or scope.
- **可开题题目**: a topic with a defined sample, key variables, data path, and empirical or writing structure.

The goal is not only to say feasible or infeasible. Always explain how to push the topic one layer closer to a writable thesis.

## Intake

Use the information the user provides. If details are missing, make cautious assumptions and label them. Ask questions only when the missing information prevents a useful diagnosis.

Useful inputs:

- Topic or research direction
- Major or discipline
- Planned method: empirical, case study, questionnaire, literature review, theoretical analysis
- Target sample: region, industry, firm type, population, time period
- Possible data source
- Initial variables or concepts
- User's current concern: data, literature, originality, model, difficulty, or topic wording

## Diagnostic Workflow

1. **Restate the topic neutrally**: avoid calling it good or bad too early.
2. **Classify the current layer**: 母题, 候选题, or 可开题题目.
3. **Score the nine dimensions** from 0 to 5.
4. **Identify hard blockers**: no data path, unmeasurable core concept, method beyond undergraduate scope, or no coherent thesis structure.
5. **Give a feasibility level**: 可直接开题, 可做但需修改, 风险较高, or 不建议做.
6. **Offer revision paths**: narrow sample, change variable, change data source, soften causal claims, add mechanism, add heterogeneity, or change method.
7. **Produce improved topic versions** when useful.

## Nine Dimensions

Score each dimension from 0 to 5:

- **母题可行性**: whether the broader direction has a stable research tradition, theory base, data path, and common models. A broad topic can score high here even if it is not yet a final thesis title.
- **题目成熟度**: whether the current wording already specifies research object, key relationship, scope, and method enough to start writing.
- **数据可得性**: whether the needed data are public, credible, large enough, time-bounded, and manageable for an undergraduate student.
- **变量可测量性**: whether every core concept can be converted into accepted indicators, proxies, questionnaire scales, or observable evidence.
- **文献基础**: whether there are enough relevant papers to support literature review, theory, hypotheses, variable design, and empirical model choices.
- **同质化风险**: whether the topic is heavily repeated and whether it has a credible small angle to avoid pure duplication. High saturation is a risk, not an automatic rejection.
- **实证难易程度**: whether the method fits undergraduate ability and available time. OLS, descriptive analysis, fixed effects, mediation, moderation, and heterogeneity are usually more suitable than DID, IV, RDD, or complex causal designs unless the design is very clear.
- **论文结构可写性**: whether the topic can naturally produce a complete paper structure: problem, theory, hypotheses, data, variables, model, results, robustness, discussion, and conclusion.
- **修改弹性**: whether the topic can be rescued by narrowing scope, changing data, changing variables, softening causal claims, switching method, or moving to an adjacent mature topic.

## Feasibility Levels

Use these levels after the dimensional diagnosis:

- **可直接开题**: data, variables, method, and structure are mostly clear. Only wording or minor scope edits are needed.
- **可做但需修改**: the direction is feasible, but the title is still too broad, too saturated, or missing key operational choices.
- **风险较高**: one or more core pieces are uncertain, such as data, measurement, causal identification, or paper structure.
- **不建议做**: no plausible data path, no measurable variables, insufficient literature, or the required method is far beyond undergraduate scope.

## Output Format

Prefer this structure:

```text
判断：可做但需修改 / 可直接开题 / 风险较高 / 不建议做
当前层级：母题 / 候选题 / 可开题题目

一句话结论：
...

维度评分：
1. 母题可行性：x/5 - ...
2. 题目成熟度：x/5 - ...
3. 数据可得性：x/5 - ...
4. 变量可测量性：x/5 - ...
5. 文献基础：x/5 - ...
6. 同质化风险：x/5 - ...
7. 实证难易程度：x/5 - ...
8. 论文结构可写性：x/5 - ...
9. 修改弹性：x/5 - ...

主要风险：
- ...

建议改法：
- ...

可改成的题目：
1. ...
2. ...
3. ...
```

Keep the final answer practical. For undergraduate users, concrete revision paths are more valuable than abstract methodology lectures.

## Calibration Rules

- Do not equate "broad" with "bad." Broad topics are often viable mother themes.
- Do not equate "many people studied it" with "cannot write." For undergraduate theses, repeated topics are often safer if a small angle exists.
- Do not demand excessive originality. A modest change in sample, time period, mechanism, variable, or context can be enough.
- Do not over-recommend complex causal methods. Prefer methods the user can realistically execute.
- Separate direction feasibility from current-title maturity.
- When data are uncertain, name possible data paths and say which one makes the topic easier.
- When a topic is risky, provide a lower-risk adjacent version instead of only rejecting it.
