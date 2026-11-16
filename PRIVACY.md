# Prompt Deck Privacy Policy

**Effective date:** November 15, 2026
**Extension:** Prompt Deck (Chrome Web Store ID `bbfipngdafknkiojjgmpjpfjiecjlkpb`)
**Developer:** simba13231

This policy explains what information the Prompt Deck Chrome extension handles, where it is kept, and when any of it leaves your browser.

## Summary

- Prompt Deck has **no account system, no server of its own, no analytics, no ads and no tracking**.
- Everything you create in Prompt Deck is stored **locally in your browser** (`chrome.storage.local`). It is not synced to any cloud service.
- Data leaves your browser only in the two cases described below: when **you** choose to use the optional AI "Enhance" feature (sent to Google's Gemini API), and a daily **update check** that downloads a version number from GitHub (no personal data is sent).
- We do not sell, rent or share your data.

## Information Prompt Deck stores on your device

Prompt Deck stores the following only in your browser's local extension storage:

- **Your prompt library:** prompts, titles, tags, folders, collections, favorites and pins.
- **Prompt tools data:** variable defaults and remembered values (only if you opt in), Builder blocks, project profiles, workflows and workflow run results you paste in.
- **History and recovery:** revision history of edited prompts, temporary editor drafts (kept up to 7 days) and automatic local backups (the most recent 8).
- **Usage statistics:** which prompt was used, when, whether it was copied or inserted, and the **hostname** of the AI site it was used on (for example `chatgpt.com`). This is used only to show "Recent" and usage stats inside the extension.
- **Settings**, including your keyboard shortcuts and, if you provide one, your **Gemini API key**.
- **Update-check status** (latest available version and when it was checked).

This information is never transmitted to the developer.

## How Prompt Deck works on AI websites

Prompt Deck runs on supported AI chat sites (such as ChatGPT, Claude, Gemini, Grok, Perplexity, Copilot, DeepSeek, Mistral and others listed in the extension's manifest) so it can show its panel and insert a prompt into the page's text box when you click Insert. It does not read, collect or store your conversations on those sites. Copying a prompt uses your system clipboard only when you click Copy.

## When data leaves your browser

1. **AI Enhance (optional, user-initiated).** If you add your own Gemini API key and click Enhance, Prompt Deck sends the prompt text you are enhancing, your chosen enhancement options, and your API key directly from your browser to Google's Gemini API (`generativelanguage.googleapis.com`). The extension shows a preview of the request before it is sent. Nothing is sent unless you request it. Google processes that request under its own terms and privacy policy: <https://policies.google.com/privacy> and <https://ai.google.dev/gemini-api/terms>.
2. **Update check.** Once a day, and when you click "Check for updates", Prompt Deck downloads a public version file from GitHub (`raw.githubusercontent.com`) to see whether a newer version exists. No prompts, settings or personal information are included in this request. As with any web request, GitHub may receive standard technical information such as your IP address; see GitHub's privacy statement: <https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>.

Prompt Deck has no other network connections.

## Exports and imports

You can export your library to a JSON file and import one back. Exports are created only when you ask, are saved where you choose, and **exclude your API key**. What you do with an exported file is up to you.

## Sharing and sale of data

The developer does not collect, receive, sell, rent or share your data with anyone. The only third party that ever receives your content is Google (Gemini API), and only when you explicitly use the Enhance feature with your own key.

## Chrome Web Store Limited Use

The use of information received by Prompt Deck complies with the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq), including the Limited Use requirements. Specifically, user data is used only to provide the extension's user-facing features; it is not transferred to third parties except as needed to provide a feature you request (Gemini Enhance); it is not used for advertising; it is not used to determine creditworthiness or for lending purposes; and no human reads it.

## Retention and deletion

Your data stays in your browser until you delete it. You can delete individual prompts, clear usage statistics and revisions from Settings, or remove all Prompt Deck data at once by uninstalling the extension. Revision history is capped at 20 versions per prompt, backups at the latest 8, and drafts expire after 7 days.

## Security

Your data is protected by your browser's built-in extension storage. Because it lives on your device, anyone with access to your browser profile may be able to see it. Your API key is masked in the settings field and excluded from exports.

## Children

Prompt Deck is not directed to children under 13, and the developer does not knowingly collect any information from children.

## Changes to this policy

If this policy changes, the updated version will be published at this same address with a new effective date.

## Contact

Questions about this policy: open an issue at <https://github.com/simba13231/prompt-deck-privacy/issues> or email the developer address shown on the Chrome Web Store listing, hartayk30@gmail.com.
