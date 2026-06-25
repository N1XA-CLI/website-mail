# Nexora — Email Directory Site

A single-file static website that looks like a normal business site but has 100 sample email addresses embedded throughout its pages and HTML source.

## Purpose

The site simulates a real company web presence with multiple pages and sub-pages, each naturally containing email addresses in the page content and as HTML comments. Useful as a test fixture for email scrapers, crawlers, or parser tools.

## Structure

- **Home** → 5 top-level links (About, Services, Blog, Contact, Support)
- Each section has **2–5 sub-pages** (e.g. `/services/web`, `/blog/tech`)
- Emails are spread across all pages — some visible on screen, some only in the HTML source as comments

## Emails

100 addresses in the format `email_N@domain.com` across 10 domains:
`gmail.com`, `yahoo.com`, `hotmail.com`, `outlook.com`, `protonmail.com`, `icloud.com`, `aol.com`, `mail.com`, `zoho.com`, `yandex.com`

## Usage

Open `index.html` in any browser. No server or dependencies needed.

## Live Demo

[https://n1xa-cli.github.io/website-mail/](https://n1xa-cli.github.io/website-mail/)

## Credit

Built by **Claude** (Anthropic) — an AI assistant. Generated entirely from a conversation prompt as part of an open source dev workflow. Feel free to fork, modify, and use it however you like.
