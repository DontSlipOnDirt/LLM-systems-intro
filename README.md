# LLM-fine-tuning
System of notebooks for easy fine-tuning for students of the Social Data Science program

## What there is
- Fine tuning notebooks:
    - LoRA finetuning
    - Houlsby adapter finetuning
- RAG notebook

## Setting up jupyter kernel with uv
`uv run ipython kernel install --user --env --active VIRTUAL_ENV $(pwd)/.venv --name=LLM-fine-tuning`

`uv run --with jupyter jupyter lab`

Once running, paste in URL when selecting kernel. Set name to `LLM-fine-tuning`