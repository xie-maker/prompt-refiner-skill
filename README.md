# Prompt Refiner Skill

Prompt Refiner is a Codex skill that turns rough requests into clear, outcome-first executable prompts, then completes the task.

It is designed for everyday writing, planning, coding, research, analysis, spreadsheets, courseware, copywriting, and project planning workflows.

## What It Does

- Refines vague requests into practical prompts with clear goals, constraints, output format, evidence boundaries, stop rules, and validation.
- Keeps prompts compact instead of blindly filling every template section.
- Executes the task after refining the prompt when execution is expected.
- Supports a `-pro` mode for deeper prompt diagnosis and testable prompt engineering.

## Modes

### Quick Mode

Use the skill normally:

```text
$prompt-refiner Help me write a project plan
```

Quick Mode briefly optimizes the request and then completes the task.

### Pro Mode

Add an independent `-pro` flag:

```text
$prompt-refiner -pro Improve this prompt: Help me write a project plan
```

Pro Mode provides:

- Diagnosis of concrete prompt weaknesses
- An optimized prompt
- A short explanation of why the revision is better
- 2 to 4 test cases or acceptance checks
- A result when execution is requested or clearly expected

The `-pro` flag is treated as a control flag and is removed from the final optimized prompt.

## Install

Copy the `prompt-refiner/` folder into your Codex skills directory:

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

## Repository Structure

```text
prompt-refiner/
  SKILL.md
  agents/
    openai.yaml
  references/
    prompt-patterns.md
```

## License

MIT
