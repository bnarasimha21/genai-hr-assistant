# GenAI HR Assistant

A Generative AI assistant that leverages OpenAI's GPT-3.5 Turbo model to generate content for HR-related tasks such as writing newsletters, composing communications, and answering HR queries.

## Features

- **AI-Powered Content Generation** -- Uses OpenAI GPT-3.5 Turbo to generate HR content
- **Customizable Prompts** -- Easily modify prompts for different HR tasks (newsletters, policy summaries, Q&A)
- **Zero Temperature Setting** -- Deterministic, consistent outputs for professional communications

## Tech Stack

- **Language:** Python 3
- **AI Model:** OpenAI GPT-3.5 Turbo
- **Library:** OpenAI Python SDK

## Setup / Installation

### Prerequisites

- Python 3.x
- An OpenAI API key

### Installation

```bash
git clone https://github.com/bnarasimha21/genai-hr-assistant.git
cd genai-hr-assistant
pip install openai
```

### Configuration

Set your OpenAI API key as an environment variable:

```bash
export OPENAI_API_KEY="your-api-key-here"
```

## Usage

Run the script to generate HR content:

```bash
python generate.py
```

To customize the output, edit the `prompt` variable in `generate.py`:

```python
prompt = "Write 3 lines newsletter on Inclusiveness"
```

You can change the prompt to generate content for various HR tasks such as:

- Writing newsletters on workplace topics
- Drafting HR policy summaries
- Generating interview questions
- Composing employee communications

## License

MIT
