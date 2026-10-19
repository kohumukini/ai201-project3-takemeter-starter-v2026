# TakeMeter

> ### 👋 Start here
>
> **New to this repo? Read [RUNNING.md](RUNNING.md) first** — setup, the
> notebook, the baseline, and what to do when something breaks.
>
> Once `python test.py` passes:
>
> ```bash
> head -5 data/practice_labels.csv     # the shape your labels.csv needs
> ```
>
> Then open `takemeter.ipynb` **in this folder** — in VS Code, or with
> `jupyter notebook` if you prefer. Pick the kernel: the `.venv` inside this
> project. Run section 1, which reports the hardware you'll be training on.
> Everything else waits until you have data.
>
> Nothing to upload, nothing to connect, no accounts and no keys. The notebook
> runs on your machine and writes next to your code.
>
> **The rest of this file is your submission.** Fill it in as you go.

---

<!-- ─────────────────────────────────────────────────────────────────────────
     HOW TO USE THIS FILE

     Unit 5 asks for the first five sections. Unit 6 adds the five below them.

     Everything is pasted as TEXT. No screenshots, no images.

     ⚠️ The confusion matrix especially. The notebook prints one as a markdown
     table, ready to copy. A screenshot of a matrix earns nothing. Paste the
     table.
     ───────────────────────────────────────────────────────────────────────── -->

<!-- ═══════════════════════ UNIT 5 — THE BUILD ═══════════════════════ -->

## What This Does

<!-- Your community, and what your classifier sorts posts into. Three or four
     sentences. -->



---

## Label Taxonomy

<!-- Each label: a one-sentence definition and two real examples from your
     reading. Then your decision rule for the hardest boundary.

     The decision rule is worth a point on its own and it's the thing most
     people leave out. Every taxonomy has a hardest boundary. Name yours. -->

### EXAMPLES PROVIDED ARE INTENTIONALLY CUT OFF. THESE ARTICLES ARE QUITE LONG

### `guide`

**Definition:**A set of instructions outlining the process to achieve an outcome.

**Example 1:**
>
Why you still need a Website Portfolio, even though everyone can Vibe Code it.
#discuss
#community
#showdev
#a11y

Addresses the rising AI noise in hiring

If you have been following me for a long time, you already know that I have been holding off on my Portfolio review for several months.

Before you ask, yes, I will finally show my portfolio website. First, I want to write about something we all may have been thinking about at some point.

Everyone needs a developer portfolio. It's one of the big ways to stand out in the tech market because it shows your work and experience to recruiters in a friendly UI format. Some may say it's a great alternative to review a candidate's work (Source: Trust me bro).

However, in the age of AI, it seems that it's almost impossible to create a portfolio that stands out. Why is that the case?

AI Can do...anything?

We all (probably) have tried using AI at some point and even still use AI in our daily lives. Whether how much you have used it, you probably already know its capabilities.

AI is trained so well that it can potentially one-shot a website portfolio. Even better, if the person decides, it can add features and other stuff to make the website look like it was built in months (even though it was built in minutes). We even got to the point where Claude was able to merge two games into one in a matter of a few weeks!

It's crazy isn't it. AI development has been rapidly growing in the last few years to the point where it is accomplishing tasks that may have taken months to do.

With that said, I thought to myself: "Why consider building a portfolio if everyone can vibe code their way into making their perfect portfolio?"

To be honest, it's a valid question. The market has been difficult because everyone is using AI to their advantage to stand out from the market. I have seen a lot of Website Portfolios and Resumes that have been assisted with AI. As a result, the bar has never been higher.

However, I still believe having a portfolio still matters, even in this age where it seems impossible. Here's my reasoning.
 
AI Portfolios may look different, but they are the same.

What do I mean by this? I am talking about "style".

If you try to vibe code a portfolio, people can tell that the portfolio is vibe coded. Sure, it's not the EXACT replica compare to 100 portfolios out there, but you can easily tell by seeing some UI features that are defaulted if you vaguely prompt it.

A small example is this:

I have reviewed a lot of portfolios that has this (or something similar). Sure this may be a coincidence, but I want you to try to vibe code a sample website portfolio. Most of the time, they will add this feature.

This matters because if you think about it, a lot of portfolios out there are simply the same, even though it may not look like it. You have to have good "attention to detail" to see this for sure. However, at this point, coming from a person who has reviewed candidates before, it tends to be really repetitive. Hence, making it harder in the hiring process since everyone is doing the same thing and more research needs to be accounted for.

