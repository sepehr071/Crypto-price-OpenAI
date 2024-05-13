
```markdown
# Cryptocurrency Price Checker

## Introduction
This project provides a tool to fetch the current price of a specified cryptocurrency in USD. It utilizes the OpenAI API to parse user input and extract the cryptocurrency name and the Coingecko API to retrieve the actual price. This application is intended for educational purposes and demonstrates the use of APIs and Python scripting.

## Features
- Extracts cryptocurrency names from user input using OpenAI's powerful language model.
- Retrieves real-time cryptocurrency prices from the Coingecko API.
- Simple CLI for easy interaction.

## Requirements
- Python 3.8 or higher
- OpenAI API key
- Internet connection

## Installation

First, clone this repository to your local machine using:

```bash
git clone https://github.com/sepehr071/Crypto-price-OpenAI
cd Crypto-price-OpenAI
```

Then, install the required dependencies:

```bash
pip install openai requests
```

Ensure you have set up an environment variable for your OpenAI API key:

```bash
export OPENAI_API_KEY='your_api_key_here'
```

## Usage

To run the application, execute the main script from the command line:

```bash
python get-crypto-price.py
```

Follow the on-screen prompts to enter the name of the cryptocurrency you are interested in. The application will then display the current price of the cryptocurrency in USD.

## Contributing
Contributions to this project are welcome! Here's how you can contribute:
- **Fork the repository**: Click on the 'Fork' button at the top right of this page.
- **Clone your fork**: Find the "Clone" button in your fork, copy the link, and run the following git command:
  
  ```bash
  git clone url_of_your_fork
  ```
  
- **Create a branch**: Navigate to your local repository, and switch to a new branch using the git checkout command.
  
  ```bash
  git checkout -b your_new_branch_name
  ```
  
- **Make your changes**: Add your changes to this branch and commit them using git commands.
- **Push your changes**: Push your changes to your fork.
  
  ```bash
  git push origin your_new_branch_name
  ```
  
- **Submit a pull request**: Go to your fork on GitHub, select your branch, and click the 'Pull request' button. Fill out the form and submit.



### Notes
- Replace `yourusername` with your actual GitHub username.
- Replace `'your_api_key_here'` with an appropriate placeholder or instruction for the user to replace this with their actual API key.
- Adjust the repository URL and any specific details to fit the actual setup of your project on GitHub.
- You may want to include an actual LICENSE file in your repository if you mention it in the README. The MIT License is commonly used for open source projects.
