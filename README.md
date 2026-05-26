<div align="center">

# Afaq Javed

### Python Automation · Web Scraping · B2B Lead Generation

<p>
<a href="mailto:faaqjaved@gmail.com"><img src="https://img.shields.io/badge/faaqjaved%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/afaq-javed-460880249"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
&nbsp;
<a href="https://github.com/FAAQJAVED"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
&nbsp;
<img src="https://img.shields.io/badge/Available-Remote%20Freelance-22c55e?style=flat-square"/>
</p>

<br/>

<table>
<tr>
<td align="center"><b>6</b><br/><sub>interconnected tools</sub></td>
<td align="center"><b>565</b><br/><sub>tests — zero network calls</sub></td>
<td align="center"><b>20,000+</b><br/><sub>leads generated</sub></td>
<td align="center"><b>3</b><br/><sub>CI operating systems</sub></td>
<td align="center"><b>8.7 / 10</b><br/><sub>avg project rating</sub></td>
</tr>
</table>

</div>

---

## What I build

A complete, production-grade B2B lead generation system in Python — six interconnected tools that together cover the full pipeline from **discovery → enrichment → CRM-ready output**. Any business directory on the internet. Any city. Any sector.

This toolkit has processed **20,000+ verified business leads** across the UK property management sector.

---

## The pipeline

```
  DISCOVERY    find companies from any source
  ---------------------------------------------------------------
  +-  Google Maps Scraper       Maps listings + email enrichment
  +-  LeadHunter Pro            4 search engines, HOT/WARM/COLD
  +-  Trustpilot Scraper        reputation-filtered businesses
  +-  JSON Directory Harvester  any JSON API, config-only
  +-  HTML Directory Scrapers   any HTML or WordPress directory

  ENRICHMENT   add verified contact details
  ---------------------------------------------------------------
  +-  Email & Phone Enricher    HTTP + Playwright, CF bypass

  OUTPUT       consistent schema across all 6 tools
  ---------------------------------------------------------------
  +-  3-sheet Excel  ( Data  /  Flagged  /  Summary )
      deduplicated  *  validated  *  CRM-importable
```

> A client who needs 10,000 verified business contacts — starting from zero — gets back a single deduplicated, formatted Excel file drawn from multiple sources and ready for CRM import.

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### 🗺️ [Google Maps Business Scraper](https://github.com/FAAQJAVED/Google-Maps-Business-Scraper)

