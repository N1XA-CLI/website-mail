# Nexora — Email Directory Site

A static multi-page website that looks like a normal business site but has 100 sample email addresses embedded throughout its pages and HTML source.

## Purpose

The site simulates a real company web presence across 22 separate HTML files organised into actual folders and sub-folders. Each page is a directory listing (Name / Last Modified / Size / Description) with real relative links between pages. Useful as a test fixture for email scrapers, crawlers, or parser tools that need to follow links across a real file structure.

## File Structure

```
index.html
about/
  index.html
  team/index.html
  history/index.html
services/
  index.html
  web/index.html
  seo/index.html
  cloud/index.html
  design/index.html
  analytics/index.html
blog/
  index.html
  tech/index.html
  business/index.html
  news/index.html
contact/
  index.html
  sales/index.html
  support/index.html
  press/index.html
support/
  index.html
  faq/index.html
legal/
  privacy/index.html
  terms/index.html
```

## Emails

100 addresses in the format `email_N@domain.com` across 10 domains:
`gmail.com`, `yahoo.com`, `hotmail.com`, `outlook.com`, `protonmail.com`, `icloud.com`, `aol.com`, `mail.com`, `zoho.com`, `yandex.com`

Emails appear both as visible content on the page and as HTML comments in the source.

## Usage

Extract the ZIP and open `index.html` in any browser. No server or dependencies needed. Works on GitHub Pages as-is.

## Live Demo

[https://n1xa-cli.github.io/website-mail/](https://n1xa-cli.github.io/website-mail/)

## Credit

Built by **Claude** (Anthropic) — an AI assistant. Generated entirely from a conversation prompt as part of an open source dev workflow. Feel free to fork, modify, and use it however you like.