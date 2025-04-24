# Purpose of this project
Replicate this [tutorial](https://python.langchain.com/docs/tutorials/rag/) to learn more about RAGs for our Resume RAG.

# Prerequisites
1. Follow this [tutorial](https://docs.smith.langchain.com/administration/how_to_guides/organization_management/create_account_api_key) to get your `LANGSMITH_API_KEY`.
2. Fill in the `LANGSMITH_API_KEY` in `.env.txt`.
3. Rename `.env.txt` to `.env`.
4. `ollama run llama3:8b`, can ctrl+c when finished with running this project to save system resources.

# Installation process
1. Pull from GitHub.
    * [SSH] `git clone git@github.com:random-logic/BasicRAGTutorial.git`.
    * [Default] `git clone https://github.com/random-logic/BasicRAGTutorial.git`.
2. `cd BasicRAGTutorial`.
3. `conda create -n "BasicRAGTutorial" python=3.12`.
4. `conda activate BasicRAGTutorial`.
5. `pip install poetry`.
6. `poetry install`.
7. Run `main.ipynb` in the `BasicRAGTutorial` conda env.

# Configure Environment on VSCode
1. Enter `Cmd+Shift+p` on Mac or `Ctrl+Shift+p` on PC.
2. Type `Python: select interpreter`.
3. Select the Anaconda `BasicRAGTutorial` env.

# Adding a dependency
`poetry add [pip package name]`

# Removing a dependency
`poetry remove [pip package name]`