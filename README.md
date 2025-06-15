# Coding Agent Model

This project is an intelligent coding agent designed to automate workflows, process prompts, and interact with external data sources. It features a modern PyQt5 GUI for user interaction and a modular backend for extensibility.

## Features
- Modular backend logic in Python
- Workflow automation and prompt processing
- PyQt5 GUI for easy, modern interaction (gui.py)
- Environment variable management via .env

## Project Structure
```
main.py                # Entry point for backend logic (CLI)
gui.py                 # PyQt5 GUI application
pyproject.toml         # Project dependencies and configuration
requirements.txt       # Python dependencies
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

## Running the PyQt5 GUI
```sh
python gui.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)
