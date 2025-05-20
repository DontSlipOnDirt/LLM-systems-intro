# LLM-fine-tuning
System of notebooks for easy fine-tuning for students of the Social Data Science program

## Setting up jupyter kernel
`uv run ipython kernel install --user --env --active VIRTUAL_ENV $(pwd)/.venv --name=LLM-fine-tuning`

`uv run --with jupyter jupyter lab`

Once running, paste in URL when selecting kernel. Set name to `LLM-fine-tuning`