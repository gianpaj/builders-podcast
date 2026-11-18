# The Builders on Break: spike

> Created: 2026-11-18
> Last updated: 2026-11-18

A first proposal for the show: what it is, how four voices from a pool of up to six can share it, what an episode looks like, a first season, and how it gets made at close to zero cost. Written to be safe for a public repository: it names no client, employer, account or private person.

Status: a proposal to argue about. Nothing here is decided.

How it was put together: one researcher read what experienced podcasters and existing multi-host tech shows do; one mined months of our own notes (a daily newsletter radar, a studio knowledge base with creator teardowns and tool reviews, a trading-bot project) for material; one designed the production pipeline. Where a number below comes from a secondary source that could not be traced to its origin, it says so.

## 1. The show in one paragraph

Working developers who also build things of their own, on a break. Four of us per episode, talking about what we read, tried, shipped or broke that week: AI-assisted development, tools and repositories, the news that matters to people who build, and the unglamorous side of trying to start something. Tagline: "coffee, code, and questionable decisions". The tone is a conversation between friends who disagree, not a lecture and not an interview.

**What makes it ours.** Most shows in this space sell certainty. We have receipts for the opposite: ideas we scored and killed, bots that lost on paper, tools that did not survive a week, and creator income claims checked against the creators' own words. The promise to the listener: we tell you what happened when we actually tried it.

## 2. People and rotation

**The problem with four voices.** Coaches and producers warn that beyond three voices listeners stop telling people apart, and remote calls make crosstalk worse (secondary sources). The four-voice shows that last have one thing in common: somebody is in charge of the conversation. All-In has a fixed moderator; JS Party ran a rotating panel around a regular anchor for 361 episodes.

**Proposal.**
- A pool of up to six. Exactly four on air per episode.
- **One chair per episode**, rotating. The chair runs the order, keeps time, cuts tangents and calls on whoever has been quiet. The chair is not the star; the chair is the referee.
- **One producer per episode**, rotating, and never the chair: collects the tracks, runs the scripts, does the headphone listen, opens the publishing PR.
- Everyone says their own name in the first minute, every episode.
- Each host has a declared angle (the sceptic, the shipper, the infrastructure person, the one who reads the terms of service). Contrast between voices is what lets a listener tell four people apart.
- If the first two recordings are a mess of crosstalk, drop to three on air and keep the pool.

**A fair schedule for six hosts, first twelve episodes** (checked by script: every host is on air eight times and chairs twice, nobody rests two episodes running, every pair of hosts shares four or five episodes):

| Ep | On air | Chair | Resting |
|---|---|---|---|
| 1 | B D E F | D | A C |
| 2 | A C E F | E | B D |
| 3 | B C D F | B | A E |
| 4 | A B D E | A | C F |
| 5 | A C D F | C | B E |
| 6 | B C E F | F | A D |
| 7 | A B D F | D | C E |
| 8 | A C D E | E | B F |
| 9 | A B C F | B | D E |
| 10 | B C D E | C | A F |
| 11 | A D E F | F | B C |
| 12 | A B C E | A | D F |

With a pool of four, everyone is on every episode and only the chair rotates. With five, one rests each time.

## 3. What an episode is

**Length and pace.** About 45 minutes after editing, every two weeks, in seasons of eight to ten. One analysis of 100,000 feeds found that more than half never got past six episodes (secondary source), so the plan is built to survive: record two episodes per session, and have three finished before the first one goes out.

**Default running order, "the stand-up" (45 minutes, four voices):**

| Minutes | Block | Who |
|---|---|---|
| 0:00 | Cold open: one true story in under 90 seconds | Chair |
| 1:30 | Names, and what is in today's episode | All |
| 3:00 | Tried it: one thing each actually used this week, verdict in a sentence, then pushback | 4 x 5 min |
| 23:00 | The main argument: one question, one person presents, one person is the assigned sceptic | 15 min |
| 38:00 | Questionable decision of the week | 4 min |
| 42:00 | Break picks: one thing off-screen each | 4 x 30 s |
| 44:00 | Close, and next episode's question | Chair |

**Alternative, "the deep break" (60 minutes):** a two-minute round each, then one topic for half an hour with a presenter and a sceptic, then a listener question.

**Rules of the room.**
- One screen-share-free prep document, open 48 hours before recording. Minimum three bullets per host.
- Every item is phrased as a question somebody can disagree with.
- A raised hand in the chat is how you get in. The chair picks.
- If nobody disagrees after two minutes, the chair moves on.

## 4. Recurring segments

Each one is fed by notes we already keep, so prep is mostly selection.

