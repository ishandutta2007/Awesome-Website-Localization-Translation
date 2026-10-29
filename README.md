# Awesome-Website-Localization-Translation

# Top Website Localization & Translation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Multilingual Storefronts, Continuous Localization & Self-Hosted Translation Management*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Website Localization & Translation**. These tools enable organizations to translate website content, manage multilingual storefronts, and automate the flow of strings between code, translators, and production—reaching global audiences without rebuilding sites for each market.

**Examples** include Shopify Translate & Adapt, Weglot, Langify, Transcy, Bablic, Lokalise, Smartling, Phrase, Crowdin, and Localize (the category leaders).

**Open-source emphasis**: Website Localization is a domain where open-source tooling is **emerging but still limited for turnkey website translation**. The strongest active project is **Localess**, a free and open-source translation management tool built on Angular and Firebase, offering AI-assisted translation and a CMS for structured content . However, most open-source localization tools focus on developer-centric string management (like **Crowdin**'s open-source alternatives or **Phrase**'s developer APIs) rather than the plug-and-play website translation experience of Weglot or Transcy. Organizations seeking a self-hosted website translation layer must often assemble components or accept that the SaaS platforms lead significantly in ease of deployment for non-technical users.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Shopify Translate & Adapt](https://apps.shopify.com/translate-and-adapt)**  
  Shopify's native translation app for merchants; supports auto-sync for up to 8 languages (US/CAN update, October 2026), automatically translating new and updated content weekly without overwriting manual translations . Free for basic auto-translation (2 languages historically), with manual translation for unlimited languages via CSV .

- **[Weglot](https://www.weglot.com/)**  
  Leading website translation plugin compatible with WordPress, Shopify, Webflow, and others; features Weglot 2.0 with an AI Translation Model trained around brand profiles, a Visual Editor for in-context review, Image Translation, and automatic hreflang/SEO handling . Translations are served from the cloud, keeping the origin database light .

- **[Langify](https://www.langify-app.com/)**  
  Shopify-focused translation app with a free plan (manual translation up to 5 languages) and paid tiers for machine translation (DeepL/Google), bulk translation via word packages, and third-party app content translation . Machine translations are triggered manually—not automatic—and legal text should be reviewed by humans .

- **[Transcy](https://transcy.io/)**  
  Shopify translation app emphasizing **market-specific translations**: a "Default Translation" layer applies universally, while "Market-Specific Translations" allow unique content per country/market with fallback logic . Includes third-party app translation (Judge.me, Klaviyo, PageFly) and AI engines (OpenAI, DeepL, Gemini), though third-party content often cannot be manually edited .

- **[Bablic](https://www.bablic.com/)**  
  Website translation service with flexible modes: automatic translation, on-demand translation, or manual-only (no machine translation) . Languages can be configured and published independently, with visual editor support for customization.

- **[Lokalise](https://lokalise.com/)**  
  Developer-first localization platform with **Workflows** (no-code multi-step automation), AI translation that selects the best output from multiple LLMs (Claude, GPT-4o, DeepL), GitHub Actions for CI/CD localization, and analytics for tracking translation ROI .

- **[Smartling](https://www.smartling.com/)**  
  Enterprise translation platform with **LQA Agent** (automated MQM-based quality scoring, 90% agreement with human reviewers), Auto Select LLM, Style Rules for AI (punctuation/date formats across 30+ languages), Instant AI Translation via synchronous API, and AI Image Translation . Deep enterprise integrations (AEM, Drupal, WordPress, Figma).

- **[Phrase](https://phrase.com/)**  
  Enterprise localization platform with **zero-touch localization** (developers open a PR, Phrase detects strings, translates, and commits back to the branch), Figma localization, Style Guides for consistent brand voice, Quality Profiles, and MCP support for AI agent workflows . 200+ integrations including Notion, ServiceNow, and Airtable.

- **[Crowdin](https://crowdin.com/)**  
  Localization management platform with a marketplace of apps (Google Drive, HubSpot, Mailchimp, Dropbox), GitHub Actions for automated localization, API 2.0, and integrations for Azure Repos, Adobe XD, and design tools . Strong for developer-driven continuous localization.

- **[Localize](https://localizejs.com/)**  
  Website translation integration (WordPress plugin available) with unlimited languages and collaborators, automatic string detection, professional human translation ordering, and translation analytics .

## Open-Source GitHub Projects

- **[Localess](https://github.com/Lessify/localess)**  
  Free and open-source translation management tool and CMS built with Angular and Firebase; uses AI (Google Translate) to accelerate translation, provides real-time editing of localization content, supports hierarchical content with validation (Schematics), and publishes changes instantly via Google CDN . **The most complete open-source website localization platform available**, though it requires Firebase infrastructure and is better suited for application content than full website auto-translation like Weglot.

### Additional Strong Open-Source Options

- **Crowdin (self-hosted alternatives)** — While Crowdin itself is SaaS, its open API and GitHub Actions ecosystem enable developer-driven localization workflows that can be self-managed for string extraction and deployment . No direct self-hosted Crowdin clone exists, but the CI/CD patterns are reproducible with open tools.
- **Phrase MCP integrations** — Phrase's MCP server support allows AI agents to access translation memories and glossaries, a pattern that could be replicated with open-source LLM tooling for teams building custom localization pipelines .

**Frameworks for building custom systems**: Combine **Localess** for translation management and CMS with AI-assisted translation, **Crowdin's CI/CD patterns** (GitHub Actions) for string extraction and deployment automation, and custom API integrations for content delivery. For teams needing a self-hosted website translation layer comparable to Weglot, Localess provides the closest foundation, though it lacks the automatic DOM detection and subdomain routing that SaaS plugins handle out of the box.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Website localization platforms handling content and user data must comply with applicable privacy regulations and accessibility standards; machine translations should be reviewed for legal, medical, and safety-critical content .
- **Open-source website localization is limited**—Localess provides a strong translation management foundation but requires Firebase setup and lacks the automatic website detection/routing of commercial plugins . Most SaaS platforms (Weglot, Transcy, Langify) lead in zero-code deployment for non-technical users.
- Verify license terms for commercial use; Localess is free and open-source .

---

**Made for localization managers, web developers, ecommerce operators, and international marketing teams.**  
Let's make website localization more open, but with honest acknowledgment of where SaaS still leads in deployment simplicity.
