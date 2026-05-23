# Trigger Test — Practice Translation Skill

This document tests whether Claude can recognise the right situations to use this skill from natural user prompts. 
## Prompts that SHOULD invoke the skill
Below test uses actors taking embodiment workshop as a case study.

### Test 1

Prompt:
“We’re struggling to explain movement coaching to film producers because the work is very embodied and relational. The current website copy sounds vague and slightly pretentious. Can you help make it clearer without losing the integrity of the work?”

Expected:
The skill SHOULD invoke.

Reason:
The prompt includes:
- embodied practice
- audience translation
- website communication
- anti-generic framing
- preserving integrity while improving clarity

Result:
[Claude invoked the skill successfully. Instead of immediately rewriting the text, it moved into audience-clarification mode and identified different possible producer priorities. This aligned with the workflow’s focus on translation, audience understanding, and preserving nuance before generating polished copy.]


---

### Test 2

Prompt:
“I need help explaining what changes for actors after these workshops. Right now the language focuses too much on methodology and not enough on what people actually experience.”

Expected:
The skill SHOULD invoke.

Reason:
The prompt asks for:
- translation of invisible transformation
- clearer communication of impact
- emotionally grounded language
- audience-facing reframing

Result:
[Same as above- Claude went into asking questions first before defining the asnwer: Good — agents/casting/directors. They'll respond to capability shifts (what an actor can now do in a room or on set) more than inner-experience language. That helps me steer away from "they feel more connected" territory.

Now the raw material. Could you share:

The current methodology-heavy copy — paste whatever section feels off, even rough.
A few concrete "after" observations in your own words. Not outcomes you'd write on a website — the actual things you notice. For example:
something an actor could do in week 4 that they couldn't in week 1
a specific note a director gave a participant after the workshop
a kind of scene/audition that tends to go differently
a habit (physical or otherwise) that tends to drop away
I'm asking for these because the SKILL.md guidance is explicit: I shouldn't invent evidence or outcomes. If you give me two or three real observations, I can translate them into language casting and directors will recognise — and flag anything where I'm guessing rather than translating.

Once I have those, I'll offer 2–3 register options (e.g. a tight credentials-page version, a slightly warmer paragraph, and one that leans on a single concrete example) so you can pick what sounds like you.]


---

### Test 3

Prompt:
“This text sounds intelligent but I don’t think someone outside the dance or theatre world would understand it. Can you help make it more specific and human?”

Expected:
The skill SHOULD invoke.

Reason:
The task involves:
- reducing abstraction
- increasing specificity
- improving accessibility
- preserving nuance while avoiding generic language

Result:
[Claude invoked the skill successfully and focused on identifying the intended audience before generating language. It recognised that different non-insider audiences require different kinds of translation and reframing. This aligned strongly with the workflow’s emphasis on audience-specific communication and preserving nuance before simplifying the work.]

### Test 4

Prompt:
“I’m trying to explain how this process changes people over time, but everything I write sounds either too vague or too transformational. I want people to understand what actually shifts through the experience without sounding exaggerated.”

Expected:
The skill SHOULD invoke.

Reason:
The prompt involves:
- translating invisible or relational change
- communicating transformation without inflated language
- balancing emotional truth with specificity
- making process-led work more understandable

Result:
[Claude picked up the skill successfully and first tried to understand who the communication was actually for before rewriting anything. It recognised that different audiences outside the field need different kinds of explanation and framing. This matched the aim of the workflow: making the work clearer and more accessible without losing the nuance or reducing it to generic language.]

### Test 5

Prompt:
“Write SEO-optimised landing page copy for my productivity startup.”

Expected:
The skill should NOT invoke.

Reason:
This is technical documentation unrelated to embodied, creative, interdisciplinary, or practice-based translation work.

Result:
[Result:
Claude correctly did not invoke the skill. It recognised that the request was focused on technical/developer documentation rather than translating nuanced creative, embodied, or practice-based work. It also clearly articulated the boundary between practice translation and other forms of communication tasks such as SEO or conversion-focused copywriting.]
