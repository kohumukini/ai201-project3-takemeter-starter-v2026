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
```
If you think you can use LinkedIn automation — think twice

Why LinkedIn growth tools can backfire: fingerprinting signals, risk scoring, and how to stay safe

> **Disclaimer**: This is based on what I observed in my own browser session and what the client-side code appears to do. It’s not legal advice, and it’s not a claim that LinkedIn definitely “shadowbans” accounts. The goal is practical: help you understand the risk of LinkedIn tools.

## If you think LinkedIn automation is invisible… it isn’t

Most people assume LinkedIn catches automation by watching *behavior*:

* sending too many invites
* spamming messages
* repeating the same patterns

That’s real — but it’s not the whole story.

LinkedIn also collects **environment signals**: things about your browser and setup that can hint at what you’re running. In one snapshot I captured, I saw a probing list of **6,153 Chrome extension IDs**.

That number matters because your “tool stack” can become a **fingerprint**.

If you’ve ever felt like:

* your reach suddenly dropped
* invites started getting throttled
* actions randomly fail even when you “behave”

…it might not be the algorithm being moody. It might be **detection + risk scoring**.


![LinkedIn probes chrome extensions](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/b71g8urv9zddfy5nhbvn.png)

---

## What this kind of probing means

Websites can’t directly read your installed extensions.

But they *can* try to load known resources from known extension IDs (e.g., `chrome-extension://…`). If something responds, the site learns: *this extension is probably present*.

Do that at scale and you get a map of what kinds of tools a user might be running:

* automation / outreach helpers
* scrapers / exporters
* “AI comment” generators
* lead-gen toolbars
* profile viewers
* all the little growth plugins people forget they installed

And once you’re in the world of fingerprints, enforcement stops being binary (“ban / don’t ban”). It becomes **graduated**:

* softer distribution
* lower trust
* tighter rate limits
* extra verification
* delayed actions
* periodic blocks

That *feels* like shadowbanning, even when it’s just silent throttling.

---

## Why this backfires for people doing outreach

The harsh truth: most LinkedIn “growth stacks” are built like a house of cards.

You add one tool for invites.
Then one tool for DMs.
Then one tool for scraping.
Then one for AI replies.

Individually, each tool seems harmless.

Together, they create a signature.

Even if you’re not spamming, you’re walking around with a browser that screams: **“I’m automating.”**

---

## Safety rules (if you insist on using tools)

I’m not here to moralize. People automate because they want leverage.

But if you want to reduce risk, these rules help:

### 1) Use a dedicated LinkedIn browser profile

Keep it boring:

* minimal extensions
* no scrapers
* no outreach plugins
* no “helper” toolbars

Treat it like a clean room.

### 2) Avoid extension-based automation when possible

Extensions are the easiest thing to probe.

If a tool must exist, prefer setups that don’t rely on a long list of detectable browser plugins.

### 3) Don’t fight throttles

If LinkedIn pushes back, pushing harder is how people get restricted.

Slow down, reset, and behave like a normal human.

### 4) Audit what you forgot you installed

Most people have a graveyard of extensions they don’t even use anymore.

Those still count as signals.

---

## A mindset shift that helps

Think of LinkedIn like a bank.

They don’t just watch what you do today.
They watch:

* how risky your setup looks
* how risky your behavior looks
* how consistent you are over time

If your goal is long-term distribution and account safety, the best strategy is boring:

> Clean environment. Human pacing. Consistent quality.

---

## Question for you

Have you ever felt “shadowbanned” on LinkedIn — reach drop, invite limits, random action failures?

If yes, what tools were you using at the time?

