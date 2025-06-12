# Introduction to Fateless Dungeon

Visit the [**Devlog**](devlog.md) page to keep up-to-date with the progress of Fateless Dungeon.

## What is Fateless Dungeon?

To put it simply, Fateless Dungeon is my attempt to *rebuild tabletop RPGs* into a more *modular and intuitive* experience.<br>

**What this means:** Role-playing becomes significantly less complex and easier to dive into. Even better — *immersion and nuance aren't lost at all.* In fact, they're *enriched*.<br>

Instead of throwing dice and number crunching, nuance comes from using AI to interpret the *probability* of actions, their *intensity*, and their *feasibility* — all through skill checks and contextual situations with *no human intervention required*.

## Why Fateless Dungeon?

First, I don't want you to misunderstand me:

I love Dungeons & Dragons — or at least the **concept** and **beauty** behind it.

My issue isn't with D&D itself — it's with the **barriers** that keep people from playing it. The time, the rules, and the pressure to know how everything works before you even join a campaign. I get *why* they exist, but I feel there's a better way. A smarter way. One that keeps the heart of the experience intact — and maybe even *frees it* — by using AI to interpret the mechanics behind the scenes.<br>

***BUT DON'T DISMISS ME JUST YET!***

I know what you're thinking:<br>
"AI is flawed. It's limiting. It can't capture nuance, and it struggles to hold context — especially in long campaign sessions."<br>
You’re not wrong. A lot of the D&D inspired AI tools out there? They’re interesting, even fun — but they’re not quite there. Some don’t even try to follow traditional rulesets. But there's just a small piece of the puzzle that I think can make this work the way it should...<br>

**Don't let AI take over the experience.**
I know that sounds strange — especially when I *just* advocated for AI — but I don't believe AI should dominate a campaign run by people.<br>
I *want* the players to stay in full control of their characters.<br>
I *want* the Dungeon Masters to shape their own worlds, challenges, and arcs.<br>
And above all, I *want* creativity to thrive between everyone.<br>
With Fateless Dungeon, you'll have control over the narrative in your campaign.<br>
You’ll have the freedom to build your world, tell your story, and bring your vision to life — all while the system quietly handles the background logic so you don’t have to.

## How Fateless Dungeon?

So, Fateless Dungeon is going to use AI, but not a lot of it, and never takes control away from the players. You might be wondering:<br>

**What's the AI is even doing in the first place?** Fair question.<br>

Let's keep it simple.<br>
**I'm replacing dice.**<br><br>
All you tabletop nerds out there know about the iconic 1d20. You know why it exists and what purpose it serves. But here's the thing:<br>
It only gives you 20 probable outcomes, and nuance starts hitting a ceiling pretty fast. So how much nuance do you need?<br>

***UNLIMITED NUANCE!***

*That* much. And you might wonder how that's even achievable?<br><br>
The solution is stupidly elegant: **use a float**.<br>
(For the unfamiliar: a float is just a decimal — typically between 0.0 and 1.0.)<br>

Now ask yourself — how many numbers are there between 0.0 and 1.0?<br>
If you said *infinite*, you're starting to see the picture.<br>

That’s where the nuance comes from. Not from a 1 through 20 range. From an infinite continuum of meaning — subtlety, margin, intensity — not just “success or failure,” but everything *in between*.<br>

**So what does the AI actually do?**

It doesn’t generate the float.<br>
It doesn’t play the game for you.<br>
It doesn’t make decisions or take control.

**It interprets.**

Here’s why that matters:

Large language models — the kind that power today’s AI tools like ChatGPT — already operate using floats.
Every word they generate is based on probability — on weighted decisions, guided by decimal values between 0.0 and 1.0.

These weights are what allow AI to understand tone, emotion, and intent. It’s how it knows when something’s sarcastic, uncertain, confident, or funny.

So in Fateless Dungeon, when a float is generated — let’s say a character rolls a `0.47` during a stealth attempt — the AI steps in, looks at that value, and tells you what that moment feels like.

Was it a close call?<br>
A nearly-blown cover?<br>
A clumsy step that somehow didn’t draw attention?

That’s the AI’s job: to turn the float into **feeling** — into *narrative texture*.

Humans can’t naturally assign meaning to a number like `0.47`. But AI can. That’s what makes this system work.

## What does this mean for Fateless Dungeon?

Actually? **It means a lot more than you think.**

Yeah, earlier I ranted about how D&D is this beautiful, but rigid time-sink that constantly checks your memory of the rules under the scrutiny of dice, and then I proposed a solution to all of that... but that’s just *the tip of the iceberg*.

Sure, you’ve got **unlimited nuance** now.<br>
But guess what? *So do people*.

People are nuanced.<br>
They interpret things.<br>
They feel things.<br>
They bend rules, tell stories, and build worlds from scratch — not with numbers, but with meaning.

So what does that mean for Fateless Dungeon?

**It means you can build entire worlds, generate living characters, and create unique adventures — with storytelling as your main mechanic.**

No spreadsheets. No manuals. Just you and your imagination, guided by a system that speaks your language.

That’s the real ambition here.

I’m not trying to patch over old systems. I’m rebuilding the foundation from scratch — using **prompt architecture** and a **custom-built backend** that holds its own weight. No more GM vs player tug-of-war. No more "read the rulebook" gatekeeping.

Take character creation, for example.

You won’t be plugging in numbers.<br>
You’ll be telling a story.

What kind of life did your character live?<br>
What did they train for?<br>
What did they survive?<br>
What are they *already* good at — and what scars do they carry?

All of that gets fed into the system. And from that story, **stats are born**.

But here's the twist — they’re not born as numbers you see.<br>
They're born as **floats** — invisible, under-the-hood values between 0.0 and 1.0.

You won’t see those floats.
But the AI will.

It uses them to determine **probability**, **intensity**, and **feasibility** — the unspoken rules behind *how well* your character pulls something off.

And what do *you* get back?

You get clean, readable stats — intuitive, expressive, and grounded in your character’s narrative.<br>
It’s not just an illusion of depth. It’s *depth with a disguise*.<br>
An illusion that’s *real enough to matter*.

You wrote the story.<br>
The AI just translated it.