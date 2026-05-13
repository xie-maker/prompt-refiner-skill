# Prompt Refiner

Prompt Refiner is a portable prompt-improvement workflow for AI assistants. It turns rough requests into clear, outcome-first executable prompts, then completes the task when execution is expected.

## One-Click Downloads

| Use case | Download |
| --- | --- |
| Any AI assistant: ChatGPT, Claude, Gemini, Cursor, etc. | [Download Universal Prompt Pack](https://github.com/xie-maker/prompt-refiner-skill/releases/latest/download/prompt-refiner-universal.zip) |
| Codex skill install | [Download Codex Skill Folder](https://github.com/xie-maker/prompt-refiner-skill/releases/latest/download/prompt-refiner-codex-skill.zip) |
| Full source code | [Download Repository ZIP](https://github.com/xie-maker/prompt-refiner-skill/archive/refs/heads/main.zip) |

Most AI products do not allow a GitHub repository to install a prompt directly into the app with one click. The universal pack gives you a one-click download that works anywhere: unzip it, open `PROMPT.md`, and paste it into your assistant's custom instructions, project instructions, rules, or first chat message.

It works as:

- A **copy/paste prompt** for ChatGPT, Claude, Gemini, Cursor, and other assistants
- A **Codex skill** with Quick Mode and `-pro` Pro Mode
- A lightweight prompt-review pattern for writing, planning, coding, research, analysis, spreadsheets, courseware, copywriting, and project planning

## What It Does

- Refines vague requests into practical prompts with clear goals, constraints, output format, evidence boundaries, stop rules, and validation.
- Keeps prompts compact instead of blindly filling every template section.
- Executes the task after refining the prompt when execution is expected.
- Supports a `-pro` mode for deeper prompt diagnosis, rewrite rationale, and test cases.

## Universal Use

If you are not using Codex, download the [Universal Prompt Pack](https://github.com/xie-maker/prompt-refiner-skill/releases/latest/download/prompt-refiner-universal.zip), unzip it, open `PROMPT.md`, and paste it into your assistant as:

- ChatGPT: a custom GPT instruction, project instruction, or the first message in a chat
- Claude: project instructions or the first message in a chat
- Gemini: a saved instruction or the first message in a chat
- Cursor: project rules or chat context
- Any other model: system prompt, developer prompt, or reusable instruction

Then use it like this:

```text
Use Prompt Refiner on this request:
Help me write a project plan
```

For Pro Mode:

```text
Use Prompt Refiner -pro on this request:
Improve this prompt: Help me write a project plan
```

## Codex Skill Install

Download the [Codex Skill Folder](https://github.com/xie-maker/prompt-refiner-skill/releases/latest/download/prompt-refiner-codex-skill.zip), unzip it, and copy the `prompt-refiner/` folder into your Codex skills directory:

```text
~/.codex/skills/prompt-refiner
```

On Windows, this is commonly:

```text
C:\Users\<you>\.codex\skills\prompt-refiner
```

Then invoke it from Codex:

```text
$prompt-refiner Your rough request here
```

or:

```text
$prompt-refiner -pro Your rough request here
```

## Modes

### Quick Mode

Quick Mode briefly optimizes the request and then completes the task.

Use it for everyday work:

```text
$prompt-refiner Help me write a project plan
```

or in any assistant:

```text
Use Prompt Refiner on this request:
Help me write a project plan
```

### Pro Mode

Pro Mode is for deeper prompt review, failure analysis, comparison, and testable prompt engineering.

Use:

```text
$prompt-refiner -pro Improve this prompt: Help me write a project plan
```

or:

```text
Use Prompt Refiner -pro on this request:
Improve this prompt: Help me write a project plan
```

Pro Mode provides:

- Diagnosis of concrete prompt weaknesses
- An optimized prompt
- A short explanation of why the revision is better
- 2 to 4 test cases or acceptance checks
- A result when execution is requested or clearly expected

## Repository Structure

```text
PROMPT.md
QUICKSTART.md
prompt-refiner/
  SKILL.md
  agents/
    openai.yaml
  references/
    prompt-patterns.md
```

## License

MIT
