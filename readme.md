# Blackbox Chat with Repository

This repository contains an assignment from **Blackbox.ai** that enables interaction with a GitHub repository through a chatbot powered by `llama-index`, `langchain`, and other libraries. The chatbot allows you to ask questions about the repository's contents.

## Installation and Setup

Follow these steps to set up and run the project.

### Prerequisites

Ensure you have the following tools installed on your machine:
- **Git**: Download and install from [here](https://git-scm.com/).
- **Conda**: For managing the virtual environment, install [Anaconda or Miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

### Step-by-Step Instructions

1. **Clone the Repository**  
   Open a terminal and run the following command to clone this repository:
   ```bash
   git clone <repository-url>
2. **Navigate to the Project Directory
   Once cloned, navigate to the repository directory:
   ```bash
   cd blackbox
3. **Create a Virtual Environment
   Create a new virtual environment using conda with Python version 3.10:
   ```bash
   conda create -n blackbox python==3.10
4. **Activate the Virtual Environment
   Activate the newly created environment:
   ```bash
   conda activate blackbox
5. **Install Required Dependencies
   Install all required Python libraries using the following pip command:
   ```bash
   pip install python-dotenv llama-index llama-index-llms-ollama llama-index-packs-ragatouille-retriever llama-index-packs-code-hierarchy llama-index-vector-stores-qdrant llama-index-embeddings-fastembed langchain llama-index-embeddings-langchain -U langchain-community

### Usage
1. Modify black.py
   Open the black.py file and modify the repository or question inside the script as needed.

2. Run the Script
   Once you've made the necessary changes, you can run the script by executing:
   ```bash
   python black.py



