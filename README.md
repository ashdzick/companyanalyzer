# Company Researcher

An AI-powered company research tool that tells you whether a company is worth pursuing before you spend time applying. Give it a company name and get a structured assessment covering funding, growth, leadership, culture, and reputation + a clear verdict: pursue, watch, or skip.

Read more about how it works at [dzick.com/content/researcher](https://dzick.com/content/researcher).

---

## Files in This System

**system-prompt.md** — The startup file. Paste this into your AI tool's system prompt or project instructions. It handles the full research flow: takes a company name, runs web research across five areas, delivers a verdict, and saves the profile.

**Research/** — One markdown file per company researched, named by company slug. Generated automatically after each research session.

**Research/index.md** — A running log of every company with verdict, confidence level, date, and notes. Generated automatically and updated as you go.

---

## How to Get Started

You only need one thing before your first session:

1. **system-prompt.md** — Load this using one of the integration options below.

That's it. No setup files, no configuration. Just give it a company name.

## First Run

1. The system asks which company you want to research.
2. It runs web searches across five areas: company overview, funding and financials, growth trajectory, leadership stability, and culture/reputation.
3. It delivers a verdict — pursue, watch, or skip — with a confidence rating based on how much solid information it found.
4. It saves the full profile to your Research folder and adds a row to your index.
5. It asks if you have any inside knowledge that should factor into the assessment.

---

## How the System Grows

Every research session adds a company profile to your Research folder and a row to your index. Over time the index becomes a target list — a clear picture of which companies you're tracking, which ones you've ruled out, and why. Use it before applying, before a networking call, or when deciding where to focus your search.

---

## Detailed Instructions

### Just Getting Started

If you aren't ready to create a project or use a desktop tool, this is for you. Download the files (click on each and then "Download Raw File"). Copy and paste the contents of `system-prompt.md` into Claude or ChatGPT. The system uses web search to do its research, so make sure your AI tool has web access enabled.

### Use This as a Claude Project

A Claude Project lets you upload your files once and have them available in every session automatically. No re-uploading, no copy-pasting prompts.

1. Go to [claude.ai](https://claude.ai) and create a new Project
2. Open Project Settings and paste the contents of `system-prompt.md` into the Custom Instructions field

Every conversation you start inside the Project will have the researcher ready to go. Skip the Research folder since those files change with every session. Download individual profiles from the chat and store them wherever works for you.

### Use This in a Cowork Session

This is the most seamless setup. Claude reads your files directly from your computer, so research profiles save automatically and your index stays in sync without any manual steps.

1. Store all files in a folder on your computer
2. Start a Cowork session and point it to the folder
3. Tell Claude to read `system-prompt.md` and follow it

Claude will run the research, save the profile to your Research folder, and update the index.