| Segment | What it is | Length |
|---|---|---|
| **Radar round** | Each host picks one story from the week's newsletters and defends why it matters | 10 min |
| **Tried it** | One tool or repository, a verdict, and the host who really ran it | 8 min |
| **Idea autopsy** | One idea we scored or killed: why it looked good, what killed it | 10 min |
| **Guru math** | One creator's income claim next to what they admit in the same video | 10 min |
| **Bot diary** | What the paper-money trading bots did this fortnight, and which bug turned up | 6 min |
| **Claim vs backtest** | A trading claim from social media, then the number we measured | 5 min |
| **The receipt** | One AI cost figure and what it really buys | 5 min |
| **Agent incident of the week** | An agent that misbehaved, and the guard that would have stopped it | 5 min |
| **Questionable decision of the week** | One of ours. Mandatory. | 4 min |

## 5. Thirty episode ideas

Each has the question the four of us would argue about. Talking points come from public reporting and from our own experiments.

**A. Building with AI**
1. **Output is not value.** Are agents making teams faster, or just busier? (One team tripled its weekly pull requests and saved no time.)
2. **Review is the new bottleneck.** If the agent writes it, who signs the merge?
3. **The rewrite is back.** Is "never rewrite" dead now that a port costs tokens instead of years?
4. **If you understand it, script it.** When should a prompt become plain code?
5. **Memory is a cost.** Should agents forget? (One model did better with nine notes than with four hundred.)
6. **The missing first rung.** How does a junior get in when the entry-level work is automated?

**B. Agents, security and trust**
7. **Agents use every bit of access you give them.** How much autonomy is safe?
8. **"Don't ask again" becomes a commit.** What is in your dotfiles, and should a tutorial tell anyone to turn the safety off?
9. **Vibe-coded, then leaked.** Can non-engineers ship safely?
10. **The laptop is the vault door.** Are people still the weak point?
11. **Banks without front doors.** Should a bank let your agent in?
12. **Every free trial is a GPU donation.** How do you price an AI product without feeding fraud?

**C. Side-business reality**
13. **Zero signups.** Was it the idea or the channel? (A validation test of ours: a quarter of people replied, nobody signed up, and one said plainly "I wouldn't pay".)
14. **Most projects never earn a dollar.** A portfolio of small bets, or one bet?
15. **Nine ways an idea lies to you.** Why do most ideas die on first contact with a buyer?
16. **A launch is not a channel.** Where did a hundred founders actually find customers?
17. **Boring pays.** Originality or distribution?
18. **The co-founder clause.** Do you write the break-up terms before there is anything to split?

**D. Creator economics**
19. **The free challenge.** Is free training ever free?
20. **"Have I done it myself yet? No."** Do you take advice from someone selling what they have not sold?
21. **The candid one.** Are custom AI builds a business or a trap?
22. **Sponsored tools have a half-life.** Do you trust a creator's tool pick?
23. **Agent-edited video.** Can an agent replace an editor? (Also: how this show is made.)
24. **Titles overclaim.** Does it matter if the content is good?

**E. Building trading bots, and what went wrong**
25. **A 76% win rate, measured.** Why does it shrink when you test it?
26. **One survivor out of twenty-nine.** Is retail trading content just noise?
27. **The bug that hid the target.** What does paper trading actually catch?
28. **The inverted field.** Who reviews your data assumptions?
29. **Copy the winners?** Do yesterday's best traders stay the best?
30. **Killed by geography.** How much does where you live decide what you can build?

For theme E, see the rule in section 9: we describe what we built and what went wrong, never what anyone should buy.

## 6. A first season

Ten episodes, in this order: 13, 25, 1, 19, 7, 14, 27, 2, 15, 23.

Why: we open with our own failures, so the show has earned the right to be sceptical before it is sceptical about anyone else. The business, trading and development strands alternate so every host gets a home episode. The season closes on how the show itself is made.

**Cold opens we already have** (true, each under 90 seconds):
- A paper bot made 173 trades and hit its profit target once, because a timestamp bug threw the target away five minutes after entry.
- A "76% win rate" strategy measured 51% when somebody ran it.
- Weeks of analysis turned out to be testing the opposite trade, because of one misread field.
- A waitlist's only signup was a bot typing random letters.
- A creator's agent replied to reviews so fast that the platform blocked it for a day.
- A thirty-second read of a forum's rules prevented a ban.

## 7. How it gets made

**Recording, free.** Each host records their own microphone locally (48 kHz mono, headphones on) while we talk on a normal call; one shared clap at the start and one at the end. A recording bot on the call gives a second copy per speaker as backup. Local tracks mean no time limits, no watermark and no dependence on anyone's free tier.

**From recording to published:**

