# ChatGPT Prompting for Developers

A comprehensive collection of Jupyter notebooks teaching effective prompt engineering techniques for ChatGPT and other large language models.

## What You'll Learn

This course covers essential prompting principles and practical applications:

- **Guidelines for Prompting** - Learn the two fundamental principles for effective AI communication
- **Iterative Prompt Development** - Master the process of refining prompts for better results
- **Summarizing** - Generate concise summaries with specific focus areas
- **Inferring** - Extract sentiment, emotions, and topics from text
- **Transforming** - Translate, reformat, and transform text across different styles
- **Expanding** - Generate detailed content from brief inputs
- **Building a Chatbot** - Create conversational AI with maintained context

## Setup Instructions

### Prerequisites
- Python 3.9.19 (recommended version)
- OpenAI API key

### Step 1: Create Virtual Environment
```bash
# Create a virtual environment with Python 3.9.19
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Set Up API Key
1. Get your OpenAI API key from [OpenAI Platform](https://platform.openai.com/account/api-keys)
2. Create a `.env` file in the project directory
3. Add your API key to the `.env` file:
```
OPENAI_API_KEY="your-api-key-here"
```


## Course Structure

| Notebook | Topic | Description |
|----------|-------|-------------|
| `0-Read-This-First.ipynb` | Course Overview | Detailed notes and summary of all lessons |
| `1-Guidelines-For-Prompting.ipynb` | Fundamentals | Two core principles for effective prompting |
| `2-iterative-prompt-development.ipynb` | Iteration | Refining prompts through iterative improvement |
| `3-summarizing.ipynb` | Summarization | Creating focused summaries from long text |
| `4-inferring.ipynb` | Analysis | Extracting insights and classifications |
| `5-transforming.ipynb` | Transformation | Language translation and format conversion |
| `6-expanding.ipynb` | Generation | Expanding brief inputs into detailed content |
| `7-chatbot.ipynb` | Chatbots | Building conversational AI systems |

## Key Learning Outcomes

### Principle 1: Write Clear and Specific Instructions
- Use delimiters to separate different parts of input
- Ask for structured output (JSON, HTML, etc.)
- Check if conditions are satisfied before proceeding
- Use few-shot prompting with examples

### Principle 2: Give the Model Time to "Think"
- Specify step-by-step instructions
- Ask the model to work out its own solution first
- Use structured formats for complex tasks

### Practical Applications
- **Translation**: Multi-language support with tone control
- **Sentiment Analysis**: Detect emotions and attitudes in text
- **Content Generation**: Create emails, reviews, and marketing copy
- **Data Processing**: Convert between formats and extract information

## Technical Features

- **Temperature Control**: Adjust AI creativity and randomness
- **Context Management**: Maintain conversation history in chatbots
- **Error Handling**: Robust prompting techniques to avoid hallucinations
- **Format Conversion**: Transform data between JSON, HTML, and other formats

## Troubleshooting

### Common Issues
1. **API Key Errors**: Ensure your `.env` file is properly configured
2. **Module Import Errors**: Verify all dependencies are installed in your virtual environment
3. **OpenAI Library Version**: This course uses OpenAI library version 0.27.0

## Credits
**DeepLearning.AI**