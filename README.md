# WeGotWorkspace Product

Product intent for WeGotWorkspace. Every issue in this repository is a **Goal**: one user outcome, written in product language.

Engineering work (epics, tasks, chores, bugs) and the code live in [WeGotWorkspace/WeGotWorkspace](https://github.com/WeGotWorkspace/WeGotWorkspace).

## Where to look

- **[Product roadmap](https://github.com/orgs/WeGotWorkspace/projects/1)**: the board. Start here, not at the Issues tab.
- **[0.9 Roadmap](https://github.com/orgs/WeGotWorkspace/projects/1/views/4)**: Goals adopted for the beta (`Adopted` + milestone `v0.9`).
- **[Discussions](https://github.com/WeGotWorkspace/WeGotWorkspace/discussions)**: ideas and early exploration. Anyone can start a thread.

## How Goals work

- Status on the board is **Identified → Adopted → Fulfilled**.
  - **Identified**: recognized user outcome, draft backlog. No milestone.
  - **Adopted**: committed to a release. May take a milestone (`v0.9`, `v1.0`, …) as a soft target. Stays Adopted while it is being built.
  - **Fulfilled**: product judges the outcome met. Close the issue (`completed`); the board keeps Status Fulfilled.
- One Goal is one outcome. Do not parent a Goal under another Goal. Group siblings with `area:*` labels and an optional milestone.
- Labels: `type:goal` plus one or more `area:*`.
- Delivery attaches as **sub-issues** from the code repository: epics and tasks in WeGotWorkspace/WeGotWorkspace list the Goal as their parent.
- Goals are never the `Source:` of a spec and are never closed by a pull request.

Only maintainers file Goals. Issues opened here by anyone else are closed automatically with a pointer to Discussions and the bug report template.

Full process: [GOVERNANCE.md](https://github.com/WeGotWorkspace/WeGotWorkspace/blob/main/GOVERNANCE.md) and [docs/product/](https://github.com/WeGotWorkspace/WeGotWorkspace/tree/main/docs/product) in the code repository.

## Language

Goals and comments are written in **English**, even when the discussion that produced them was not.

Goals are read by customers and the product lead, so they use plain English (CEFR B1): what a person can do and how we know it works, not how it is built. Technical design lives in the Epic under each Goal in the code repository. When technical text is taken out of a Goal, it moves to that Epic; it is never just deleted. Rules and examples: [plain-language.md](https://github.com/WeGotWorkspace/WeGotWorkspace/blob/main/.agents/skills/developer/plain-language.md).
