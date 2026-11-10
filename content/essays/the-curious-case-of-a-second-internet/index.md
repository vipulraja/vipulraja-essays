---
title: "The Curious Case of a Second Internet"
date: 2026-11-10
draft: false
description: "What if there were a second internet with one rule: only humans allowed? We could use both; but AI could only use the current one."
tags: ["epistemology", "ai", "internet", "privacy"]
ShowToc: false
---

*What you read below is a fictional, hypothetical essay in the traditional sense of literature and the English language, i.e. a piece of writing that intersects current phenomena and builds on them with the author's imagination. This is a curious thought that I watered over coffee chats and lunch conversations. All out of wonder and awe! I am a power AI user (whatever that means to you) and can't argue strongly enough about the use of AI for the benefit of our species, planet and beyond. I hope this essay sparks curiosity in the reader or at the very least provides entertainment; we could use more of both in our lives.*

Sometime in 2024, for the first time, most of the traffic on the internet stopped being human. Imperva's 2025 Bad Bot Report put automated traffic at 51 percent of everything that moved across the web that year, with people at 49 percent and falling.[^1] Volume, though, is the mildest part of the story. At the engineering firm Arup, a finance worker wired $25 million after joining a live video call in which the CFO and every colleague on screen turned out to be a deepfake.[^2] In June 2025, a zero-click flaw in Microsoft 365 Copilot (*EchoLeak*, CVE-2025-32711) showed that a single incoming email carrying hidden instructions could coax a workplace AI assistant into pulling confidential files and exfiltrating them without the recipient clicking a thing.[^3] By November, Anthropic was reporting the first AI-orchestrated cyber-espionage campaign, in which an agentic coding tool carried out 80 to 90 percent of an operation against roughly thirty organizations largely on its own,[^4] and within weeks a solo operator used commercial AI agents to breach nine Mexican government agencies and walk away with hundreds of millions of citizen and taxpayer records.[^5] On the privacy side, desktop features like Windows Recall and a new crop of "agentic" browsers normalized quietly reading whatever sits on our screens, from banking tabs to private messages, even as security researchers showed that hidden prompts on ordinary web pages could hijack those same browsing agents into leaking data from logged-in accounts.[^6]

The privacy and security risks associated with frontier AI advancements are (more than) significant, as is widely accepted by the top AI labs as of this writing. Sit with that long enough and an odd question shows up, one that sounds wild at first. What if there were a second internet? Not to replace the one we have, but a separate refuge built on top of the same wires with a single rule: only humans may enter and traverse it. People would be free to move between both. Machines would stay in the first.

You would still reach it in a browser, your words would still sit on disks, and search would still be search. Nothing about the physical network would have to change; the web itself is already a space layered on top of TCP/IP, the way a national park sits on the same geology as the strip mall outside its gate. What changes is the rule about *who is using it*. An autonomous agent could not browse it, post to it, scrape it, or train on it. A person could read in both places and, if they chose, carry ideas from one back into the other: a membrane that is one-way for machines and two-way for people.

## What could this possibly mean?

Anything you, I, our agents or someone worse write in public is, by default, training material. I will expand on this below. Cloudflare's decision in July 2025 to block AI crawlers by default for new sites, and to let publishers charge for access, was a remarkable admission by the company that carries roughly a fifth of web traffic.[^7] Yet site-by-site opt-outs depend on whoever happens to own the server. Imagine a commons where that flipped default is simply the ground rule of the place.

Extraction is what happens when machines read a human room; something just as corrosive happens when they talk back in it. Almost every harm that AI amplifies online is a harm of scale. One scammer with one script is a nuisance; one scammer running ten thousand patient, persuasive, individually tailored personas is an industry.

Humans are limited in a way that turns out, for once, to be load-bearing. We get tired. We can only hold so many conversations at once. We cannot be forked. In a room that admits only people, influence is once again bounded by the number of actual human beings willing to spend part of their day holding a view, which means the old, rough heuristics of social proof start working again. Imperfectly, as they always did, but well enough to miss now that they are breaking.

