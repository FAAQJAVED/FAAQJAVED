<div align="center">

# Afaq Javed

### GTM Engineer · B2B Outbound Operations

**I run the outbound loop — ICP → sourcing → enrichment → verification → cold email → CRM —<br/>and build the automation underneath it when off-the-shelf tools run out.**

<p>
<a href="https://faaqjaved.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-Case%20studies%20%26%20process-C2470F?style=for-the-badge"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/faaqjaved"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
&nbsp;
<a href="mailto:faaqjaved@gmail.com"><img src="https://img.shields.io/badge/Email-2A2520?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p>
<img src="https://img.shields.io/badge/Open%20to-GTM%20%2F%20RevOps%20roles-16a34a?style=flat-square"/>
&nbsp;
<img src="https://img.shields.io/badge/Remote-UK%20%26%20US%20hours-666666?style=flat-square"/>
</p>

</div>

---

## Why these repos exist

I am not a developer who drifted into sales. I ran outbound by hand first — sourcing, qualifying, and sending for a UK property compliance company, alone, for six months. I scraped 150 websites a day by hand and asked to automate it. The answer was no.

So the tools below are not tutorial projects. Each one removes a bottleneck I personally hit while trying to get a reply rate off the floor.

**The lesson that shaped all of them:** most outbound does not fail on copy or tooling. It fails on the list. I burned five months and 15,000 sends learning that.

---

## Results these tools support

| | |
|---|---|
| **50,000+** | B2B contacts sourced and processed |
| **<1% → ~7%** | reply rate after diagnosing a failing 15,000-email campaign |
| **1,000 → 70** | prospects qualified down; **70% replied**, 25% of those bought |
| **576 leads / 49 min** | two sources, deduplicated, delivered unattended |
| **22,700 → 9,567** | messy client list cleaned, deduplicated and ICP-qualified |

Full teardowns — including what broke and how it was fixed — are on the
**[portfolio](https://faaqjaved.github.io/Portfolio/)**.

---

## The pipeline

```
DISCOVERY  ─────────────────────────────────────────────
  Google Maps Scraper        Maps listings + enrichment
  LeadHunter Pro             4 engines, HOT/WARM/COLD
  Trustpilot Scraper         reputation-filtered
  JSON Directory Harvester   any JSON API, config only
  HTML Directory Scrapers    any HTML / WordPress AJAX

ENRICHMENT  ────────────────────────────────────────────
  Email & Phone Enricher     HTTP pass → Playwright pass

VERIFICATION  ──────────────────────────────────────────
  VERIFIED     mailbox confirmed  →  full volume
  CATCH-ALL    unconfirmable      →  separate domain, low volume
  INVALID      no MX / role-based →  dropped

OUTPUT  ────────────────────────────────────────────────
  One row per contact, 16-field schema, CRM-importable
```

A client needing 10,000 verified contacts from zero gets back one deduplicated file, drawn from several sources, ready for HubSpot or Zoho.

---

## Tools

| Repository | Tests | What it does |
|---|---|---|
| **[Google Maps Business Scraper](https://github.com/FAAQJAVED/Google-Maps-Business-Scraper)** | 122 | Playwright scraper with concurrent email enrichment, Cloudflare decoding, crash-safe checkpoint/resume |
| **[HTML Directory Scrapers](https://github.com/FAAQJAVED/html-directory-scrapers)** | 184 | Dual-engine: CSS-selector scraper for any paginated directory, plus a WordPress AJAX engine with nonce lifecycle handling |
| **[Trustpilot Business Scraper](https://github.com/FAAQJAVED/Trustpilot-Business-Scraper)** | 121 | Reputation-filtered listings with ratings and review counts — established companies only |
| **[JSON Directory Harvester](https://github.com/FAAQJAVED/json-directory-harvester)** | 102 | Config-only retargeting for any JSON API directory. New source = new YAML, no code |
| **[Email & Phone Enrichment Tool](https://github.com/FAAQJAVED/Email-Phone-Number-Enrichment-Tool)** | 88 | Two-pass crawler — fast HTTP, Playwright fallback for JS pages. E.164 normalisation |
| **[LeadHunter Pro](https://github.com/FAAQJAVED/Leadhunter_Pro)** | 78 | Bing, DuckDuckGo, Mojeek and Yahoo in parallel, with configurable keyword scoring |

**695 automated tests · zero network calls in any test · CI on Ubuntu, Windows and macOS · all MIT-licensed**

There is a seventh, private: an orchestration layer that runs these together — plugin system, SQLite run history, FastAPI control surface. One command returns a finished, deduplicated sheet. That one stays closed because it is the thing that turns a six-hour delivery into 49 minutes.

---

## What I work with

**GTM & outbound**
ICP definition · trigger-based targeting · enrichment waterfalls · deliverability (SPF/DKIM/DMARC, warmup, dedicated subdomains) · sequencing and A/B testing · reply-rate diagnosis · CRM handoff design

**Platforms**
Apollo.io · LinkedIn Sales Navigator · Clay · Instantly · HubSpot · Zoho · Airtable · Google Sheets

**Build**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

**Going deeper on:** Clay to certification · n8n · signal-based targeting · Salesforce

> Salesforce appears in roughly 45% of GTM engineering postings and I have not worked in it. Listing it as a skill would be a lie you would find out about in week one, so it is listed here instead.

---

## Currently

Open to **GTM Engineer / RevOps** roles and freelance outbound work. Remote, UK and US hours.

If your outbound is not working, the fastest thing I can do is tell you whether it is a list problem, a deliverability problem or a targeting problem — usually within one conversation.

**[faaqjaved@gmail.com](mailto:faaqjaved@gmail.com)** · **[Portfolio](https://faaqjaved.github.io/Portfolio/)** · **[LinkedIn](https://www.linkedin.com/in/faaqjaved)**
