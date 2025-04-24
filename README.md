# Purpose of this project
Replicate this [tutorial](https://python.langchain.com/docs/tutorials/rag/) to learn more about RAGs for our Resume RAG.

# Prerequisites
1. Follow this [tutorial](https://docs.smith.langchain.com/administration/how_to_guides/organization_management/create_account_api_key) to get your `LANGSMITH_API_KEY`.
2. Fill in the `LANGSMITH_API_KEY` in `.env.txt`.
3. Rename `.env.txt` to `.env`.
4. `ollama run llama3:8b`, can ctrl+c when finished with running this project to save system resources.

# Installation process
1. `conda create -n "BasicRAGTutorial" python=3.12`.
2. `conda activate BasicRAGTutorial`.
3. `pip install poetry`.
4. `poetry install`.
5. Run `main.ipynb` in the `BasicRAGTutorial` conda env.

# Configure Environment on VSCode
1. Enter `Cmd+Shift+p` on Mac or `Ctrl+Shift+p` on PC.
2. Type `Python: select interpreter`.
3. Select the Anaconda `BasicRAGTutorial` env.

# Adding a dependency
`poetry add [pip package name]`

# Removing a dependency
`poetry remove [pip package name]`