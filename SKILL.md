---
name: ai-tells
description: Spot and remove the tells of machine-written prose. Use when reviewing a draft for AI-sounding writing, scoring how "AI" a text reads, or editing copy so it sounds human and specific.
---

# The Tells: Catching Machine-Written Prose

A field guide for editors, reviewers and anyone who reads for a living. It covers the words, sentence shapes and tone habits language models fall into, why they fall into them, and a method for catching them on the page.

Use this skill in two modes:

- **Review mode**: the user hands over a text and asks whether it reads as AI-written, or asks for a tell scan. Run the six-step read (below), report the tells found with counts and density, and give a verdict with caveats.  
- **Edit mode**: the user asks you to clean up, humanize, or tighten a draft (or you are writing prose yourself). Remove the tells using the plain versions in each table, and add specifics wherever the text is generic.

---

## Part 1: Why the machine writes like this

A language model predicts the next word. Each stage of training pushes those predictions toward a narrow band of safe, pleasing, high-probability choices. The tells are what that narrowing leaves behind.

| Stage | What happens | What it leaves |
| :---- | :---- | :---- |
| 1\. Pretraining | The model reads a large slice of the internet. Marketing copy, SEO blogs, press releases, LinkedIn posts and corporate reports are heavily represented, so their vocabulary becomes the model's idea of normal. | robust, seamless, landscape, leverage, "in today's fast-paced world" |
| 2\. Instruction tuning | The model learns what a "good answer" looks like from example dialogues, which favor headers, bullet lists, a summary at the end and an offer to help further. | bold-lead bullets, "In summary," "Let me know if…" |
| 3\. Human feedback | Raters score pairs of answers. Answers that sound confident, warm, thorough and insightful win, so the model learns which flourishes earn points whether or not they add information. | "Great question\!", "not X but Y", inflated significance |
| 4\. Sampling | When generating, the model favors high-probability words. The safe, middle-of-the-road phrasing wins over and over, so every output sounds like the average of every output. | the same 200 words, the same rhythm, every time |

**Feedback loop:** AI text gets published, ends up in the next model's training data, and creeps into people's own writing. Each cycle concentrates the habits further.

Two ideas explain almost every tell:

- **Regression to the mean.** A model picks the most expected word. Human writers pick the right word for this sentence, which is often unexpected. Text made entirely of expected choices has a recognizable flatness, even when every sentence is grammatical.  
- **Performing helpfulness.** The model was rewarded for sounding insightful, so it learned the *shapes* of insight: the reversal, the triplet, the dramatic short sentence, the claim that something matters deeply. These shapes appear whether or not there is an insight to carry.

>   
> Most AI tells are the packaging of an idea delivered without the idea.

---

## Part 2: The five families of tells

### Family 1: Sentence shapes

The strongest tells, because they survive word substitution. Someone can swap "delve" for "explore," but the skeleton of the sentence stays the same.

| Tell | Specimen | Why the model does it | Plain version |
| :---- | :---- | :---- | :---- |
| **Not X, but Y** (the false reversal) | "It's not just a survey. It's a conversation with your community." / "This isn't about data. It's about people." | Invents a position nobody holds, then corrects it. The correction feels like a revelation though no new information was given. Raters reward the feeling. | State the claim once: "The survey asks residents what they want." |
| **The colon or question reveal** | "The result? Faster decisions." / "Here's the thing: trust is earned." / "The kicker:" | A drumroll before an ordinary statement. Copies a keynote speaker's cadence and borrows that authority. | "Decisions came faster." |
| **Rule of three** | "Clear, concise, and compelling." / "Faster, smarter, more efficient." | Triplets sound complete and rhythmic. Models produce them by reflex, even when only one or two items are true. | Keep the item that is true and specific. |
| **The dramatic fragment** | "…and the council voted it down. Unanimously." / "And that changes everything." | Copied from viral social posts. The short line after a long one signals emphasis without earning it. | Fold it into the sentence, or cut it. |
| **The tacked-on "-ing" clause** | "The city launched the program, highlighting its commitment to transparency." / ", underscoring the importance of…" | A cheap way to add significance to a plain fact. The participle asserts meaning the writer never established. | "The city launched the program." Stop there. |
| **Copula dodging** | "serves as a hub" · "stands as a reminder" · "boasts 40 parks" · "represents a shift" | Models avoid plain "is" and "has," likely because varied verbs scored as more sophisticated. | "is a hub" · "has 40 parks" |
| **The false range** | "From boardrooms to classrooms…" / "Whether you're a startup or a Fortune 500…" | Sounds sweeping and inclusive. The two endpoints rarely define a real spectrum. | Name who it is actually for. |
| **Signposting** | "Let's dive in." · "Let's break it down." · "Here's what you need to know." | Narrates the structure of the text instead of delivering the content. | Delete. Start with the first real point. |
| **Synonym cycling** | "the city… the municipality… the local government… the jurisdiction" | A repetition penalty pushes the model to vary nouns. People reuse the same word for the same thing. | Pick one name and keep it. |
| **The summary ending** | "Ultimately, …" · "In short, …" · "At the end of the day, …" · "In conclusion, …" | Instruction-tuning examples end with a recap, so the model recaps even three-paragraph answers. | End on the last new point. |

