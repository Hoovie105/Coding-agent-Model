# Coding Agent Model

This project is an intelligent coding agent designed to automate workflows, process prompts, and interact with external data sources. It is structured for modularity and extensibility, with a planned PyQt5 front end for user interaction.

## Features
- Modular backend logic in Python
- Workflow automation and prompt processing
- Planned PyQt5 GUI for easy interaction
- Environment variable management via `.env` (hidden from version control)

## Project Structure
```
main.py                # Entry point for backend logic
pyproject.toml         # Project dependencies and configuration
src/
    __init__.py
    firecrawl.py       # Data crawling and external data logic
    models.py          # Data models and schemas
    propmpts.py        # Prompt processing logic
    workflow.py        # Workflow automation
```

## Setup Instructions
1. **Clone the repository:**
   ```sh
   git clone https://github.com/Hoovie105/Coding-agent-Model.git
   cd Coding-agent-Model
   ```
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
   Or, if using Poetry:
   ```sh
   poetry install
   ```
3. **Set up environment variables:**
   - Create a `.env` file in the project root for any sensitive configuration (this file is ignored by git).

## Running the Backend
```sh
python main.py
```

## PyQt5 Front End (Coming Soon)
A PyQt5-based GUI will be added to provide a user-friendly interface for interacting with the agent.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)
