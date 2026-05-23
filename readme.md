# LLM Programming on Python

This repository is dedicated to exploring and testing major large language models (LLMs) with Python. It is built as a learning playground for LLM engineering, model evaluation, prompt design, and practical experimentation using notebooks.

## Goals

- Test major LLM models and compare their behavior
- Learn practical LLM engineering techniques
- Build reusable Python workflows for model evaluation
- Explore local and cloud-based model deployments
- Document findings, best practices, and model-specific observations

## Repository Structure

- `readme.md` - This project overview and guide
- `ollama/` - Notebook examples focused on Ollama-powered model testing
  - `multi_model_ollama_chat.ipynb` - Multi-model chat experiments using Ollama
  - `test_ollama_cloud.ipynb` - Cloud-based Ollama model testing and validation
  - `test_ollama_local.ipynb` - Local Ollama model testing and setup

## Getting Started

1. Clone the repository:

```bash
git clone <repo-url>
cd llm_programming_on_python
```

2. Activate your Python virtual environment (if available):

```powershell
& .\.venv\Scripts\Activate.ps1
```

3. Install dependencies as needed for your notebook environment.

4. Open the notebooks in Jupyter or VS Code to begin experimentation.

## Recommended Workflow

1. Start with `ollama/test_ollama_local.ipynb` to verify local model setup.
2. Move to `ollama/test_ollama_cloud.ipynb` to compare cloud-hosted model behavior.
3. Use `ollama/multi_model_ollama_chat.ipynb` for side-by-side comparisons and prompt engineering tests.
4. Record model observations, strengths, and weaknesses as you test.

## LLM Engineering Focus Areas

- Prompt design and prompt templates
- Response quality and consistency
- Model latency and usage costs
- Safety and output filtering
- Versioning, fine-tuning, and model selection
- Integration patterns for Python applications

## Notes

- This repo is intentionally lightweight and notebook-driven.
- Add new notebooks or Python scripts as you explore additional models.
- Use the notebooks to capture experiments and compare model results.

## Contributing

- Add new model evaluation notebooks or scripts
- Document setup steps for additional LLM providers
- Share notes on prompt strategies, prompt chains, and evaluation metrics

---

Happy experimenting with LLMs and Python!