# Support JSON-based paragraph pools

Add support for storing reusable text snippets (e.g. paragraphs) in a JSON configuration file. Users should be able to select from a pool of predefined paragraphs when generating documents.

**Why:** Cover-Letter-Generator uses `sample.json` to hold paragraphs and reuse data; the current project has no similar configuration storage.

**Acceptance criteria:**
- A JSON file holding paragraph templates
- API/CLI to list available options
- Mechanism to merge selected paragraphs into output
