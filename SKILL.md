---
name: research-idea-log
description: Capture, retrieve, update, and resume research ideas in a persistent project log with sources, evidence boundaries, decisions, and next actions. Use for requests such as "记下这个 idea", "保存刚才的研究想法", "列出未验证的想法", "继续研究 IDEA-...", or an explicit request to capture ideas throughout the active discussion. Do not treat ordinary brainstorming or questions about this skill as authorization to save all conversation content.
---

# Research Idea Log

Maintain a durable, source-aware research notebook. Use the user's language. Keep portable skill code separate from private research records.

## Resolve the operation and destination

1. Identify capture, list/search, update, resume, or export. Resolve "this idea" from visible conversation first. Ask one focused question only when competing targets materially change the record.
2. Reuse the selected project log and its persistent identity. Otherwise search the available persistent file service for a matching project research-idea log before creating one. With ChatGPT Library, use its current Library skill and tools for search, read, create, and replacement.
3. Use a user-specified repository or local destination when supplied, checking repository instructions. Otherwise default to a persistent document named `<project>-research-ideas.md`, using a Markdown-safe project slug. Use `research-ideas.md` for a clear but unnamed project. Ask when several projects/logs fit equally well.
4. If persistent storage is unavailable, disclose the limitation and offer a copyable draft or ask for a durable destination. Never describe scratch files or chat-only text as durably saved.
5. Read the current log before editing or resuming. Preserve identity and unrelated entries. Use version guards where supported; reread and reconcile conflicts without discarding other edits.

## Capture an idea

1. Read [the record template](references/record-template.md). Capture enough rationale to resume without the original conversation, not merely a title.
2. Search existing entries for the same question. Update a continuing idea; preserve distinct alternatives as separate, cross-linked entries.
3. Assign a stable `IDEA-YYYYMMDD-NNN` ID using the user's local date and the next unused sequence in the current log. Preserve existing IDs; resolve collisions after concurrent edits.
4. Separate the user's proposal, assistant elaboration, and supervisor direction. Attribute supervisor instructions only to explicit user reports or available sources; mark reports as reported, not independently verified.
5. Save the question, approach, rationale, dependencies, limitations, smallest next step, and success/stop criteria when available. Label suggested criteria as proposals; leave unknown details explicitly unknown.
6. Record actual URLs, DOI/PMID, file identity/path and section, or conversation date/excerpt. Never invent conversation links or sources. Distinguish inspected sources from citations merely mentioned in a previous answer. Capturing does not require a new literature review.
7. Distinguish proposals, inferences, reported results, and source-checked results. Never upgrade an assistant answer to evidence, a plan to completed work, or a suggestion to a supervisor mandate.
8. Save durably with the destination's supported workflow. Confirm the idea ID, summary, status, and usable link only after success. On failure retain any draft, disclose that durable saving failed, and check for partial success before retrying to avoid duplicate entries.

## List and search

- Search the selected log by ID, title, keyword, project, status, or source type; read matched entries before making content claims.
- Return ID, title, progress, and next action in a compact table. Distinguish "no match in this log" from "never discussed".
- Do not search unrelated private projects for project-specific requests.

## Update and resume

1. Load the complete entry and necessary linked records. Briefly state the stopping point, established information, and unresolved question.
2. Recheck time-sensitive facts when they affect a decision. Do not silently turn unverified citations into checked evidence.
3. For "continue research", perform the smallest useful authorized research step. If the user asks only for a plan or next-step explanation, provide that without executing research or modifying the log. Resume is not automatic permission for training, purchases, deployment, external messages, or publishing private data.
4. When substantive findings or decisions arise within the authorized scope, append them with dates and update the summary and next action. Do not write a redundant entry for a read-only recap. Preserve earlier reasoning in change history. Mark superseded or contradictory claims explicitly.
5. Keep progress separate from evidence status. A completed investigation can reject a hypothesis. Require actual outputs before claiming execution or validation.
6. Record why approaches were paused or rejected; acknowledge that decision and any new justification before reopening them.

## Research integrity

- Preserve disease, tissue, species, population, assay, model, age definition, and study design where relevant.
- Distinguish gene selection, embedding similarity, coexpression, shared pathways, physical interactions, directed regulation, and causality.
- Treat same-cohort analyses and reused predictions as dependent evidence, not independent validation.
- Separate development questions from held-out evaluation; distinguish human review from agent review.
- Preserve gaps and conflicts. Never turn a snapshot miss into evidence of absence.

## Persistence and sharing

- Keep research logs outside this installable skill directory. Bundle only generic templates and synthetic examples.
- Do not continuously monitor other chats or promise automatic cross-chat capture. Honor explicit capture instructions in the active conversation; read the saved log when resuming later.
- For GitHub export, distinguish skill code from notes. Establish target repository and visibility before creating a repository or making content public; ask only for missing details and never reconfirm already explicit instructions.
- Inspect outgoing paths and content; publish only requested material. Exclude notes, credentials, and unrelated files. Never push an entire personal-skills repository to a public remote merely to share this skill.
- Distinguish successful skill installation, research-note storage, and GitHub publication.

## Example requests

- `记下刚才的想法，标记待核查，保留引用和下一步。`
- `列出这个项目未验证的 ideas，按下一步工作量排序。`
- `继续 IDEA-20261025-001，先核查数据，不运行实验。`
- `把失败结果追加到原记录，并说明暂停原因。`
- `只把通用技能代码发布到指定的 GitHub 仓库。`
