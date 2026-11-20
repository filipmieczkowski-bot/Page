# Faceless GTA 6 fast-news page

The working files for a faceless GTA 6 fan page: fast, verified news plus credited
clips with an AI voiceover, 7 posts a day on X, TikTok and YouTube Shorts.

Built from [this setup prompt by @arceyul](https://x.com/arceyul/status/2123221909366337776).
All the rules are in [playbook.md](playbook.md).

## Settings

| | |
|---|---|
| Name and handle | **TBD.** Shortlist in [playbook.md §1](playbook.md#1-account-info) |
| Angle | Fast news |
| Platforms | X, TikTok, YouTube Shorts (Instagram later) |
| Posts per day | 7 (X 4, TikTok 2, Shorts 1) |
| Time zone | Europe/Warsaw, available from 16:00 |
| Voiceover | AI voice |
| Approvals | None for normal posts. Spending and name or bio changes need the owner. |

## Who does what

- **You:** own the accounts and logins, edit clips in CapCut, schedule in Buffer, reply to comments. Never put passwords in these files.
- **Claude** (open a session on this repo): checks official news, keeps [facts.md](facts.md) current, writes the day's posts and AI voice scripts into [idea-bank.md](idea-bank.md), and runs the weekly review from the numbers you put in [scoreboard.csv](scoreboard.csv). For example: *"Daily batch: check official GTA 6 news, update facts.md, write today's 7 posts."*

## 7-day kickoff

Launch week is the biggest traffic window GTA 6 will have. If the accounts are ready
before Day 4, start posting the ready X drafts (N1, N2, G1, Q1 in
[idea-bank.md](idea-bank.md)) right away.

**Day 1 (Fri Nov 20)**
- [x] Answer the setup questions
- [x] Create the folder structure (this repo)
- [ ] Pick the name and handle, and check it's free on X, TikTok and YouTube
- [ ] Create the three accounts with the same handle, bio, avatar and banner ([playbook.md §2](playbook.md#2-account-setup-and-voice))
- [ ] Connect the three channels in Buffer

**Day 2 (Sat Nov 21)**
- [ ] Open every link in [facts.md](facts.md) and mark each fact Verified
- [ ] Fill [watchlist.md](watchlist.md): 20+ creators and streamers, 3 to 5 bigger pages to study
- [ ] Save official screenshots and trailers to `media/official/` in your storage

**Day 3 (Sun Nov 22)**
- [ ] Bring [idea-bank.md](idea-bank.md) to 15 drafts across all pillars
- [ ] Make a CapCut template: hook text style, caption style, one AI voice
- [ ] Edit the first 3 vertical clips (C1, C2, C3)

**Day 4 (Mon Nov 23)**
- [ ] Start the 7-post daily mix ([playbook.md §3](playbook.md#3-daily-mix-7-posts))
- [ ] Log every post in [log.md](log.md) and [scoreboard.csv](scoreboard.csv)
- [ ] Start the engagement routine

**Day 5 (Tue Nov 24)**
- [ ] First 24 h metric reads
- [ ] Run the first one-variable test (T1 in [learning.md](learning.md))
- [ ] Turn comment questions into HOW TO drafts

**Day 6 (Wed Nov 25)**
- [ ] Keep posting
- [ ] Prepare the kit for the next big drop: templates, watchlist, an empty queue window

**Day 7 (Thu Nov 26)**
- [ ] First weekly review: top 3, bottom 3, median by pillar, slot and platform
- [ ] Double down, cut, pick next week's tests
- [ ] Update [playbook.md](playbook.md) with what changed

## Files

| File | What's in it |
|---|---|
| [playbook.md](playbook.md) | Account info, voice, daily mix, all the rules |
| [facts.md](facts.md) | Verified facts only, each with its official source link |
| [idea-bank.md](idea-bank.md) | Ready-to-go drafts by pillar |
| [watchlist.md](watchlist.md) | Official accounts, creators, subreddits to monitor |
| [log.md](log.md) | Every post that went out |
| [scoreboard.csv](scoreboard.csv) | Per-post metrics at 12 h, 24 h and 72 h |
| [learning.md](learning.md) | Wins, losses, current rules, tests, weekly reviews |
| [takedowns.md](takedowns.md) | Removal requests and what we did |
| `media/` | `official/`, `raw/`, `edits/`. Video and image files are git-ignored, so keep them in your storage. |