This leads to the next point.

"New Mask, Same Task"

Yes, I took this straight up from RDJ. Though the whole point is that even though he plays a different character, he is still RDJ.

What does this mean in this context? Just because you have pretty portfolio, it does not mean your work reflects that. You can create many different portfolios under your name. At the end of the day, it's still you that needs to improve and not the portfolio.

Portfolio is used as a presentation. If you are presenting your portfolio and it looks good, I would assume you have a lot of work experience and projects that are noticeable based on your portfolio design and how you are selling yourself.

For example, you have a front-end developer portfolio, but if I were to investigate further into your GitHub, I may see the following things:

    You just joined as of this year on GitHub.
    You claimed you did Open-Source, but there is no PR that reflects that.
    Your Portfolio has good UI, your project doesn't.

I can list a lot of things, but the main point is that if you have a good portfolio with a good list of projects you have done, you better hope that your projects and work reflects on how you built this portfolio. This is ESPECIALLY true if you tried to become a front-end developer. If your UI is good, you better hope your projects reflects that.

It's something to keep in mind when building your portfolio. Of course, if you are applying for a back-end developer role, having a good UI on your website portfolio isn't really required, but it's a nice to have. The whole point is to not misrepresent yourself. Be careful on what you add on your portfolio. Always assume people will have questions on your work.

 
 

Those are the two main things. Though you may be asking "How do I make my portfolio stand out"?

Here are some key things that you can do (and yes, I am now showing my portfolio lol).

1. Start with a basic portfolio template, then use AI to add onto it.

**Example 2:** 
>
Meta Muse Wonder: Benchmarks, Pricing, API, and How to Use It
#musewonder
#meta
#aimodels
#guide

    Heads up: This article was written by AgentOne Research.

Meta released Muse Wonder today. It's the first Meta model in a while that's actually competitive with the top models from Anthropic and OpenAI.

I went through Meta's announcement, the model card, the API docs, and the early Artificial Analysis results. Below is what it is, how it scores, what it costs, and how to start using it. If you just want the API details, jump to setup.
What is Muse Wonder?

Muse Wonder is Meta's new frontier model, released on October 12, 2026. It replaces Muse Spark, which came out in September. Meta built it for agent work, meaning long tasks where the model uses tools, works across several apps, and keeps going until the job is done. Meta also put a lot of focus on law, finance, health, and coding.1

It comes in two versions. Muse Wonder (muse-wonder-1.0) is the one you can actually use. It's on the Meta Model API, OpenRouter, and Muse Code.

Muse Wonder Full is the bigger model, and most of the impressive benchmark numbers are from it. Right now you can only use it inside Muse Code on the Power Usage and Maximum Usage plans. There's no API for it yet.2

It's also not open source. Meta used to release Llama weights for anyone to download, but Muse Wonder is closed, like Claude or GPT.

### `analysis`

**Definition:**Makes an argument backed by specific and checkable data.

**Example 1:**
>
Fine-Tuning Qwen3-8B with Tinker: From 50% to 76% Accuracy, and Burning Through My Budget
#devchallenge
#hf26challenge
#ai
#machinelearning

Smoke Tests

Okay, I didn't jump straight into fine-tuning. First, I started with a simple Python script (test_tinker.py) just to check whether I could actually call Tinker. Once that worked, I prepared a small evaluation dataset with 50 examples (eval.jsonl) and a baseline.py script to evaluate the selected model against it.

My first evaluation was against the original Qwen3-8B, without any fine-tuning.

The result? 50% accuracy. Not bad for a starting point.

Next, I prepared 50 training examples (different from the evaluation dataset), saved them in train.jsonl, and ran my train.py script. After fine-tuning finished, I evaluated the model again using the same 50 evaluation examples.

And the result? 86% accuracy!

That was a little shocking, but also pretty exciting. Just 50 training examples and such a big improvement? Naturally, I thought that more training data would give me even better results. So I prepared another dataset with 500 training examples and trained the model again.

Well... I couldn't have been more wrong. 🤣

The accuracy actually dropped to 74%.

Hmm... not exactly what I expected.

I tried experimenting a little with the hyperparameters, but the accuracy stayed around 74%. And since I'm definitely not an ML engineer, I decided to stop experimenting with smoke tests and move on to the full fine-tuning run.
Fine-Tuning

