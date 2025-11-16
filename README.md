# AI-Coding-Tools
Any model features strong code understanding, multi-turn dialogue, and reasoning capabilities.

Important: Clear Anthropic Environment Variables Before Configuration
Before configuring, ensure you clear the following Anthropic-related environment variables to avoid conflicts with Any Provider API:
ANTHROPIC_AUTH_TOKEN
ANTHROPIC_BASE_URL


Edit or create the Claude Code configuration file located at ~/.claude/settings.json. In this file, add or update the env field as shown below.

Set <ANY_API_KEY> to the API key obtained from Any model provider .

{
  "env": {
    "ANTHROPIC_BASE_URL": "https://example.com/anthropic",
    "ANTHROPIC_AUTH_TOKEN": "<ANY_API_KEY>",
    "API_TIMEOUT_MS": "3000000",
    "CLAUDE_CODE_DISABLE_NONESSENTIAL_TRAFFIC": 1,
    "ANTHROPIC_MODEL": "ANY",
    "ANTHROPIC_SMALL_FAST_MODEL": "ANY",
    "ANTHROPIC_DEFAULT_SONNET_MODEL": "ANY",
    "ANTHROPIC_DEFAULT_OPUS_MODEL": "ANY",
    "ANTHROPIC_DEFAULT_HAIKU_MODEL": "ANY"
  }
}

After completing the configuration, navigate to your working directory and run the claude command in the terminal to start using Claude Code. After startup, select Trust This Folder to allow it to access the files in your folder 
You can now start using Claude Code for development.
