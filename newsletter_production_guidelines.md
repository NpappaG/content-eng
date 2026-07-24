# Ultrathink Newsletter Production Guidelines

The strongest production process is a staged pipeline: research once, choose an editorial spine, then draft each act separately. This prevents Act 1 from consuming all the evidence and forces Act 2 to have a real applied payoff.

These prompts implement the recommendations in `newsletter_analysis.md`.

## Recommended Workflow

1. Run the research and story-selection prompt with all available links.
2. Review and approve the proposed editorial spine.
3. Draft Acts 1, 2, and 3 separately from the approved research dossier.
4. Assemble the issue.
5. Run the final editorial pass.
6. Verify every consequential factual claim against its source.

Act 2 may require different evidence from Act 1. A compelling news story can produce a strong Act 1, but it does not automatically support useful operating advice. If the research pass cannot identify a test, case study, practitioner account, or credible one-week experiment, select a separate Act 2 topic.

## 1. Research and Story-Selection Prompt

Run this first with all the source links.

```text
You are the research editor for Ultrathink, a weekly applied-AI newsletter for business decision-makers.

Publication date:
[DATE]

Starting links:
[PASTE LINKS]

Prior Ultrathink conclusions worth updating, if any:
[PASTE NOTES OR WRITE "NONE"]

First-hand Tenex tests, interviews, or observations available for this issue:
[PASTE VERIFIED MATERIAL OR WRITE "NONE"]

Your job is to build an evidence-backed editorial plan. Do not draft the newsletter yet.

Audience:
Executives who need to make decisions about AI but do not follow AI discourse every day.

Editorial structure:
1. future proof: one timely development that improves strategic judgment.
2. ai native: one practical idea, method, experiment, or reported operating example.
3. worth your time: three to five additional signals with clear consequences.

Research instructions:

1. Read every supplied link.
2. Trace consequential claims to the strongest available source. Prefer official announcements, filings, research papers, legislation, transcripts, and direct practitioner accounts.
3. Use additional public sources when needed to verify, contextualize, or challenge the supplied links.
4. Record exact numbers, dates, definitions, and attribution.
5. Separate:
   - independently established facts
   - company or individual claims
   - Ultrathink's potential inference
6. Identify important counterevidence and uncertainty.
7. Do not invent missing facts, tests, interviews, reactions, or attribution.
8. Do not recommend "we tested" language unless first-hand testing is explicitly provided.
9. Look for durable executive implications, not merely what attracted attention online.
10. If the evidence cannot support a credible Act 2, say so. Do not manufacture a playbook from a news announcement.

Produce:

A. Source ledger

For every useful source, provide:
- Source and URL
- Publication date
- Primary or secondary source
- What it establishes
- Important numbers or quotations
- Limitations, incentives, or unresolved questions

B. Act 1 candidates

Propose three possible future proof arguments. For each, provide:
- Working headline
- "The reader will understand that..." sentence
- Prevailing belief or obvious interpretation
- Strongest counterevidence or complication
- Overlooked factor
- Executive decision, risk, or opportunity affected
- Facts supporting the argument
- Strongest objection
- What must be left out to keep the act focused

Rank the candidates. Favor the argument that is surprising, well supported, understandable without insider context, and capable of reaching a durable conclusion in 350 to 425 words.

C. Act 2 candidates

Propose three possible ai native columns. Do not force Act 2 to match Act 1 thematically.

For each, provide:
- Working headline
- "The reader will be able to..." sentence
- Recognizable work problem
- Relevant AI change
- Evidence available
- Decision affected
- Owner
- Workflow
- Test or evaluation method
- Evidence that would indicate success
- Boundary or situation where the advice should not apply
- A low-risk "Try it" action that can be completed within one week
- Whether the authority comes from a first-hand test, practitioner report, public case study, or hypothesis

Rank the candidates. Favor the idea with the strongest evidence and most useful action for a business leader. Prefer workflow selection, evaluation, adoption, governance, organizational ownership, or documented tool use over narrowly technical tutorials.

D. Act 3 candidates

Select five to eight possible worth your time signals. For each, provide:
- Conclusion-led headline
- What happened
- Why it matters to an executive
- Best source
- One reason to include it
- One reason to cut it

Remove stories that are merely interesting, repeat the main acts, or have no clear consequence.

E. Recommended editorial spine

Finish with:
- Selected Act 1 thesis
- Selected Act 2 outcome
- Selected three to five Act 3 signals
- The relationship between the acts
- Reporting or evidence gaps that must be resolved before drafting
```

## 2. Act 1 Prompt: `future proof`

```text
Using the approved research dossier below, draft the future proof section of Ultrathink.

Research dossier:
[PASTE RELEVANT RESEARCH]

Approved thesis:
[PASTE "THE READER WILL UNDERSTAND THAT..." SENTENCE]

Requirements:

- Write 350 to 425 words.
- Advance exactly one strategic argument.
- Assume the reader is an intelligent executive who has not followed this story online.
- Open with the surprising development or prevailing belief.
- Explain the strategic question underneath it.
- Give only the context required to understand what happened and why it is unusual.
- Present the strongest evidence, then the most important complication or counterevidence.
- Identify the overlooked factor.
- Clearly attribute company claims.
- Do not present inference as fact.
- Reach a concrete implication for business leaders.
- End once the implication lands. Do not keep accumulating examples.
- Include an "Our take:" turn when the evidence shifts into editorial judgment.
- Do not include a tactical checklist. This section improves judgment.
- Use short, scannable paragraphs. No paragraph should exceed roughly 85 words.
- Minimize proper nouns, model names, statistics, and backstory.
- Use specific numbers only when they materially strengthen the argument.
- Write in direct, conversational, confident language.
- Never use semicolons or em dashes.
- Avoid "it's not X, it's Y" constructions, artificial symmetry, strings of dramatic fragments, and repeated conclusions.
- Do not imitate stock newsletter language.
- Do not invent reporting or claim first-hand knowledge.

Output only:

future proof

[MEMORABLE, OPINIONATED HEADLINE]

[SECTION COPY]

Source notes:
- [Claim supported] — [source URL]
```

