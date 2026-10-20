# BuildersAlpha Coach

Coaches you through your BuildersAlpha exercise: it tells you where you are, sends your work for feedback when you ask, and gives hints.

## Use

Open your exercise in BuildersAlpha, choose Open Claude here, and press Enter. Claude answers with the exercise you are on. Say "check my work" when you want feedback.

## What data is sent

The plugin adds a skill (instructions for Claude) and points Claude at the BuildersAlpha connector at https://app.buildersalpha.com/mcp/coach. When you ask Claude to check your work, Claude sends the text of your own work for that exercise (your prompt, the reply, or the file text you are working on) to BuildersAlpha, together with the name of the Claude model and the version of this skill. Claude can also send a short note about what you just did while an exercise is open. Nothing is sent when you are not working on a BuildersAlpha exercise. You sign in to the connector yourself, with your own BuildersAlpha account, and you can remove the connector or this plugin at any time.

Version 1.0.0.
