# Create Memory Entry

This task guides the user through creating a new memory entry in the knowledge network.

**Instructions:**

1.  **Elicit Information:** Ask the user for the following information:
    *   The core conclusion or finding.
    *   The type of memory (decision, implementation, learning, concept, or issue).
    *   A descriptive English ID for the file name (e.g., `2023-10-27-add-caching-layer`).
    *   A conclusion-focused English title for the memory.
    *   Relevant tags (comma-separated).
    *   Prerequisite memories (if any, as `[[wiki-links]]`).
    *   Consequent impacts (if any, as `[[wiki-links]]`).
    *   Related memories (if any, as `[[wiki-links]]`).
    *   A detailed explanation of the core content in Markdown.
    *   Relevant file paths (if any).
2.  **Generate Memory Entry:** Use the `memory-entry-tmpl.yaml` template to generate the memory entry.
3.  **Save Memory Entry:** Save the generated memory entry to the `memory/` directory in the project root. The filename should be the descriptive ID with a `.md` extension.
