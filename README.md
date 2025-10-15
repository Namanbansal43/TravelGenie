# TravelGenie: A Multi-Agent Travel Assistant

TravelGenie is a simple multi-agent travel planner built using the `smolagents` library from Hugging Face. It features a single manager agent that helps users plan a trip by:
1. Searching for flights.
2. Finding hotels at the destination.
3. Checking the weather for the chosen date.

## Installation & Usage

1. Create and activate a virtual environment:
```bash
python -m venv .venv
# On Windows: .venv\Scripts\activate
# On macOS/Linux: source .venv/bin/activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Gradio UI:
```bash
python -m src.main
```
This launches a local Gradio UI at http://127.0.0.1:7860.
