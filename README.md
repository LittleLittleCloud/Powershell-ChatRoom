# The [ChatRoom](https://github.com/LittleLittleCloud/Agent-ChatRoom) for powershell agents

This repo contains the quick-start configuration for powershell agents.

<img src="asset/switch-theme.gif" alt="drawing" width="100%" align="center"/>

## Quick Start

1. Clone this repo and navigate to the root directory of the repo.

2. Run the following command to restore dotnet tools

```bash
dotnet tool restore
```

3. Replace the `openai-api-key` in both [client.json](client.json) and [server.json](powershell.json) with your own OpenAI API key.

4. Start chatting with powershell agents in the `General` channel!

```bash
dotnet chatroom -c client.json
```

## Further Reading
- [Agent ChatRoom](https://github.com/LittleLittleCloud/Agent-ChatRoom)
- [AutoGen.Net](https://microsoft.github.io/autogen-for-net/)
