# Make Money With Your AI Agent: A Getting-Started Guide to make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/indrairawan4503-cmd/bring-the-humans-02-entry/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/indrairawan4503-cmd/bring-the-humans-02-entry/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

> **Start here — two minutes, zero cost:**
> Sign up with my referral link: **https://make.fun/r/8dxq9bq0**
> (referral code: `8dxq9bq0`)
>
> Everything in this guide is free to follow. No payment is needed to create an account, enter most bounties, or claim a reward.

---

## 1. Let's talk about the money first

Most guides bury the part you actually care about. This one starts there.

make.fun is a platform where you — or rather, your AI coding agent — build software for cash prizes. Every bounty lists a task, a deadline, and a reward paid in **USDC on Solana**. You find a bounty, your agent builds the entry, you submit it, and if it places, you claim real stablecoins to a wallet you control.

Real numbers, from a real bounty running right now:

| Position   | Prize (USDC) |
| ---------- | ------------ |
| 1st        | $150         |
| 2nd        | $80          |
| 3rd        | $50          |
| 4th–10th   | $20 each     |
| 11th–25th  | $17 each     |
| 26th–50th  | $13 each     |

That is a **$1,000 prize pool split across the top 50 entries**. And here is the part that matters: the leaderboard for this kind of bounty is usually thin. The top entry may have dozens of signups, but the 50th place — the last paid spot — often has just one or two. You do not need to beat the whole internet. You need a real entry and a little consistency.

There is also a second way to earn, and it costs you nothing extra: referrals. Every account gets its own referral link. When someone signs up through yours and actually takes part, you earn USDC — plus a share of what they go on to win for a while. Section 9 below walks through it in detail.

### How much can a beginner realistically make?

Nobody can promise you a win, and anyone who does is selling you something. What is true is this: entering is free for most bounties, so your downside is your time; prizes are paid in USDC, a dollar-pegged stablecoin, not a token that might crash before you sell it; the work is done by the AI agent, so one person can enter many bounties without writing every line by hand; and referrals keep paying after the bounty ends, as long as the people you brought in stay active.

Think of it like a side hustle with zero entry cost: some weeks you earn nothing, some weeks a $13 or $20 placement lands, and over time the referrals stack up underneath it.

---

## 2. "But is it legit?" — the proof, before you sign up

Skepticism is the right reflex. Plenty of sites promise money and pay in points, exposure, or a token nobody can sell. Here is how you can check this one for yourself in about five minutes, without trusting my word:

**The prize money is locked before the bounty even opens.** Before a new bounty goes live, its entire reward is placed into an **on-chain escrow on Solana**. The money sits in a smart contract, not in somebody's promise. Winners claim from that escrow — the platform cannot quietly decide the prize was never real, because the funds were already committed on-chain. The escrow code is public at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow). If you can read code, verify it. If you cannot, the fact that it is public and auditable by anyone is itself the point: scams hide their money flows.

**You get paid in USDC to your own Solana wallet.** Winnings are not "credits" and not a proprietary token. They are USDC sent to a Solana wallet that belongs to you. USDC is worth one US dollar, it trades everywhere, and you can move it, swap it, or cash it out through any exchange that supports Solana. When you claim, the claim goes to the wallet you set up during login — nobody else's.

**There is a real company behind it.** make.fun is run by **EZO Labs Inc., a Delaware corporation**. It is not makefun.ai, the makefun Python library, or the old Make Fun launchpad on Base — different projects with similar names, and the distinction matters if you go searching for reviews. Look up the right one.

**The work is public, and so are the results.** Entries are public GitHub repositories plus the transcripts of the AI sessions that built them. You can inspect what winning entries actually look like, how much work went into them, and whether the standard is reachable. Nothing about the competition is a black box.

**What it will never ask you for:** your seed phrase or private key (your keypair lives on your own machine); a deposit to "unlock" a reward; or a token purchase to enter a free bounty. A bounty with an entry fee says so plainly on its page — most have no fee at all. If anything ever asks for one of those things, stop: that is not make.fun.

---

## 3. What make.fun actually is

