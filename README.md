# Adara AI Assistant — AI for Google Docs, Sheets & Slides

Draft, analyze, format, chart, and add images **without leaving your file**. Adara brings **Gemini 2.5 Pro + GPT-5** into Google Docs, Sheets & Slides so you can create faster and share higher-quality work.

**→ Install on Google Workspace Marketplace:** https://www.adaraaiassistant.com/

---

## Table of contents

* [What you can do](#what-you-can-do)
* [Install (1 minute)](#install-1-minute)
* [Quick start](#quick-start)
* [Screenshots & GIFs](#screenshots--gifs)
* [Pricing & credits](#pricing--credits)
* [Privacy & security](#privacy--security)
* [Troubleshooting](#troubleshooting)
* [FAQ](#faq)
* [Contact & support](#contact--support)
* [For admins / IT](#for-admins--it)

---

## What you can do

**Docs**

* Draft sections, emails, and summaries from a short prompt.
* Rewrite tone (friendly, concise, formal), fix grammar, and apply formatting.
* Insert stock or AI-generated images.

**Sheets**

* Clean and format data (freeze header, zebra-stripe, highlight top values).
* Analyze and summarize selections.
* Create charts (bar, line, pie) and get the right formulas (incl. Google Finance).

**Slides**

* Create slides with layouts (Title & Body, Section Header, etc.).
* Auto-add titles, bullets, and speaker notes.
* Find stock photos or generate AI images and place them correctly.

---

## Install (1 minute)

1. Open **https://www.adaraaiassistant.com/** and click **Install**.
2. Open any Google **Doc/Sheet/Slide** → **Extensions → Adara AI Assistant → Start**.
3. You’ll see the Adara sidebar on the right.

> First-time users get **free monthly credits**—no card required to try.

---

## Quick start

* **Docs:** Select a paragraph → type “Rewrite to friendly & concise.”
* **Sheets:** Select a table → type “Clean this, freeze row 1, and insert a column chart.”
* **Slides:** Type “Create a ‘Title & Body’ slide about ‘Quarterly Results’ and insert a relevant image.”

Tips:

* Pick a model in the sidebar (Gemini 2.5 Pro or GPT-5) depending on speed/creativity needed.
* You can chain actions, e.g., “Create a slide → add title → insert image.”

---

## Screenshots & GIFs

**Docs – sidebar + starter actions**
![Adara Docs Sidebar](contractdoc1.gif)

**Docs – rewrite selected text**
![Rewrite Text](rewritedocproj2.gif)

**Sheets – starter view + actions**
![Sheets Sidebar](sheetOne.gif)

**Sheets – create a chart from selection**
![Chart from Data](chartsheetp2.gif)

**Slides – open & start**
![Slides Start](slide1.gif)

**Slides – build a slide and add image**
![Slides Image Insert](projslidescotland2.gif)

---

## Pricing & credits

* Every account starts with a **free credit allocation** that **refills monthly**.
* Upgrades unlock higher limits, priority processing, advanced analysis, and **AI image generation**.
* Manage or cancel any time in the in-app billing portal (Stripe).

> You can see **remaining credits**, **usage**, and **reset date** in the profile area inside the add-on.

---

## Privacy & security

* Adara runs inside Google Docs/Sheets/Slides.
* We only process the text/data you send to the assistant for each request.
* External calls are made to model providers (Gemini/OpenAI) and optional image sources (e.g., stock images) solely to fulfill your requests.
* We don’t sell personal data. See our full Privacy Policy on our site for details.

---

## Troubleshooting

**I installed it, but don’t see the sidebar.**
Extensions → **Adara AI Assistant → Start**. If you’re on Google Workspace (work/school), your admin may need to approve Marketplace apps.

**The add-on says I’m out of credits.**
Open the profile panel to view remaining credits and reset date. You can also upgrade for higher limits.

**Images didn’t insert.**
Make sure your cursor is placed in the document/slide and that you granted file permissions when prompted. Try again.

**Slides layout didn’t change.**
Ask specifically: “Change this slide to **Title & Body** layout, then add the title ‘Quarterly Results’ and insert a relevant image.”

---

## FAQ

**Does it work with personal Gmail and Workspace accounts?**
Yes. On managed (work/school) accounts, your domain admin might need to allow Marketplace apps.

**Which models are available?**
You can pick **Gemini 2.5 Pro** or **GPT-5** per request. Choose what fits best for speed, analysis depth, or creativity.

**Can I use it for charts & formulas in Sheets?**
Yes—ask for summaries, highlights, and charts, or say “Write a formula that…” (including Google Finance).

**How do billing and cancellations work?**
Payments are handled by Stripe. You can manage or cancel your plan at any time from the in-app billing portal.

**Do you store my documents?**
We don’t store your full documents. Requests are processed to generate outputs; see our Privacy Policy for specifics.

---

## Contact & support

* Email: **[hello@adaraaiassistant.com](mailto:hello@adaraaiassistant.com)**
* Website: **[https://adaraaiassistant.com](https://adaraaiassistant.com)**
* Twitter/X: **@adarassistant**
* Feature request or bug? Open a GitHub **Issue**.

---

## For admins / IT

**Scopes requested** (Apps Script):

* `…/spreadsheets.currentonly`
* `…/documents.currentonly`
* `…/presentations.currentonly`
* `…/script.container.ui`
* `…/script.external_request`
* `…/userinfo.email`

**Outbound endpoints (whitelisted):**

* Stripe API (`https://api.stripe.com/`)
* Firestore (`https://firestore.googleapis.com/`)
* Gemini (`https://generativelanguage.googleapis.com/`)
* OpenAI (`https://api.openai.com/`)
* Images/stock sources (e.g., Pexels/Unsplash)
* Google APIs as needed for Workspace operations

**Tech notes**

* Google Apps Script (V8).
* Firestore for credit tracking.
* Stripe for subscription management.
* Optional Pexels/Unsplash for stock images.

> Trademarks: Google Workspace, Google Docs, Google Sheets, and Google Slides are trademarks of Google LLC. OpenAI and GPT are trademarks of OpenAI. Gemini is a trademark of Google LLC. Adara AI Assistant is not affiliated with or endorsed by Google or OpenAI.

---

### Badges (optional)

[![Marketplace](https://img.shields.io/badge/Install-Google%20Workspace%20Marketplace-4285F4)]([{MARKETPLACE_LINK}](https://www.adaraaiassistant.com/))
![Made with Apps Script](https://img.shields.io/badge/Apps%20Script-V8-blue)
![Models](https://img.shields.io/badge/Models-Gemini%202.5%20Pro%20%7C%20GPT--5-purple)

---
