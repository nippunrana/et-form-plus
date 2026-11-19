# et-form-plus — AI Context

Read this file fully before planning or editing. Keep it under 150 lines; depth lives in `docs/`.

## 1. Overview & Tech Stack

A WordPress plugin for building forms (contact us, sales, etc.) and conversational forms (multi-step, one question at a time, conditional branching).

**Targets WordPress 7.1+ and PHP 8.4+**, chosen so modern code and components can be used easily. **Never** add fallbacks, polyfills, or compatibility code for older WordPress or PHP versions.

The rest of the tech stack and tooling is undecided — **never** assume it; ask.

## 2. Single Sources of Truth

None yet.

## 3. Built Systems vs Roadmap

| System | Status | Where |
| :--- | :--- | :--- |
| Form builder plugin (standard + conversational forms) | Roadmap | `docs/plan/form-builder-plugin.md` |

## 4. Environment & Deployment Constraints

- The GitHub repository is **public**. **Never** commit secrets, API keys, licence keys, or customer data.

## 5. Development & Deployment Guidelines

### Plans (`docs/plan/`)

`docs/plan/` holds the plans we are working on or still have to work on. It exists so an idea the owner likes can be kept when there is no time to build it or research it further.

- **A plan file is a captured idea, not a spec.** **Never** treat it as researched, approved, or built, and **never** start coding straight from one.
- **Picking up a plan starts with intensive planning and research** on that topic, specific to this plugin's case, before any implementation. That research is deliberately deferred until the plan is picked up.
- **Capturing an idea means writing it down briefly and stopping.** **Never** expand a new idea into designs, architecture, or task lists unprompted — that work belongs to the pick-up step.
- One idea per file, each with a `Status` line.
