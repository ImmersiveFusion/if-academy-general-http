---
title: Borrowed judgment
diataxis: explanation
tags: [essay]
---

# Borrowed judgment

*This one is about a quiet kind of trouble: the kind that does not announce itself, that shows up on no dashboard, that the people closest to it cannot feel coming. There is no emergency in it. That is the point.*

---

Picture someone good at their job. Not a beginner. Years in, trusted, the person other people check with. They have been moved onto something new: pricing the company's AI product. There will be tiers, Basic, Professional, Premium, and the job is to set them so the company makes money and the customer is protected from a runaway bill, the kind everyone now points at, the half-billion-dollar invoice that made the news.

It is a new domain. Nobody has deep intuition for what AI usage costs yet, because the ground is too new to have grown any. So they do what a sensible person does with a new tool that is good at numbers: they let it build the first model. It produces the tier limits, the cost projections, the per-plan budgets. The numbers are clean. They are internally consistent. They look right.

The plans ship. Every month the costs come in roughly where the model said they would, which is exactly what the plan promised, so nothing ever asks anyone to look again.

Here is the part worth slowing down on, because it is the whole essay.

A note in the design said the AI functionality was vendor-agnostic. That was true, at the level of the plumbing: the system could run on more than one model provider. And somewhere between that true sentence and the pricing, the word quietly grew. *Vendor-agnostic* became *we can sell on any vendor.* It sounds like the same thing. It is not the same thing.

Underneath *vendor-agnostic* sat a whole world: each provider has its own approvals to clear, runs out of its own data centers, prices on its own curve. A heavy model on one provider is not a heavy model on another. The word was carrying far more than it could hold, and it was accepted whole, the way you accept a word when you do not yet have the feel for what it is hiding.

We have done this before, in these essays, with other words. The first one took *safe* and broke it into the parts a parent actually needs at a kitchen table. The firefighter took *caution* and broke it into the temperature of the door, the give in the floor. The move is always the same: when a word in front of you is carrying too much, you break it into the parts that matter. *Vendor-agnostic* was exactly that kind of word. The thing that breaks a word like that into its parts is judgment, the felt sense of what is hiding inside a confident phrase. And that is the thing that was never there.

---

Set that beside the other thing the model got, quietly, wrong.

The caps were round, plausible, authoritative numbers that had never been checked against what real use actually looks like. Nobody ran the real usage, because the model had already produced a number and the number looked fine. The plans held only because, at first, almost no one was really using them. The first time the product got used hard, in earnest, by the people building it, the caps drained far faster than the plan had assumed. The model had not been wrong on its own terms. It had answered the question it was handed, *what is a reasonable-looking cap*, which was never the real question, *what cap does real use actually require.* Nothing in the clean output marked the difference between those two questions. A person with the judgment would have felt the difference. There was no person with the judgment.

So now name what actually went missing here, because it is easy to name the wrong thing.

The wrong thing to name is the checking. It is tempting to say the lesson is *they should have verified the numbers,* and verification is a real skill, and we have written a whole essay about it. But that is not what happened here, and saying it was would let everyone off too easy. You cannot check a number you have no feel for. Checking assumes you already hold the judgment that tells you a number is worth a second look. The trouble in this story is one level underneath checking: the judgment that would have made the number feel wrong was never built.

Here is how judgment gets built, when it gets built. You do the thing yourself. You model the cost by hand, and you get it wrong, and the wrongness costs you something small, and you learn what the numbers mean by being corrected by them. You do it again. After enough of that, you have a feel: you can look at a projection and something in you says *that cannot be right,* before you can even say why. That feel is not magic. It is the residue of having struggled with the material and been corrected by it, many times. The struggle is not the tedious part of building judgment. The struggle is the part that builds it.

This is not a theory we are floating. When researchers gave nearly a thousand students a version of an AI tutor with no guardrails, the students solved about 48 percent more practice problems correctly while they had it, and then scored 17 percent below the students who never used it on an exam they had to take without it. The tool made the work look better and the learning worse, at the same time, and nothing in the moment told anyone which was happening. The same study built a second version of the tool, one that made the student do the thinking first, and that version did no such harm: those students came out no worse than the ones who had no AI at all. The difference was never the tool. The difference was whether the person was made to do the cognitive work or allowed to skip it.

That is the named thing. We will call it by what happened: the formative loop never ran. The tool did the task, correctly, from the first day, and the correctness is exactly what removed the struggle that would have built the judgment. Nobody decided to skip the formation. The formation was skipped because nothing required it, and skipping it cost nothing visible, and everything on the surface said the work was going well.

None of this is about pricing, particularly. It is about new ground. A surgeon who has read scans for twenty years lets an AI draft the first read on a kind of imaging the hospital only just adopted, and the old instinct that would have caught the miss never fires, because it was built on the old machine, not this one. An editor who can feel a weak sentence at a glance lets a tool do the first structural pass on a kind of writing they have never built by hand, and the feel that protects them everywhere else has nothing to grip here. The pattern does not care about the field. It cares whether the ground is new enough that the judgment you trust was built somewhere else.

---

Now, the honest objection, because this is the essay where we owe you the strongest version of it.

