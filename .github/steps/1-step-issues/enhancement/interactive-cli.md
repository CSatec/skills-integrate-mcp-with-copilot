# Add interactive CLI prompts

Create an interactive command-line interface for generating reports or documents. The CLI should ask users questions, offer choices, and collect inputs, similar to the helper functions in the external repo.

**Use cases:**
- Guide a user through selecting template options
- Collect data without editing JSON files manually

**Implementation notes:**
- Use Python `input()` or a library like `prompt_toolkit`
- Keep CLI logic separate from API code
