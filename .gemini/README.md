# Google Gemini

As of 16 Nov 2025, Gemini Code Assist extension in VS Code does not provide an intuitive way for the reearch-plan-implement workflow. Custom commands must be defined in `.vscode/settings.json` under `geminiCodeAssist.customCommands`.

Gemini CLI supports having custom commands in `.gemini/commands/`, but the output is not as accurate as GitHub Copilot Chat in agent mode (using Claude Sonnet 4 onwards).

We recommend using GitHub Copilot Chat in agent mode for a more seamless experience with the research-plan-implement workflow.