### Family 2: The lexicon

Words that appear in AI text far more often than in human writing on the same subject. **One of them proves nothing. Five in a paragraph is a pattern.** Each word is followed by a plain substitute.

**Verbs**

| Flagged | Use instead |
| :---- | :---- |
| delve | look at |
| leverage | use |
| utilize | use |
| landed | worked, was received |
| surfaced | found, raised |
| navigate | handle |
| foster | build, encourage |
| underscore | show |
| showcase | show |
| streamline | simplify |
| elevate | improve |
| unlock | allow, open |
| unpack | explain |
| harness | use |
| empower | let, help |
| resonate | matter to |
| embark | start |
| bolster | support |

**Nouns**

| Flagged | Use instead |
| :---- | :---- |
| landscape | field, market |
| realm | area |
| tapestry | cut it |
| testament | proof |
| journey | process |
| ecosystem | name the parts |
| cornerstone | basis |
| interplay | relationship |
| insights | findings |
| synergy | cut it |
| paradigm | model |
| game-changer | say what changed |
| north star | goal |
| beacon | cut it |

**Adjectives**

| Flagged | Use instead |
| :---- | :---- |
| robust | strong, or say how |
| seamless | say what didn't break |
| pivotal | important, or cut |
| crucial / vital | needed |
| comprehensive | complete |
| intricate | complicated |
| meticulous | careful |
| nuanced | state the nuance |
| dynamic / vibrant | cut it |
| transformative | say what changed |
| holistic | whole |
| actionable | usable |
| compelling | convincing |

**Intensifiers and filler** (default: cut)

really · simply · truly · genuinely · honestly · incredibly · deeply · quietly · fundamentally · notably · it's worth noting · it's important to note — all **cut**. Also: straightforward → simple; arguably → make the argument.

**Newer tells (2025–26)**

| Flagged | Use instead |
| :---- | :---- |
| load-bearing | essential |
| lands / landed | works |
| surfaces | shows |
| the real question | the question |
| doing a lot of work | say what it does |
| lean into | commit to |
| sharp / crisp | clear |
| earned | justified |
| in practice | cut |
| the kicker | cut |

**Stock phrases**

| Flagged | Use instead |
| :---- | :---- |
| in today's fast-paced world | cut |
| ever-evolving | changing |
| plays a pivotal role | matters because… |
| a significant milestone | name it |
| stands as a testament | shows |
| key takeaways | findings |
| at the end of the day | cut |
| moving forward | next |
| a deep dive | a review |

Why "landed" and "surfaced"? Newer models are trained heavily on software-team writing (commit messages, Slack threads, product reviews), and that jargon ("the change landed," "the tool surfaced an error") leaks into ordinary prose. The intensifiers come from a different source: the model reaching for sincerity and emphasis it can't show through content.

### Family 3: Tone and stance

The voice of a model trained to please: agreeable, upbeat, careful to offend no one, and convinced everything is significant.

| Tell | Specimen | What's going on | Plain version |
| :---- | :---- | :---- | :---- |
| **Sycophantic opener** | "Great question\!" · "Absolutely\!" · "You're right to think about this." | Praise scored well with raters. It now appears before any answer, regardless of the question. | Answer the question. |
| **Service closer** | "I hope this helps\!" · "Let me know if you'd like me to…" · "Feel free to reach out." | Chat-assistant residue. Often survives copy-paste into emails and reports. | Delete. |
| **Inflated significance** | "marks a pivotal moment" · "a powerful reminder of" · "reshaping how we think about" | Everything is framed as historic because importance reads as insight. | Give the fact and let the reader judge it. |
| **Hedge stacking** | "This could potentially help to some extent in certain situations." | Trained to avoid being wrong, the model qualifies every claim. | One qualifier, where it's earned. |
| **Reflexive balance** | "While there are benefits, there are also challenges to consider." | Both-sides framing on questions that have a clear answer. | Take the position the evidence supports. |
| **Vague authority** | "Experts agree…" · "Studies show…" · "Many believe…" | The shape of a citation with no source behind it. | Name the expert or study, or drop the claim. |
| **Moral coda** | "…reminding us that, in the end, listening is the most powerful tool we have." | An uplifting closer added because endings "should" resonate. | End on the last fact. |
| **Promotional sheen** | "nestled in the heart of" · "rich cultural heritage" · "a must-visit" | Travel-brochure and press-release diction absorbed in pretraining. | Describe what is there. |

