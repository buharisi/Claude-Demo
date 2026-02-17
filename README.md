# Claude API Demo - Simple Model Calling

A simple demonstration of how to call the Claude API using the Anthropic Python library.

## Overview

This project demonstrates basic interaction with Claude Anthropic's API. The `SimpleModelCalling` notebook shows how to:
- Set up the Anthropic client
- Load API credentials from environment variables
- Make a simple API call to the Claude model
- Process and display the response

## Prerequisites

- Python 3.x
- API key from Anthropic (set via `.env` file)

## Installation & Setup

1. Install the required package:
   ```bash
   pip install anthropic
   ```

2. Create a `.env` file in the project root with your API key:
   ```
   ANTHROPIC_API_KEY=your_api_key_here
   ```

## Usage

The demo makes a simple request to the Claude Opus 4.6 model asking "What should I search for to find the latest developments in renewable energy?" and displays the response.

### Running the Python Script

```bash
python SimpleModelCalling.py
```

### Running the Jupyter Notebook

Open and run `SimpleModelCalling.ipynb` in your Jupyter environment.

## Files

- `SimpleModelCalling.ipynb` - Jupyter notebook with step-by-step demonstration
- `SimpleModelCalling.py` - Python script version
- `.env` - Environment file for storing your API key (not included in repo)

## Notes

- The model used is `claude-opus-4-6` with a maximum of 1000 tokens
- Requires `python-dotenv` for loading environment variables from `.env` file