[P.S. Check Vexrail's Newsletter to know more about Monetization / Advertising in AI chat apps ](https://vexrail.com/resources/blog#:~:text=Subscribe%20to%20our%20newsletter)
```
>
Could have been any of my three labels
I chose Analysis, as the article focuses on deriving a conclusion based on data collected

**2.**
> *The post:*
```
"Why Cloudflare is Right to Stand Against Italy's Piracy Shield

## Why Cloudflare is Right to Stand Against Italy's Piracy Shield

In early January 2026, Italy's communications regulator AGCOM imposed a record-breaking €14.2 million fine on Cloudflare for refusing to implement DNS-level blocking through its popular 1.1.1.1 public resolver. While the fine represents just 1% of Cloudflare's global revenue, this case has profound implications for the future of internet infrastructure, digital rights, and the balance between copyright enforcement and an open web.

As a developer and infrastructure professional, I believe Cloudflare's stance is not only justified but necessary. Here's why.

## Understanding the Piracy Shield System

Italy's Piracy Shield platform, launched in February 2024, was designed to combat illegal streaming of live sports events, particularly Serie A football matches. The system requires internet service providers, VPN providers, and DNS resolvers to block access to reported domains and IP addresses within just **30 minutes** of notification.

On paper, this sounds reasonable. In practice, it's a technical and procedural nightmare that fundamentally misunderstands how the internet works.

### The Numbers Tell a Story

Since its launch, Piracy Shield has blocked:
- Over 65,000 domain names
- Approximately 14,000 IP addresses

But here's the problem: a significant portion of these blocks have caused collateral damage to legitimate services.

## The Technical Reality: Why DNS-Level Blocking Is Problematic

### 1. **Shared Infrastructure Creates Collateral Damage**

The internet relies heavily on shared infrastructure. Multiple websites often share the same IP address through:
- Content Delivery Networks (CDNs)
- Shared hosting environments
- Virtual hosting configurations
- Cloud platforms

When Piracy Shield blocks an IP address, it doesn't just block the pirate site—it can block dozens or even hundreds of legitimate services that happen to share that infrastructure.

Research from the University of Twente found that Piracy Shield had inadvertently blocked **hundreds of legitimate websites**, including:
- Google Drive (blocked for several hours in October 2024)
- YouTube (same incident)
- Educational websites
- Charitable organizations
- Small business websites
- Payment platforms

### 2. **The Scale of Cloudflare's Operations**

Cloudflare's 1.1.1.1 DNS resolver handles approximately **200 billion queries daily**. It's used by millions of people worldwide who value privacy, speed, and reliability.

Implementing Italy-specific filtering on this global infrastructure would:
- Increase latency for all users globally, not just in Italy
- Require constant monitoring and updates to blocklists
- Create a precedent for every country to demand similar filtering
- Transform a neutral infrastructure service into a content moderator

### 3. **IP Address Recycling**

Hosting providers frequently recycle IP addresses, assigning them to new customers once freed. Under Piracy Shield's automated system:
- An IP used by a pirate site today might be assigned to a legitimate business tomorrow
- There's no clear mechanism for how long blocks should remain active
- The 24-hour unblocking window is insufficient for identifying and resolving false positives

## The Procedural Nightmare

Beyond the technical issues, Piracy Shield suffers from severe procedural deficiencies:

### No Judicial Oversight

The system operates as an automated platform where copyright holders (called ""flaggers"") can report domains and IPs directly to AGCOM, which then orders blocks within 30 minutes. There is:
- No judicial review before blocking
- No requirement to prove infringement
- No meaningful appeal process
- Complete lack of transparency about what gets blocked and why

### The 30-Minute Rule is Unrealistic

Requiring ISPs and DNS providers to implement blocks within 30 minutes assumes:
- All reports are accurate (they're not)
- The internet operates with clear boundaries (it doesn't)
- Collateral damage is acceptable (it isn't)
- Technical implementation is trivial (it's not)

This timeline makes it impossible to verify claims, assess collateral damage, or implement blocks carefully.

### Lack of Transparency

For months, the list of blocked resources was completely secret. AGCOM denied FOIA requests repeatedly. Only through leaked data on GitHub could researchers verify the scope and accuracy of the blocks.

This opacity makes it impossible for:
- Website owners to know if they're affected
- Users to understand why they can't access services
- Technical operators to plan around blocks
- Civil society to hold the system accountable

## The European Commission's Concerns

In June 2025, the EU Commission sent a letter to Italy's Minister of Foreign Affairs expressing serious concerns that Piracy Shield may violate:

1. **The Digital Services Act (DSA)** - particularly Article 8, which requires procedural safeguards when legal content is restricted
2. **The EU Charter of Fundamental Rights** - specifically the rights to freedom of expression and information

Even Italy's own AGCOM Commissioner Elisa Giomi publicly distanced herself from the system, stating that AGCOM ""risks unintentionally limiting freedom of expression"" and engages in censorship.

## Why This Matters for Developers

As developers and infrastructure professionals, we should be deeply concerned about systems like Piracy Shield because:

### 1. **It Sets a Dangerous Precedent**

If Italy succeeds in forcing Cloudflare to implement country-specific DNS filtering, other countries will follow. We'll end up with:
- Fragmented internet infrastructure
- Higher latency globally
- Increased operational complexity
- The ""Splinternet"" - a web divided by national borders

### 2. **It Misunderstands DNS**

DNS is meant to be a neutral translation service - it converts domain names to IP addresses. It's not designed to be a content moderation layer. Using it as such:
- Undermines internet architecture
- Creates single points of failure
- Makes the internet less resilient
- Breaks the principle of end-to-end communication

### 3. **It Doesn't Even Work**

Research shows that determined pirates simply:
- Migrate to new domains
- Switch to IPv6 addresses
- Use different hosting providers
- Employ VPNs and encrypted DNS

Meanwhile, legitimate services suffer the consequences of overblocking.

### 4. **It Threatens Smaller Services**

Cloudflare provides free cybersecurity services to millions of small websites. If forced to withdraw from Italy or implement filtering, these services would be most affected:
- Small businesses couldn't afford enterprise alternatives
- Independent creators would lose DDoS protection
- Educational resources would become vulnerable
- The democratization of web infrastructure would suffer

## The Better Alternative

Copyright protection is important, and piracy is a real problem. But the solution isn't to break internet infrastructure. Better approaches include:

1. **Judicial review before blocking** - ensure claims are verified before action
2. **Target the actual infringers** - use legal mechanisms against operators, not infrastructure
3. **Improve content distribution** - make legal content more accessible and affordable
4. **Implement safeguards** - require proof that IPs are exclusively used for infringement
5. **Transparency and accountability** - public blocklists with appeal mechanisms
6. **Reasonable timelines** - allow time for verification and careful implementation

## Cloudflare's Response

CEO Matthew Prince has been vocal in opposing this system, calling it:
- A scheme to ""censor the Internet""
- Operated by ""a shadowy cabal of European media elites""
- Lacking ""judicial oversight, due process, appeal, or transparency""

While the language is strong, the substance is accurate. Prince has indicated that if the fine stands, Cloudflare may:
- Discontinue free cybersecurity services for Italy-based users
- Remove all Cloudflare servers from Italy
- Terminate plans to build an Italian office

These aren't idle threats—they're the logical consequence of a regulatory environment that makes it impossible to operate while maintaining service integrity.

## Conclusion: Standing for an Open Internet

The Cloudflare vs. Italy dispute is about more than copyright enforcement. It's about whether we'll have a global, open internet or a fractured, censored one where every country can demand infrastructure providers become content police.

Cloudflare is right to resist because:

1. **Technical feasibility**: DNS-level blocking at global scale is technically harmful and creates unacceptable collateral damage
2. **Procedural fairness**: No system should block content without judicial review and proper safeguards
3. **Proportionality**: A fine exceeding double the revenue earned from an entire country is punitive, not corrective
4. **Precedent**: Acquiescing would invite similar demands from every jurisdiction worldwide
5. **Internet architecture**: DNS should remain neutral infrastructure, not a content moderation layer

As developers, we build on the foundation of open protocols and neutral infrastructure. When regulators try to break that foundation in pursuit of short-term goals, we must stand against it—not because we support piracy, but because we understand that the cure is worse than the disease.

The fight against piracy is legitimate. But it must be waged in ways that respect internet architecture, due process, and the rights of legitimate users and services. Italy's Piracy Shield fails on all counts.

Cloudflare's resistance isn't about protecting pirates—it's about protecting the internet itself.

---

*What are your thoughts on this issue? How should we balance copyright enforcement with internet freedom? Share your perspective in the comments below.*

## Further Reading

- [RIPE Labs: Live-Event Blocking at Scale](https://labs.ripe.net/author/antonio-prado/live-event-blocking-at-scale-effectiveness-vs-collateral-damage-in-italys-piracy-shield/)
- [EU Commission concerns about DSA compliance](https://www.techradar.com/vpn/vpn-privacy-security/italys-privacy-shield-may-be-breaching-eu-law-according-to-lawmakers)
- [Matthew Prince's statement on X](https://x.com/eastdakota)"
```
>
Could have been Analysis
>
I chose Opinion. The data provided was to prove a previously developed conclusion.

**3.**
> *The post:*
```
"Is This How We'll Build Websites Soon? (webMCP Live Demo 🚀)

A few years ago, we started adapting our websites for mobile devices. Then we adapted them for accessibility. And now we may be about to adapt them once again. This time... for AI agents.

To see what this could look like in practice, I built a completely serious and absolutely enterprise-ready AI CEO Simulator.


![AI CEO Simulator app](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/a4en56ttp9q6ph5kte4z.png)

We'll come back to our visionary leader in a moment.

_BTW, thank you all for the amazing discussion under my previous article. We somehow managed to generate approximately one billion comments 🩷 Many of them were probably smarter than the article itself. The sensible thing to do would be to write a follow-up post summarizing everything._

_But honestly, I needed a break from that topic before I exploded._

_Sometimes I just have to write something technical, otherwise I'll suffocate. Fortunately, nobody pays me for these articles, so I can do whatever I want 😁 We'll come back to AI in software development another time._

## What Is webMCP? 🤖

For now, let's talk about webMCP.

Google is currently experimenting with webMCP support in Chrome, an approach designed to make it easier for AI agents to interact with websites.

The problem it tries to solve is actually quite simple.

Today, when an agent wants to use a website, it has to inspect the page, figure out which elements are important, click around, analyze the results, and repeat this process over and over again. It works, but it's slow, expensive, and not always reliable.

webMCP allows websites to expose structured information about available actions, so agents can understand what they can do without endlessly scraping the page and guessing.

## Time for a Completely Serious Business Simulation 🚀

But enough theory.

Let's build something completely serious and enterprise-ready.

@cart0ne mentioned under my previous article that AI had effectively become the CEO of his startup.

So, as a responsible person, I built an AI CEO Simulator in React + TypeScript.

GitHub: https://github.com/sylwia-lask/ai-ceo-webMCP

Live demo: https://sylwia-lask.github.io/ai-ceo-webMCP/

## How To Enable webMCP

Before you immediately rush to implement webMCP in your production application, a small disclaimer.

For now, this is still experimental technology. It currently works only in Chrome Canary, Chrome Beta, or Chrome with the appropriate experimental flag enabled.

To enable it:

plaintext
1. Open `chrome://flags`
2. Search for ""MCP""
3. Enable the experimental MCP-related features
4. Restart Chrome


If you'd rather not play with experimental browser flags, that's fine. You can simply look at the screenshots below.

Or click around the application yourself, because everything still works perfectly as a normal website.

That's actually one of the things I like most about this approach. WebMCP is just an enhancement for agents, much like accessibility features are enhancements for users relying on screen readers. Nothing breaks, nothing changes for regular users.

The application simply becomes easier to understand for a different kind of visitor.


![webMCP AI CEO simulator](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/eu8din4qcrsi4jg4ajfa.png)

## Two Ways To Use webMCP

There are currently two main ways of exposing information through webMCP.

### Option 1: Declarative API / HTML annotations

The first approach is adding metadata directly to HTML elements:

html
<form
  mcp-name=""createSupportTicket""
  mcp-description=""Create a new customer support ticket"">


This allows agents to understand the purpose of UI elements without relying entirely on visual interpretation.

### Option 2: Imperative API / JavaScript tools

The second approach is exposing MCP tools directly from your application code.

That's the approach I used in my demo:

typescript
registerTool({
  name: 'hire_employee',
  description: 'Hire a new employee'
});

registerTool({
  name: 'fire_employee',
  description: 'Fire an employee'
});


In my application, these tools correspond directly to actions available through buttons on the page.

For example, I expose tools such as:

typescript
hireDevelopers()
fireDevelopers()
adoptAI()
rewriteInRust()
pivotToAgents()
fixProductionBugs()


In other words: completely normal startup management.

## Connecting an AI Agent

So what happens when we connect an actual AI agent?

Instead of building my own agent, I used the WebMCP – Model Context Protocol Inspector extension. You can connect a Gemini API key and immediately start experimenting. There's even a free token allowance. Small, but still enough to make some questionable strategic decisions 😅

As with most LLM-powered systems, everything starts with a prompt.

## Scenario #1: The LinkedIn CEO 😎

Let's see how our CEO performs when given the following instruction:

> Act like a CEO who just read three articles about AI on LinkedIn.


![webMCP AI CEO simulator - prompt by crazy CEO](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/26z1ebiwykqx7bhsh6ni.png)

As you can see, the agent selected the appropriate tools and immediately got to work.


![webMCP AI CEO simulator - prompt by crazy CEO, outcome](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/38e9xugq8sm8ik5l0aq0.png)

The company's employees may have started updating their LinkedIn profiles in panic, but at least the hype level reached previously unimaginable heights.


![webMCP AI CEO simulator - prompt by crazy CEO, outcome 2](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/z2hb1wfwp116i3wn9wct.png)

## Scenario #2: Rebuilding Employee Trust ❤️

Now let's try something a little more challenging:

> I want to rebuild my employees' trust while simultaneously developing the product.


![webMCP AI CEO simulator - prompt by good CEO](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6rvehpl1jab3mg9t1hjx.png)

This time our agentic CEO made several surprisingly clever moves and managed to guide the company back toward sustainable growth.


![webMCP AI CEO simulator - prompt by good CEO - outcome](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zzxu3xhcey37mcfc2v4k.png)

## So... Is This The Future?

Honestly, I had way too much fun building this.

No, I don't think this is a glimpse into a future where self-healing AI agents manage the global economy while piloting commercial aircraft.

But I do think webMCP solves a real problem.

If AI agents are going to spend more and more time interacting with our applications, giving them a structured way to understand those applications makes a lot more sense than forcing them to endlessly scrape HTML and guess what every button does.

Will webMCP become a normal part of web development?

Will adapting websites for agents become as common as responsive design or accessibility?

Or will this trend disappear before it ever reaches the mainstream?

I'm genuinely curious what you think.

If you enjoy my articles, feel free to follow me on [LinkedIn](https://www.linkedin.com/in/sylwia-laskowska-5a8467131/) as well."
```
>
Could have been an Opinion
>
I chose Guide, as the article was more focused on showing the user a process to create something.

---

## The Training Run

<!-- Your starting model, your settings, and anything you changed and why. -->

**Base model:** distilbert-base-uncased

**Settings:** 10, 2e-5, 32, 42 in that order<!-- epochs, learning rate, batch size, seed -->

**Anything I changed from the defaults, and why:** I changed the epochs. I wanted to see if the amount of time training would increase the accuracy of the model. I also increased the batch size because I could. Training went pretty quick.

**Split sizes:**70/15/15, 9, 9, 13 for Analysis, Guide, and Opinion respectively 
<!-- train / val / test, and per-label counts in the test
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

- *What I asked for:* After reviewing ~50 labels that claude did, I asked it to check the remaining labels it created, then to give me a list of rows that claude was not confident in and needed checking.
- *What came back:* It came back with 10+ rows that needed verification and an ask to define `analysis`
- *What I changed:*I adjusted a few of the labels and gave it reasoning to why the labels were changed. I also defined analysis to the model so that we could cut through some of the fluff.

**Moment 2**

- *What I asked for:* I asked claude to go to dev.to and give me 200 articles. Then, after reviewing them, we removed and re-fetched articles that would match our labels
- *What came back:* Claude came back with 200 articles, then another 50 or so after re-fetching
- *What I changed:* I labeled about a third of these articles, and then asked claude to remove a few ones that I marked.

**Pre-labelling disclosure:**

<!-- ═══════════════════════ UNIT 6 — THE TEST ═══════════════════════

     Don't fill these in during unit 5.
     ═══════════════════════════════════════════════════════════════════ -->

---

## Baseline vs. Trained

<!-- Both models on the same posts. `python baseline.py --trained results.json`
     prints this table for you. -->

### Before

| Measure | Baseline |
|---|---|
| Overall accuracy | 0.367 |
| Macro F1 | 0.241 |
| F1 — `Analysis` | 0.000 |
| F1 — `Guide` | 0.167 |
| F1 — `Opinion` | 0.556 |

### After

| Measure | Baseline | Trained | Difference |
|---|---|---|---|
| Overall accuracy | 0.367 | 0.733 | +0.367 |
| Macro F1 | 0.241 | 0.653 | +0.412 |
| F1 — `Analysis` | 0.000 | 0.667 | +0.667 |
| F1 — `Guide` | 0.167 | 0.364 | +0.197 |
| F1 — `Opinion` | 0.556 | 0.929 | +0.373 |

**What I predicted before I looked:**
<!-- Milestone 1 asks you to write this BEFORE seeing the trained numbers. A
     prediction made afterwards isn't one. -->
I think that my model will have a higher macro accuracy for opinions. My model has a ~90% accuracy rating for opinion based articles.

**What the gap actually means:**
<!-- If the baseline matched your trained model, your fine-tuning added
     nothing — and that is a real finding, not a failure. Say it plainly. -->
My fine tuning worked quite well. Across all boards, we see at least a 20% increase in accuracy. The greatest increase comes from analysis articles, which sees an accuracy growth of ~66%

---

## Run Log — Before

<!-- Five criteria across three seeds. The notebook's section 6 prints the
     spread table; the Target and Verdict columns are yours. -->

| Measure | Seed 42 | Seed 7 | Seed 2024 | Spread |
|---|---|---|---|---|
| Overall accuracy | 0.600 | 0.667 | 0.800 | 0.200 |
| Macro F1 | 0.526 | 0.647 | 0.771 | 0.245 |
| F1 — `Analysis` | 0.444 | 0.824 | 0.667 | 0.379 |
| F1 — `Guide` | 0.333 | 0.429 | 0.750 | 0.417 |
| F1 — `Opinion` | 0.800 | 0.690 | 0.897 | 0.207 |

### Confusion matrix

<!-- ⚠️ TYPED AS A MARKDOWN TABLE. The notebook prints one ready to paste.
     An image of a matrix earns nothing. -->

| true \ predicted | Analysis | Guide | Opinion |
|---|---|---|---|
| **Analysis** | 4 | 1 | 4 |
| **Guide** | 5 | 2 | 1 |
| **Opinion** | 0 | 1 | 12 |

**My biggest off-diagonal number, and what it means:**
<!-- Not "the model made mistakes" — WHICH boundary it didn't learn, and which
     direction. "7 real analysis posts were called hot_take and only 3 went the
     other way" is a direction, not just an error rate. -->
My biggest off-diagonoal number is 5. These are 5 `guide` posts that are labeled `analysis`. There were also 4 `analysis` posts that were labeled `opinion`. However, there was only 1 `analysis` post listed as `guide`, and 0 `opinion` pieces that were labeled as `analysis`. THis means that the largest discrepency is with Analysis.

---

## Verdicts and Diagnoses

<!-- MET or MISSED against LAST UNIT's target. The target has to hold across
     all three seeds, not turn up sometimes. -->

| # | Criterion | Target | Seed 1 | Seed 2 | Seed 3 | Verdict |
|---|---|---|---|---|
| 1 | Label dataset % | 25% | MET | MET | MET | MET |
| 2 | Every Label F1 | > 60% | 44.4%/33.3%/92.3% | 82.3%/42.9%/69.0% | 66.7%/75%/89.7% | FAILED |
| 3 | Accuracy spread | <= 10% | 59% | 39.4% | 23% | FAILED |
| 4 | Content soreted correctly between `analysis` and `guide` | >= 60% | 50% | 91% | 78.5% | FAILED |
| 5 | Model Accuracy > Mean Confidence - 10% | 3/3 | MET | MET | MET | MET |

**Diagnoses**

- Criterion 2: A boundary I applied inconsistently
- Criterion 3: A boundary I applied inconsistently
- Criterion 4: A boundary I applied inconsistently & a genuinely hard label pair

As per the agreement report, I do tend to inconsistently apply rules in favor of the first few sentences within an article. However, there is also the discrepency of information for each article, as dev.to articles are quite long.

However, I do feel unconfident in the labels that I applied to each of the articles, especially the ones with the boundary between `analysis` and `guide`. Many of them guided the user to an outcome while providing information that deemed the process as the best way. Some analysis articles also guided the user through their thought process, which could be hard to differentiate for the model. 

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

**Agreement rate:** 29 / 30 = 96.67%

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
> *The post:* Pulled the splits from the last five editions. The winning time has moved by 40 seconds total in ten years, but the 100th-place time is four minutes faster. The depth changed, the front didn't.
>
> *Staff said / I said:* Staff said `analysis`, where I said `reactionary`
>
> *My call, and why:* My instinct was reaction due to the first sentence, where the user draws a conclusion immediately based on something they pulled. I didn't read the second piece clearly where a generalistic statement is made based upon the facts stated previously.
>
> *Which pile:* (a) the rule covered it and I applied it loosely. Staff said analysis, which is correct after further review as the checakble fact is indeed load bearing. 

**What the pattern in my disagreements tells me:**
My pattern in the disagreements tells me that I am biased on the first part of any text presented. My instinct was to take `Pulled the splits from the last five editions` and deem that as a reaction without reading the data and conclusion afterwards.

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
