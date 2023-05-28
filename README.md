## Disclaimer!


This plugin is based on https://github.com/smol-ai/developer

Thank you all for using, feel free to apply PR's there! :)





## Smol-Ai-Developer Plugin for Auto-GPT

This plugin allows you to use Auto-GPT with the Smol-Ai-Developer to generate great code and text.

# Running Auto-GPT with this plugin

To run this plugin, zip this repo and put it under Auto-GPT/plugins/
To run it, add the following to your start command:
```
For non docker:
python -m autogpt --install-plugin-deps

For Docker:
docker-compose run --rm auto-gpt --install-plugin-deps
```

# Auto-GPT-Plugins

Plugins for Auto-GPT

Clone this repo into the plugins direcory of [Auto-GPT](https://github.dev/Significant-Gravitas/Auto-GPT)

Then zip it:

To download it directly from your Auto-GPT directory, you can run this command on Linux or MacOS:

curl -L -o ./plugins/Auto-GPT-Plugins.zip https://github.com/Wladastic/Auto-GPT-Smol-Plugin/archive/refs/heads/master.zip
Or in PowerShell:

Invoke-WebRequest -Uri "https://github.com/Wladastic/Auto-GPT-Smol-Plugin/archive/refs/heads/master.zip"     -OutFile "./plugins/Auto-GPT-Smol_Ai.zip"


For interactionless use, set `ALLOWLISTED_PLUGINS=SmolPlugin` in your `.env`

| Plugin   | Description                                                                                                         |
|----------|---------------------------------------------------------------------------------------------------------------------|
| Smol AI Developer | AutoGPT is capable of creating real projects now thanks to https://github.com/smol-ai/developer. |

