# Discord Bot Legal Pages Template

This repository is a ready-to-use template for Discord bot developers who need public legal pages for their bot.
It contains a Terms of Service page and a Privacy Policy page in HTML format, designed to be hosted publicly with GitHub Pages.
The purpose of this repository is to help bot owners quickly create legal document links they can provide to Discord in the Developer Portal or App Directory submission process.

## What this repository includes

This repository usually contains:

- `index.html`
- `terms-of-service.html`
- `privacy-policy.html`
- `README.md`

### File overview

#### `index.html`
This is the homepage of the legal site.  
It usually contains links to the Terms of Service and Privacy Policy pages.

#### `terms-of-service.html`
This file contains the Terms of Service template for a Discord bot.

#### `privacy-policy.html`
This file contains the Privacy Policy template for a Discord bot.

#### `README.md`
This file explains what the repository is, how to use it, and what needs to be edited before publishing.

## Who this repository is for

This repository is for:

- Discord bot developers
- people submitting a bot to Discord
- people who need public policy links for their app
- developers who want a simple GitHub Pages setup
- beginners who want a legal page template they can edit

## What this repository does

This repository gives users a simple way to:

1. copy the template
2. edit the legal placeholders
3. publish the files with GitHub Pages
4. get public links
5. submit those links to Discord

## Important note before using

This repository is a template.  
It is not final legal advice.

Every bot is different.

Some bots collect no stored data.  
Some bots store user IDs, guild IDs, commands, moderation logs, analytics, or message content.  
Because of this, every user must review and edit the files before publishing them.

Do not publish the templates without replacing the placeholder sections.

## What users need to edit

Before publishing, users should replace all placeholder text such as:

- `[Bot Name]`
- `[Owner Name]`
- `[Organization Name]`
- `[Contact Email]`
- `[Support Server Link]`
- `[Country/State]`
- `[Location]`
- `[Effective Date]`
- `[Last Updated Date]`
- `[Data Retention Period]`
- feature descriptions
- payment terms if applicable
- liability cap amount if applicable

Users should also remove any section that does not apply to their bot.

## Recommended use

This repository is best used as a public legal site for one Discord bot or as a reusable base template for multiple bot owners.

A user can either:

- fork this repository
- clone this repository
- download the files and upload them into their own repository

## How to use this repository

### Step 1
Create a new public GitHub repository.

Example names:

- `bot-legal`
- `discord-bot-legal`
- `mybot-policies`

### Step 2
Upload or paste the files from this template into the repository.

### Step 3
Edit the HTML files and replace all placeholder values with real details.

### Step 4
Enable GitHub Pages.

Go to:

`Settings > Pages`

Then choose:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/root`

### Step 5
Save the settings and wait for GitHub Pages to publish the site.

### Step 6
Open the public URLs.

Example:

- `https://yourusername.github.io/your-repository-name/`
- `https://yourusername.github.io/your-repository-name/terms-of-service.html`
- `https://yourusername.github.io/your-repository-name/privacy-policy.html`

### Step 7
Paste the Terms of Service link and Privacy Policy link into the Discord Developer Portal.

## Example repository structure

```text
discord-bot-legal/
├── index.html
├── terms-of-service.html
├── privacy-policy.html
└── README.md
