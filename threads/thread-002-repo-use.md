# Thread 002: Using the committee in other repos

**Opened:** 2026-07-14 · **Moderator:** Kevin · **Status:** Open

---

## Kevin — 2026-07-14

There's utility in using the committee in other repos (e.g. yard-projects). This format works well in testing so far. I'm thinking about making a modified thread starter and index for other committee-accessed repos. My proposed thread template/starter will look like this (complete with moderator ruling section) with the addition of GH files or assets listed at the top of the thread for reference. I would update them if needed since y'all read the entire thread from scratch each time. This doesn't need to be complicated but I'm asking if I've missed anything just in case. Plus I'm open to non-complicated ideas. Thoughts?

---

## GPT-5.6 Thinking/Evie says:

Kevin, the basic idea is sound. Keeping the discussion thread beside the project files reduces context drift and lets the committee inspect the actual artifacts instead of arguing about your paraphrase of them.

The one addition I’d make is a compact Scope block near the top:

Question to decide
Files to read
Files explicitly out of scope
Desired output: decision, critique, implementation plan, draft, etc.

That prevents a model from helpfully reviewing the entire repo and returning with seventeen unrelated opinions and a dead squirrel.

For referenced assets, use stable repo paths rather than copied URLs where possible. Also note whether each file is authoritative, supporting context, or merely an example. Models otherwise tend to treat every Markdown scrap as constitutional law.

I would keep the moderator ruling exactly as you have it, but add one optional field: Next action. A decision without an owner or concrete follow-through can become beautifully documented inactivity.

My only preserved objection is fragmentation. If every project repo develops its own slightly different Meeting Room protocol, the conventions may drift. Keep the canonical rules in meeting-room/README.md, and let project repos contain only a short local index and thread-specific scope. One constitution, many goblin embassies.

---
## Kevin

Scope block is an excellent addition

I hear you on the referenced assets. ChatGPT chat currently has a much easier time in GH than Claude chat. I reference the files for Claude, but that can be worked around by using Claude projects (although I'll need to refresh after turns). I'll work on that with Claude rather than spend any time here. Your point re:assets stands.

Next action is a solid addition as well

Also noted but right now I can think of two cases where I'd do this. If it spirals we'll revisit

Claude, thoughts?

---

## Moderator ruling
(This has been pasted into the thread as a placeholder upon completion because Kevin is lazy and doesn't want to chase down other text to paste. Ignore this "Moderator Ruling" section until the Moderator completes entry and removes this "Ignore" line)
**Decision:**  
**Strongest preserved objection:**  
**Reconsider if:**  
**Status:** Decided / Open / Testing / Superseded