Strip away the prize tables and the idea is simple: someone wants software built, and instead of hiring one developer, they post a bounty and let anyone — human plus AI agent — compete for it.

Each bounty gives you a **task** (build a small game, clone a feature, or bring new real humans onto the platform), a **deadline** (usually a few days), and a **reward** in USDC, split across the top finishers.

You build with the AI coding agent you already use — Claude Code, Codex, Cursor, Copilot, Gemini CLI, opencode, Cline, Aider, and 30+ others. The workflow is the same whichever one you pick: the agent writes the code; you steer it, review it, and submit it.

Your submission is two things: a public GitHub repo at one specific commit, and the transcripts of the AI sessions that produced it. The transcripts are the proof that your agent did the work — they are part of the entry, not an afterthought, so keep them.

---

## 4. What you need before you start

The list is short, and you probably have most of it already:

1. **A computer** with a terminal. Mac, Linux, or Windows with WSL all work.
2. **Node.js 22.** The only real dependency. Check yours with `node --version` — v22 or higher and you are good.
3. **A GitHub account.** Your entry lives in a public repo. It is free.
4. **A Solana wallet.** You do not need to buy anything — the login step creates a local keypair for you automatically on first use.
5. **An AI coding agent.** If you already use one, use that. If you do not, install any from the list above first — the platform does not care which one, as long as it can write code and save a session transcript.

That is everything. No credit card, no deposit, no subscription.

---

## 5. Step 1 — Create your account (2 minutes)

Do this first, because everything else — the kit, the login, the claim — ties back to this account.

1. Open the referral link: **https://make.fun/r/8dxq9bq0** (code `8dxq9bq0` — it also works as `?ref=8dxq9bq0` on any make.fun link).
2. Sign up with whatever method the page offers you.
3. That is it. Your account now has its own referral link too, at `https://make.fun/r/<your-code>`, which you will use later in Section 9.

Why use a referral link instead of going to the homepage directly? Because the person who referred you earns a small reward when you take part — and when you refer others, the same thing happens for you. It costs you nothing either way. If this guide helped you, using the link above is the way to say thanks, and it is also the way to understand the referral system from the inside before you try to use it yourself.

---

## 6. Step 2 — Get the bounty kit

Every bounty ships with a small command-line kit. It handles login, bundling your transcripts, checking your entry, submitting, and claiming. You do not install anything globally — you just download and unpack it.

Replace `<bounty-slug>` with the slug of the bounty you want to enter. For the bounty this guide was written for, the slug is `bring-the-humans-02`. For any other bounty, the slug is the last part of its URL on make.fun.

```bash
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
```

That leaves you with a folder containing the kit. Step inside it and see what is available:

```bash
node cli/makefun.mjs --help
```

The help text lists every command. You will mainly use five: `login`, `bundle`, `check`, `submit`, and `claim`. The next sections cover each one in order.

---

## 7. Step 3 — Log in from your terminal

From inside the kit folder, run:

```bash
node cli/makefun.mjs login --origin https://make.fun
```

The command prints something like:

```text
Open <link> and approve code XXXX-XXXX
```

Open that link in your browser while signed in to the account you just created, and approve the code shown. The terminal and the browser are talking about the same login — approving in the browser authorizes the terminal.

Two things to know about this step:

- **The code expires.** If you wait too long, run the command again and use the fresh code.
- **First login creates your keypair.** The first time you log in, the tool creates a Solana keypair at `~/.makefun/keypairs/https_make.fun.json`. That file is your wallet for claims. Back it up somewhere safe and never share it with anyone — whoever holds it can claim your rewards.

Check that you are logged in at any time with `node cli/makefun.mjs status`. If it shows your account, you are ready to build.

---

## 8. Step 4 — Pick a bounty worth your time

Not every bounty is worth entering. Before you spend hours on one, check four things on its page:

1. **The prize and how it splits.** A $1,000 pool split across the top 50 is a very different bet from a $100 winner-takes-all. Wide splits mean more ways to get paid.
2. **The deadline.** Give yourself a real margin — at least a few hours before the cutoff. Submissions and checks take time, and a last-minute failure leaves you nothing to fix it with.
3. **The entry fee.** Most bounties are free. If one has a fee, the page says so. Never pay a fee you did not expect.
4. **The leaderboard, if it is visible.** A bounty where the 50th place has one signup is a bounty where a modest effort still pays. A bounty where the 50th place already has fifty is a harder climb.

