# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is not a software project — it's a personal notes repository for studying toward the AWS Certified
Solutions Architect – Associate (SAA) certification. Content is Markdown study guides written in
Brazilian Portuguese, covering AWS services in depth (theory, real-world trade-offs, exam gotchas,
hands-on lab steps, and AWS CLI snippets).

There is no build, lint, or test tooling — the repository is just Markdown files.

## Content conventions

Each topic file (e.g. `API-GATEWAY.md`) follows a consistent structure worth preserving when editing
or adding topics:

1. **Conceptual sections** — numbered `##` headings walking through a service's features, explaining
   the *why* behind each behavior, not just the *what*. Sections often call out "o que muita gente erra
   na prova" (common exam/real-world mistakes) and "no dia a dia" (real-world usage notes) to distinguish
   textbook knowledge from practical experience.
2. **🧪 Laboratório prático** — a hands-on lab section near the end with step-by-step console/CLI
   instructions to actually build the service in AWS, plus a numbered list of small experiments to
   reinforce each concept.
3. **AWS CLI úteis** — a block of copy-pasteable AWS CLI commands relevant to the topic.
4. **Tabela de decisão rápida** — a closing decision-table (`| Cenário | Resposta provável |`) that
   maps common scenarios to the "expected" answer, for quick exam review.

When adding a new topic file, follow this same shape so the repo stays consistent, and keep the
language in Brazilian Portuguese to match existing content.
