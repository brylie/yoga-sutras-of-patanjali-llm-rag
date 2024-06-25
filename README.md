# Yoga Sutras of Patanjali LLM RAG

Chat with the Yoga Sutras of Patanjali using Large Language Models and Retrieval-Augmented Generation (RAG).

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.dev/brylie/yoga-sutras-of-patanjali-llm-rag)


## Project Goal

This project aims to create an AI agent that acts as a helpful devotee of the Yoga Sutras of Patanjali. The agent responds to user input with answers based on the yoga sutras. When the conversation steers too far away from the yoga sutras or there is no relevance to the yogic wisdom and philosophy, the agent politely steers the discussion back towards the topic of yoga and the Sutras of Patanjali.

## Prerequisites

- Python 3.10.x (managed by pyenv)
- [Langflow](https://github.com/logspace-ai/langflow) installed

## Project Structure

- `.python-version`: Used by pyenv to select the correct Python version (3.10.x) to run the project
- `LICENSE`: MIT License
- `README.md`: This file
- `requirements.txt`: For installing project dependencies
- `Yoga Sutras of Patanjali RAG chat.json`: Exported Langflow project for users to import
- `YogaSutrasOfPatanjali-pg2526.txt`: Full text of the Yoga Sutras of Patanjali from Project Gutenberg

## Using GitHub Codespaces

This project is configured to work with GitHub Codespaces, allowing you to start developing quickly without setting up a local environment.

To start using Codespaces:

1. Go to the GitHub repository page
2. Click on the "Code" button
3. Select the "Codespaces" tab
4. Click on "Create codespace on main"

This will create a new Codespace with all necessary dependencies installed. Langflow will start automatically, and you can access it at http://localhost:7860.

Note: 
- The first time you create a Codespace, it may take a few minutes to set up.
- Langflow will be running in the terminal. To stop it, use Ctrl+C in that terminal.
- To start Langflow again, run 'langflow run' in the terminal.

## Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/brylie/yoga-sutras-of-patanjali-llm-rag.git
   cd yoga-sutras-of-patanjali-llm-rag
   ```

2. Ensure you have Python 3.10.x installed. If you're using pyenv, it will automatically select the correct version based on the `.python-version` file.

3. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Running the Project

1. Start Langflow:
   ```sh
   langflow run
   ```

2. Open your web browser and go to the Langflow UI (usually `http://localhost:7860`).

3. In the Langflow UI, import the `Yoga Sutras of Patanjali RAG chat.json` file.

4. Run the imported flow to start chatting with the Yoga Sutras of Patanjali AI agent.

## Usage

Once the Langflow project is running, you can interact with the AI agent by typing your questions or comments related to the Yoga Sutras of Patanjali. The agent will respond based on its knowledge of the sutras and attempt to keep the conversation focused on yogic wisdom and philosophy.

## Contributing

Contributions to improve the project are welcome. Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- The Yoga Sutras of Patanjali text is sourced from Project Gutenberg.
- This project uses Langflow for the chat interface and RAG implementation.
