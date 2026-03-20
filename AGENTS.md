# Repository Guidelines

## Project Structure & Module Organization

This repository is a documentation-first learning path for LLM and Agent engineering. Most content lives under `AI_Agent_LLM_学习路径/`, organized by stage (`阶段0_...` through `阶段4_...`) and then by chapter (`章节01_...`, `章节02_...`). Each chapter is split into four fixed subdirectories:

- `学习资料/README.md`: reading and study notes
- `理论考试/README.md`: theory questions
- `代码考试/README.md`: implementation tasks
- `实际项目/README.md`: capstone-style project work

Top-level workflow documents such as `提交流程.md`, `评分与晋级规则.md`, `学习进度总览.md`, and `当前学习状态.md` define submission, scoring, and progress tracking.

## Build, Test, and Development Commands

There is no single project-wide build or test entrypoint at the repository root. Use lightweight validation commands while editing:

- `rg --files AI_Agent_LLM_学习路径`: list tracked curriculum files quickly
- `find AI_Agent_LLM_学习路径 -name README.md | sort`: verify chapter coverage
- `git diff -- AGENTS.md`: review documentation edits before commit

For code added inside a chapter, document its own run and test commands in that chapter’s `代码考试` or `实际项目` README.

## Coding Style & Naming Conventions

Keep directory names aligned with the existing pattern: `阶段N_主题/章节NN_主题/子目录/README.md`. Preserve Chinese names already used across the curriculum. Write Markdown with concise headings, short paragraphs, and fenced code blocks for commands or examples. Use UTF-8 and keep shell commands copy-pastable. If a chapter includes Python examples, prefer Python 3.11+ and 4-space indentation.

## Testing Guidelines

This repository does not currently define a centralized automated test suite or coverage target. Treat consistency checks as the baseline: confirm every chapter keeps the four standard subfolders, and ensure any added code sample includes explicit run instructions, expected output, and dependency notes in its local README.

## Commit & Pull Request Guidelines

Git history is minimal and currently uses short lowercase subjects such as `first commit`. Continue with brief, imperative commit messages, ideally scoped to one chapter or workflow document. Pull requests should state the affected stage/chapter, summarize content changes, link any related issue, and include screenshots or logs when updating `实际项目` guidance or sample outputs.
