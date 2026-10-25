<h1 align="center">Awesome Agent Skills</h1>

<p align="center"><a href="https://airankwp.com"><img src="assets/banner.png" alt="Awesome Agent Skills. Click here to check how AI sees your site with AIRankWP." width="100%"></a></p>

<p align="center">
<a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
<img src="https://img.shields.io/badge/PRs-welcome-brightgreen" alt="PRs welcome">
<img src="https://img.shields.io/badge/license-CC0--1.0-blue" alt="License CC0 1.0">
<a href="https://github.com/devanasolver/awesome-agent-skills/commits/main"><img src="https://img.shields.io/github/last-commit/devanasolver/awesome-agent-skills" alt="Last commit"></a>
</p>

<p align="center">
<a href="https://github.com/devanasolver"><img src="https://img.shields.io/badge/Follow-@devanasolver-181717?style=for-the-badge&logo=github" alt="Follow on GitHub"></a>
<a href="https://github.com/devanasolver/awesome-agent-skills/stargazers"><img src="https://img.shields.io/github/stars/devanasolver/awesome-agent-skills?style=for-the-badge&logo=github&label=Star%20this%20list" alt="Star this list"></a>
<a href="https://airankwp.com"><img src="https://img.shields.io/badge/Free%20AI%20audit-airankwp.com-4638c8?style=for-the-badge" alt="Free AI audit at airankwp.com"></a>
</p>

> Agent skills (SKILL.md style packs) for AI coding agents, grouped by what you want to get done. Covers Claude Code, Codex, Gemini CLI, Google Antigravity, Cursor, Copilot and others.

A **skill** is a folder with a SKILL.md file and optional scripts that an agent loads when a task matches. The format started with Claude but several other agents now read the same kind of folder. Support differs by agent, so each entry only says which agents the repo itself names.

