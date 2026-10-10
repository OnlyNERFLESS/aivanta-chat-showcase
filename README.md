<p align="center">
  <img src="media/aivanta-logo.svg" width="120" alt="Aivanta Chat logo">
</p>

<h1 align="center">Aivanta Chat</h1>

<p align="center">
  A chat assistant for WordPress that guides visitors through your own forms<br>
  and hands every request to your team: inbox, WhatsApp, Telegram and more.
</p>

<p align="center">
  <b>Free 1.4.0</b> · <b>Pro add-on 1.0.0</b> · WordPress 5.3+ · PHP 7.2+ · English, Persian, Arabic
</p>

---

> **This repository is a showcase.** It documents the plugin and its progress.
> The source code is private. If you'd like Aivanta Chat on your site, see [Get it](#get-it).

<p align="center">
  <img src="media/chat-desktop.png" width="380" alt="The chat window with contact buttons and a bottom bar">
  &nbsp;&nbsp;
  <img src="media/phone-open.png" width="260" alt="The chat on a phone">
</p>

## What it does

- **Guided conversations.** Visitors pick what they need (product information, a quote, a word with your team) and the chat walks them through the steps you defined.
- **A form builder, not a script.** Build any flow from choices, typed answers, form fields, quantities and contact details. Reorder, duplicate or switch forms off without touching code.
- **Every channel you use.** WhatsApp, Telegram, Messenger, Instagram, LinkedIn, Discord, GitHub, email or a custom link, each with its own icon.
- **Nothing gets lost.** Every request is saved in WordPress first, then emailed, and WhatsApp or email can open with the whole request already written.
- **Built for real sites.** The chat renders in its own isolated layer, so theme CSS can't break it and it can't break the theme. On phones it sits under your menu until it's opened, then above everything.

## Free and Pro

The free plugin is complete on its own. Pro is an add-on that installs beside it.

| | Free | Pro |
|---|:---:|:---:|
| Unlimited forms and requests | ✓ | ✓ |
| Contact buttons and bottom bar with brand icons | ✓ | ✓ |
| Requests saved in WordPress and emailed | ✓ | ✓ |
| Colour themes, button shapes, phone settings, Custom CSS | ✓ | ✓ |
| Persian, Arabic and every WordPress language | ✓ | ✓ |
| AI answers with your own Claude or OpenAI key | | ✓ |
| Ready answers with synonyms and typo tolerance | | ✓ |
| Products & categories with pictures | | ✓ |
| Five button animations | | ✓ |
| No "Powered by" link (opt-in on Free) | | ✓ |

<img src="media/plans.png" alt="The License page with the Free and Pro plans">

Pro is unlocked with a license key that is checked on your own server: no account, no tracking, nothing sent anywhere. If a subscription ends, Pro switches off and Free keeps working, with everything you set up kept for renewal.

## Contact channels

<img src="media/contact-buttons.png" alt="Choosing which contact buttons the chat offers">

Fill in the channels you use, then choose which appear as **contact buttons** (when a visitor wants a person, after a request, and when the chat has no answer) and which three sit in the **bottom bar**.

<img src="media/channels.png" alt="Channel addresses, each with its brand icon">

## Your language

<p align="center">
  <img src="media/persian-chat.png" width="320" alt="The chat in Persian, right to left">
</p>

<img src="media/persian-dashboard.png" alt="The dashboard in Persian, right to left">

The plugin follows the language set in WordPress. Persian and Arabic ship complete, with right-to-left layout and the Vazirmatn font, and the plugin can be translated into any other language. Arabic-speaking visitors on a site in another language get Arabic replies.

## The dashboard

<img src="media/overview.png" alt="Overview: requests per day, top forms, and a setup checklist">

An overview with requests per day, top forms, products and countries, and a checklist that shows what still needs setting up.

### Appearance with a live preview

<img src="media/appearance.png" alt="Appearance settings with a live preview on a light page, a dark page and a phone">

Every change shows instantly on a light page, a dark page and a phone, drawn with the same stylesheet visitors get.

### Shapes and animations

<img src="media/button-templates.png" alt="Shape and animation picker cards, each with a live demo">

Three shapes on Free. Pro adds five animations: Spinning border, Floating, Ripple rings, Comet and Hello wave.

### Forms

<img src="media/forms.png" alt="The form builder showing the steps of a quote form">

### Custom CSS with a built-in guide

<img src="media/custom-css.png" alt="The Custom CSS box and its list of selectors with Insert buttons">

## Security and privacy

- Every post from the chat carries a short-lived token signed with the site's own keys. Request tokens are single-use.
- Posts from other websites, oversized bodies and non-JSON bodies are refused before anything is read.
- Limits per visitor and daily ceilings for the whole site, for requests and for AI answers.
- Answers are checked against the saved form on the server. Prices and totals are never taken from the browser.
- The AI key (Pro) is encrypted at rest and never sent to browsers.
- IP addresses are used only for rate limits and never stored. WordPress's Export and Erase Personal Data tools cover chat requests.
- The free plugin passes WordPress's official Plugin Check with no errors.

## Progress

See the [changelog](CHANGELOG.md) for what changed in each release.

## Get it

Aivanta Chat is **available on request**. For pricing, a demo, or a setup on your site, email
**[Chaosmp81@gmail.com](mailto:Chaosmp81@gmail.com)**.

---

<p align="center">Designed and built by <b>NERFLESS</b> · © 2026</p>
