---
name: structure-spoken-notes
description: Use when the user sends messy spoken language, rough notes, fragmented thoughts, or chat-style wording and wants it rewritten into clear structured text, especially when they ask for a detailed version, concise version, business-formal version, polished version, or logically organized statement without changing the meaning.
---

# Structure Spoken Notes

Rewrite the user's original words into clearer, more structured writing without changing the meaning.

This skill is meaning-preserving by default. Do not treat stylistic polish as permission to add content, hidden assumptions, or analysis the user did not ask for.

## Core Rule

- Preserve intent
- Do not add facts the user did not say
- Do not over-explain
- Improve only structure, wording, and readability
- Do not smuggle advice, interpretation, or strategy into a rewrite-only request

## When To Use

Use this skill when the user says things like:

- "帮我整理一下这段话"
- "把我的话变成结构清晰的文字"
- "转成正式一点的话"
- "整理成适合发给客户/公司/合作方的话"
- "总结一下，但别改意思"
- "出一个详细版"
- "再来一个精简版"

Typical inputs:

- 口语化表达
- 想到哪说到哪的内容
- 没有分段的长句
- 重复、跳跃、补充很多的描述

## Output Modes

### Detailed Version

Use when the user asks for:

- 详细版
- 完整版
- 正式版
- 结构化说明

Requirements:

- Keep the original meaning complete
- Add light structure with short sections when helpful
- Group related points together
- Make the logic flow natural
- Keep the tone aligned with the user's intent
- Do not inflate the content beyond what the source supports

### Concise Version

Use when the user asks for:

- 精简一点
- 简洁版
- 短一点
- 压缩一下

Requirements:

- Keep only the essential meaning
- Remove repetition and filler
- Use fewer paragraphs
- Stay direct and easy to forward
- Do not compress away the user's core ask

### Business-Formal Version

Use when the user asks for:

- 正式商务版
- 对外沟通版
- 适合发给客户
- 适合发给公司
- 适合发给合作方
- 写正式一点

Requirements:

- Keep the original meaning intact
- Make the wording professional, steady, and externally shareable
- Remove casual filler and overly spoken phrasing
- Clarify background, current issue, and asks when relevant
- Avoid sounding stiff or exaggerated
- Do not make the text sound more certain than the source actually is

## Default Behavior

If the user does not specify a mode:

- Start with a clean standard version
- Prefer concise structure over long explanation
- Keep enough detail to preserve the full meaning
- If the wording appears intended for external communication, lean slightly professional

If the user asks for a rewrite and not an analysis, do not add recommendations, next steps, or explanation.

## Writing Rules

- Prefer clear paragraph structure over bullet overload unless the content is naturally list-shaped
- If the original content contains multiple questions, separate them clearly
- If the user is speaking to a company, client, or partner, make the wording more professional
- If the user asks for "just rewrite", do not add analysis, advice, or next steps
- If the user asks for multiple versions, label each version clearly
- Available labels include `详细版`, `精简版`, and `正式商务版`
- If ambiguity remains, prefer slightly general wording over invented specifics
- If the user's source is bilingual or requests bilingual output, keep the two versions aligned in meaning

## Compression Pattern

When converting spoken language into structured writing:

1. Identify the topic
2. Merge repeated ideas
3. Reorder into a natural sequence
4. Separate background, current issue, and core questions when relevant
5. Rewrite in smooth written language

## Safety Rule

If a key fact is genuinely ambiguous, keep the wording slightly general instead of inventing specifics.

## Completion Standard

Before claiming the rewrite is complete, confirm:

- the original meaning is preserved
- no new factual claims were introduced
- the requested tone or mode is actually reflected
- the output is clearer than the source
- multiple requested versions are clearly labeled

Do not claim the task is done if the rewrite is cleaner but has drifted in meaning.
