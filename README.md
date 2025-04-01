# Function-Calling-with-Ollama-and-Llama3.2-for-Local-CRUD-Operations
## Project Overview
This project demonstrates how to leverage Ollama for serving Llama3.2 3B/1B models and perform CRUD operations on a local file system (`Convo.txt`) using Python. By integrating function calling and AI inference, the project automates file management tasks such as creating, reading, updating, and deleting files, ensuring seamless AI-driven workflows.

## Technologies Used
- **Ollama**: Model serving framework for Llama3.2 models.
- **Llama3.2 3B/1B**: Llama models used for performing inference.
- **Python**: Programming language used for CRUD operations and function calling.
- **GGUF Model Format**: Optimized format for fast model inference and backend performance.

## Key Features
- Perform CRUD operations on a local file (`Convo.txt`) using Llama3.2 models.
- Integration of function calling with Ollama for seamless interaction with Python.
- Fast inference and backend optimization using Ollama's GGUF model format.
- Python-based implementation to automate file management tasks.

## Project Setup
### Prerequisites
- Ubuntu 22.04 or any system supporting Ollama and Llama3.2.
- Python 3.x installed on your local machine.

### Installation Instructions
1. **Install Ollama**:  
   Follow the installation instructions from [Ollama's GitHub Repository](https://github.com/ollama/ollama/blob/main/docs/linux.md) to set up Ollama on your machine.
   
2. **Install Python Dependencies**:
   You can install the required Python packages using the following command:
   ```bash
   pip install -r requirements.txt
