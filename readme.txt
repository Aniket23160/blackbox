How to use:
git clone 
cd Blackbox 
conda create -n blackbox python==3.10
conda activate blackbox 
pip install python-dotenv llama-index llama-index-llms-ollama llama-index-packs-ragatouille-retriever llama-index-packs-code-hierarchy llama-index-vector-stores-qdrant llama-index-embeddings-fastembed langchain llama-index-embeddings-langchain -U langchain-community
Change the repo or question inside black.py 
run 
python black.py 
