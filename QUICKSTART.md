# Prompt Refiner Quick Start

Prompt Refiner works with ChatGPT, Claude, Gemini, Cursor, Codex, and other AI assistants.

## If You Use ChatGPT, Claude, Gemini, Cursor, Or Another Assistant

1. Download `prompt-refiner-universal.zip` from the latest GitHub release.
2. Unzip it.
3. Open `PROMPT.md`.
4. Copy the full prompt into your assistant's custom instructions, project instructions, rules, or first chat message.
5. Use it like this:

```text
Use Prompt Refiner on this request:
Help me write a project plan
```

For Pro Mode:

```text
Use Prompt Refiner -pro on this request:
Improve this prompt: Help me write a project plan
```

## If You Use Codex

1. Download `prompt-refiner-codex-skill.zip` from the latest GitHub release.
2. Unzip it.
3. Copy the `prompt-refiner/` folder into your Codex skills directory.

macOS/Linux:

```text
~/.codex/skills/prompt-refiner
```

Windows:

```text
C:\Users\<you>\.codex\skills\prompt-refiner
```

Then use:

```text
$prompt-refiner Your rough request here
```

or:

```text
$prompt-refiner -pro Your rough request here
```
