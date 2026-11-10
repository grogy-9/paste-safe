# Paste Safe

A free, browser-only tool that flags personal details (emails, phone numbers, IBAN-like and PPS-like numbers) before you paste text into an AI chat.

**Not a legal or GDPR compliance tool.** It uses simple pattern matching, can miss things, and can flag things that are fine. Always check text yourself before pasting it anywhere.

## How it works

- Open `index.html` in a browser.
- Paste text (use fake sample details for demos), press **Scan**, then **Replace flags with placeholders**.
- Everything runs locally in your browser. Nothing is uploaded.

## What it looks for (v0.1)

- Email addresses
- Irish-style mobile numbers (08x...) and +353 forms
- IBAN-like strings
- Long digit runs that look like account or card numbers
- PPS-like patterns (format guess only)
- Street/address cue phrases
- Words like "password" or "account number" near digits

Part of the "AI Made Simple" experiment by Kuo-yuen Hui. Licensed under MIT.
