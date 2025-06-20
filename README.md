# GitHub Copilot Extension Workshop

This is the project for the GitHub Copilot Extension Workshop. It contains the code and resources needed to build a simple VS Code extension that uses GitHub Copilot.

## Prerequisites

Before attending the workshop, please ensure you have the following:

- **A GitHub account**
  (Obvious, but worth mentioning!)

- **Signed up for GitHub Copilot**
  [GitHub Copilot](https://github.com/features/copilot) has a free tier and is also free for open source maintainers.

- **Node.js LTS installed (Node 22 at the moment)**

  [Download Node.js](https://nodejs.org/en/download)

  Alternatively, you can use [nvm](https://github.com/nvm-sh/nvm) (Node Version Manager) to install and manage Node.js versions easily.

- **Visual Studio Code installed**
  [Download VS Code](https://code.visualstudio.com/download)
  (You can use another editor, but you’ll need to handle port forwarding yourself, as it’s built into VS Code.)

  ## Workshop Setup
- **Fork this repository**
- **Clone your fork at the first step of the workshop**
  ```bash
  git clone git@github.com:<your-username>/copilot-extension-workshop.git && cd copilot-extension-workshop && git checkout tags/step-1 -b step-1
  ```
- **Install dependencies**
  ```bash
  npm install
  ```

## Resources

- [Slide deck for the workshop](https://docs.google.com/presentation/d/e/2PACX-1vTHnYQJZ3E-sXHPot1qSmZxXf40voLGtDzgTSuIg2WyjCFi8nSMeNp6StIqlNNs9qcpX9H-Ze9aPu5_/pub?start=false&loop=false&delayms=5000)
- [Official GitHub Copilot documentation](https://docs.github.com/en/copilot)
- [nickytonline/copilot-extension-template](https://github.com/nickytonline/copilot-extension-template)
- [Creating a GitHub Copilot Extension: A Step-by-Step Guide](https://www.nickyt.co/blog/creating-your-first-github-copilot-extension-a-step-by-step-guide-28g0/)
- [Building an Ollama-Powered GitHub Copilot Extension](https://www.nickyt.co/blog/building-an-ollama-powered-github-copilot-extension-2l4n/)
- [VS Code specific Copilot Extensions](https://code.visualstudio.com/docs/copilot/copilot-extensibility-overview)
- [GitHub Open Source Spotlight: Building Copilot Extensions with Nick Taylor](https://www.youtube.com/watch?v=zE-O-3CGcEc&list=PLcR4ZgxWXeIAa0VXPJQ7fgXkx73A5TeGU&index=2)
- [Building a Copilot skillset for your Copilot Extension](https://docs.github.com/en/copilot/building-copilot-extensions/building-a-copilot-skillset-for-your-copilot-extension)
- [Building a Copilot agent for your Copilot Extension](https://docs.github.com/en/copilot/building-copilot-extensions/building-a-copilot-agent-for-your-copilot-extension)
- [GitHub Copilot: The agent awakens](https://github.blog/news-insights/product-news/github-copilot-the-agent-awakens/)