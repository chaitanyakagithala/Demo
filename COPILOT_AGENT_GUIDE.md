# Using GitHub Copilot Agent in VS Code

This guide will help you set up and use GitHub Copilot Agent in Visual Studio Code.

## Prerequisites

Before you can use GitHub Copilot Agent in VS Code, ensure you have:

1. **An active GitHub Copilot subscription** - Individual, Business, or Enterprise
2. **VS Code version 1.93.0 or later** - Download from [code.visualstudio.com](https://code.visualstudio.com/) (agents require recent versions)
3. **A GitHub account** - Connected to your Copilot subscription

## Installation Steps

### Step 1: Install GitHub Copilot Extension

1. Open VS Code
2. Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X on Mac)
3. Search for "GitHub Copilot"
4. Click **Install** on the GitHub Copilot extension

### Step 2: Install GitHub Copilot Chat Extension

1. In the Extensions view, search for "GitHub Copilot Chat"
2. Click **Install** on the GitHub Copilot Chat extension

### Step 3: Sign in to GitHub

1. After installation, you'll see a prompt to sign in to GitHub
2. Click **Sign in to GitHub**
3. Follow the authentication flow in your browser
4. Authorize VS Code to access your GitHub account

## Using Copilot Agent

### Opening Copilot Chat

- **Windows/Linux**: Press `Ctrl+Shift+I`
- **Mac**: Press `Cmd+Shift+I`
- Or click the Copilot Chat icon in the sidebar

### Available Agents

You can use different agents by typing `@` followed by the agent name:

- **@workspace** - Ask questions about your entire codebase
- **@terminal** - Get help with terminal commands
- **@vscode** - Get help with VS Code features and settings

### Example Usage

```
@workspace What does this project do?
@terminal How do I run the tests?
@vscode How do I change the color theme?
```

## Troubleshooting

### Common Issues and Solutions

| Issue | Solution |
|-------|----------|
| Copilot not responding | 1. Check your internet connection<br>2. Clear VS Code extension cache (Developer: Clear Extension Cache)<br>3. Restart VS Code |
| "Not authorized" error | Verify your GitHub account has an active Copilot subscription at github.com/settings/copilot |
| Chat not appearing | Ensure both Copilot and Copilot Chat extensions are installed and enabled |
| Sign-in issues | Sign out via Settings > Accounts, restart VS Code, then sign in again |
| Agent commands not recognized | Update VS Code to the latest version and update Copilot extensions |

### Checking for Errors

1. Open the Output panel: View > Output
2. Select "GitHub Copilot" from the dropdown
3. Look for any error messages

### Verifying Your Subscription

1. Go to [github.com/settings/copilot](https://github.com/settings/copilot)
2. Verify your subscription status is active

## Getting More Help

- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [VS Code Copilot Guide](https://code.visualstudio.com/docs/copilot/overview)
- [GitHub Copilot Community Discussions](https://github.com/orgs/community/discussions/categories/copilot)

## Still Having Issues?

If you continue to experience problems, please create an issue with the following information:

1. Your VS Code version (Help > About)
2. The exact error message you're seeing
3. Screenshots of the issue (if applicable)
4. Steps to reproduce the problem
