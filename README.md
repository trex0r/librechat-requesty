# 🚀 LibreChat Requesty Integration

## Quick Setup

### 1️⃣ Update Your `.env` File
Add the following lines to your LibreChat `.env` file:

```bash
CONFIG_PATH="https://raw.githubusercontent.com/trex0r/librechat-requesty/refs/heads/main/librechat-env.yaml"
REQUESTY_KEY="your_requesty_api_key_here"
```

### 2️⃣ Restart LibreChat
Simply restart LibreChat to apply the changes.

### 3️⃣ You're All Set! 🎉
Now you can use Requesty in LibreChat.

This also covers openrouter. To get that working too we can set:

OPENROUTER_KEY="x" in the .env too

The sample librechat env file also covers mcp servers.

Note that the .env needs to have NOTION_KEY in it, and that is set as follows:

https://github.com/makenotion/notion-mcp-server?tab=readme-ov-file
