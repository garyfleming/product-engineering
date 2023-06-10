theme: Titillium, 1


Prework:

* pack a stopwatch. Use iphone if you forget.
* Turn up to the stage ahead of time. Take a picture of yourself with the "Too meta?" slide. Put it into this run of the slide deck.
* Capture the stopwatch time. Add to the data table.

---

# Estimates And Complexity
# A Tale In Forty Two And A Half Minutes

@garyfleming

^ This talk is called Estimates... [start stopwatch visibly]
^ My name is Gary, I am a ..., been doing agile stuff for many years.
^ My first question to you is: do you think that this talk will take 42.5 minutes?

---

# Disclaimer

Opinions expressed in this talk are my own, and not representative of my employer's views.

^ While you ponder that here's the a small disclaimer. Much of the experience this talk is based on happened before I started with my current employer.

---

# Forty Two And A Half Minutes.

^ Back to the question: who thinks this talk will be done 42.5 minutes after I started? i.e. who thinks it'll take that amount of time or less?
^ I mean, I could stop the talk right now and fulfill that criteria, but I probably wouldn't have done the job of delivering the talk.
^ Let's imagine I do a reasonable conference talk in terms of content and takeaways: do you think I'll finish within a few minutes of the title's implicit deadline?


---

# Deadlines

^ I used the word deadline there. I'm sure most of you are familiar with deadlines: A date is given by when something absolutely positively must be complete or there will be GRAVE CONSEQUENCES.
^ I think the problem with deadlines is that they're largely self-imposed and... nothing really happens when they go whizzing by.

^ Many deadlines come out of either:
A) HIPPO
B) Wild guesses
C) A pseudo-estimation process like story pointing being turned into a date based on questionable methods (we will be coming back here)

^ The only real deadlines I've seen are where they're tied to external events that we can't control or where there is a dependency on something else with a long lead time we can't control

Examples:
* Building an app for a sporting event,
* Regulatory requirements kicking in,
* Creation of physical items

^ They're not going to delay Wimbledon for your app.
^ HMRC aren't gonna move the end of the tax year for you.
^ Making iPhones takes time; pretty hard to control for that.

^ Most deadlines aren't real. There are few meaningful product consequences. Doesn't mean we can entirely ignore them, however. There can be very real social consequences, fair or unfair.

^ Given the length of my slot, I *can* go a few minutes over my imposed deadline. 45 minute slot, gives me 2 and a half minutes of slack. I *might* be able to go on a few minutes into the lunch break/next slot too.
^ But eventually that has social consequences: you want lunch so you'll likely leave, The next session starts at some point so someone would come and get me off stage. And I'd probably not be invited back again. That doesn't help anyone.
^ TODO what are you trying to say here?


^ IRL Maybe a manager gets annoyed that their self-imposed deadline they reported didn't get met. It doesn't matter that it was realistic or not, that it was artificial or not; there's a lot of trust and social capital. Teams who fail to deliver to deadlines consistently will lose trust.
^ Conversely, teams who are frequently held to unrealistic and arbitrary deadlines will lose trust in their management and leadership - Why should they be treated poorly for bad deadlines?
^ TODO what should we do as managers and stakeholders

^ To summarise: there are often consequences for deadlines, real or imagined, being missed; for both those held to the deadline and those who set it.

---

# 42.5

^ Anyway, back to 42.5 minutes.
We've established some external constraints (someone will kick me off stage eventually), but why do you think I'll finish on time? What information is that based on? Let me drip feed you a few things

* I claim I've never gone over a talk time in the past. Not even by a few seconds.
* You've seen me talk before and the last claim is true in your experience.

^ Experience. Experience matters. If we've got relevant experience in doing something, we're better able to predict whether we can do something similar... assuming it's the kind of thing that is repeatable, where we have experience.


---

TODO insert explanation of complexity here.
TODO talk about complexity of system e.g. interdependent teams hard to predict: any 

---

* I've done this talk zero times before.

| Place | Date | Slot time | Run time |
| --- | --- | --- | --- |
| Lean Agile Glasgow | 14th June 2023 | 45m approx. | ? | 