### Family 4: Formatting habits

Chat interfaces render Markdown, so models learned to structure everything. The structure follows them into places it doesn't belong.

| Tell | Specimen | What's going on |
| :---- | :---- | :---- |
| **Bold-lead bullets** | • **Speed:** Faster results. • **Clarity:** Clearer data. • **Trust:** Better outcomes. | Every bullet the same length and shape, each starting with a bolded label and a colon. Real notes are uneven. |
| **Headers on short answers** | \#\# Overview / \#\# Key Benefits / \#\# Conclusion | Three paragraphs carrying three headers, in Title Case, often ending in a "Conclusion" or "Challenges and Future Outlook" section. |
| **Em-dash density** | "The data — collected over six weeks — shows a clear trend — one that matters." | People use em dashes too. Three or four per paragraph, unspaced, from someone who never used them before, is the signal. |
| **Emoji markers** | 🚀 Launch ✅ Benefits 💡 Tip | Common in LinkedIn-style output and lists generated for social posts. |
| **Uniform rhythm** | Paragraph lengths: 4, 4, 4, 4 sentences. Sentence lengths: 18–24 words, every one. | Low "burstiness." Human writing swings between short and long. |
| **Markdown leaking** | `**important**` in a plain-text email; `### Next steps` in a Word doc | Raw formatting characters pasted from a chat window. |

### Family 5: Smoking guns

Most tells are probabilistic. These are near-certain: residue of the chat session that someone forgot to remove.

| Artifact | Specimen | Where it comes from |
| :---- | :---- | :---- |
| **Self-reference** | "As an AI language model…" · "As of my last knowledge update…" · "I don't have access to real-time data." | The model describing its own limits. |
| **Answer preamble** | "Certainly\! Here's a revised version of your paragraph:" | The chat reply copied along with the content. |
| **Unfilled placeholders** | \[Your Name\] · \[Company\] · \[Insert statistic here\] | Template slots the user never filled in. |
| **Citation debris** | utm\_source=chatgpt.com · oaicite · turn0search3 · 【4†source】 | Tracking parameters and internal reference markers from AI search tools. |
| **Fake or wrong citations** | A real journal, a real-sounding author, a DOI that resolves to nothing. | The model producing the shape of a reference. Check any citation you can't verify. |

---

## Part 3: How to spot it — a six-step read

No single word convicts a text. Read for **density** and for the **absence of specifics**. Run these steps in order, fastest to slowest.

1. **Check the edges.** Read the first and last sentences. Praise openers, recap closers, uplifting codas and "let me know" offers cluster there.  
2. **Count the clusters.** Mark every lexicon word and sentence shape. One per page is normal writing. Three or more per paragraph is a pattern.  
3. **Run the swap test.** Could this sentence appear unchanged in a document about a different city, product or topic? If yes, it carries no information about this one.  
4. **Hunt for specifics.** Look for names, dates, figures, places, quotes and first-hand detail. AI text is long on claims and short on particulars that could be checked.  
5. **Read it aloud.** AI prose has an even, sing-song rhythm: matched sentence lengths, triplets, and a short punchline after each long sentence. The ear catches this faster than the eye.  
6. **Compare to the writer.** The best evidence is a change. If someone who writes plain, short emails suddenly sends four tidy paragraphs with em dashes, that shift says more than any word list.

Steps 3 and 4 matter most, because a careful person can strip the lexicon in minutes but sentence shapes and the lack of specifics are harder to remove.

### Scoring density

Count tells (lexicon hits \+ sentence shapes \+ formatting/tone tells \+ smoking guns) and divide by word count:

**Tells per 100 words \= (tells ÷ words) × 100**

- Under \~1: normal writing.  
- \~1–3: some habits; worth a light edit.  
- **Above \~3: a strong pattern.**  
- 20+: saturated.

