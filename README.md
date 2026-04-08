# Discord Bot Legal Pages Template

This repository is a reusable template for Discord bot developers who need public legal pages for their bot.

It includes:

- a homepage
- a Terms of Service page
- a Privacy Policy page
- setup instructions

These files are meant to be hosted publicly with GitHub Pages so developers can submit the public links to Discord.

## Purpose of this repository

This repository exists to help Discord bot owners quickly create and publish legal documents for their bot.

Many Discord applications need public legal links, especially for developer submissions, verification, or App Directory use.

This repository gives users a simple starting point.

## What this repository includes

- `index.html`
- `terms-of-service.html`
- `privacy-policy.html`
- `README.md`

## File overview

### `index.html`
This is the homepage of the legal site.

It explains what the repository is and links to the Terms of Service and Privacy Policy pages.

### `terms-of-service.html`
This file contains the Terms of Service template.

It explains the general rules for using a Discord bot, acceptable use, service availability, liability limits, and contact information.

### `privacy-policy.html`
This file contains the Privacy Policy template.

It explains what information a bot might collect, how it might use it, how long it might keep it, and how users can request deletion or support.

### `README.md`
This file explains how the repository works and how users should edit and publish it.

## Who this repository is for

This repository is for:

- Discord bot developers
- people creating public legal pages for their bot
- beginners using GitHub Pages
- developers who want a reusable template
- users who need Terms of Service and Privacy Policy links for Discord

## What users must do before publishing

This repository is a template.

It is not ready for direct use without editing.

Each user must replace all placeholder text such as:

- `[Bot Name]`
- `[Owner Name]`
- `[Organization Name]`
- `[Contact Email]`
- `[Support Server Link]`
- `[Country/State]`
- `[Location]`
- dates
- retention periods
- payment terms
- feature descriptions
- third-party providers

Users must also remove sections that do not apply to their bot.

## Important legal note

This repository is a starting point only.

It does not replace legal advice.

Every Discord bot is different.

Some bots store no long-term data.
Some bots store user IDs, guild IDs, logs, settings, support records, message content, analytics, payments, or AI prompts.

Because of this, users are responsible for checking that the legal pages match what their bot truly does.

## Recommended repository structure

```text
discord-bot-legal/
├── index.html
├── terms-of-service.html
├── privacy-policy.html
└── README.md
