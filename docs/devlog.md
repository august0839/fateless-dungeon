# Fateless Dungeon Progress Report

This is a devlog to keep track of what my programming journey has been like for [**Fateless Dungeon**](index.md). To read everything in order, start from the very bottom and make your way up. Latest information is just below.

## 2025-06-11 | First Day of Logging

<p>Hello, I'm August. I started this project not too long ago, but I made many different discoveries and realizations on the way. Python and ChatGPT has been my bestfriends and I'm learning so much every passing day. I don't know what came over me, but I just had this idea to reinvent the wheel for tabletop roleplaying games. Sure enough, here I am.</p>

I have little to no history or experience with programming with Python or Large Language Models (LLMs), let alone any language for that matter. Even programming with prompts is foreign to me, yet I'm here trying to build an entire prompt architecture that is largely supported by a Python backend. If you read the [**main page**](index.md), you'd kind of know what I'm talking about already. I'm not really getting help with this project either other than using ChatGPT. The more I used it, the more hurdles I realized I had to overcome, the more impressed I became with technology. AI is amazing, but... moreso the human brain.

After growing a deeper understanding about all the tools I'm using, the more I realize that AI is just a really impressive tool that strongly depends on the prompting of a human engineer. I've got llama3:8b installed locally, but it wasn't nearly enough to come out with impressive results. But it didn't take me long to understand that the impressive results isn't due to other models being better. It's because the other models had more finetuning to get to the state they are today. God knows what sort of prompt architecture ChatGPT is using, but it's absolutely incredible. If I want Fateless Dungeon to be as cohesive as ChatGPT's AI, I have to be very smart about how I build everything in tandem with one another.

**Let's talk more about Fateless Dungeon.**<br>
*It's not a game.* It's moreso a system. A system that... *without sounding like a corporate shill...* introduces tabletop roleplaying games to a modern era.<br><br>
Okay, that still sounds like I'm a shill. But one thing to note is that I'm serious about this vision. I actually believe this is something that could work and be a thing, and I feel like I'm the only one willing to push the envelope with my rudimentary understanding of anything related to this.<br>

What I wish to do is modularize roleplaying games by reducing all of the rules into float based stats and dice rolls. That sounds horrendous on paper, but that's actually excellent for AI. See, AI flourishes from interpreting weights via floats. But on the other hand, that's not for the user to worry about. My idea is to convert these values into readable stats that accurately depicts your character. It won't automatically know what `0.2435 strength` means, but if you create a prompt that gives a *standard* for what numerous values could stand for, the AI will follow that and "weigh out" what your character is like. Floats are the AI's language, and it is programmed to spit out an interpretation into our natural language. This is what an AI is *good* at, and I intend to take advantage of its strong points. It is *not* however strong at leading a solid campaign. That's the human's job. The AI is only going to read floats and interpret as we go.

**What I plan to do with Fateless Dungeon.**<br>
I want to take this float based system and expand upon it greatly. It's not going to rebalance D&D, it should reinvent tabletop roleplaying games. I want people to be able to create character, world, or campaign by simply executing vivid storytelling. In the end, you could be as nuanced or vague as you like and the blanks will be filled. But all of this has to have a robust design in mind. Prompts can't just be massive paragraphs that will autofill blank spots in a json file, it should be constructed in a modular way. I'm figuring everything out as I go.

**What I've done so far...**<br>
I've scaled Strength. `0.5` is for an average human, `0.0` is a lifeless corpse or ghostly spirit, and `1.0` is a God with infinite strength. This is a very rough design, but a solid start to just get something working. This will be refined further, because I do feel like strength grows in an exponential way. When a person gets stronger, there are diminishing returns, so `+0.05` gets more and more critical the closer you get to `1.0`. Does that make sense?

In addition, I have a bit of a sandbox environment that I've programmed (with ChatGPT's help) to simulate a round system with a Farmer and Goblin attacking each other. I'm going to need to work on this some more at some point, but I do want to improve upon it in the near future.

Welp, that was my first day doing a devlog. Rough, wordy, and uninteresting. It's past midnight and I got work on the morning. Good night all.