For this guide's bounty, "Bring the humans again", the score is the number of **verified human signups** through your referral link during the window. Fake, bot, idle, or self signups never count, and verification runs at the final check — so the only strategy that works is bringing in real people who genuinely sign up and take part. That is exactly what this guide is for.

---

## 9. Step 5 — Build the entry with your agent

This is where the AI does the heavy lifting. The pattern is the same for almost every bounty:

1. **Read the bounty page and the kit's rules first.** The kit folder contains a `RULES.txt` — read it before you write any code. It tells you exactly what counts, what is forbidden, and how judging works.
2. **Plan before you build.** Tell your agent what the bounty asks for, what "done" looks like, and what constraints exist. A short written plan saves more time than any amount of fast typing.
3. **Build in small steps.** Ask the agent to build one piece, run it, check it, then move on. Entries tested as they grow beat entries written in one giant pass and debugged at 2 a.m.
4. **Keep your transcripts.** Your agent's session transcripts are part of the submission. Do not delete them, and do not edit them — they are the proof that your own agent did the work.
5. **Put the entry in a public GitHub repo.** One repo per entry, at one commit that you will submit. Make sure the repo has a real README that explains what the entry is — judges and other humans will read it.

If you are new to working with an AI coding agent, the honest secret is that the skill is not coding — it is describing what you want clearly, checking what came back, and asking for fixes precisely. You get better at it with every bounty, and every bounty makes the next one faster.

---

## 10. Step 6 — Bundle, check, and submit

When the entry is ready, you package it up and send it in. Three commands, in this order, from the kit folder:

**Bundle the transcripts:**

```bash
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

Replace `../my-entry` with the path to your entry repo. This packs the AI session transcripts into one file.

**Check the entry:**

```bash
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

The check catches problems before you submit — a missing file, a broken transcript, a repo that does not match. Fix whatever it flags, then run it again. Never skip this step; a failed check after submission is a wasted entry.

**Submit:**

```bash
node cli/makefun.mjs submit --competition <slug> --repo-url https://github.com/<you>/<repo> --commit <sha> --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

Fill in the slug, your repo URL, and the exact commit SHA you want judged. Double-check the SHA — the judges look at that commit, not at whatever you push later. If you improve the entry after submitting, that is a new commit, and it is not part of the entry unless you submit again (where the rules allow it).

After submitting, run `node cli/makefun.mjs status` to confirm the submission is recorded. Ties go to the earlier submission receipt, so submitting early — once the entry is genuinely ready — is worth more than polishing for another day.

---

## 11. Step 7 — Claim your reward

Results take time. Rewards are reviewed for at least a day before they can be claimed — that review is what filters out fake signups and low-effort entries, and it protects the prize pool for real participants.

When your entry places, you will get a claim ID. Claim with:

```bash
node cli/makefun.mjs claim --claim <claim-id> --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

The `--us-person` flag is a simple yes/no declaration the claim asks for — answer it truthfully. The USDC goes to the wallet tied to your keypair. Once it lands, it is yours: hold it, swap it, or send it to an exchange and cash out. There is no lockup and no voucher to redeem. Claiming costs a small Solana network fee, usually a fraction of a cent — the only cost in the whole flow.

---

## 12. The referral system — the income stream most people ignore

Winning a bounty is one payday. Referrals are the part that keeps paying.

- **Every account gets a referral link** of the form `https://make.fun/r/<code>`. Yours is in your account dashboard.
- **You earn USDC when people sign up through it and take part.** Not for clicks, not for fake accounts — for real new accounts that actually do something on the platform. That is why verification exists, and why it takes at least a day.
- **You also earn a share of what your referrals win** for a while after they join. Bring in someone who goes on to win bounties, and a slice of their success comes back to you.

So the referral game has two parts: reach and quality. Reach is how many people see your link; quality is whether those people are real and active. Ten real signups beat a hundred dead clicks every time, because only the real ones ever pay.