| Step | How |
|---|---|
| Collect four tracks | A script checks they are all there |
| Sync on the clap, level to the podcast loudness standard (-16 LUFS, true peak -1 dB) | Scripted with ffmpeg, checked by ear |
| Transcribe each track separately | Local Whisper. One file is one speaker, so no guessing who spoke |
| Draft chapters, show notes, six titles, pull quotes | A model drafts; every quote carries a timestamp |
| Cut list | A model proposes, a host approves. Cuts are never applied unapproved |
| Headphone listen | One host who was on the episode. Required |
| Export, upload, publish | The audio goes to object storage, a pull request adds the episode, the merge builds the site and the feed |
| Three short clips with captions | Scripted, chosen by a human |
| Post | Each host from their own account, by hand |

**Rule for quotes and summaries:** anything attributed to a host is checked against the audio by that host before it is published.

**The repository.**

```
episodes/NNN-slug/   index.md (show notes), transcript.md, chapters.json, clips/ (captions only)
hosts/               one card per host
segments/            the recurring segments, defined
ideas/backlog.md     parked ideas (live ones are issues)
site/                the website and the feed template
scripts/             sync, mix, transcribe, validate
docs/                templates, rotation, release checklist
```

**What never goes in a public repository:** raw audio and video, prep documents, cut lists, unreleased episodes, anyone's contact details. Prep and drafts live in a private sibling repository; audio lives in object storage.

**GitHub as the editorial room.** An issue is an episode pitch. One board: idea, prepped, recorded, edited, published. One pull request per episode at publish time, reviewed by a host who was on it. One check on every pull request: valid episode metadata, no media files, no secrets.

**Website and feed.** A small static site built from the episode folders, with a feed that meets Apple's and Spotify's requirements, served from a domain the show owns so the feed address never has to change. The quicker alternative for episode one is a free podcast host; the price is that they own the feed address.

**Costs.** Everything above is free at our size. The first paid thing is a domain (about 10 to 15 EUR a year); the second is probably storage for raw tracks. Realistic expectations: the median new podcast episode gets under 30 downloads in its first week, and passing 100 puts a show in the top quarter (secondary source).

## 8. Templates

**Prep (private):**

```markdown
# Prep: NNN <working title>
Record: YYYY-MM-DD HH:MM | Chair: <name> | Producer: <name> | On air: <a>, <b>, <c>, <d>
Do not mention: <clients, employers, unreleased work, absent people>

## Cold open
<one true story, under 90 seconds>

## Tried it (5 min each)
- <a>: what, verdict in one line, link, the question for the others
- <b>: ...

## The main argument (15 min)
Question: <phrased so someone can disagree>
Presents: <name> | Sceptic: <name>
Three facts with links:

## Questionable decision of the week
## Break picks
```

**Show notes (public):**

```markdown
---
number: NNN
title: ""
date: YYYY-MM-DD
hosts: [a, b, c, d]
chair: a
audio: https://<our domain>/NNN.mp3
duration: "00:45:00"
---
One paragraph, written or checked by a host.

## Chapters
- 00:00 Cold open

## Links
- [Name](url): why it came up
```

**Host card (public):** name, city, two lines on what you build and what you argue about, what to ask you about, what never to ask you about, and a dated yes to your voice and name being published.

## 9. Ground rules

- **No client, employer, colleague or private person is named** without their yes. Each host checks their own employment contract.
- **Trading and investing:** we say what we built, what we tested and what went wrong. We disclose if we hold something we discuss. We never say what anyone should buy or sell. A "not financial advice" line does not put a show outside the rules on investment recommendations in the EU or the UK; behaviour does. No sponsorship from brokers or crypto platforms.
- **Consent:** a guest says yes in writing before recording. Any host can ask for a takedown.
- **Music:** only with a written licence that covers podcasts and clips, or made by one of us.
- **Ownership, in one page, before episode one:** who holds the feed, the domain and the accounts; what happens when someone leaves; how any money is split.
- **A release checklist** on every episode: listened on headphones, quotes checked, do-not-mention list checked, consent on file.

## 10. Open questions for the group

1. Four, five or six in the pool? And is everyone in for a season of ten?
2. Audio only, or video from the start? (Video roughly doubles the editing work; YouTube is now where a large share of people listen.)
3. English only?
4. Who are the first two chairs and the first two producers?
5. May hosts name their own products and projects on air, including the ones that failed?
6. The name: two web searches found no existing show called "Builders on Break". The app stores and the trademark registers have not been checked.
7. A recording slot that all six time zones and day jobs can keep.

## 11. Suggested first three weeks

1. **Week 1:** agree the pool, the slot, the ground rules and the one-page ownership note. Each host writes a card and pitches three episodes as issues.
2. **Week 2:** a throwaway test recording of 20 minutes with four voices, to hear the crosstalk problem for ourselves and to test the track-per-person setup. Nobody publishes it.
3. **Week 3:** record episodes 1 and 2 in one session. Build the sync-and-transcribe script against those tracks. Decide the launch date only when three episodes exist.