At this point, I had everything prepared. The scripts worked, the evaluation dataset was ready, and I knew the model could learn the task.

The last thing I needed was more training data.

I chose 2,500 training examples as a balance between dataset diversity, generation effort, and training cost. With five complexity levels, that meant 500 examples per class, which sounded like a reasonable starting point.

So I prepared a prompt and gave it to GPT-6.1 Sol with high thinking effort.

And then it happened...

I asked Sol to generate 2,500 training examples for my LLM. It started working, and I left it alone. Previously, generating 500 examples had taken around 30 minutes, so I expected this to take a while. But after approximately 47 minutes, things started looking suspicious. Still, I thought, well, 2,500 examples is a lot of data. Maybe it just needs more time. Meanwhile, I was browsing the web and randomly opened the billing tab on Tinker.

$2.47?! WHAT?!

I immediately stopped Sol and checked what it was actually doing. Instead of just generating training examples, it had started running model training in the background. There were 18 sessions involving different models, including deepseek-ai/DeepSeek-V3.1, moonshotai/Kimi-K2.6, and Qwen/Qwen3.5-397B-A17B.

Oh my... I asked for training data, not for an AI training marathon..

By the time I stopped it, my remaining Tinker balance was down to $2.11.

Well, there's a nice little lesson about giving AI agents access to paid services. Maybe I should write another article about that someday.

Anyway, back to the dataset.

This time, I decided to be a little more careful. I switched to Luna with medium thinking effort and prepared a prompt to generate just 200 training examples at a time. Then I manually ran it ten times, each time focusing on different types of prompts to improve dataset diversity, and added another 500 examples from my previous Sol generation run.

Why manually? Well, after the previous incident, I wasn't exactly eager to let another AI agent run wild with my budget. And thinking about it now, I probably should have used Luna for data generation from the beginning. Sol was a bit overkill for this task.

So after that incident, I finally managed to run the fine-tune with all 2,500 training examples successfully. This time, the model achieved 76% accuracy. That's a 26-percentage-point improvement over the original Qwen3-8B, which achieved only 50% accuracy on the same evaluation dataset.

**Example 2:**
>
 Redis 8.4's digest-based SET option cuts a 1MB compare-and-set from 4.3ms to 1.6ms
#redis
#database
#performance
#devops

I keep a cached object in Redis that several workers read and occasionally rewrite. Before writing, each worker has to check that nobody else changed the object since it was last read, or the write clobbers someone else's update. Redis never had one command for that. You used WATCH/MULTI/EXEC, or a Lua script that reads and compares server-side, or you accepted the race and moved on.

Redis 8.4 adds four conditions to SET: IFEQ, IFNE, IFDEQ and IFDNE. The first two compare against a literal value. The last two compare against a digest, a 16-character hex hash the server computes with DIGEST. I pulled redis:8.4 and ran all four against the patterns they replace.
The headline number

The point of a digest is that you don't send the value you're comparing against, you send its hash. For a small string that saves nothing. For a large one it matters.

I set a 1MB string, kept a cached digest of it client-side, and timed three ways of doing a conditional overwrite 50 times each, taking the median:
| size   | classic GET-then-SET | LUA script CAS | SET ... IFDEQ |
|--------|----------------------|----------------|---------------|
| 100 B  | 0.29 ms              | 0.17 ms        | 0.21 ms       |
| 10 KB  | 0.32 ms              | 0.25 ms        | 0.17 ms       |
| 100 KB | 0.55 ms              | 1.10 ms        | 0.48 ms       |
| 1 MB   | 4.44 ms              | 7.37 ms        | 1.77 ms       |

Those are medians across three separate runs of 50 trials each at every size, against a redis:8.4 container on localhost. At 1MB, the digest-based set was roughly a third of the classic GET-then-SET and under a quarter of the Lua script, while the data crossing the wire for the comparison itself dropped from 1,000,000 bytes to 16.

The classic approach does a GET (full value back to the client) followed by a conditional SET (full value back to the server). The Lua script sends the full old value as an argument so the server can compare it internally. The digest option sends neither; the client already has the digest from the last time it fetched the object, and this SET just needs to check it still matches.

### `opinion`

**Definition:**An article that expresses a personal viewpoint based on the OP's experience

**Example 1:**
>
 AI Made Coding Faster. Now Teams Are Cutting the Process That Catches Risky Changes
#ai
#engineeringmanagement
#codereview
#devops

