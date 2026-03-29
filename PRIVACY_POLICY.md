# Prompt Studio — Privacy Policy

**Last updated: March 28, 2026**

## Overview

Prompt Studio is a Chrome extension that helps users craft AI image generation prompts. We are committed to protecting your privacy and being transparent about how data is handled.

## Data Collection

Prompt Studio does **not** collect, transmit, or store any personal data on external servers. Specifically:

- **No analytics or tracking** — we do not use any analytics services, cookies, or tracking pixels.
- **No user accounts** — the extension does not require registration or login.
- **No data sold or shared** — we never sell, share, or transfer user data to third parties.

## Data Stored Locally

The extension stores the following data **locally on your device** using Chrome's built-in storage API (`chrome.storage.local`):

- Your prompt text and selected presets (so they persist between sessions)
- Your settings preferences (chosen AI provider, model selection, max tokens, custom system prompt)
- Your API key, if you choose to enter one

This data **never leaves your device** except when making API calls to the AI provider you have configured (see below).

## External API Calls

If you configure an AI provider in Settings (such as Google Gemini, OpenAI, OpenRouter, or Anthropic), the extension will send your prompt text and selected presets to that provider's API when you click the "Beautify" button. 

- API calls are made **directly from your browser** to the provider's servers. No data passes through our servers.
- Your API key is sent only to the provider you selected, as required for authentication.
- We encourage you to review the privacy policy of your chosen AI provider.

If no API key is configured, the extension operates entirely offline using local beautify rules.

## Permissions

The extension requests only two Chrome permissions:

- **sidePanel** — to display the prompt editor as a browser side panel
- **storage** — to save your settings and prompt state locally

## Changes

We may update this privacy policy from time to time. Any changes will be reflected in the "Last updated" date above.

## Contact

For questions about this privacy policy, contact: [your-email@example.com]