![Version](https://img.shields.io/badge/v2.0.0-blue?style=flat-square)
![Tests](https://img.shields.io/badge/tests-122-brightgreen?style=flat-square)
![CI](https://img.shields.io/badge/CI-Ubuntu%20%7C%20Windows-lightgrey?style=flat-square&logo=github-actions)

Playwright-driven Maps scraper with **concurrent email enrichment**, Cloudflare XOR decode, and atomic checkpoint/resume. Runs survive interruption and pick up exactly where they left off.

`Playwright` `ThreadPoolExecutor` `openpyxl` `Cloudflare bypass`

</td>
<td width="50%" valign="top">

### 📧 [Email & Phone Enrichment Tool](https://github.com/FAAQJAVED/Email-Phone-Number-Enrichment-Tool)

![Version](https://img.shields.io/badge/v1.0.0-blue?style=flat-square)
![Tests](https://img.shields.io/badge/tests-78-brightgreen?style=flat-square)
![CI](https://img.shields.io/badge/CI-Ubuntu%20%7C%20Windows%20%7C%20macOS-lightgrey?style=flat-square&logo=github-actions)

**Two-pass crawler**: fast HTTP first, Playwright fallback for JS-rendered pages. E.164 phone normalisation. Works standalone or as the enrichment layer for any discovery tool.

`httpx` `Playwright` `E.164 normalisation` `Cloudflare bypass`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔍 [LeadHunter Pro](https://github.com/FAAQJAVED/Leadhunter_Pro)

![Version](https://img.shields.io/badge/v1.1.0-blue?style=flat-square)
![Tests](https://img.shields.io/badge/tests-72-brightgreen?style=flat-square)
![CI](https://img.shields.io/badge/CI-Ubuntu-lightgrey?style=flat-square&logo=github-actions)

4-engine parallel search (Bing, DuckDuckGo, Mojeek, Yahoo) via **abstract base class architecture**. Configurable HOT/WARM/COLD/NOISE keyword scoring. Domain deduplication before enrichment.

`Abstract base classes` `4-engine orchestration` `YAML scoring config`

</td>
<td width="50%" valign="top">

### ⭐ [Trustpilot Business Scraper](https://github.com/FAAQJAVED/trustpilot-business-scraper)

![Version](https://img.shields.io/badge/v1.2.0-blue?style=flat-square)
![Tests](https://img.shields.io/badge/tests-121-brightgreen?style=flat-square)
![CI](https://img.shields.io/badge/CI-Ubuntu%20%7C%20Windows-lightgrey?style=flat-square&logo=github-actions)

Selenium + Chrome scraper for Trustpilot listings — name, contact, website, **rating, review count**. Targets only established, active companies. Anti-scraping evasion built in.

`Selenium` `Chrome` `reputation filtering` `anti-bot evasion`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗂️ [JSON Directory Harvester](https://github.com/FAAQJAVED/json-directory-harvester)

![Version](https://img.shields.io/badge/v1.0.0-blue?style=flat-square)
![Tests](https://img.shields.io/badge/tests-79-brightgreen?style=flat-square)
![CI](https://img.shields.io/badge/CI-Ubuntu-lightgrey?style=flat-square&logo=github-actions)

**Config-only retargeting** — no code changes to point at a new JSON API directory. Two pagination modes, dot-path navigation, geographic bounding-box filter, two-pass deduplication. Best-documented codebase in the toolkit.

`Generic pipeline` `dot-path JSON` `geo filtering` `pure functions`

</td>
<td width="50%" valign="top">

### 🏗️ [HTML Directory Scrapers](https://github.com/FAAQJAVED/html-directory-scrapers)

![Version](https://img.shields.io/badge/v1.1.0-blue?style=flat-square)
![Tests](https://img.shields.io/badge/tests-93-brightgreen?style=flat-square)
![CI](https://img.shields.io/badge/CI-Ubuntu-lightgrey?style=flat-square&logo=github-actions)

**Dual-engine toolkit**: Engine 1 for any paginated HTML via CSS selectors; Engine 2 for WordPress AJAX — automatic nonce extraction, mid-run nonce refresh, manual gzip/zlib decompression. Most technically complex codebase in portfolio.

`CSS selectors` `WordPress AJAX` `nonce lifecycle` `ThreadPoolExecutor`

</td>
</tr>
</table>

---

## Stack

### Languages & runtime

<p>
<img src="https://img.shields.io/badge/Python%203.9–3.12-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Type%20hints-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white"/>
</p>

### Scraping & automation

<p>
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white"/>
<img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white"/>
<img src="https://img.shields.io/badge/httpx-009688?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Requests-FF6B35?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/BeautifulSoup4-59666C?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/lxml-2980B9?style=for-the-badge&logo=python&logoColor=white"/>
</p>

> **Specialist techniques**: Cloudflare XOR email decoding · WordPress `admin-ajax.php` nonce lifecycle · manual gzip/zlib decompression · SMTP RCPT email verification · anti-bot fingerprint evasion

### Data engineering

<p>
<img src="https://img.shields.io/badge/openpyxl-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>
<img src="https://img.shields.io/badge/pyyaml-CB171E?style=for-the-badge&logo=yaml&logoColor=white"/>
<img src="https://img.shields.io/badge/dnspython-003366?style=for-the-badge&logo=python&logoColor=white"/>
</p>

> **Techniques**: two-pass deduplication (ID-based + normalised name+postcode) · E.164 phone normalisation · geographic bounding-box filtering · HOT/WARM/COLD/NOISE keyword scoring · configurable record validation

### Concurrency & resilience

<p>
<img src="https://img.shields.io/badge/ThreadPoolExecutor-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/tqdm-FFC107?style=for-the-badge&logo=python&logoColor=white"/>
</p>

> **Patterns**: exponential-backoff retry · circuit-breaker (N failures → auto-pause) · atomic file ops (`.tmp → os.replace()`) · crash-safe checkpoint/resume · cross-platform keyboard listener · `command.txt` headless controls · `tqdm`-safe log routing

### Infrastructure & DevOps

<p>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
<img src="https://img.shields.io/badge/pytest--cov-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
<img src="https://img.shields.io/badge/ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black"/>
<img src="https://img.shields.io/badge/flake8-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/pyproject.toml-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/python--dotenv-ECD53F?style=for-the-badge&logo=dotenv&logoColor=black"/>
</p>

> **CI matrix**: Ubuntu · Windows · macOS across Python 3.9 – 3.12

---

## What I'm learning next

<p>
<img src="https://img.shields.io/badge/asyncio%20%2F%20aiohttp-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Proxy%20Rotation-555555?style=flat-square&logo=python&logoColor=white"/>
</p>

Each of these directly extends what the current toolkit can do — async throughput, database output, cloud-deployable APIs, visual dashboards.

---

## Specialisation

B2B sales market , Lead Generation and CRM. Property management, Sales, Lettings, and professional services directories.

Postcode validation, geographic filtering, and UK, US, and EU sector categorisation are **built into the architecture** — not retrofitted.

---

## Contact

Open to remote freelance projects — scraping pipelines, lead generation, data extraction, automation.

📧 **faaqjaved@gmail.com** &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/afaq-javed-460880249) &nbsp;·&nbsp; [GitHub](https://github.com/FAAQJAVED)
