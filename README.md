# Context-based Q&A Chatbot

A Jupyter Notebook-based chatbot that uses contextual information to provide accurate answers to user queries using OpenAI's GPT models.

## Features

- Loads context from various data sources.
- Processes user questions with context-aware prompting.
- Generates responses using OpenAI's GPT API.
- Demonstrates interactive usage within a Jupyter Notebook.

## Requirements

- Python 3.8 or higher
- Jupyter Notebook
- Python packages listed in `requirements.txt`:
  - openai
  - numpy
  - pandas

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate into the project directory:
   ```bash
   cd <repository-directory>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open `Context_based_Q&A_Chatbot.ipynb`.
3. Follow the notebook cells to:
   - Set your OpenAI API key.
   - Load context data.
   - Query the chatbot interactively.

## File Structure

```
.
├── Context_based_Q&A_Chatbot.ipynb    # Main notebook
├── requirements.txt                   # Python dependencies
└── README.md                          # Project overview and instructions
```

## Configuration

Set your OpenAI API key in an environment variable before running the notebook:
```bash
export OPENAI_API_KEY="your_api_key_here"
```

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

## License

Licensed under the MIT License. See [LICENSE](LICENSE) for details.
