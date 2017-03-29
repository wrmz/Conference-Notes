# Guaranteed Successful Design

__Speaker__: [Noah Iliinsky](http://complexdiagrams.com/), Senior UX Architect at Amazon Web Services

Video: [John Scully on Steve Jobs](https://youtu.be/S_JYy_0XUe8) (46 sec.)

## Takeaways

- Design the _right_ thing
- Design the right thing _well_

---

### Separate Required Function (What) from Implementation (How)

Do not get deeply into implementation at the start. If you do, you fail to see the broader scope and miss better solutions.

As an analogy, consider what one would look for in a relationship (for kicks & giggles):

| Function | Implementation |
| - | - |
| Attractive (to me) | Tall, dark |
| Entertaining, fun (to me) | Funny |
| Stable/Prestigious | Rich |

- __Function (What)__ _What you shouldn't be talking about_
  - Search
  - Redundant
  - Link
  - Remote
  - Multiple
  - Window
  - Host
  - Mobile
  - App
  - Button
  - Portable
  - Cloud
  - Page
  - Dropdown
- __Implementation (How)__ _What you should be talking about_
  - Available
  - Durable
  - Pleasant
  - Performant
  - Scalable
  - Affordable
  - Accessible

### Abstract Your Requirements

Analogy:

> When considering a design for a faucet, you may be tempted to design immediately around __temperature__ and __volume__. But what you really want to consider is __comfort__ and __pressure__. Once you solve _that_ abstraction, you can begin determining how best to translate that into temperature and volume.

### Track Your Assumptions

1. Write them down
2. Compare lists
3. Question them
4. Disrupt them (What in this list wasn't a constraint?)
5. Disprove them (Maybe that's not the right answer)

### Introduce Constructive Constraints

> Sometimes we need a little (creative) constraint, because the world is infinite.
> \- Danielle Applestone

Dropdowns are bad UI. Most of the time you shouldn't be using them. Try an exercise where a better solution to dropdowns are discovered.

### Pursue Bigger, Better Boxes

Designers don't think "out of the box". If they think in new ways, they've only just made their box bigger.

The bigger and weirder the box, the better it is. Diversify the thinking with other perspectives.

![Bigger, better boxes](https://s3.amazonaws.com/resources.sketch.cloud/private/277bb059-65a6-4507-89fa-1ff077eb2c86.png?AWSAccessKeyId=AKIAIS7X2P6WUKGTP2GA&Expires=1491065463&Signature=IxnTNBa0ERwhCSjn%2FapFtmYu49Q%3D)

### No Two Families Alike

> Who is missing from the future you're designing?
> \- Genevieve Bell

Have an inclusive vision and design for diversity.

### Work "Up Here" Instead of "Down Here"

Data is awesome, but that's a baby step. You need to refine it to get to answers, and refine it more to get to solutions. The higher from the bottom you go, the more value you retrieve.

- :raised_hands: __VALUE__
- :arrow_up: Solutions
- :arrow_up: Actions
- :arrow_up: Answers
- :arrow_up: Information
- :arrow_up: Data

### Architect for Use

Data is organized differently in our databases than it is presented to users. Consider how the users would use the information we're presenting and plan your UI somewhere along that axis.

### Typical Web Design

> I remain amazed and perplexed at how often people think they can solve an information architecture problem with interaction design
> \- Jesse James Garrett

There is no _"I'm [this kind of] learner."_ We're all visual. We're all auditory. It's a myth that certain people can only learn visually or auditorily.

### Draw the Map or Diagram

Use the Diagram to __guide__ a focused approach. Otherwise you may wind up with something like:

> Designer made awful UI [X], because manager tasked odd requirement [Y], because customer (or stakeholder) wanted [Z] not really understanding what they were asking nor the implications.

![xkcd](https://xkcd.com/657/large/)

### What Could Possibly Go Wrong?

![xkcd](https://imgs.xkcd.com/comics/exploits_of_a_mom.png)

How will your product react in different situations?

Example: [Gmail's mic drop April fool's fail](https://www.theguardian.com/technology/2016/apr/01/google-disables-april-fools-joke-gmail-mic-drop)

### Design Systems for Human Inaction

People are lazy. Get the behavior you want even if your users don't do the right thing, if they do it at all. If the success of your system depends on humans doing the right thing, your system __will__ fail, if not now, eventually.

Direct deposit is an example of a system doing the right thing without human action.

### Design the Right Thing

Find the right problem to solve.

Track your annoyances:

1. Keep a bug list
2. Keep a resignation list
  - What am I resigned to that I could find a solution for?

### Root Cause Analysis

Investigate with [Five Whys](https://en.wikipedia.org/wiki/5_Whys)

Example:

- __Problem__: There is a cup under the coffee grounds basket at the coffee machine.
- __Why?__: To catch the drips from the coffee grounds basket
- __Why?__: There are still grounds in the basket after a brew.
- __Why?__: Nobody emptied the grounds from the basket
- __Why?__: Because it's a hassle to empty without a mess
- __Why?__: I don't know how empty it without making a mess

When you hear a passive voice, ask _who_ is doing it.

- "These things just keep happening!"
- ["Mistakes were made"](https://en.wikipedia.org/wiki/Mistakes_were_made)

When there is a lack of ownership, there is probably a party who is responsible or at least involved.

### Analyze the Market Visually

![Visually analyze the market](https://s3.amazonaws.com/resources.sketch.cloud/private/2c4a3876-8002-4593-a8f0-fe096affde4f.l.png?AWSAccessKeyId=AKIAIS7X2P6WUKGTP2GA&Expires=1491068345&Signature=ZljSbSWSpuScd54e4T%2FESL8k0tM%3D)

## How We Apply It