**Rules of this list:** every repo exists, is public, is not archived and has a license or a clear note. One plain sentence each. No copied text from other lists. Repos are listed on merit, including the maintainer's own (marked). Checked 2026-10-17. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Official and reference skills](#official-and-reference-skills)
- [Big collections and registries](#big-collections-and-registries)
- [Design, diagrams and slides](#design-diagrams-and-slides)
- [Marketing and SEO](#marketing-and-seo)
- [Product management](#product-management)
- [Research and knowledge](#research-and-knowledge)
- [Writing](#writing)
- [Planning and agent workflow](#planning-and-agent-workflow)
- [Video](#video)
- [Browser, Office and workspace automation](#browser-office-and-workspace-automation)
- [Other awesome lists](#other-awesome-lists)
- [How to choose](#how-to-choose)
- [Contributing](#contributing)

## Official and reference skills

Start here to see how skills are written and shared.

- [anthropics/skills](https://github.com/anthropics/skills) ![stars](https://img.shields.io/github/stars/anthropics/skills?style=flat&label=%E2%98%85) - Anthropic's public repo of Agent Skills, with example skills and the skill format. A good place to learn how a SKILL.md is built. _(check repo)_
- [github/awesome-copilot](https://github.com/github/awesome-copilot) ![stars](https://img.shields.io/github/stars/github/awesome-copilot?style=flat&label=%E2%98%85) - Community instructions, agents and skills for GitHub Copilot, kept by GitHub. _(MIT)_
- [tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills) ![stars](https://img.shields.io/github/stars/tech-leads-club/agent-skills?style=flat&label=%E2%98%85) - A validated skill registry for coding agents. Lists Antigravity, Claude Code, Cursor and Copilot as targets. _(check repo)_
- [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) ![stars](https://img.shields.io/github/stars/vercel-labs/agent-skills?style=flat&label=%E2%98%85) - Vercel's collection of agent skills. _(check repo)_

## Big collections and registries

Many skills in one repo. Pick what you need. Do not install everything.

- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) ![stars](https://img.shields.io/github/stars/addyosmani/agent-skills?style=flat&label=%E2%98%85) - Engineering skills for AI coding agents, such as planning, testing and review. _(MIT)_
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) ![stars](https://img.shields.io/github/stars/alirezarezvani/claude-skills?style=flat&label=%E2%98%85) - Large set of skills and plugins across engineering, marketing and product. Says it supports Claude Code, Codex, Gemini CLI, Cursor and more. _(MIT)_
- [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) ![stars](https://img.shields.io/github/stars/Jeffallan/claude-skills?style=flat&label=%E2%98%85) - 67 skills for full-stack developers, for Claude Code. _(MIT)_
- [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) ![stars](https://img.shields.io/github/stars/K-Dense-AI/scientific-agent-skills?style=flat&label=%E2%98%85) - Skills and database connectors for science: biology, chemistry, medicine and more. _(MIT)_
- [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering) ![stars](https://img.shields.io/github/stars/muratcankoylan/Agent-Skills-for-Context-Engineering?style=flat&label=%E2%98%85) - Skills on context engineering and multi-agent design, for people building agent systems. _(MIT)_
- [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) ![stars](https://img.shields.io/github/stars/Orchestra-Research/AI-Research-SKILLs?style=flat&label=%E2%98%85) - Skills for AI research and engineering work. Says it works with Claude Code, Codex and Gemini agents. _(MIT)_
- [sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) ![stars](https://img.shields.io/github/stars/sickn33/agentic-awesome-skills?style=flat&label=%E2%98%85) - Catalog of 2,600+ skills with a CLI and local MCP server to find and pick them. _(MIT)_
- [wshobson/agents](https://github.com/wshobson/agents) ![stars](https://img.shields.io/github/stars/wshobson/agents?style=flat&label=%E2%98%85) - Plugin marketplace for several agents. Lists Claude Code, Codex, Cursor, OpenCode, GitHub Copilot and Google Antigravity. _(MIT)_

## Design, diagrams and slides

Skills that produce visuals: UI, diagrams, illustrations, decks and social images.

- [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) ![stars](https://img.shields.io/github/stars/cathrynlavery/diagram-design?style=flat&label=%E2%98%85) - Makes clean HTML and SVG diagrams (44 types) from an agent. Works with Claude Code, Codex, Copilot, Cursor and others. _(MIT)_
- [chuspeeism/dashi-ppt-skill](https://github.com/chuspeeism/dashi-ppt-skill) ![stars](https://img.shields.io/github/stars/chuspeeism/dashi-ppt-skill?style=flat&label=%E2%98%85) - Generates presentations you can edit in the browser and export to HTML, PDF and PPTX. _(AGPL-3.0)_
- [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) ![stars](https://img.shields.io/github/stars/Leonxlnx/taste-skill?style=flat&label=%E2%98%85) - Skills that push coding agents toward better visual design, using reference images and a browser check. _(MIT)_
- [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) ![stars](https://img.shields.io/github/stars/nextlevelbuilder/ui-ux-pro-max-skill?style=flat&label=%E2%98%85) - Design guidance skill for building cleaner UI and UX across platforms. _(MIT)_
- [op7418/guizang-social-card-skill](https://github.com/op7418/guizang-social-card-skill) ![stars](https://img.shields.io/github/stars/op7418/guizang-social-card-skill?style=flat&label=%E2%98%85) - Makes carousel and cover images for Xiaohongshu and WeChat. Docs are partly Chinese. AGPL licence. _(AGPL-3.0)_
- [tt-a1i/archify](https://github.com/tt-a1i/archify) ![stars](https://img.shields.io/github/stars/tt-a1i/archify?style=flat&label=%E2%98%85) - Turns an idea, plan or codebase into an interactive diagram. _(MIT)_
- [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) ![stars](https://img.shields.io/github/stars/wheresryan22/anatomy?style=flat&label=%E2%98%85) - Makes detailed isometric SVG illustrations of machines and systems. _(MIT)_

## Marketing and SEO

Skills for search, copy, social and growth.

- [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) ![stars](https://img.shields.io/github/stars/AgriciDaniel/claude-seo?style=flat&label=%E2%98%85) - Large SEO skill set: technical SEO, schema, GEO/AEO, llms.txt, local and e-commerce SEO. _(MIT)_
- [Bhanunamikaze/Agentic-SEO-Skill](https://github.com/Bhanunamikaze/Agentic-SEO-Skill) ![stars](https://img.shields.io/github/stars/Bhanunamikaze/Agentic-SEO-Skill?style=flat&label=%E2%98%85) - SEO analysis skill for Antigravity, Codex and Claude, with sub-skills and helper scripts. _(MIT)_
- [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) ![stars](https://img.shields.io/github/stars/coreyhaines31/marketingskills?style=flat&label=%E2%98%85) - Marketing skills: conversion work, copywriting, SEO, analytics and growth. _(MIT)_
- [devanasolver/ai-seo-toolkit](https://github.com/devanasolver/ai-seo-toolkit) ![stars](https://img.shields.io/github/stars/devanasolver/ai-seo-toolkit?style=flat&label=%E2%98%85) - Free command-line AI-search audit, keyword ideas and Search Console data. It is a CLI, not a SKILL.md pack. By the maintainer of this list. _(MIT)_
- [sergebulaev/linkedin-skills](https://github.com/sergebulaev/linkedin-skills) ![stars](https://img.shields.io/github/stars/sergebulaev/linkedin-skills?style=flat&label=%E2%98%85) - 12 skills for LinkedIn posts, comments and publishing plans. For Claude Code and Codex. _(MIT)_
- [zubair-trabzada/geo-seo-claude](https://github.com/zubair-trabzada/geo-seo-claude) ![stars](https://img.shields.io/github/stars/zubair-trabzada/geo-seo-claude?style=flat&label=%E2%98%85) - SEO skill focused on AI search: citability scoring, AI crawler checks and schema. _(MIT)_

## Product management

Skills for product discovery, strategy and launch.

- [deanpeters/Product-Manager-Skills](https://github.com/deanpeters/Product-Manager-Skills) ![stars](https://img.shields.io/github/stars/deanpeters/Product-Manager-Skills?style=flat&label=%E2%98%85) - Product management skills built on established methods. For Claude Code, Codex and other agents. _(check repo)_
- [phuryn/pm-skills](https://github.com/phuryn/pm-skills) ![stars](https://img.shields.io/github/stars/phuryn/pm-skills?style=flat&label=%E2%98%85) - 100+ skills and plugins for product managers, from discovery to launch. _(MIT)_

## Research and knowledge

Skills that gather, summarize and organize information.

- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) ![stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=flat&label=%E2%98%85) - Skills that teach an agent to work with Obsidian notes, Markdown, Bases and JSON Canvas. _(MIT)_
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) ![stars](https://img.shields.io/github/stars/mvanhorn/last30days-skill?style=flat&label=%E2%98%85) - Researches a topic across Reddit, X, YouTube, Hacker News and the web, then summarizes it. _(MIT)_
- [teng-lin/notebooklm-py](https://github.com/teng-lin/notebooklm-py) ![stars](https://img.shields.io/github/stars/teng-lin/notebooklm-py?style=flat&label=%E2%98%85) - Unofficial Python API and agent skill for Google's notebook tool. Unofficial, so it can break. _(MIT)_
- [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) ![stars](https://img.shields.io/github/stars/virgiliojr94/book-to-skill?style=flat&label=%E2%98%85) - Turns a technical book PDF into a Claude Code skill. _(MIT)_
- [yusufkaraaslan/Skill_Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) ![stars](https://img.shields.io/github/stars/yusufkaraaslan/Skill_Seekers?style=flat&label=%E2%98%85) - Turns docs sites, GitHub repos and PDFs into Claude skills. _(MIT)_

## Writing

Skills for prose and fiction.

- [blader/humanizer](https://github.com/blader/humanizer) ![stars](https://img.shields.io/github/stars/blader/humanizer?style=flat&label=%E2%98%85) - Skill that removes common signs of AI-written text. _(MIT)_
- [sinadwm1/write-natural](https://github.com/sinadwm1/write-natural) ![stars](https://img.shields.io/github/stars/sinadwm1/write-natural?style=flat&label=%E2%98%85) - Persian and English writing skill for faithful revision and anti-slop editing, with optional offline diagnostics; no paid keys required by the skill (by the author). _(MIT)_
- [zenstory-ai/oh-story-claudecode](https://github.com/zenstory-ai/oh-story-claudecode) ![stars](https://img.shields.io/github/stars/zenstory-ai/oh-story-claudecode?style=flat&label=%E2%98%85) - 13 skills for writing long web novels, with continuity tracking. Docs mix Chinese and English. _(MIT)_

## Planning and agent workflow

Skills that change how the agent plans, answers or decides.

- [0xNyk/council-of-high-intelligence](https://github.com/0xNyk/council-of-high-intelligence) ![stars](https://img.shields.io/github/stars/0xNyk/council-of-high-intelligence?style=flat&label=%E2%98%85) - Runs a structured multi-perspective debate on hard decisions, across Claude Code, Codex, Gemini CLI and OpenCode. _(MIT)_
- [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) ![stars](https://img.shields.io/github/stars/ayghri/i-have-adhd?style=flat&label=%E2%98%85) - Skill that makes agent answers short and direct, with the answer first. _(MIT)_
- [nidhinjs/prompt-master](https://github.com/nidhinjs/prompt-master) ![stars](https://img.shields.io/github/stars/nidhinjs/prompt-master?style=flat&label=%E2%98%85) - Claude skill that writes prompts for other AI tools. _(MIT)_
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) ![stars](https://img.shields.io/github/stars/OthmanAdi/planning-with-files?style=flat&label=%E2%98%85) - File-based planning for long agent tasks, so plans survive context resets. _(MIT)_

## Video

Skills for making videos.

- [latent-spaces/brag](https://github.com/latent-spaces/brag) ![stars](https://img.shields.io/github/stars/latent-spaces/brag?style=flat&label=%E2%98%85) - Makes a short launch video of your project with one command. _(MIT)_
- [Vincentwei1021/video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) ![stars](https://img.shields.io/github/stars/Vincentwei1021/video-shotcraft?style=flat&label=%E2%98%85) - Skill for product videos made with Remotion, with shot recipes and a template. For Claude Code and Codex. _(Apache-2.0)_

## Browser, Office and workspace automation

Let an agent drive a browser, Office files or Google Workspace.

- [browser-act/skills](https://github.com/browser-act/skills) ![stars](https://img.shields.io/github/stars/browser-act/skills?style=flat&label=%E2%98%85) - Browser automation CLI for agents, with multiple sessions and hand-off to a human when stuck. _(MIT)_
- [googleworkspace/cli](https://github.com/googleworkspace/cli) ![stars](https://img.shields.io/github/stars/googleworkspace/cli?style=flat&label=%E2%98%85) - One command-line tool for Drive, Gmail, Calendar, Sheets and Docs. Includes agent skills. _(Apache-2.0)_
- [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) ![stars](https://img.shields.io/github/stars/iOfficeAI/OfficeCLI?style=flat&label=%E2%98%85) - Single-binary tool that lets agents read and edit Word, Excel and PowerPoint files without Office installed. _(Apache-2.0)_

## Other awesome lists

Related lists. This one does not try to replace them.

- [composio-community/awesome-codex-skills](https://github.com/composio-community/awesome-codex-skills) ![stars](https://img.shields.io/github/stars/composio-community/awesome-codex-skills?style=flat&label=%E2%98%85) - Curated list of Codex skills. _(check repo)_
- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) ![stars](https://img.shields.io/github/stars/ComposioHQ/awesome-claude-skills?style=flat&label=%E2%98%85) - The well-known curated list of Claude skills. Worth reading alongside this one. _(check repo)_
- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) ![stars](https://img.shields.io/github/stars/hesreallyhim/awesome-claude-code?style=flat&label=%E2%98%85) - Curated list of Claude Code resources. _(check repo)_
- [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) ![stars](https://img.shields.io/github/stars/travisvn/awesome-claude-skills?style=flat&label=%E2%98%85) - Curated list of Claude skills and resources, with a Claude Code focus. _(check repo)_
- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) ![stars](https://img.shields.io/github/stars/VoltAgent/awesome-agent-skills?style=flat&label=%E2%98%85) - Large curated list of 1000+ skills for Claude Code, Codex, Gemini CLI, Cursor and more. _(MIT)_
- [VoltAgent/awesome-codex-subagents](https://github.com/VoltAgent/awesome-codex-subagents) ![stars](https://img.shields.io/github/stars/VoltAgent/awesome-codex-subagents?style=flat&label=%E2%98%85) - 130+ specialized subagents for Codex. _(MIT)_
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) ![stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=flat&label=%E2%98%85) - Collection of OpenClaw skills sorted by category. _(MIT)_

## How to choose

- **Check the licence and the scripts.** A skill can run code on your machine. Read the SKILL.md and any scripts before you install, and prefer repos you can audit.
- **Install few.** Skills overlap. Too many skills crowd the agent's context.
- **Check your agent.** Only some repos name Antigravity, Codex or Gemini CLI. If yours is not named, test with one small task first.
- **Young repos change fast.** Look at the last commit and open issues.
- **Counts like "2,600+ skills" are the authors' own claims.** We did not test each skill.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). One repo per pull request, plain words, real repos only.

## About

Maintained by [@devanasolver](https://github.com/devanasolver), who also builds [AIRankWP](https://airankwp.com), a WordPress plugin for AI-search visibility. Listings follow the rules in CONTRIBUTING, not ownership.
