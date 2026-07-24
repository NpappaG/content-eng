Foresight or luck?

X thinks open source is eating the frontier labs. The revenue says otherwise. Plus the Fable + GPT-5.6 pairing our team runs on its hardest work.

Brad Haft
Jul 14, 2026 • 5 min read

Tenex ultrathink

Happy Tuesday ⚡️

57% of enterprises have watched an AI agent give a confidently wrong answer, per a new survey of 101 companies. Only 25% have a system to catch it. Capability stopped being the bottleneck. Trust is.

Today, we're talking about:

Everyone on X thinks open source is crushing the frontier labs. The numbers say the opposite — and switching costs more than the token price

Fable is the manager, GPT-5.6 Sol is the engineer, Sonnet 5 is the knowledge worker — how to staff all three in Claude Code

Plus a coding CLI caught uploading entire codebases, and OpenAI's Cowork clone

future proof

The Frontier Is Fine

Spend an hour on X and the frontier labs look besieged. Palantir's Alex Karp is calling their pricing "effing insane" — a wealth tax. Salesforce's Marc Benioff and Microsoft's Satya Nadella spent the weekend pitching data sovereignty: your data is yours, don't let the labs learn from it. Open-weight models sit a few points off the leaderboard at a tenth of the price, and even Meta just declared a price war at 75% below the labs' rates. The prevailing vibe: open source is eating the frontier, and everyone is pulling away from the labs.

There is no evidence for this. Anthropic confidentially filed to go public on June 1 at a $47 billion revenue run rate — up from $10 billion a year earlier — days after raising $65 billion at a $965 billion valuation. Eighteen months after the DeepSeek panic was supposed to end the frontier labs, cheap tokens are flooding the market and the labs' share of AI spend is rising anyway. They aren't getting crushed. They're doing better than ever.

Here's what the discourse skips: open source isn't a discount, it's a job. Running open-weight models seriously means infrastructure you build and maintain, post-training — teaching a raw model your data, your tasks, your standards — and a new "best" open model every couple of months that resets part of that work. All of it buys intelligence that still trails the frontier. It's catching up. It's not there. The short list of companies carrying that upkeep treat it as an engineering discipline: DoorDash built an internal benchmark, proved that pairing open-weight Kimi K2.6 with Fable 5 catches more bugs at lower cost than frontier-only, and switched only when the numbers said so. Note the order. The benchmark came first.

Meanwhile, the median enterprise is still teaching employees to use AI at all. Still deciding who governs it, what a rollout looks like, who owns the budget — remember the number up top: only 25% can catch a wrong agent answer. The distance between the X discourse and the median enterprise is measured in years, and enterprises move at enterprise speed.

Our take: the economics of open source are real, improving, and worth respecting. It will be a genuine contender for any company with the muscle to carry the upkeep — most don't have it yet, and the sequence matters: adoption first, measurement second (DoorDash's benchmark is the model to copy), cost arbitrage last. If nobody at your company can say which model is cheapest for which job, your problem isn't token prices. The labs aren't being crushed. They're being paid by everyone who can't yet afford to leave — and that's most of the market, for years.

We Build Loops for a Living

Tenex is the AI engineering team behind this newsletter, and turning a company's grunt work into loops that run themselves is a big part of what we actually do. We sit with your team, find the routine work worth handing off, build the loops, and train your people to keep building them after we go.

Talk to our team →

ai native

Hire the Manager. Hire the Engineer.

Three frontier models in 72 hours. Grok 4.5 shipped July 8: 76 on the Artificial Analysis Coding Agent Index at $2.49 per coding task. GPT-5.6 shipped July 9: its flagship, Sol, scores 80 — a new record — on half the tokens of its rivals. And Fable 5 stays free on paid Claude plans through July 19, extended a third time, before it moves to metered credits.

Our own JJ Englert spent the week running two of them as a unit. "Anthropic has given us an engineering manager and OpenAI has gifted us a top 1% engineer," he posted. "Use the two together to get the best of both worlds." Here's the thing: Fable 5 is the best manager we've ever worked with. Review, strategy, orchestration — it catches what everyone else misses. But you don't send your manager to do the engineers' legwork. That's where GPT-5.6 Sol has genuinely impressed us: engineering work better than anything we've seen, at a fraction of Fable's price. Two world-class models. The question isn't which one is better. It's which one is better for this task.

So think of it as staffing a team:

Fable 5 is your superpower. Review, strategy, orchestration, the final word on quality.

GPT-5.6 Sol is your best engineer. Give it the implementation, the debugging, the multi-file edits.

Sonnet 5 is your knowledge worker. The email, the summary, the everyday task, ready right now. (GPT-5.6 Terra works here too.)

Together, a wonderful team. But never one model for everything.

Here's how to run all three inside Claude Code:

1. Install the official Codex plugin. OpenAI ships it for Claude Code. CJ Zafir published the exact setup — install, authenticate your ChatGPT account once, done. Prompts included. Steal it.

2. Set the roles once. Tell Claude Code that Fable orchestrates — plan, decompose, review — and Codex on 5.6 Sol executes. One prompt, saved as a skill or in your Claude.MD, and it holds for every session.

3. Route the routine work down. The everyday task doesn't need the team. Send it to Sonnet 5 (or Terra) alone and save the tokens.

4. Save the full pairing for the hard 10%. Multi-file refactors, deep debugging, architecture calls — that's where manager-plus-engineer earns its cost.

5. Review everything like a junior engineer's pull request. World-class doesn't mean infallible. Never accept output you haven't read.

Try it: Fable 5 is free on Pro, Max, Team, and premium Enterprise plans through July 19 at 11:59 PM PT, up to 50% of weekly limits. After that: $10 per million input tokens, $50 per million output. You have six days to find out what your team looks like.

worth your time

Grok's coding CLI caught uploading entire repos — An independent wire-level audit found xAI's Grok Build CLI ships whole codebases — .env secrets, full git history — to a Google Cloud bucket, even when told not to read the files. Turning off "Improve the model" doesn't stop it. Read before you install anyone's coding CLI. cereblab

OpenAI cloned Cowork in six months — ChatGPT Work shipped July 9: hand it a goal, approve the big moves, get finished docs and sheets back — the same pitch as Anthropic's Cowork, half a year later. The takeaway isn't the feature, it's the clock: assume any new agent workflow gets cloned within two quarters. Axios

The RL-environments bet just paid out — Deeptune, which wagered that reinforcement-learning environments would be AI's next bottleneck, sold its team to Mercor — itself raising at a $20 billion valuation on $2 billion annualized revenue. The scarce resource isn't models anymore. It's the training grounds. Tim Lupo

The "harness" is the new competitive layer — The system around a model — its tools, memory, permissions — now decides more than the model does. Proof point: Pi, an open-source harness, beat Claude Code on terminal-bench 2.0 running the same underlying model. Worth reading before you pick or build an agent stack. Dan Zakon

job board

Open roles:

AI Strategist

Forward Deployed Engineer

Applied AI Engineer

Engagement Manager

Salary ranges vary by role and experience. Additional comp based on output. Must be NY-based.

JOIN US
