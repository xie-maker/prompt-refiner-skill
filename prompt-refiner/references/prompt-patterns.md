# Prompt Patterns Reference

Use this reference only when Pro Mode needs a sharper diagnosis or task-specific pattern. Keep outputs concise and adapt only the relevant parts.

## Universal Diagnosis Checklist

- Goal: Is the desired outcome concrete enough to execute?
- Audience: Is the reader, user, learner, or stakeholder clear?
- Context: Are source materials, background, assumptions, and current state available?
- Output contract: Is the deliverable format, length, language, and level of detail specified?
- Success criteria: Is there a way to tell whether the result is good?
- Constraints: Are inclusions, exclusions, tone, tools, deadlines, and boundaries explicit?
- Evidence boundary: Should the assistant use provided context only, local files, current web sources, or citations?
- Stop rule: Is there a clear point to stop searching, iterating, or asking?
- Validation: Can the result be checked with tests, citations, examples, calculations, or acceptance scenarios?

## Common Anti-Patterns

- Vague goal: "help me with this" without a deliverable.
- Persona padding: long motivational roles that do not change execution.
- Process overfit: rigid step lists where success criteria would work better.
- Hidden audience: no indication of who will read or use the result.
- Missing evidence boundary: unclear whether to browse, inspect files, cite, or use provided context only.
- No stop condition: encourages endless searching or unnecessary questions.
- Conflicting constraints: asks for both exhaustive depth and a very short answer without priority.
- Unverifiable output: no tests, examples, acceptance checks, or quality bar.

## Task Emphasis

- Research: topic scope, source quality, recency, minimum evidence, citation style, confidence, and what to do when sources conflict.
- Coding: repository inspection, target behavior, files or modules, compatibility constraints, tests to run, and what not to touch.
- Writing: audience, purpose, tone, examples to emulate or avoid, length, structure, and final-use context.
- Planning: decision criteria, tradeoffs, dependencies, risks, assumptions, owners, milestones, and next action.
- Data and spreadsheets: input files, required columns, transformations, formulas, charts, validation checks, and final workbook or table shape.
- Courseware: learner profile, objectives, outline, examples, practice tasks, assessment, pacing, and format.
- Creative: concept, mood, style references, constraints, variants, anti-patterns, and selection criteria.

## Pro Mode Output Tests

Use 2 to 4 tests that fit the task:

- Trigger test: Does the refined prompt produce the requested artifact without another clarification round?
- Boundary test: Does it avoid unsupported facts, invented citations, or out-of-scope work?
- Format test: Does the output match the requested structure, language, length, and file type?
- Quality test: Does it satisfy the stated audience, success criteria, and constraints?
- Validation test: Can the result be verified through tests, citations, calculations, examples, or review criteria?
