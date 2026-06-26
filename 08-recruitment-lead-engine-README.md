# Recruitment Lead Engine

A multi-tool automation that finds companies actively hiring, identifies the right decision-maker to contact, and builds hyper-personalised outreach — delivering warm leads straight to a recruitment agency's CRM.

## The Problem

Recruitment agencies burn hours chasing cold leads. They manually search job boards, cross-reference company info, figure out who to contact, and then write generic outreach that gets ignored. This system automates the entire pipeline from lead discovery to personalised email-ready profiles.

## What It Does

- Scrapes job listings from LinkedIn Job Boards and Indeed
- Identifies companies hiring for roles the agency can fill
- Enriches each lead with company data and decision-maker info
- Sources personal details about the decision-maker for customised outreach
- Delivers enriched, ready-to-contact leads

## How It Works

```
Agency inputs target role requirements
        ↓
Make.com triggers the pipeline
        ↓
Apify scrapes LinkedIn and Indeed for matching job postings
        ↓
Listings are cleaned and placed in a processing sheet
        ↓
Data sent to Clay via webhook
        ↓
Company data enriched + decision-maker identified
        ↓
Decision-maker info sourced for personalised outreach
        ↓
Warm leads delivered, ready to contact
```

## What Makes It Different

This isn't just a scraper. The enrichment layer is where the real value sits — by the time a lead reaches the agency, they know the company, the role, the decision-maker's name, and enough personal context to write outreach that doesn't sound like a template.

## Tech Stack

- **Make.com** — orchestration and workflow automation
- **Apify** — job board scraping (LinkedIn, Indeed)
- **Clay** — data enrichment and decision-maker identification
- **LLMs** — content processing and personalisation

## My Role

Team project — I served as the orchestrator, building and connecting the automation pipeline end to end.

> **Note:** This is a showcase repository. Setting up this system requires the Make.com scenarios and Clay table templates.

## About

Built to give recruitment agencies piping-hot leads delivered on demand, instead of hours spent chasing cold contacts with no significant results.

---
