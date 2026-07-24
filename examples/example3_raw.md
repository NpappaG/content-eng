The moat is a parking lot

Why the AI race just turned into a fight over electricity Tesla already owns, plus the five-part "loop" that turns the AI tasks you redo every week into something that runs itself.

Brad Haft

Jun 23, 2026 • 6 min read

Tenex ultrathink

Happy Tuesday ⚡️

Amazon reportedly spent around $75 million making a movie about Sam Altman, then shelved it weeks before release. Luca Guadagnino's "Artificial" casts Andrew Garfield as Altman across the five days OpenAI fired and rehired him, and early screenings went well, right up until someone connected it to the $50 billion Amazon poured into OpenAI in February. Word is the final cut runs darker than the pitch, with Altman and Musk landing as the two characters audiences like least, so Amazon dropped it and Netflix and Focus took a look and passed too. The most expensive studio note in history might be "our new strategic partner comes off badly."

Today, we're talking about:

Tesla quietly trademarking a way to skip the years-long wait for grid power, and why the whole AI race just turned into a fight over electricity

The five-part "loop" that turns the AI tasks you redo every week into a system that runs itself, and how to build your first one

Plus the AI that broke into the NSA in hours, a Chinese model spooking Silicon Valley, and a tiny-house kit strangers funded before it existed

future proof

The Moat Is a Parking Lot

The thing the AI giants can't buy their way out of this year isn't computer chips, and it isn't models. It's electricity, plus somewhere to plug it in. The big labs have the cash and the chip orders to build whatever they want, but the power to actually run it is stuck behind a grid-connection line that now takes years. That one bottleneck is quietly redrawing the map of who wins, and last week Tesla filed paperwork suggesting it found a way around the line entirely.

On June 18, Tesla filed a trademark for something called MEGAPOD, a modular AI data center you assemble on site: servers, networking, power, and cooling in one crate. The box isn't the interesting part, though; where Tesla wants to put it is. Musk has said the company plans to bolt compute straight onto its Supercharger locations, where it already sits on roughly 7 gigawatts of power that's wired up and permitted. While OpenAI and Oracle pour $500 billion into Stargate to raise 10 gigawatts of data centers out of empty dirt, a job measured in years, Tesla is holding a power footprint nearly that big that it built for charging cars and can quietly repoint at AI chips.

Then there's the bigger idea Musk floated on an earnings call, the one that sounds invented but isn't. Every Tesla already carries a chip built for self-driving, and the average car sits parked about 95% of the day. Link enough of them and you get what he calls distributed inference, the AI's work spread across millions of cars instead of one giant building. By his math, 100 million cars at a kilowatt each is 100 gigawatts of computing that somebody else already bought, powered, and cooled. Our take is that the Supercharger half of this is real and shrewd, because permitted power is the scarce thing right now and Tesla has a decade's head start on it. The parked-car half is a someday story, since Tesla has maybe 8 million cars on the road today instead of 100 million, and nobody has solved the lag, the security, or the simple question of why you'd lend a stranger your car's brain. Price in the parking lots; leave the driveways for later.

The people on the losing end are everyone still standing in the grid line. The same day Tesla filed, the federal energy regulator got nervous enough about that backlog to order the big grid operators to fast-track data centers, aiming to cut a multi-year wait down toward 90 days, as long as those data centers bring their own power or go quiet when the grid is strained. When Washington starts rewriting the rules of the power grid to get AI plugged in faster, electricity has stopped being a line item and become the whole contest.

And the cost doesn't evaporate; in places where data centers are multiplying fastest, regulators are already staring at bills that ordinary ratepayers could end up covering. For everyone not named Tesla, the read is colder: if your AI plans assume compute keeps getting cheaper and easier to get, the thing your vendors start rationing is power.

Tesla spent ten years building the largest private fast-charging network on the planet, and everyone filed it under cars. Turns out it might have been building the one thing this boom can't make more of fast enough: a parking lot that's already wired to the grid.

We Build Loops for a Living

