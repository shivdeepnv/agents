# Agent Development Course - LlamaIndex and Hugging Face

This repository contains educational materials and Jupyter notebooks for a course on building agents using LlamaIndex and Hugging Face. Explore various concepts from basic agent construction to complex workflow management.

## Notebook Summaries

### `components.ipynb`
This notebook introduces core components of LlamaIndex, focusing on building a `QueryEngine` for Retrieval Augmented Generation (RAG). Key topics include:
- Loading and indexing a dataset of personas.
- Querying the indexed data.
- Evaluating the RAG system.
- Observability using Arize Phoenix for tracking and debugging.

### `dummy_agent_library.ipynb`
This notebook provides a step-by-step guide to creating a simple agent from scratch. It covers:
- Utilizing the Hugging Face `InferenceClient` for model interaction.
- Understanding and applying chat templates for conversational models.
- Implementing the fundamental thought-action-observation loop characteristic of agent behavior, demonstrated with a `get_weather` tool example.

### `workflows.ipynb`
This notebook explores the concept of workflows in LlamaIndex, enabling the creation of more complex and structured agent interactions. It includes:
- Building single-step and multi-step workflows.
- Managing state and context across different steps in a workflow.
- Implementing loops and conditional branches for dynamic workflow execution.
- Designing multi-agent workflows where different agents collaborate to achieve a goal.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab

### Installation
It is recommended to set up a virtual environment.

1.  **Clone the repository:**
    ```bash
    git clone <repository_url> # Replace <repository_url> with the actual URL
    cd <repository_name> # Replace <repository_name> with the folder name
    ```
2.  **Install dependencies:**
    Each notebook lists its required dependencies at the beginning. You can install them by running the pip install commands in the cells. For a consolidated approach, you might consider creating a `requirements.txt` file.

### Hugging Face Setup
-   **Token:** Many notebooks require a Hugging Face token for accessing models via Serverless Inference APIs. You can obtain a token from [https://hf.co/settings/tokens](https://hf.co/settings/tokens). It's recommended to set this as an environment variable (`HF_TOKEN`) or use the secret management tools if you're on a platform like Google Colab.
-   **Model Access:** Some models, like those from Meta Llama, require you to request access first. Please ensure you have the necessary permissions for the models used in the notebooks.

## Contributing
Contributions to this course material are welcome! If you have suggestions for improvements, new examples, or find any issues, please feel free to:
1.  Fork the repository.
2.  Create a new branch for your changes.
3.  Make your modifications.
4.  Submit a pull request with a clear description of your changes.

## License
Please refer to the LICENSE file in this repository. If no LICENSE file is present, assume the content is for educational purposes only, and all rights are reserved by the authors.
