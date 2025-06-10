# Fishbowl Advanced Assistant

An AI assistant for Fishbowl Inventory Advanced, powered by official documentation.

## Structure

- **manifest.json**: GPT configuration (name, description, icon, knowledge sources).
- **prompts/system.txt**: System prompt engineering.
- **prompts/examples.json**: Example user/assistant pairs for the builder.

## Usage

1. Open ChatGPT Builder: `https://chat.openai.com/gpts/new`
2. Click **Import from manifest** and provide the contents of `manifest.json`.
3. Upload or paste `system.txt` into the system prompt field.
4. Add example messages from `examples.json`.
5. Configure retrieval to point to the Fishbowl documentation URL.
6. Publish your GPT.