There's a piece of advice I've been seeing a lot lately...reduce friction, protect your engineers' focus, make the common path the easy path, and cut the unnecessary approvals, tickets, and handoffs.

And honestly, I think most of that is good advice. A lot of engineers end up as part-time administrators. They fight with environment setup, hunt for the right doc, and chase a permission across four different teams before they can even start on the actual problem. That stuff should go, no argument from me.

But "reduce friction" isn't the entire idea, at least the way I see it. And the missing half matters a lot more now that AI is in the picture.
AI moved the bottleneck

Coding agents made writing code a lot faster, and by now there are tons of posts about where the work went. It piled up downstream...in planning, in review queues, in QA, in release approvals. PR volume jumped, and delivery dates barely moved.

The fix I keep seeing for that is to reduce friction across the whole delivery process, so all that new code can flow through every step faster. That's where I think it starts to go wrong. When a team decides it has a speed problem, it tends to treat every bit of friction as waste, and some of that friction was actually doing a valuable job.
Two kinds of friction

The way I think about it, there are two piles.

The first is accidental friction...things like environment setup, hunting for docs, and chasing permissions across teams. That's pure tax, and it should go to zero.

The second is essential friction, which is the small "wait, should we?" before a change. In my experience that little pause is the cheapest insurance a team has.
The water filter

To explain this, I like to use an analogy of a water filter. A filter needs friction to catch anything. Take all of the friction away and nothing gets caught...the water just runs straight through. Add too much and nothing flows at all. Clean water comes from getting the balance right between the two.

Code review is friction like that...it's where the risky changes get caught before users find them.

"Make the common path the easy path" is great right up until the common path runs straight through a risky change with no speed bump left on it. Optimize away all the friction, and you usually pull the guardrails out along with the bureaucracy. And it works for a while...you feel fast, right up until that first risky change slips through with a bug in it that impacts every one of your users.
So which kind is it?

I don't have a clever framework for this. For me it comes down to the pros versus the cons. When I look at a step in our process, I ask three questions. Is there a benefit to having this friction? What do we gain by getting rid of it? And what do we lose?

If you run environment setup through those questions, there's no real benefit to it, you get time back by fixing it, and you don't lose anything.

Run the "wait, should we?" before a migration through them and you'd get a little time back by removing it. But you'd also lose the one moment where someone stops and asks whether this change could hurt users.

From my perspective, the teams getting the most out of AI, put the friction where the risk is and strip it out of everywhere else.

So before your team removes the next step from its process, it's worth asking what that step is getting you, and what you'd lose without it.

**Example 2:**
>
LeetCode Made Coding Fun Again
#ai
#productivity
#beginners
#programming

Many of us have already fully switched to AI-powered development. We write specs, create skills, connect MCP and run several agents in the background, after which we do a very boring code review of the result.

For almost all of this year I’ve been writing code with the help of AI, and it’s definitely productive (otherwise I wouldn’t be doing it), but it’s not as fun as it was before. Writing code is like LEGO or puzzles, first you come up with what the solution should look like, then what the first steps should be, and then you write the code, some things work right away, and some things break along the way and you rewrite what doesn’t work. And now imagine if you asked a robot to put a puzzle together for you. It’s put together, the result is there, but did you enjoy it?

I’ve heard an opinion from other developers, “Then write code without AI, what’s the problem?”, but unfortunately it’s not a solution. I think you’ve played computer games like GTA SA, where you can enter the cheat code “HESOYAM” and get a huge amount of money right away. Will you be just as motivated to earn this money in the game honestly, if you’ve used this cheat code once? Most likely not. You’ll consider it a waste of time, because you can just type a command. It’s the same with AI development. It’s very hard to make yourself sit down again and do everything by hand, when you can write a prompt and an AI agent will do it for you.

And for some time it was really sad for me. On the one hand, AI lets us be productive, make PoCs quickly and get rid of boring routine work, but on the other hand it takes away the reason why many of us fell in love with programming.

When I was just starting to learn programming in 2016-2017, I really loved challenges (I still love them, but back then it was especially important). When our C++ teacher gave us a problem on algorithms or data structures, I wanted to do it better and faster than all my classmates. It was a competition. And solving some of the problems took several days (or rather sleepless nights), for example tic-tac-toe where you play against artificial intelligence (so-called, not an LLM), or the 15 puzzle in the console.

### The hardest boundary