Beneath both privacy and scale sits the part I keep coming back to: what happens to how we figure out what is true.

Knowledge grows through conjecture and criticism. Someone puts an explanation on the table, others try to break it, and what survives is what we provisionally keep. Karl Popper gave that idea its sharpest form, though you do not need to be a Popperian to see that the engine of progress is people criticizing each other's ideas in good faith.

There is an irony here worth savoring. Machine learning researchers have their own name for what happens when models feed on synthetic output. Shumailov and colleagues showed in *Nature* in 2024 that models trained recursively on generated data lose the tails of the distribution first, the rare dialects, the odd ideas, the minority positions, before collapsing toward a bland center.[^8] Frontier labs now treat verifiably human text as a scarce, non-renewable resource. The very industry flooding the commons has, by its own math, the strongest reason to hope that somewhere on earth unscraped human thought continues to happen in the wild. Even the first internet has reason to want a second one.

So, let's summarize. So far, we now have 2 threads we're poking at with possibilities with a second internet: A) Humans find a place to talk with fellow non-machine intelligence forms. B) This actually gives us great fodder to train better AI for the future.

There's a third consequence worth mulling over: "What could a human's day look like if this were true?" I picture myself having to frequently switch between the 2 internets, one to connect with other humans and the other to check on my AI. I could see companies operating 2 private networks, one on each internet. We'd let a whole lot of autonomous AI work happen on the AI internet and keep private crown jewels on the human-only internet.

## Parting words

The analogy that I have from our planet for this is how our civilization is shaped. We decided to draw lines on the map, and on one side of the line the bulldozers stopped. The land on the other side is not worse land. It is the same land. It is simply land where a particular class of capable machine has been told *no*.

Just like a national park is not an attack on cities, having wilderness doesn't mean you cannot also have highways.

The first internet was built on the assumption that there was a person on the other end. We never wrote it down because reality enforced it for free. Reality no longer does. Maybe we simply get used to that, the way we got used to robocalls, and learn to read everything online with a permanent flinch. Or maybe, alongside the internet where people and machines mingle at machine speed, we draw a line on the map and keep one place where a sentence is still evidence of a non-machine lifeform.

The wild places are not wild by accident; which internet in this story you consider wild is up to you!

---

[^1]: Imperva (Thales), *2025 Bad Bot Report*. Automated traffic 51%, of which 37% "bad bots" and 14% "good bots"; human traffic 49%. https://www.imperva.com/resources/resource-library/reports/2025-bad-bot-report/
[^2]: Hong Kong police disclosure of HK$200 million (US$25.6 million) deepfake video-conference fraud at Arup (February 2024). https://edition.cnn.com/2024/02/04/asia/deepfake-cfo-scam-hong-kong-intl-hnk/index.html
[^3]: Microsoft Security Response Center, CVE-2025-32711 (*EchoLeak*), zero-click indirect prompt injection in Microsoft 365 Copilot disclosed by Aim Security (June 2025). https://msrc.microsoft.com/update-guide/vulnerability/CVE-2025-32711
[^4]: Anthropic, "Disrupting the first reported AI-orchestrated cyber espionage campaign" (13 November 2025). https://www.anthropic.com/news/disrupting-AI-espionage
[^5]: Gambit Security, "A Single Operator, Two AI Platforms, Nine Government Agencies: The Full Technical Report" (2026). https://gambit.security/blog-posts/a-single-operator-two-ai-platforms-nine-government-agencies-the-full-technical-report
[^6]: Simon Willison, "The lethal trifecta for AI agents: private data, untrusted content, and external communication" (16 June 2025). https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/
[^7]: Cloudflare, "Content Independence Day: no AI crawl without compensation" (1 July 2025). https://blog.cloudflare.com/content-independence-day-no-ai-crawl-without-compensation/
[^8]: Ilia Shumailov et al., "AI models collapse when trained on recursively generated data," *Nature* 631 (2024). https://www.nature.com/articles/s41586-024-07566-y
