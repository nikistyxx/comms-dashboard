# comms-dashboard

A Claude Cowork skill that builds a personalized daily communications dashboard from your Slack, Outlook email, and Google Docs — in one self-contained HTML file.

## Install

```bash
npx skills add YOUR_GITHUB_USERNAME/comms-dashboard
```

Or install the `.skill` file directly in Claude Cowork by dragging it into the chat window.

## What it does

Connects to your Slack, Outlook, and Google Docs, then generates an interactive HTML dashboard with:

- Action items sorted by priority (high / medium / low)
- Draft replies for Slack messages needing a response
- Unread emails, messages, and active docs in one view
- Interactive filters by priority and source
- Three-tab layout: Dashboard, Completed log, and daily journal
- Hourly auto-refresh during work hours (8 AM–5 PM, weekdays)

## Choose your style

When you run the skill, you'll pick a style:

**Standard** — Clean, professional layout. Neutral colors. Optimal for focus and quick scanning.

**Creative** — Bold Memphis design with thick borders, saturated colors, geometric shapes, and a daily tarot card drawn from the full 78-card deck.

Both styles include the same data and features.

## How to use

Start a Cowork session, select an output folder, and say something like:

- *"Build me a communications dashboard"*
- *"What needs my attention today?"*
- *"Show me my action items from Slack and email"*
- *"Make me a colorful dashboard with a tarot card"*

The skill pulls your latest messages, extracts action items, generates the HTML file in your selected folder, and sets up an hourly refresh schedule.

## Requirements

- Claude Desktop with Cowork mode enabled
- Slack connector
- Outlook connector
- Google Drive connector

## About

Created by [Niki Selken](https://nikiselken.com). Open source under MIT license.
