---
name: Data Scraping
description: Use this skill to scrape data, find leads, and gather information from the web.
---

# Data Scraping Skill

## Overview
This skill provides the instructions and workflow for gathering lead data, scraping websites, and finding relevant information across the web to empower the marketing engine.

## Strict AI Lead Generation Rules (The 6-Step Gauntlet)
Whenever instructed to find leads, the AI MUST pass every prospect through these absolute filters. If a prospect fails any rule, they must be discarded.

1. **The "Money in Motion" Filter (Mandatory):**
   - **Instruction:** Only flag businesses actively running ad campaigns (check Facebook Ad Library / Google Ads).
   - **Rule:** If they are not spending money on ads, discard them.

2. **The "Performance Gap" Filter (The Hook):**
   - **Instruction:** Run the prospect's URL through Google PageSpeed Insights (Mobile).
   - **Rule:** If the Mobile Score is > 60 or load time is < 2.5s, discard them. Keep only slow sites where Next.js provides obvious value.

3. **The "Local Platform & Activity" Filter:**
   - **Instruction:** Scan their Facebook Business Page, Instagram, or LinkedIn.
   - **Rule:** The business or founder must have posted within the last 14 days. If dormant, discard.

4. **The "Tech Stack Vulnerability" Filter:**
   - **Instruction:** Use Wappalyzer/BuiltWith logic to detect their CMS.
   - **Rule:** Prioritize WooCommerce, OpenCart, Magento, or bloated Shopify stores.

5. **The "Anti-Wantrepreneur" Filter (Absolute Disqualifier):**
   - **Instruction:** Check company age and reviews.
   - **Rule:** If the business has < 20 reviews or the domain is < 1 year old, discard them. Target established businesses only.

6. **The "Direct Decision Maker" Rule:**
   - **Instruction:** Scrape for the Founder, CEO, or Head of E-commerce.
   - **Rule:** Discard generic `info@` or `support@` emails. If a decision maker's direct contact cannot be found, flag for manual review.

## Core Capabilities
- **Lead Finding:** Extracting contact info, company details, and decision-maker profiles from directories and websites.
- **Content Discovery:** Finding trending posts and relevant conversations for social engagement.
- **Data Structuring:** Organizing unstructured web data into structured tables or JSON for use in cold outreach.

## Execution Workflow
1. **Understand the Target:** Always start by identifying the exact ICP (Ideal Customer Profile) or the exact type of content you are trying to find.
2. **Apply Filters:** Pass targets through the 6-Step Gauntlet defined above.
3. **Data Extraction:** When reading URLs, summarize or extract ONLY the information required (e.g., email addresses, pain points, core offerings). Do not clutter context with raw HTML.
4. **Data Delivery:** Always present the final scraped data to the user or subsequent tools in a structured format (Markdown table or CSV/JSON artifacts).

## Guidelines
- **Respect Privacy & Terms:** Avoid scraping sensitive PII (Personally Identifiable Information) beyond standard B2B contact details.
- **Efficiency:** If a page is too large, use search tools or targeted queries instead of dumping the entire DOM.
- **Verification:** Cross-reference data if possible to ensure high lead quality.
