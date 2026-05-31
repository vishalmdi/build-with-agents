# Course Walkthrough

Build With Agents is a 7-day sequence for turning Claude Code from a chat interface into a practical automation partner.

The official course lives at [buildwithagents.vercel.app](https://buildwithagents.vercel.app/).

## Course promise

By the end of the challenge, you should have built:

- A workflow that can run from plain-English instructions.
- A live-data scraping pattern with MCP.
- A reusable skill for repeated work.
- A cloud automation that runs without your laptop.
- A screenshot-based frontend improvement loop.
- A scheduled routine and monitoring loop.
- A personal executive assistant folder that can compound over time.

## Day 1: Your First Workflow

Build: Newsletter automation

You create a workflow that accepts a topic, researches it, drafts a newsletter, saves the draft, asks for review, and sends only after approval.

What this day teaches:

- Why `CLAUDE.md` acts as the project brain.
- How to separate project context from workflow instructions.
- Why Plan Mode matters before execution.
- How to add review gates around publishing or sending.

Success looks like:

- A working workflow file.
- At least one saved draft.
- A review step before sending.
- One observed failure and a documented recovery.

## Day 2: Using an MCP Server

Build: Job listing scraper

You connect Claude Code to Firecrawl MCP and use it to scrape structured data from live websites.

What this day teaches:

- What MCP changes about an agent.
- How to choose between map, scrape, crawl, and extract.
- How to keep tool references in a cheat sheet instead of burying them in prompts.
- How to handle empty extraction results.

Success looks like:

- Firecrawl MCP connected.
- A scrape workflow that produces structured output.
- A fallback when extraction returns empty or incomplete data.

## Day 3: Your First Skill

Build: Reusable skill

You turn a repeated task into a reusable Claude Code skill with guardrails, examples, and references.

What this day teaches:

- How skills differ from one-off prompts.
- How to keep a skill focused.
- How to avoid loading too much context.
- How to iterate a skill after real runs.

Success looks like:

- One custom skill.
- Clear invocation rules.
- References separated from the main skill body.
- Notes from at least one improvement pass.

## Day 4: Deployment

Build: Trigger.dev automation

You convert the Day 1 workflow into a cloud task that can run without your laptop.

What this day teaches:

- How local agent builds differ from deployed deterministic tasks.
- How env vars, logs, and retries matter.
- Why production automations need explicit failure messages.
- Why sending or publishing requires safety gates.

Success looks like:

- A deployed task.
- Logs you can inspect.
- Env vars documented.
- A failure mode that does not fail silently.

## Day 5: Frontend Build Loop

Build: Landing page screenshot loop

You use Claude Code to build and improve a frontend page with screenshots as feedback.

What this day teaches:

- How to create a visual improvement loop.
- How to inspect desktop and mobile.
- How to fix overflow, spacing, tap targets, and visual hierarchy.
- Why visual verification is part of frontend work.

Success looks like:

- A landing page that renders locally.
- Desktop and mobile screenshots.
- At least one visual issue found and fixed through the loop.

## Day 6: Scheduled and Looping Agents

Build: Scheduled automation plus monitoring loop

You create a routine that runs on a schedule and a loop that monitors something in the current session.

What this day teaches:

- The difference between scheduled runs and active loops.
- How to avoid automations that ask questions during execution.
- How to report uncertainty instead of blocking.
- How to preserve logs and improvement notes.

Success looks like:

- One scheduled routine.
- One monitoring loop.
- Output saved somewhere inspectable.
- Defaults documented for unattended execution.

## Day 7: Executive Assistant System

Build: Personal EA folder

You wrap the week into a personal operating system with context files, operating rules, a decision log, and at least one skill.

What this day teaches:

- How to structure personal context for an agent.
- How to keep context current without bloating prompts.
- How to record decisions.
- How to build toward a long-term assistant instead of a one-off demo.

Success looks like:

- EA folder created.
- Context files populated.
- Operating rules documented.
- First useful skill connected.
- Next three skills planned.

## Capstone

The capstone asks you to harden one automation and explain what you built.

A strong capstone includes:

- Clear failure messages.
- Logs and saved outputs.
- Retry or fallback behavior.
- Approval gates for risky actions.
- Documentation for setup and troubleshooting.
- A one-page writeup of what worked, what broke, and what comes next.

## Start the course

Go to [buildwithagents.vercel.app](https://buildwithagents.vercel.app/) and start with Day 1.
