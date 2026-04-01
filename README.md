# Building with Claude API

Simple Jupyter notebooks for learning how to use the Anthropic Claude API with Python.

## What's included

- Top-level notebooks for API basics, system prompts, temperature, output control, and streaming
- `prompt_engineering/` for prompt design examples
- `prompt_evaluation/` for evaluation notebooks and sample data

## Requirements

- Python 3.10+
- An Anthropic API key
- Jupyter Notebook or JupyterLab

## Setup

1. Create and activate a virtual environment.
2. Install dependencies:

	```bash
	pip install -r requirements.txt
	```

3. Create a `.env` file from `.env.example`.
4. Add your API key:

	```env
	ANTHROPIC_API_KEY="your-api-key-here"
	```

5. Start Jupyter:

	```bash
	jupyter notebook
	```

## Usage

Open the notebooks and run them in order, or jump to the section you want to explore.

## License

This project is licensed under the terms in [LICENSE](LICENSE).