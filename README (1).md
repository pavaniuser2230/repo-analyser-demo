# RepoPilot — GitHub Repository Analyser

RepoPilot is a responsive, dark-mode dashboard prototype for a GitHub Repository Analyser Agent. It demonstrates how an AI-powered developer assistant could help review a code repository, identify potential issues, and plan improvements.

## Features

- **Repository overview** — a dashboard-style summary of repository health and activity.
- **Code findings** — example findings and improvement suggestions.
- **File explorer** — a sample interface for browsing project files and code previews.
- **AI assistant demo** — predefined sample responses for prompts about code improvements, bug detection, and feature planning.
- **Security review interface** — example security checks and recommendations.
- **Responsive design** — a premium dark theme designed for desktop and smaller screens.
- **Single-file frontend** — HTML, CSS, and JavaScript are bundled into one HTML file.

## Project Status

This project is currently a **frontend prototype**. The dashboard uses sample data and predefined demo responses. It does not yet connect to a live GitHub repository or Microsoft Foundry agent.

## Getting Started

### Option 1: Open locally

1. Download or clone this repository.
2. Locate `repo-analyser-advanced.html`.
3. Open the file in a modern browser such as Google Chrome or Microsoft Edge.

### Option 2: Clone with Git

```bash
git clone https://github.com/YOUR-USERNAME/repo-analyser-demo.git
cd repo-analyser-demo
```

Open `repo-analyser-advanced.html` in your browser.

Replace `YOUR-USERNAME` with your GitHub username and update the repository URL if you chose a different repository name.

## Files

```text
repo-analyser-demo/
├── README.md
└── repo-analyser-advanced.html
```

The HTML file contains the page structure, styles, and client-side interactions.

## Example Prompts

Try prompts such as:

- “Suggest improvements to this project.”
- “Find potential bugs in the code.”
- “Plan a contact form feature.”
- “Review security best practices.”

The current prototype responds with demonstration content rather than performing real AI analysis.

## Planned Enhancements

- Connect a GitHub repository and retrieve its files securely.
- Integrate a Microsoft Foundry agent for real code analysis.
- Add repository authentication and permission handling.
- Provide evidence-based findings with file paths and line references.
- Support safe feature suggestions and review workflows.
- Add automated tests and exportable analysis reports.

## Technology Stack

- HTML5
- CSS3
- JavaScript

No build step is required for the standalone frontend prototype.

## Security Notes

- Do not add access tokens, API keys, passwords, or other secrets to this repository.
- A real GitHub/Microsoft Foundry integration should use secure authentication and keep credentials out of client-side code.
- Treat all sample findings and scores as illustrative until live analysis is connected.

## License

No license has been specified yet. Unless a license is added, normal copyright rules apply and others should not assume they have permission to reuse or redistribute this project.