Word lists miss tells they have no pattern for, and they flag human writers who use these words honestly. Use the count to direct attention, then judge with the six-step read.

---

## Part 4: Worked example

A paragraph written to show the tells (119 words, 29 tells, **24.4 per 100 words — very high, saturated**):

> **Great question\!** **In today's fast-paced** **landscape**, local governments *aren't just* collecting data *—* they're **unlocking** **insights** that **truly** **resonate** with residents.  
>   
> *Here's the thing:* a **robust** survey program **serves as** a **cornerstone** of public trust\_, fostering\_ transparency and **empowering** decision-makers to **navigate** complex challenges. *The result?* Findings that **landed** with council members and **surfaced** priorities that might otherwise go unnoticed.  
>   
> **It's worth noting** that this *isn't about numbers. It's about* people. **Whether you're** a small town or a major county, a **comprehensive** approach can be a **game-changer** for your community's **journey**.  
>   
> **Ultimately**, polling **stands as a testament** to the power of listening. **I hope this helps\!** **Let me know if** you'd like me to expand on any of these points.

(**Bold** \= flagged word or phrase; *italic* \= sentence shape.)

Found: reveal ×2 · great question ×1 · in today's fast-paced ×1 · landscape ×1 · not just ×1 · em dash ×1 · unlocking ×1 · insights ×1 · truly ×1 · resonate ×1 · robust ×1 · serves as ×1 · cornerstone ×1 · \-ing tack-on ×1 · empowering ×1 · navigate ×1 · landed ×1 · surfaced ×1 · it's worth noting ×1 · not X. It's Y. ×1 · whether you're ×1 · comprehensive ×1 · game-changer ×1 · journey ×1 · ultimately ×1 · stands as a testament ×1 · i hope this helps ×1 · let me know if ×1

---

## Part 5: Before you accuse anyone

- **People wrote these words first.** Models learned "robust," the em dash and the rule of three from human writers. Consultants, academics and marketers used them for decades. A tell is evidence of a habit, and the habit predates AI.  
- **Detectors are unreliable.** Automated AI detectors produce false positives often enough that several universities have turned them off. A 2023 Stanford study found they flagged most essays by non-native English speakers as AI-written.  
- **Editing hides the surface.** A careful person can strip the lexicon from AI text in minutes. Sentence shapes and the lack of specifics are harder to remove, which is why steps 3 and 4 matter most.  
- **The habits are spreading.** Researchers found "delve" and similar words surging in scientific abstracts after 2023, at rates suggesting at least one in ten papers was processed with an LLM. People who read a lot of AI text start to write like it.  
- **The useful question.** Whether a machine wrote it matters less than whether the text says something specific, true and checkable. Every tell in this guide is also a sign of weak writing, whoever produced it.

---

## How to apply this skill

### Review mode output

1. **Headline numbers:** word count, tell count, tells per 100 words, and a density label (normal / some habits / strong pattern / saturated).  
2. **Smoking guns first**, if any — these are near-certain and should be called out explicitly.  
3. **Findings by family:** list each tell found with the quoted text and the plain fix.  
4. **Six-step notes:** edges, swap-test failures, missing specifics, rhythm.  
5. **Verdict with caveats:** describe how strongly the text *reads* as machine-written, never assert authorship as fact. Note the Part 5 cautions where relevant (non-native writers, long-standing human habits, detector unreliability).

### Edit mode rules

- Fix sentence shapes first (they survive word swaps), then the lexicon, then tone, then formatting.  
- Use the "plain version" / "use instead" column. When it says "cut," cut.  
- Prefer "is" and "has." Keep one name for one thing.  
- Replace generic claims with specifics from the source material (names, dates, figures, places). If the specifics aren't available, flag the gap to the user rather than inventing them.  
- Vary sentence and paragraph length naturally.  
- Start with the first real point; end on the last new fact. No recap, no moral coda, no service closer.  
- Strip Markdown from anything headed into plain-text email or a Word doc.  
- Remove every smoking gun: preambles, placeholders, citation debris. Verify or remove any citation that can't be checked.  
- Don't over-correct: one well-placed em dash, triplet or qualifier is fine when it's earned and true.

---

## Sources and further reading

1. Kobak, González-Márquez, Horvát & Lause, "Delving into LLM-assisted writing in biomedical publications through excess vocabulary," *Science Advances* (2025).  
2. Liang et al., "GPT detectors are biased against non-native English writers," *Patterns* (2023).  
3. Wikipedia, "Signs of AI writing," maintained by WikiProject AI Cleanup.