^ I've literally never said these words out loud. Never in practice. Never for anything else. There's clearly a structure I'm following and a plan I have in mind, but I don't know if that's sound knowledge based on my understanding of this subject and the constraints we have today. I mean, the fact I have slides is a pretty obvious indicator that it's not all just off the cuff thinking. I had to write the slides. It took many hours. Including writing and planning to say this part here about how I haven't practiced, but do have a structure.
^ TODO make a note of the stopwatch time and add the data here.


---

Too Meta?

^ TODO insert picture of me here

^ Some of you are probably getting a little bit uncomfortable about the metaness of the talk. But think about this, a talk is a deliverable, with a fairly real deadline, based on some knowledge and some unknowns, that we have to make decisions on upfront. I had to submit a title and and abstract and learning outcomes about this talk before I had written it. I had to decide the product months in advance, rather than feel my way along.
If that's not a microcosm for a lot of software development, I don't know what is.
So yes, the analogy will continue, but don't worry we'll be going to more overtly software stuff soon.

---

* I wrote the talk title 5 months before I wrote the talk (because I thought this stopwatch idea was a good hook).

^ The title isn't based on knowledge of the talk itself.
^ Title is an estimate I gave *in a real unit of time* months before I knew exactly what the content was going to be. A delivery estimate with only the faintest amount of information. Does this sound like a good idea? 
So how did I pick it?

---

# 45 minutes
# 42 and a half minutes

I've done this before; I know I can generally fill 45 minutes of airtime with reasonable material on most subjects I care about. I know that 42.5 is a more interesting title because of it's absurd precision.
^ 45 minutes sounds too round. Sounds like 45ish. 42.5 sounds like I'm being pretty precise

---

# 42 Minutes, Thirty Three Seconds

^ I could've called teh talk "42 minutes, and thirty three seconds" and you'd have believed me less.


---

# 42 Minutes, Thirty Three Seconds, 481 Milliseconds

^ Add in milliseconds nad it gets weird. No-one would (or should) believe that the talk will take that long. It's overly precise for the context. There are too many things that can vary. To be anywhere that precise.

---

# Increasing precision of estimates can have negative effects

^ Good estimates aren't about precision. They're not. Broad estimates that have implicit error bounds and uncertainty help establish trust. They show, to some extent, that you know that you don't know.

^ Overly precise estimates in this context decrease trust. They decrease. Use flat numerical systems with no error bounds leads to all sorts of weird behaviour and misunderstanding.

---

# story points

^ .. Which inevitably brings us to story points.

don't like them
Reasons why
* The cargo cult of story points - Blindly adhered to, rarely understood, rarely to answer a specific question, without consideration of complexity etc
precision
 - SPs are at a middling level of precision. Neither particularly precise for when that's appropriate, or revealing of the inherent error bound and unknowns in the estimate. 
people think they can do things like capacity with them.
- the Tuckman model myth in modern dynamic systems.
- Dynamic reteaming - When was last time someone joined/left your team? parental leave? Sick leave? Secondment?
- NOT advocating for 
people doing maths
2+2+2+2 is not the same as 8 story points

better alternatives
- slicing
  - how? why? mechanisms?
  - the talk: breaking it down to write
    - Theme and stopwatch conceit
    - Major takeaways
    - How do we explain those takeaways?
    - What does the audience need to know?
    - How long does each part take?
  - the talk: the performance
    - I can slice here as well
    - Know what the biggest parts are
    - What cannot be skipped
    - You don't know what the slides are so you don't know if I just skip one.
    - As long as I can keep the rough structure in my head, I can slice as we go
- Complexity
  - How 
- Just don't estimate -- in time at least
  - Flow
  - Value
- "Can't not estimate, have deadlines"
  - Slice small using metrics that prioritise value
    - Smallest version that adds critical value
  - Slice for value, then flow.
  - Deliver often.
  - CI/CD == Vital capability for delivery
  - Frequently evaluate where you are against thinnest end to end delivery
    - Pretty much *always* deliver value to users way before "deadline"
    - Can then prioritise with more information.

- Really need dates?
  - Monte carlo simulation TODO lots to unpack here.

---

# Slide Title

^ Presenter notes

---

# Thank You

@garyfleming