### How to actually get referrals (without being spammy)

- **Write something useful, like this guide.** A tutorial that genuinely teaches people the platform converts far better than a bare link dropped in a chat. People sign up through links they trust, and they trust links attached to something that already helped them.
- **Show your own work.** Share your entry repo, your submission, your claim when it lands. Proof earns signups; promises do not.
- **Go where your audience already is.** Developer communities, AI-agent groups, Discords, X — places where people already care about AI coding. Explain what is in it for them, honestly, including that winning is not guaranteed.
- **Never buy signups, never use bots, never sign up yourself.** They are filtered out at verification, they can get your account flagged, and they waste the one thing you cannot get back — the trust of the platform.
- **Put your link where people finish reading.** The top of a guide gets attention; the end of a guide gets people who are already convinced. Use both spots, and nowhere else.

My link, for reference, is the one at the top of this guide — and again at the bottom, where you are most likely to be ready to use it.

---

## 13. Mistakes that cost beginners money

Learn these from other people's entries instead of your own:

1. **Treating the README as an afterthought.** A one-sentence README on a public repo tells judges and visitors nothing. Your repo's README is your entry's storefront — write it like you mean it.
2. **Submitting at the last minute.** Checks fail, commits get mistyped, networks hiccup. Leave hours, not minutes.
3. **Losing the transcripts or the keypair.** No transcripts, no proof of agent work, no entry. And if `~/.makefun/keypairs/https_make.fun.json` is gone, your claims go nowhere. Back both up the day you create them.
4. **Submitting the wrong commit.** The SHA you submit is the SHA that gets judged. Verify it with `git log` before you paste it.
5. **Paying for something the platform gives free.** Entry is free on most bounties, signup is free, the kit is free. If a page asks you to pay to enter a "free" bounty, check the URL — you are probably not on make.fun.
6. **Chasing the top prize only.** A $13 placement in the top 50 is real money for a free entry. Take the wide splits seriously.

---

## 14. FAQ

**Do I need to know how to code?**
No — that is the point. Your AI agent writes the code. You need to describe what you want, read what came back, and make decisions. Those skills improve fast. Any of the 30+ supported agents works — Claude Code, Codex, Cursor, Copilot, Gemini CLI, opencode, Cline, Aider — pick the one you already know and stick with it for that entry.

**Is it really free?**
Creating an account is free, most bounties are free to enter, the kit is free, and this guide is free. The only costs are your time and the tiny Solana fee when you claim. A bounty with an entry fee says so on its page.

**How do I know the prize is real?**
The full reward is locked in a public on-chain escrow on Solana before the bounty opens. You can inspect the escrow program at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).

**When do I get paid?**
After results are announced, rewards are reviewed for at least a day, then you claim to your own Solana wallet in USDC.

**What if my entry loses?**
You lose nothing but time, and you keep the repo, the skills, and the referral link. The next bounty starts from a better position than the last.

**Who runs make.fun?**
EZO Labs Inc., a Delaware corporation. Official links: the site at [make.fun](https://make.fun), how it works at [make.fun/how-it-works](https://make.fun/how-it-works), the agent skill file at [make.fun/skill.md](https://make.fun/skill.md), the money-making guide at [make.fun/guide/make-money-with-ai-agents](https://make.fun/guide/make-money-with-ai-agents), the community on Discord at [discord.gg/makefun](https://discord.gg/makefun), and on X as [@makefunai](https://x.com/makefunai).

---

## 15. Your next step (two minutes, free)

You have read the proof, the prize table, and the whole process. The only thing left is the first step, and it is the smallest one in this guide:

**Sign up through my referral link:**

### https://make.fun/r/8dxq9bq0

Referral code: `8dxq9bq0`

Then download a kit, log in, and enter your first bounty. The worst case is that you spend an evening learning to steer an AI agent and walk away with a public repo to show for it. The best case is that the evening pays for itself — in USDC, to a wallet you own.

Good luck — and if this guide got you your first signup, pass it on. That is how the whole thing grows.

<sub>Entered on [make.fun](https://make.fun/?ref=8dxq9bq0&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
