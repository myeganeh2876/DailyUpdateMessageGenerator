# DailyUpdateMessageGenerator

Easily create daily update messages from git commit messages in a specific date range with an example template and a custom prompt.

## Features
- Fetch commit messages from a private GitHub repository using your personal access token.
- Specify a **date range** to include only the relevant commits.
- Choose an OpenAI model (e.g., GPT-3.5-Turbo, GPT-4) to generate the update message.
- Provide an **update template** to guide the format of the generated message.
- Include a **custom prompt** to tailor the OpenAI output as needed.
- User-friendly interface with dropdowns, input fields, and textarea for customization.

## Requirements
- A GitHub personal access token with repository read permissions.
- An OpenAI API key with access to the OpenAI models.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/DailyUpdateMessageGenerator.git
   ```
2. Open the `index.html` file in your web browser to use the tool.

## Usage
1. Open the `index.html` in a browser.
2. Enter the following details:
   - **GitHub Token**: A personal access token with the necessary permissions.
   - **Repository URL**: The URL of the GitHub repository you want to fetch commits from.
   - **OpenAI Token**: Your OpenAI API key.
   - **OpenAI Model**: Choose from the available models (e.g., GPT-3.5-Turbo, GPT-4).
   - **Update Template**: Provide an example template for the desired update message format.
   - **Custom Prompt**: Add specific instructions for generating the message.
   - **Date Range**: Specify the start and end dates for the commits to include.
3. Click **Generate Update** to:
   - Fetch the commit messages from the repository.
   - Send the commit messages, template, and custom prompt to OpenAI for processing.
4. The generated update message will be displayed in the output section.

## Example Template and Prompt
### Template:
```plaintext
Daily Update:
- [Task 1]: Completed implementation of X.
- [Task 2]: Fixed bug related to Y.
- [Task 3]: Started working on Z.
```

### Custom Prompt:
```plaintext
Please summarize the commit messages into a structured daily update format. Include only meaningful updates and avoid technical jargon where possible.
```
---

Feel free to replace placeholder text like `your-username` or paths for screenshots as appropriate!