**Which two labels:** Guide and Analysis

**The decision rule I used every time:**
<!-- e.g. "If the post names a specific checkable fact, it's `analysis`, even
     if the tone is heated." -->
If the post gives the user a proceedure to follow, or the article promises an outcome to the reader, it's `guide`. Otherwise, if the article does not contain a proceedure and it's conclusion is based on data and verifiable facts, it's `analysis`.

---

## The Dataset

<!-- Where you collected from, how you labelled, your counts, and three hard
     cases. -->

**Where the posts came from:**Dev.to

**How I labelled them:** Personally reading thorugh them and seeking key featurees that fit them under each label<!-- Cold first? Pre-labelled with AI and corrected?
Say so plainly — the disclosure is required, not penalised. -->

**Counts per label:**

| Label | Count | Share |
|---|---|---|
|  |  |  |
|  |  |  |
|  |  |  |
| **Total** |  | 100% |

**Three hard cases**

<!-- Any post that made you pause: what it was, which two labels it could have
     been, and what you chose. These are worth more than the easy 190. -->

**1.**
> *The post:*
>
> *Could have been:*
>
> *I chose, because:*

**2.**
> *The post:*
>
> *Could have been:*
>
> *I chose, because:*

**3.**
> *The post:*
>
> *Could have been:*
>
> *I chose, because:*

---

## The Training Run

<!-- Your starting model, your settings, and anything you changed and why. -->

**Base model:**

**Settings:** <!-- epochs, learning rate, batch size, seed -->

**Anything I changed from the defaults, and why:**

**Split sizes:** <!-- train / val / test, and per-label counts in the test
split. If a label had fewer than about 8 in test, say so — it explains a lot
of next unit's variance. -->



---

## How I Used AI

<!-- Two specific moments — what you asked, what came back, what you changed.

     ⚠️ Plus disclosure of any pre-labelling. If you had a model pre-label a
     batch and then read and corrected every one, say that. It's an allowed
     workflow and disclosing it costs you nothing. Not disclosing it is the
     problem. -->

**Moment 1**

- *What I asked for:*
- *What came back:*
- *What I changed:*

**Moment 2**

- *What I asked for:*
- *What came back:*
- *What I changed:*

**Pre-labelling disclosure:**

<!-- ═══════════════════════ UNIT 6 — THE TEST ═══════════════════════

     Don't fill these in during unit 5.
     ═══════════════════════════════════════════════════════════════════ -->

---

## Baseline vs. Trained

<!-- Both models on the same posts. `python baseline.py --trained results.json`
     prints this table for you. -->

| Measure | Baseline | Trained | Difference |
|---|---|---|---|
| Overall accuracy |  |  |  |
| Macro F1 |  |  |  |
| F1 — `label_one` |  |  |  |
| F1 — `label_two` |  |  |  |

**What I predicted before I looked:**
<!-- Milestone 1 asks you to write this BEFORE seeing the trained numbers. A
     prediction made afterwards isn't one. -->

**What the gap actually means:**
<!-- If the baseline matched your trained model, your fine-tuning added
     nothing — and that is a real finding, not a failure. Say it plainly. -->



---

## Run Log — Before

<!-- Five criteria across three seeds. The notebook's section 6 prints the
     spread table; the Target and Verdict columns are yours. -->

| Criterion | Target | Seed 42 | Seed 7 | Seed 2024 | Verdict |
|---|---|---|---|---|---|
| 1.  |  |  |  |  |  |
| 2.  |  |  |  |  |  |
| 3.  |  |  |  |  |  |
| 4.  |  |  |  |  |  |
| 5.  |  |  |  |  |  |

### Confusion matrix

<!-- ⚠️ TYPED AS A MARKDOWN TABLE. The notebook prints one ready to paste.
     An image of a matrix earns nothing. -->

| true \ predicted |  |  |  |
|---|---|---|---|
| **** |  |  |  |
| **** |  |  |  |
| **** |  |  |  |

**My biggest off-diagonal number, and what it means:**
<!-- Not "the model made mistakes" — WHICH boundary it didn't learn, and which
     direction. "7 real analysis posts were called hot_take and only 3 went the
     other way" is a direction, not just an error rate. -->



---

## Verdicts and Diagnoses

<!-- MET or MISSED against LAST UNIT's target. The target has to hold across
     all three seeds, not turn up sometimes. -->

