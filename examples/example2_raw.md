The Wealth Tax Nobody Voted For

Palantir's CEO torched the AI industry's pricing model on live TV, plus a framework for testing which frontier model actually wins your job.

Brad Haft

Jul 7, 2026 • 5 min read

Tenex ultrathink

Happy Tuesday ⚡️

Half a trillion dollars. That's what investors poured into startups in the first six months of 2026, a new record, and 43% of it went to exactly two companies: OpenAI and Anthropic pulled in $217 billion between them. Every other startup on the planet split what was left.

Today, we're talking about:

Why Palantir's CEO calling the AI industry "effing insane" on live TV might be the smartest sales pitch of the year

How to actually pick the right AI model for your job, because it turns out your favorite one might not be everyone's

Plus OpenAI offering Washington a slice of itself, Adobe buying up an entire category of AI tools, and a field guide for finding what you don't know you don't know

future proof

The Wealth Tax Nobody Voted For

Alex Karp went on CNBC on July 1 to talk about a new Palantir-Nvidia partnership and instead spent nine minutes calling the entire AI industry "effing insane." Strip out the theater and there's one question underneath that every company buying AI this year has to answer: when you build on a rented model, what do you actually own?

Karp's charge: OpenAI and Anthropic bill per token, basically per chunk of text you send and get back, while collecting the data customers feed in and using it to train the next release. He called it a "wealth tax." His fix, conveniently, is Palantir's own new deal with Nvidia: open-weight models, where the model files sit on hardware you control instead of a vendor's.

Our take: the spiciest accusation doesn't survive a fact-check. Anthropic doesn't train on business customers' data by default, OpenAI's API terms say the same, and Karp was selling the alternative for all nine minutes, so grade the rant like the sales pitch it is. But the question underneath is legitimate, and older than AI: buy versus build. Renting frontier intelligence has been the right call for most companies, nobody builds their own power plant to keep the lights on. It just means the vendor sets the price, the terms, and what you're left holding when the contract ends. And this time what you'd walk away from isn't a CRM license, it's every fine-tune, prompt, and workflow your team built on top.

The biggest players are already answering the ownership question for themselves. Nvidia's half of the Palantir deal pushes Nemotron, Nvidia's own family of open-source models, a chipmaker climbing up into the model layer. Anthropic just opened talks with Samsung to make its own chip, weeks after OpenAI unveiled one with Broadcom, the labs digging down into silicon. The All-In crew is calling this the AI sovereignty wars, and the frontier is still being set: everyone at the table wants to own the whole stack, top to bottom.

Zoom out and this week reads like shots fired for the next wave of AI. The fight isn't over which lab has the smartest model anymore, it's open source versus frontier, the models you can own versus the ones you can only rent. That's the main stage for the foreseeable future, and Karp just grabbed the mic.

We Build Loops for a Living

Tenex is the AI engineering team behind this newsletter, and turning a company's grunt work into loops that run themselves is a big part of what we actually do. We sit with your team, find the routine work worth handing off, build the loops, and train your people to keep building them after we go.

Talk to our team →

ai native

Date Before You Marry Your Model

We spent last week running the same batch of knowledge-work tasks through Claude Sonnet 5, Claude Fable 5, and GLM 5.2, a rival lab's open-source model, then graded the outputs blind. The humans reached for the open-source GLM over Fable more than once. The AI agents grading the same work picked Fable across the board, every single time.

That split is the whole story of model picking right now. The labs have caught up to each other enough that "best" depends on who's judging and what the job is. Fable is the strongest model we've ever used for multi-step agent work, tasks where it strings several actions together like a human assistant would, which is exactly why agents grading agents love it. But for the email, the summary, the slide, the stuff most knowledge work is actually made of, it's overkill, the gap has nearly closed and taste takes over. And as of today, Fable is off included usage and only available through metered API tokens, which makes it pricier than it needs to be for most of what you're actually doing day to day. The "just use the best model" era is officially over.

Every serious builder we know is testing more models right now than at any point in the last two years, same prompt, side by side, keeping whichever one earns it. If you've been riding one model on autopilot, this is your next level up, and it costs nothing but twenty minutes:

1. Pick one real task. Grab something you'd actually do this week: a client email, a board summary, a first draft of a proposal.

2. Run the exact same prompt through three models. We'd point you at Sonnet 5, GPT-5.5, and GLM 5.2: three different labs, three different price points. A platform like OpenRouter lets you run all three from one place and compare side by side. (Skip Fable for your first bake-off, at its new pricing it's overkill for everyday work.)

3. Judge on your job. Skip "which one sounds smartest." Ask which draft you'd send with the fewest edits. That's the only benchmark that actually pays your bills.

4. Write down which model won and why. One line is enough: "GLM nailed the tone, Sonnet was faster, GPT missed the context." That note is worth more than any published benchmark for your specific job.

5. Repeat monthly. New versions ship every few weeks now. The model that won in June might not win in September, and the only way to know is to keep testing.

We posted the entire test, unedited outputs included, free on YouTube. Watch where each model wins and loses, then go run your own. Steal the method, keep the results.

worth your time

OpenAI offers Washington a piece of itself — OpenAI pitched the government a 5% stake, worth roughly $42 billion at its March valuation, modeled after Alaska's oil-revenue fund that cuts residents a check every year. Framed as sharing AI's upside, it also reads like buying political cover before the next Karp-style headline. The Kobeissi Letter

Adobe just bought your Photoshop plugins — Adobe is acquiring Topaz Labs, the AI upscaling and restoration tools a huge chunk of Creative Cloud users already bolt on separately, and folding it straight into Photoshop, Lightroom, and Premiere. Read: the "install five plugins to get the real AI features" era of creative software is ending. TechCrunch

Anthropic built an app just for scientists — Claude Science packages artifacts, on-demand compute environments, and 60+ pluggable research databases into one beta app built around how research actually gets done. Worth a look before your R&D team builds its own scaffolding around Claude from scratch. Claude

A field guide for the gap between your prompt and your codebase — Anthropic's Thariq wrote up the exact framework he uses to find what he calls "unknowns," the space between what you told Claude to do and what the work actually needs, before it turns into three hours of cleanup. Useful the moment you're running agents on anything more complex than a one-off script. Thariq

Anthropic found a hidden "workspace" inside Claude — New research maps a small, sparse slice of Claude's internal activity, dubbed J-space, that behaves like the "global workspace" theory of human consciousness: only a tiny fraction of everything happening inside the model is ever accessible to reasoning or verbal report, the same divide neuroscientists describe in your own brain. Anthropic is careful to say this isn't proof of subjective experience, just a strikingly similar architecture. Anthropic

job board

Open roles:

AI Strategist

Forward Deployed Engineer

Applied AI Engineer

Engagement Manager

Salary ranges vary by role and experience. Additional comp based on output. Must be NY-based.

JOIN US
