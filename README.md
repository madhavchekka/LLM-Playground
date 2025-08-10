Before working on any LLM project, it is important that you have proper virtual environment set up with necessary packages. Setting up the environment from scratch is cumbersome. Instead, you can clone this repo and start working on your LLM project right away! Instructions provided are for Mac users.

# Run the following commands in Terminal
# Install uv using homebrew
>> brew install uv

# Create a new project folder
>> mkdir LLMWorkSpace

# Clone this repo (If you do not have git, install git first):
>> git clone git@github.com:madhavchekka/LLM-Playground.git

# Create venv
>> cd LLM-Playground
>> uv python pin 3.11  
>> uv sync  

# Optional Steps:
# If any package you need is missing 
>> uv add <package-name>

# Upgrade all packages if needed. They apply to the environment
>> uv lock --upgrade  
>> uv sync  

# Launch Jupyter notebook and start working
>> uv run jupyter notebook