You might say: people get better with these tools, not worse. There is good evidence for that. In one large study of call-center workers given a capable AI assistant, the workers got measurably more productive, fast: about 14 percent more on average, and 34 percent more for the least experienced, who gained the most. Some of the gain stuck even when the tool was taken away. We will hold that finding to the same standard we are about to ask of our own: it is one setting, one kind of work, measured while the tool was in use, and it is the strongest case against what this essay is worried about. The tool spread hard-won expertise to people who did not have it yet. That is real, and we are not going to pretend it away to win the argument.

And you might add a second objection, the one that matters more here, because the person in our story is not a beginner. *I am experienced. I have spent years learning how to tell when a thing is off. I have been burned by plausible-looking numbers before, in other work. That instinct travels. I would have caught this.* That objection is strong, and partly right. A seasoned person does carry something a true beginner does not: a transferable sense of how to interrogate a confident answer, a memory of having trusted a clean number that lied. Expertise in one place is real scaffolding for learning another. The experienced person is not a blank slate; they are a faster, better-defended novice. And there is more than one way to build the missing judgment: you can study, you can be taught, you can interrogate the tool's output hard, without ever doing the grunt work by hand.

We concede all of that. It is true. And it is not enough, for one specific reason. We should be honest about the standing of what comes next: the studies that exist were run on students and new workers learning a skill for the first time, not on seasoned people thrown into new ground. So when we carry the finding to the experienced person, we are reasoning by resemblance, not pointing at a measurement of exactly that case. We think the resemblance holds, and here is why.

The two findings are not in conflict, because they measure different things. The workers who got better were engaged with the underlying work; the tool was helping them do a thing they were also learning. The trouble we are describing is what happens to the person for whom the tool did the underlying work from the start, so the engagement that builds the judgment never had to happen. And the transferable instinct of the expert, the one that travels, is weakest in exactly the place this story lives: in genuinely new territory, where the new domain fails in ways the old domain never taught. A veteran of one kind of pricing has no stored instinct for how token economics breaks, because nothing in their past ever broke that way. Worse, the expert's confidence is itself part of the trap. The feeling of *I would catch it* is precisely the feeling that keeps you from looking, because looking is for people who are not sure. The better you are everywhere else, the more your own competence helps hide the one place you have not earned it yet.

So the experienced person is genuinely better off than the beginner, and genuinely not safe. Both of those are true. The essay does not need them to be defenseless. It only needs them to be less defended than they feel.

---

There was a third cost in this story, and it is the one that left the building.

Before any of the trouble surfaced, the experienced person stood in front of other experienced people and made the case, with the easy confidence of someone who is usually right: these tiers save the customer money and cost us less, because the token costs are predictable and we are leaning on our own caching and other optimizations. It was a good case, well made, by someone trusted, and the room believed it because the room had reason to.

It was wrong on both halves. The limits were too small. The model ran more expensive, not less, for everyone. The company had to walk the statements back, reach out to customers, and clean it up. And the thing that allowed the confident claim was not arrogance. It was the absence of the judgment that would have said, quietly, before the meeting, *I do not actually know this well enough to promise it.* That sentence is one of the most important things judgment does. It is also one of the first things you lose when you never built the judgment, because not-knowing-what-you-do-not-know is the native state of a domain you skipped the formation in. The more authoritative the tool's output looked, the more confidently the promise got made, and the larger the eventual retraction.

---

If you have read our other essays, you know we usually turn here toward the thing you can do, and there is one, so let us be plain about it. When the ground under you is genuinely new, the judgment you trust everywhere else is not there yet, and nothing in the work will tell you that. So you have to build it on purpose. Model the new thing by hand once, even though the tool could do it faster, so that you find out where it bites. Take the confident word, *vendor-agnostic*, *predictable*, *optimized*, and break it into its parts before you build on it. Treat the clean number as a question, not an answer, until you have the feel that lets you know whether it is a good one. Whether you do that by hand, or by study, or by interrogating the tool until you understand what it understood, matters less than that you do it at all.

But here is what we are not going to do. We are not going to tell you this is easy, or that naming it fixes it, or that you will be fine. The move costs real effort, and it costs it precisely when you have the least reason to spend it, because everything visible is telling you the work is going well. There is no alarm for this. No metric turns red in time. No manager flags it, because the manager is reading the same clean numbers you are, and because the manager has their own version of this, what they owe the people whose formation they are quietly deciding, which is an essay of its own and we will write it. The reviews come back good. The plans ship. The months go by predictable, right up until the part that was never underneath them gives way.

The work that is left, the arc has said before, is the work that was always going to be yours. In this one case that line is not a comfort. It is the problem stated exactly. The work that was left for this person, the judgment underneath the numbers, was the work the tool did first, so it was never built, so when the moment came that only judgment could meet, there was nothing there to meet it. The work that is left is still yours. It is just yours to go and build, alone, unprompted, against every signal telling you that you already have.

That is the part nobody will tell you. The clean numbers least of all.

---

*by Immersive Fusion. Essays. Dated 2026-06-03.*

*Our editorial commitments, what we publish, what we don't, how we handle mistakes, are on the [About](../../about.md) page.*
