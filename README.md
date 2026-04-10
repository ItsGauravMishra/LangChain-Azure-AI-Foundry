# LangChain-Azure-AI-Foundry

Small example project that ties together a lightweight web interface and a Python app for experimenting with LangChain + Azure AI + Foundry patterns.

## Contents

- `app.py` — main Python application (example server or runner)
- `index.html` — frontend / demo page
- `requirements.txt` — Python dependencies

## Prerequisites

- Python 3.8 or newer
- (Optional) An Azure account and any credentials required by your app if it uses Azure services

## Installation

1. Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

## Running

- To run the Python application (if `app.py` is a Flask/FastAPI or similar server):

```powershell
python app.py
# then open http://localhost:5000 (or the port your app uses)
```

- To view the static frontend, open `index.html` in your browser.

## Project Notes

- This repository is a minimal skeleton for experimenting; adapt `app.py` and `index.html` to your needs.
- If your code requires Azure credentials, set environment variables or a local credentials file as your app expects.

## Contributing

Feel free to open issues or submit pull requests with improvements. Keep changes small and focused.

## License

No license specified. Add a `LICENSE` file if you intend to open-source this project.
