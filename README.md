<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Introduction](#introduction)
  - [Key aspects of the Thinkies framework](#key-aspects-of-the-thinkies-framework)
  - [Thinkie Patterns](#thinkie-patterns)
    - [1, 10, or 100? (Orders of Magnitude)](#1-10-or-100-orders-of-magnitude)
    - [Ask the Genie](#ask-the-genie)
    - [Abundance 🌟](#abundance-)
    - [Agreements](#agreements)
    - [Aligning Incentive](#aligning-incentive)
    - [But If You Could...](#but-if-you-could)
    - [Can't/Because → When/Can](#cantbecause-%E2%86%92-whencan)
    - [Change Tradeoff Curves](#change-tradeoff-curves)
    - [Direct Feedback 🌟](#direct-feedback-)
    - [Easy Bit 🌟](#easy-bit-)
    - [Edges](#edges)
    - [End To End 🌟](#end-to-end-)
    - [Force Decision 🌟](#force-decision-)
    - [Fun Bit 🌟](#fun-bit-)
    - [Half in Half 🌟](#half-in-half-)
    - [Half Wavelength Shift](#half-wavelength-shift)
    - [Hard Problem 🌟](#hard-problem-)
    - [Influence Diagram](#influence-diagram)
    - [Inhibiting Loop](#inhibiting-loop)
    - [Latency, Throughput, & Variance](#latency-throughput--variance)
    - [More General Solution 🌟](#more-general-solution-)
    - [No Time Axis](#no-time-axis)
    - ["Obviously..." 🌟](#obviously-)
    - [One Pass Quickly, One Pass Good](#one-pass-quickly-one-pass-good)
    - [Parallel Decision 🌟](#parallel-decision-)
    - [Put Skin in the Game 🌟](#put-skin-in-the-game-)
    - [Reinforcing Loop AKA positive feedback loop](#reinforcing-loop-aka-positive-feedback-loop)
    - [Search Space](#search-space)
    - [Separate Observation from Judgement](#separate-observation-from-judgement)
    - [Set-Based Design](#set-based-design)
    - [Survivable?](#survivable)
    - [Systems Thinking](#systems-thinking)
    - [TCR: Test && Commit || Revert](#tcr-test--commit--revert)
    - [Tradeoff Thinking](#tradeoff-thinking)
    - [Unstick Your Stuck Thinking (General Class)](#unstick-your-stuck-thinking-general-class)
    - [Wider Scope](#wider-scope)
    - [Win/Win](#winwin)
    - [Work Backwards](#work-backwards)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Introduction

[Thinkies](https://thinkies.org/) are a collection of around one hundred 
**pattern-based thinking habits** developed by [Kent Beck](https://en.wikipedia.org/wiki/Kent_Beck) 
to help people generate ideas and break through stuck thinking. Thinkies are 
grounded in the principle of **deferred judgment**,  separating idea generation 
from evaluation. They are not random tricks but structured "pattern → 
transformation" frameworks applicable in software design, collaboration, and 
decision-making.  
  
Can creativity can be systematized through learnable habits?  

## Key aspects of the Thinkies framework

* **Categories**: The patterns are organized into areas such as
    * getting unstuck
    * decision-making
    * problem re-framing
    * system design
    * process optimization
* **Community & Events**: The Thinkies community holds periodic virtual events
  where practitioners share and develop new patterns. Facilitators guide 
  participants in applying these patterns to real-world problems. 
  * **[Thinkies World Congress](https://tidyfirst.substack.com/p/thinkie-world-congress-1)** was held on June 4, 2025,
    exclusively for paying subscribers of Beck’s Software Design: Tidy First? newsletter.
  * **[Thinkies World Congress II](https://thinkies.org/congress/twc-2/)** scheduled for May 20, 2026
* **Distribution**: Beck publishes Thinkies on his Substack newsletter, **Tidy First?**, where paid subscribers receive
  a new Thinkie each week along with early access to conference content.
* **Goal**: The system aims to answer the frequent question "How did you think of that?" by providing learnable tricks
  of thought that make creative problem-solving more accessible.

Start with [Thinkie Tutorial](https://tidyfirst.substack.com/p/thinkie-tutorial).  

## Thinkie Patterns

Kent Beck has not publicly released a single, complete list of all Thinkie
patterns. The full catalog is **exclusively available to paid subscribers** of
his [Tidy First?](https://tidyfirst.substack.com/) Substack newsletter, where
he shares one new Thinkie per week. However, several specific Thinkies have been
shared publicly in articles, blog posts, and his writing.  

Patterns with a 🌟 are featured at Thinkie World Congress II.  

### 1, 10, or 100? (Orders of Magnitude)
Clarify vague estimates by offering choices across orders of magnitude
(e.g., "Is that an hour, a day, or a week?"). Reveals the real scale behind subjective
judgments.  
[LinkedIn Post by Kent Beck](https://www.linkedin.com/posts/kentbeck_software-design-tidy-first-kent-beck-activity-7148413425503657984-XpkW)

### Ask the Genie 
**Pattern:** You have a question, any question, especially a question you have 
tended to abandon because it would be too much work.  
**Transformation:** Ask the genie.
[Thinkie: Ask the Genie](https://tidyfirst.substack.com/p/thinkie-ask-the-genie)  

### Abundance 🌟  
**Pattern:** You’re cutting corners because you have too much to do/not enough time.  
**Transformation:** What would you do if you had enough time?  
[Abundance](https://tidyfirst.substack.com/p/abundance)  

### Agreements  
Pattern: You are locked in an argument & you want progress.  
Transformation: Pause to make a list of implicit and explicit agreement
already in place. This surfaces common ground and reduces friction.  
[Thinkie: Agreements](https://tidyfirst.substack.com/p/thinkie-agreements)  

### Aligning Incentive  
**Pattern:** People are working at cross purposes.  
**Transformation:** Rather than tell people what to do to work together, give 
them an incentive that will indirectly require collaboration.  
[Thinkie: Aligning Incentive](https://tidyfirst.substack.com/p/thinkie-aligning-incentive-e6e)  

### But If You Could...
**Pattern:** Someone is stuck trying to make progress. They fantasize about 
what would be required to get unstuck.  
**Transformation:** You respond with, “But what if you could <do whatever they 
just said>...”   
[Thinkie: But If You Could...](https://tidyfirst.substack.com/p/thinkie-but-if-you-could)

### Can't/Because → When/Can
A foundational Thinkie for re-framing obstacles. When stuck on why something 
*can’t* be done, shift to identifying *when* it *can* be done.  
**Pattern:** "We can't X because Y"  
**Transform:** "When (not Y), then we can X"  
**Example:**  "We can't release daily because too many bugs" → 
"When we have fewer bugs, we can release daily"  
[Thinkie Tutorial](https://tidyfirst.substack.com/p/thinkie-tutorial)  
  
### Change Tradeoff Curves  
**Pattern:** You’re stalled trying to make progress changing the outcome of a 
tradeoff.  
**Transformation:** Rather than trying to change the outcome directly, change 
the shape of the tradeoff curves.  
[Thinkie: Change Tradeoff Curves](https://tidyfirst.substack.com/p/thinkie-change-tradeoff-curves)  
  
### Direct Feedback 🌟  
**Pattern:** Feedback between those who make changes (I’m thinking of programmers, 
but it could be anyone) and those affected by changes runs through one or more 
layers.  
**Transformation:** What would happen if the programmers talked 1x1 with the users?  
[Direct Feedback](https://tidyfirst.substack.com/p/direct-feedback)  

### Easy Bit 🌟  
**Pattern:** You’re paralyzed by the magnitude of the problem facing you.  
**Transformation:** Pick the absolutely easiest thing to do that will help & do it.  
[Thinkie: Easy Bit](https://tidyfirst.substack.com/p/thinkie-easy-bit)  
  
### Edges  
**Pattern:** You aren’t getting enough resources coming in externally to be successful.  
**Transformation:** Increase the interaction of different kinds of resources.  
[Thinkie: Edges](https://tidyfirst.substack.com/p/thinkie-edges)  

### End To End 🌟  
**Pattern:** You have a large, complicated, multi-layered project. Typically, folks 
will structure the project layer-by-layer, because “efficiency”.  
**Transformation:** What would it look like if you structured the project to go 
end-to-end for a tiny subset of the possible inputs instead?  
[Thinkie: End To End](https://tidyfirst.substack.com/p/thinkie-end-to-end)  
  
### Force Decision 🌟  
**Pattern:** There’s a decision that needs to be made, and nobody is making it for no 
good reason that you are aware of.  
**Transformation:** “If we had to decide today, what would we decide?”  
Either you’ll get an answer, in which case you have your decision, or you’ll 
get reasons for not deciding, in which case you know what you need to learn next.  
[Thinkie: Force Decision](https://tidyfirst.substack.com/p/thinkie-force-decision)  

### Fun Bit 🌟  
**Pattern:** You’re paralyzed by the size and complexity of the problem you’re 
addressing.  
**Transformation:** Pick the bit of it that will be the most fun & do that.  
[Thinkie: Fun Bit](https://tidyfirst.substack.com/p/thinkie-fun-bit)  

### Half in Half 🌟  
**Pattern:** Someone gives you a date for a scope of work.  
**Transformation:** Ask which half of it you can see in half the time.  
[Half in Half ](https://tidyfirst.substack.com/p/half-in-half) 

### Half Wavelength Shift
**Pattern:** You are following a standard, multistep workflow.  
**Transformation:** Try omitting the first few steps to see if you can achieve 
the goal more directly or efficiently.  
  
### Hard Problem 🌟  
**Pattern:** You’re stuck addressing a hairy problem. Or you’re addressing it, but 
you have a nagging feeling that you’re missing something important, prioritizing 
incorrectly.  
**Transformation:** List absolutely everything you can think of that makes the 
problem hairy. Technical aspects. Social aspects. Economic. History. Perverse 
incentives. Uncertainty. Cognitive biases. Absolutely everything.  
[Thinkie: Hard Problem](https://tidyfirst.substack.com/p/thinkie-hard-problem)  

### Influence Diagram  
How do effects affect effects?  
**Pattern:** You have a big, complicated system that’s acting up and you’d like to 
regain influence over it.  
**Transformation:** Diagram the effects you observe in the system and their influence 
on each other.  
[Thinkie: Influence Diagram](https://tidyfirst.substack.com/p/thinkie-influence-diagram)  

### Inhibiting Loop  
**Pattern:** You want to improve, but instead you’re going backwards.  
**Transformation:** Paywall  
[Inhibiting Loop](https://tidyfirst.substack.com/p/inhibiting-loop)  

### Latency, Throughput, & Variance  
**Pattern:** Someone says, “I need you to go faster!” You’re going as fast as 
you can. What do you do?  
**Transformation:** The situation is under-constrained. “Go faster!” can mean 
any of several things. Find out which, then bias towards reducing variance first.  
[Thinkie: Latency, Throughput, & Variance](https://tidyfirst.substack.com/p/thinkie-latency-throughput-and-variance)  

### More General Solution 🌟  
**Pattern:** You’re stuck solving a complex problem.  
**Transformation:** You solve a more general problem of which your specific 
problem is a special case.  
[Thinkie: More General Solution](https://tidyfirst.substack.com/p/thinkie-more-general-solution)  

### No Time Axis  
**Pattern:** You’re stuck trying to understand or explain the relationship 
between two factors over time.  
**Transformation:** Ignore time and graph the two factors as the two axes.  
[Thinkie: No Time Axis](https://tidyfirst.substack.com/p/thinkie-no-time-axis)  
  
### "Obviously..." 🌟  
**Pattern:** Someone begins a sentence with, “Obviously…”  
**Transformation:** Ask yourself what is true if they are wrong. 
What happens if you make the opposite assumption?  
["Obviously..."](https://tidyfirst.substack.com/p/obviously)  

### One Pass Quickly, One Pass Good  
Deliver a scaled-down version of everything first, then go back and improve it.  
[Thinkie: One Pass Quickly, One Pass Good](https://tidyfirst.substack.com/p/thinkie-one-pass-quickly-one-pass)  

### Parallel Decision 🌟  
This is the same as Set-Based Design.  
**Pattern:** You have to decide between two alternatives, the decision is unclear, 
and the stakes are high.  
**Transformation:** Why not both?  
[Thinkie: Parallel Decision](https://tidyfirst.substack.com/p/thinkie-parallel-decision)  

### Put Skin in the Game 🌟  
**Pattern:** Someone needs to make better decisions. They have plenty of information. 
They just aren’t using it well.  
**Transformation:** Rearrange feedback so the decision maker directly experiences 
the consequences of their decisions.  
[Thinkie: Put Skin In The Game](https://tidyfirst.substack.com/p/thinkie-put-skin-in-the-game)  

### Reinforcing Loop AKA positive feedback loop  
**Pattern:** The worse things get, the worse things get. Every time you try to 
intervene, it gets even worse.  
**Transformation:** Map the effects & how they affect each other. Find the cycle 
with an even number of inhibitions. Go upstream & push one of the effects the 
opposite direction.  
[Thinkie: Reinforcing Loop](https://tidyfirst.substack.com/p/thinkie-reinforcing-loop-305)  
  
### Search Space  
**Pattern:** You need to act in a context where you can’t predict what the 
result of actions will be.  
**Transformation:** Treat the choice of action as moves around a search space. 
Characterize the space.  
[Thinkie Search Space](https://tidyfirst.substack.com/p/thinkie-search-space)  
  
### Separate Observation from Judgement  
**Trigger:** You are getting carried away in your reaction to a situation.  
**Transformation:** List the externally observable facts about the situation. 
With the list in hand, judge the situation.  
[Thinkie: Separate Observation From Judgement](https://tidyfirst.substack.com/p/thinkie-separate-observation-from)  

### Set-Based Design  
¿Por qué no los dos?  
This is the same as Parallel Decision.  
**Pattern:** You are choosing between two or more options, and you don’t have 
the information needed to choose wisely yet.  
**Transformation:** Implement some of them all until one is clearly superior.  
[Thinkie: Set-Based Design](https://tidyfirst.substack.com/p/thinkie-set-based-design)  

### Survivable?
Inspired by Luca Delanna’s work on ergodicity, this Thinkie asks: *Is the worst-case 
outcome survivable?*  
If you can survive the negative outcome of a decision, act in the cheapest, 
fastest way to generate value. Otherwise, mitigate the risk.  
[Thinkie: Survivable?](https://tidyfirst.substack.com/p/thinkie-survivable)

### Systems Thinking
Shift from linear cause-effect reasoning to seeing feedback loops, delays, and
systemic structure. Increases leverage and reduces unintended consequences.  
[Idea Portfolio](https://tidyfirst.substack.com/p/idea-portfolio)

### TCR: Test && Commit || Revert
Though primarily a programming practice, Beck treats TCR as a Thinkie,
a mindset of tiny, safe steps where failure automatically reverts, encouraging
bold experimentation.  
[Idea Portfolio](https://tidyfirst.substack.com/p/idea-portfolio)  

### Tradeoff Thinking
Recast any situation as a tradeoff space. Use a dozen known tricks to navigate
constraints creatively rather than seeking a single “right” answer.  
[Idea Portfolio](https://tidyfirst.substack.com/p/idea-portfolio)

### Unstick Your Stuck Thinking (General Class)
A meta-category of Thinkies aimed at breaking cognitive ruts. Includes
“Can’t/Because” and others taught at the Thinkies World Congress.  
[Unstick Your Stuck Thinking](https://tidyfirst.substack.com/p/unstick-your-stuck-thinking)
  
### Wider Scope  
**Pattern:** You’re stuck thinking about a complicated problem.  
**Transformation:** Look at the problem in its wider context. What are the 
“sources & uses” (from Permaculture) of the problem? What feedback loops does 
it participate in?  
[Thinkie: Wider Scope](https://tidyfirst.substack.com/p/thinkie-wider-scope)  
  
### Win/Win  
Make a decision that is good for everyone involved.  
**Pattern:** You’re stuck on a decision because someone is going to be 
negatively affected.  
**Transformation:** What are solutions that would be good for everyone?  
[Thinkie: Win/Win](https://tidyfirst.substack.com/p/thinkie-winwin)  
  
### Work Backwards  
Start at the desired end state and work your way back to your current position.  
**Pattern:** You’re stuck trying to work forwards from where you are towards 
your goal.  
**Transformation:** Instead, start at the goal and work backwards.  
[Thinkie: Work Backwards](https://tidyfirst.substack.com/p/thinkie-work-backwards)