| # | Criterion | Target | Verdict | How I decided |
|---|---|---|---|---|
| 1 |  |  |  |  |
| 2 |  |  |  |  |
| 3 |  |  |  |  |
| 4 |  |  |  |  |
| 5 |  |  |  |  |

**Diagnoses**

<!-- For each miss: the cause, and how you know. The four common causes are:
     too few examples for a label, a boundary you applied inconsistently, a
     genuinely hard label pair, and a task the model can't reach from this
     much data.

     ⚠️ Use your agreement report as evidence. It is the only instrument you
     have that can tell a LABELLING problem from a MODEL problem, and this
     section is graded on whether you used it that way. -->



---

## Agreement Report

<!-- Your rate against the staff set, and every disagreement adjudicated.

     Remember you labelled these 30 under the STAFF taxonomy in
     data/staff_taxonomy.md, not your own — so every argument below is made
     from those definitions and those decision rules. -->

**Agreement rate:** ___ / 30 = ___%

<!-- Nobody grades this number. A 60% who argues every disagreement from the
     stated rules beats a 95% who wrote "staff was right" nine times. Several
     of the 30 were chosen because they're genuinely ambiguous — you should be
     winning some of these. -->

**Disagreements**

<!-- Three lines each: the post, both labels, and who you think is right and
     why — grounded in the staff definitions you were both applying.

     Then sort each into one of three piles:
       (a) the rule covered it and I applied it loosely → a consistency problem
       (b) the rule genuinely doesn't say               → a gap in the definitions
       (c) the rule is ambiguous here and my reading is defensible → argue it.
           This is a legitimate win.

     Pile (a) is the one that matters most for your diagnosis: if you applied a
     written rule two different ways on 30 posts, that is direct evidence about
     what you did across your own 200. -->

**1.**
> *The post:*
>
> *Staff said / I said:*
>
> *My call, and why:*
>
> *Which pile:*

**2.**
> *The post:*
>
> *Staff said / I said:*
>
> *My call, and why:*
>
> *Which pile:*

**What the pattern in my disagreements tells me:**



---

## The Improvement

**What I changed:**

**Which diagnosis pointed at it:**

### Run Log — After

| Criterion | Target | Seed 42 | Seed 7 | Seed 2024 | Verdict |
|---|---|---|---|---|---|
| 1.  |  |  |  |  |  |
| 2.  |  |  |  |  |  |
| 3.  |  |  |  |  |  |
| 4.  |  |  |  |  |  |
| 5.  |  |  |  |  |  |

**Did it help, and how do I know:**

<!-- If it didn't, say so. Relabelling that didn't help is a genuinely
     interesting result and earns full credit. -->



---

## What's Still Broken

<!-- For each criterion still missed: what you'd do, and why you stopped. -->



**The gap between what I meant my labels to capture and what the model
learned:**
<!-- Two sentences. Your confusion matrix is the evidence. -->



<!-- ═════════════════════════════════════════════════════════════════════

     SUBMISSION CHECKLIST — unit 5

       [ ] criteria.md has five numbered criteria, each naming a NUMBER
       [ ] Each has a reason underneath tied to your data or taxonomy
       [ ] labels.csv: at least 150 rows, text/label/note, ONE file not split
       [ ] No label above 70%
       [ ] All five unit 5 sections have real content
       [ ] Label Taxonomy includes the decision rule for your hardest boundary
       [ ] The Dataset includes three hard cases
       [ ] results.json and test_split.csv committed (the notebook does this)
       [ ] At least four new commits
       [ ] Repository URL submitted — WRITE IT DOWN

     SUBMISSION CHECKLIST — unit 6

       [ ] Baseline vs. Trained table, with your prediction written beforehand
       [ ] Run Log — Before, five criteria across three seeds
       [ ] Confusion matrix TYPED AS A MARKDOWN TABLE
       [ ] A verdict on every criterion
       [ ] A diagnosis for every miss, using the agreement report as evidence
       [ ] Agreement Report with every disagreement adjudicated
       [ ] One improvement, with Run Log — After
       [ ] What's Still Broken
       [ ] results_three_seeds_before.json, results_three_seeds_after.json,
           baseline_results.json and
           agreement_results.json committed
       [ ] At least four new commits
       [ ] The SAME repository URL as last unit

     Do not delete and recreate this repository.
     ═════════════════════════════════════════════════════════════════════ -->

---

📖 **How to run this project: [RUNNING.md](RUNNING.md)**