Tenex is the AI engineering team behind this newsletter, and turning a company's grunt work into loops that run themselves is a big part of what we actually do. We sit with your team, find the routine work worth handing off, build the loops, and train your people to keep building them after we go.

Talk to our team →

ai native

Build Your First Loop

The best builders have stopped writing prompts. Boris Cherny, who runs Claude Code at Anthropic, put it plainly: "I don't prompt Claude anymore. I have loops running that prompt Claude. My job is to write loops." In Claude Code you now just type /loop and walk away. So what's a loop, and why does it beat a prompt?

A loop hands the AI a goal and a way to check itself, then lets it run, try, check, fix, until it can prove the job is done. The shape fits anything with a clear finish line: a bug ("don't quit until the tests pass"), the month's books ("reconcile until every transaction matches"), or a research brief ("keep digging until all ten questions have a source").

The free Loop Library breaks a good one into five parts:

Trigger: what kicks it off.

Action: the work it does each pass.

Proof: how it checks itself, the part everyone skips.

Memory: what carries from one run to the next.

Stopping condition: how it knows to quit.

Starting is almost too easy: tell it to loop until it's done.

1. Pick a weekly chore. The metrics recap, the pipeline update, the report you rebuild every Monday.

2. Define "done." Write those five parts in plain English, then nail the proof: tell it exactly how to know it got the task right.

3. Run it once, then let go. Watch the first pass, fix the one thing that's off, and after that just check the output.

Try it: Don't start from scratch. The Loop Library is free and full of loops to grab and bend to your job, from a daily error sweep to a weekly review that spins up its own helpers.

worth your time

Mythos broke into the NSA in hours — Last week one line tore through X: Senator Mark Warner said the general who runs the NSA told him Anthropic's Mythos model "broke into almost all of our classified systems, not in weeks, but in hours," days before the government pulled it from the public. This weekend the missing context caught up: it happened in an authorized red-team drill, and Warner brought it up to praise Anthropic and push for testing frontier models this hard before release, not to flag a hack. The scariest AI claim of the month turned out to be a stress test working as designed. IBTimes

A Chinese model is rivaling GPT-5.5 at coding for a sixth of the price — Vercel's CEO said he was almost shocked at how good GLM-5.2 is at coding, and it's open (free for companies to download and run themselves) at about a sixth of what the top models cost. That lands on a point making the rounds with engineering leaders: plenty of big orgs are overspending on AI and underusing it at the same time, defaulting every task to the biggest, priciest model when a cheaper one would do. Before you cap budgets, check your defaults.

Codex will learn a chore by watching you do it once — OpenAI shipped Record & Replay for Codex this month: show it a recurring task once, like pulling a weekly report or filing an expense, and it turns the demo into an editable, reusable skill. It's the same idea as a loop, with the setup done by demonstration instead of writing. Mac only for now.

Claude Code can now hand your team a clickable page — New in Claude Code: Artifacts, interactive pages built straight from a session, like a walkthrough of a code change or a living project dashboard, shared with your team at a private link. The output of an AI session is becoming something you hand to people, not just a transcript you read. In beta on Team and Enterprise plans.

A guy pre-sold a product before building a single unit — Ethan Buck launched BYLT, a kit where you build a tiny house with real blueprints, framing, and wiring instead of snapping plastic bricks, and let the crowd fund it before anything shipped. The old playbook of proving demand before you build just opened up to everyone: with AI, one person can spin up the video, the storefront, and the campaign to test an idea before risking a dollar.

Anthropic's chip supplier is also its customer, partner, and investor — In one announcement, Micron agreed to supply the HBM, DRAM, and SSDs Claude runs on, co-design that memory around Claude's workloads, roll Claude out across its own factories and engineering, and invest in Anthropic's Series H. That makes Micron supplier, customer, partner, and shareholder all at once, the kind of knot you only tie when the physical supply chain becomes the thing worth locking up. The market noticed: Micron popped more than 5% on the news. Yahoo Finance

job board

Open roles:

AI Strategist

Forward Deployed Engineer

Applied AI Engineer

Engagement Manager

Salary ranges vary by role and experience. Additional comp based on output. Must be NY-based.

JOIN US
