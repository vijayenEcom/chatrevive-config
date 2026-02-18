# Privacy Policy — ChatRevive

Effective date: 18 Feb 2026

ChatRevive is a Chrome extension that helps you “revive” large ChatGPT conversations by creating a new ChatGPT chat and pasting a minimized context snapshot so you can continue without slowdowns.

## Data We Collect
ChatRevive does **not** collect, transmit, sell, or share personal data.

The extension may store limited usage information **locally on your device** using Chrome’s local storage APIs:
- Daily usage counters (e.g., number of revives used today)
- Local debug logs (success/failure timestamps)

This local data never leaves your device.

## Chat Content
ChatRevive reads the currently visible chat content on ChatGPT pages only to construct a minimized “revive” prompt. This prompt is then pasted into a new ChatGPT chat tab.

ChatRevive does not send your chat content to any third-party server. The content remains in your browser and is sent only to ChatGPT when you submit the prompt in the new tab.

## Remote Configuration (Kill Switch)
ChatRevive fetches a small remote JSON configuration file from a public URL (GitHub raw) to enable/disable the extension temporarily (“kill switch”) for safety and stability.

This request does not include any personal identifiers or chat content.

## Permissions Explanation
ChatRevive uses the following Chrome permissions:
- **storage**: store local daily usage counters and local debug logs
- **tabs**: open a new ChatGPT tab for the revived chat
- **scripting**: inject code into the new ChatGPT tab to paste the revive prompt and click Send

ChatRevive is designed to run only on ChatGPT domains.

## Changes
If this policy changes, the updated version will be published at the same URL.

## Contact
For questions, contact: vijayenEcom (GitHub)