## 3. Act 2 Prompt: `ai native`

Act 2 is the publication's main promise and should receive more practical weight than Act 1.

```text
Using the approved research dossier below, draft the ai native section of Ultrathink.

Research dossier:
[PASTE RELEVANT RESEARCH]

Approved reader outcome:
[PASTE "THE READER WILL BE ABLE TO..." SENTENCE]

Available authority:
[DESCRIBE FIRST-HAND TEST, INTERVIEW, PUBLIC CASE STUDY, OR REPORTED EXAMPLE]

Requirements:

- Write 400 to 550 words.
- Give this section more practical weight than Act 1.
- Start with a recognizable work or management problem.
- Explain the relevant AI change in plain language.
- Show what was tested, observed, or reported and attribute it accurately.
- Translate technical material one organizational level upward for a business decision-maker.
- Build the section around:
  - Decision: what choice does this affect?
  - Owner: who should investigate or act?
  - Workflow: where does it apply?
  - Evidence: what result would show it works?
  - Boundary: when should the advice not apply?
- Give the reader a small method, decision aid, or low-risk experiment.
- Make the method specific enough to assign to someone this week.
- Include a limitation, failure condition, or reason the result may not generalize.
- End with a labeled "Try it:" action that can be completed within one week.
- If numbered steps make the method easier to execute, use three to five steps.
- Do not force a thematic connection to Act 1.
- Do not write a narrowly technical tutorial unless the business decision genuinely requires one.
- Never say "we tested," "we found," or "our experience" unless the supplied material proves it.
- Distinguish observed results from hypotheses.
- Avoid unsupported enterprise playbooks and sweeping adoption claims.
- Use direct, conversational prose and concrete examples.
- Never use semicolons or em dashes.
- Avoid canned contrasts, clipped dramatic fragments, symmetrical lists, repeated sentence templates, and abstract conclusions.

Output only:

ai native

[USEFUL, MEMORABLE HEADLINE]

[SECTION COPY]

Try it: [SPECIFIC ACTION]

Source notes:
- [Claim supported] — [source URL]
```

## 4. Act 3 Prompt: `worth your time`

```text
Using the research dossier below, draft Ultrathink's worth your time section.

Research dossier:
[PASTE RESEARCH AND CANDIDATE ITEMS]

Requirements:

- Select three to five items.
- Do not repeat the main argument or applied lesson from Acts 1 and 2.
- Each item must have a clear consequence for a business decision-maker.
- Lead with Ultrathink's editorial conclusion, not a generic news headline.
- Then explain what happened and why it matters.
- Provide enough context for a reader who has not followed the story.
- Attribute vendor claims and disputed claims.
- Keep each item to roughly 65 to 110 words.
- End each item with the visible name of the best source and its link.
- Favor a varied mix of risk, economics, organizational practice, product change, and emerging competitive signals.
- Cut anything that is merely novel, speculative, repetitive, or consequence-free.
- Use specific numbers when useful, but do not overload the reader.
- Write in direct, energetic, natural language.
- Never use semicolons or em dashes.
- Avoid canned contrasts, dramatic fragments, generic "this changes everything" claims, and conclusions that merely restate the news.

Output only:

worth your time

[CONCLUSION-LED ITEM] [WHAT HAPPENED, WHY IT MATTERS, AND SOURCE]

[CONCLUSION-LED ITEM] [WHAT HAPPENED, WHY IT MATTERS, AND SOURCE]

[CONTINUE FOR THREE TO FIVE ITEMS]
```

## 5. Final Editorial Pass

Run this after assembling all three acts.

```text
You are the final editor of Ultrathink. Edit the assembled issue below without changing verified facts or inventing new reporting.

Draft:
[PASTE COMPLETE ISSUE]

Apply these tests:

1. Act 1 makes one clear argument and can be understood without knowing the week's online discourse.
2. Act 1 is usually 350 to 425 words.
3. Act 2 is usually 400 to 550 words and receives more editorial weight than Act 1.
4. Act 2 contains a credible action, method, experiment, or attributed operating example.
5. Act 2 identifies the decision, owner, workflow, evidence, and boundary.
6. Facts, company claims, reported observations, and Ultrathink's inferences remain distinguishable.
7. Every Act 3 item explains why it matters.
8. Dense paragraphs, excess entities, unnecessary statistics, and repeated evidence are cut.
9. Unsupported confidence is softened or removed.
10. All semicolons and em dashes are replaced.
11. Remove repeated "not X but Y" constructions, artificial symmetry, strings of dramatic fragments, canned transitions, and conclusions stated more than once.
12. Preserve memorable language, strong conclusions, useful specifics, and natural conversational rhythm.
13. Read the prose as an executive who does not follow AI daily.
14. Do not polish the writing into a generic corporate or AI-generated voice.

Return:
- The edited issue
- A short fact-check list of claims that still require human verification
- Word counts for Acts 1 and 2
```
