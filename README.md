# BuildersAlpha plugins

This is the public plugin marketplace of BuildersAlpha. It holds one plugin, **BuildersAlpha Coach**, which coaches you through your BuildersAlpha exercises inside Claude.

## Add it in Claude

1. Open Customize, then Plugins, then Add, then Add marketplace.
2. Paste `BuildersAlpha/claude-plugins` and press Add.
3. Choose BuildersAlpha Coach and press Add. Turn on Sync automatically so updates arrive on their own.
4. Add the BuildersAlpha connector too: https://app.buildersalpha.com/mcp/coach

## What data is sent

The plugin adds a skill (instructions for Claude) and points Claude at the BuildersAlpha connector at https://app.buildersalpha.com/mcp/coach. When you ask Claude to check your work, Claude sends the text of your own work for that exercise (your prompt, the reply, or the file text you are working on) to BuildersAlpha, together with the name of the Claude model and the version of this skill. Claude can also send a short note about what you just did while an exercise is open. Nothing is sent when you are not working on a BuildersAlpha exercise. You sign in to the connector yourself, with your own BuildersAlpha account, and you can remove the connector or this plugin at any time.

This repository is generated from the BuildersAlpha application and mirrored here. Please do not edit it by hand.
