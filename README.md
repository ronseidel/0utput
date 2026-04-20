# 0utput

The 0fam directory. Source for [0utput.co](https://0utput.co).

## What is 0fam

0fam is a portfolio of small, focused web apps. Every name drops a letter for a zero. The naming scheme is the identity — no individual logos, the typography does the work.

0utput is the company. 0fam is the family.

## What's live

| App | URL | What it does |
|---|---|---|
| **d00r** | [d00r.app](https://d00r.app) | Branded timelines for processes and projects |
| **marg0** | [marg0.app](https://marg0.app) | Reading speed test across 18 fonts |
| **f0rtune500** | [f0rtune500.app](https://f0rtune500.app) | Your resume, but at defunct American companies |
| **t00t** | [t00t.app](https://t00t.app) | A fart soundboard |

## What's in progress

| App | What it does |
|---|---|
| **b0ng0** | Browser-based music playground |
| **b0p** | Song links that work on any streaming service |
| **st0rm** | Guided brainstorming with decision trees |

## Design system

Every 0fam app shares:

- **Space Mono** as the display/wordmark font (the dotted zero is the mark)
- **Inter** as the body font
- A palette anchored on `#034D32` (ink green) and `#028454` (accent green)
- Dark mode support, frequently enforced via inline `<html>`/`<body>` styles because CSS variables alone don't survive browser extensions and caching layers

See `b00t/` (in the `zer0fam` legacy monorepo) for the base shell most apps fork from.

## Stack

Most apps are a single static HTML file. Some use Cloudflare Workers for API proxying (b0p, st0rm). Hosted on Cloudflare Pages.

## This repo

This repo is the source for 0utput.co itself — the directory page. Each app listed above has its own repo:

- [0utput](https://github.com/ronseidel/0utput) — you are here
- [d00r](https://github.com/ronseidel/d00r)
- [marg0](https://github.com/ronseidel/marg0)
- [f0rtune500](https://github.com/ronseidel/f0rtune500)
- [t00t](https://github.com/ronseidel/t00t)

## Contact

Press and partnerships: hello@0utput.co
Built by [Ron Seidel](https://rontheron.com)
