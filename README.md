
# Playwright Cucumber Copilot

**Playwright Copilot** is a Visual Studio Code extension that accelerates BDD (Behavior Driven Development) testing with AI-generated code suggestions.  
It allows users to input or copy-paste BDD scenarios, select an OpenAI model, and instantly generate code for step definitions and Page Object Model (POM) implementations tailored to Playwright with Cucumber.

Playwright Copilot utilizes the novel **"Few-shot chain"** prompt technique introduced by us in our research paper – [IEEE Paper](https://ieeexplore.ieee.org/abstract/document/10812696).  
By leveraging this prompt technique, Playwright Copilot shows enhanced code generation accuracy and maintainability compared to GPT-3.5, GPT-4, and GitHub Copilot.

**Author(s)**: Suresh Babu Nettur.

---

## Important Notes and Disclaimers

1. OpenAI and ChatGPT can make mistakes—verify important outputs before use.  
2. This tool supports only **BDD format** scenarios.  
3. Review the Privacy Policy and Terms of Use.  
4. **API Key Safety**: Never expose your OpenAI API key.  
5. **Ethical Use Only**: Strictly avoid unethical, illegal, or harmful uses.  
6. **No Sensitive Information**: Do not provide any Personally Identifiable Information (PII) or Protected Health Information (PHI).  
7. **Model Limitations**: This tool uses GPT models via OpenAI API. Its limitations apply here too.

---

## Privacy Policy

This extension does **not** collect, store, or share any personal data.  
For questions, please contact us via GitHub or the Marketplace.

---

## Terms of Use

By using this extension, you agree to:

1. Use the extension “as is” with no warranties.  
2. The authors are not liable for any damages caused.  
3. Comply with all applicable laws while using this extension.

---

## Usage Guidelines

- **Ethical Use**: Generate code, documentation, and test scenarios responsibly.
- **Prohibited Activities**: Never use the tool for illegal, unethical, or harmful actions.
- **No Sensitive Data**: Do not input or share PII, PHI, or other sensitive content.
- **User Responsibility**: You are accountable for how you use this tool.
- **Model Behavior**: Outputs depend on OpenAI models and may have inconsistencies.

---

## Features

- **AI-Powered Code Generation**: Get instant step definitions and POMs from BDD scenarios.
- **Model Flexibility**: Choose from various OpenAI models for your desired output quality.
- **Code Preview Panel**: See suggestions in real-time before copying or modifying.
- **BDD Workflow Simplification**: Greatly reduces time spent on manual test scripting.

---

## Requirements

Before using Playwright Copilot, ensure the following are set up:

- **VS Code**: Download from https://code.visualstudio.com/
- **Node.js**: Required for interaction with Playwright. Get it from https://nodejs.org/
- 
  ```bash

- **Cucumber Integration for Playwright**:  
  For those setting up initially, you can clone and set up the boilerplate repo:   
  [Playwright Cucumber JS Boilerplate](https://github.com/karpurapus/playwright-cucumber-js-boilerplate.git)  
  ```bash
  # Clone the repo
  git clone https://github.com/karpurapus/playwright-cucumber-js-boilerplate.git

  # Navigate into the project directory
  cd playwright-cucumber-js-boilerplate

  # Install dependencies
  npm install

  # Run tests
  npm test
  ```
- **OpenAI API Access**: Get your API key at https://openai.com/

---

## Installation

1. Launch Visual Studio Code.  
2. Go to the **Extensions** view.  
3. Search for **Playwright Copilot** and click **Install**.  
4. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS), then run `Playwright Copilot` to activate.


## Configuration

**Set OpenAI API Key**:  
Use `Ctrl+Shift+P`, search for `Set API Key`, and enter your OpenAI API key.

**Select OpenAI Model**:  
Use the dropdown in the extension to choose between supported OpenAI models (GPT-3.5, GPT-4, etc.).

---

## Usage

1. **Input BDD Scenario**: Paste or write a scenario using Gherkin syntax.  
2. **Choose Model**: Select the model appropriate for your scenario.  
3. **Generate Code**: Click `Generate Code` to receive step definitions and POM.  
4. **Copy & Use**: Copy the code and paste it into your Playwright project.

You can integrate the generated code into your existing Playwright-Cucumber test framework.  
If you're starting from scratch, one can use the boilerplate at [https://github.com/karpurapus/playwright-cucumber-js-boilerplate.git](https://github.com/karpurapus/playwright-cucumber-js-boilerplate.git).

### Example

```gherkin
Scenario: User logs into the system
  Given the user is on the login page
  When the user enters valid credentials
  Then the user should be redirected to the dashboard
```

Select a model → Click **Generate Code** → Get complete step definitions and POM Java Script code.

---

## Known Issues

1. **API Key May Not Persist**: Re-enter using `Set API Key` if the key resets after restart.
2. **Inconsistent Outputs**: Try switching models if you encounter unusual suggestions.

---

## License

This project is licensed under:

- **Apache License 2.0**


You are free to:
- **Share**: Copy and redistribute
- **Adapt**: Remix and build upon it  
As long as you:
- **Attribute** properly

---

## Disclaimer

- This tool is for **ethical development and testing** only.  
- Avoid entering any **PII** or **PHI**.  
- You are responsible for how you use the extension.
- Playwright Copilot is an independent projects and is not affiliated with, endorsed by, or sponsored by Microsoft Playwright.

---

## Support

For questions, issues, or feature requests contact us via the Visual Studio Code Marketplace.
