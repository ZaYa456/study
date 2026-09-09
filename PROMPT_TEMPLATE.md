# Reusable AI Prompt Template

Copy this block and fill in the brackets each time you want a new topic page.
Paste the AI's raw output directly into a new `.md` file — no cleanup needed
if the AI follows the format below.

---

Generate study notes on [TOPIC] for [SUBJECT], for a college entrance exam.

Output ONLY a Jekyll Markdown page, formatted exactly like this:

    ---
    title: [Short page title]
    parent: [Math / Physics / Chemistry / Biology]
    nav_order: [number]
    ---

    # [Same title]

    [Content here]

Rules:
- Use \( ... \) for inline math and $$ ... $$ for display (block) equations.
- For Chemistry only: use \ce{...} inside $$ ... $$ for reactions/formulas
  (e.g. $$\ce{2H2 + O2 -> 2H2O}$$).
- Do not use any raw HTML tags.
- Do not wrap the output in Markdown code fences.
- Use ## for subheadings (Definition, Example, Practice Problem, etc.)
- Keep explanations concise and exam-focused.

---

## Notes

- `nav_order` controls the position in the sidebar under each subject —
  increment it by 1 for each new page in that subject.
- File naming convention: lowercase, hyphenated, matching the topic
  (e.g. `chain-rule.md`, `stoichiometry.md`), saved inside the matching
  subject folder (`/math/`, `/physics/`, `/chemistry/`, `/biology/`).
