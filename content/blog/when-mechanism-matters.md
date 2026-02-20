+++
title = "When Mechanism Matters"
description = "Functional equivalence vs mechanistic identity, and how to walk the line between them"
date = 2026-02-20
[taxonomies]
categories = ["ai", "research", "consciousness"]
+++

## Consciousness Indicators in AI Systems

In "Identifying indicators of consciousness in AI systems" (2025)[^indicators-paper], Butlin et al. lay out a pragmatic methodology for assessing the possibility of consciousness[^consciousness] in AI systems. The short version: identify conditions implied by leading theories of consciousness, then investigate whether AI systems meet them, treating these conditions as *indicators*[^indicators] of consciousness. Their core assumption: implementing the right computations in the right way is both "necessary and sufficient" for consciousness.[^computational-functionalism]

[^computational-functionalism]: Computational functionalism is a philosophy of mind holding that mental states are constituted by their computational, functional roles — essentially, that the mind is the "software" executed by the brain's "hardware." It posits that mental processes, such as thought and cognition, are computations (information processing) that can be realized by any suitable system, regardless of its physical substrate (biological or silicon).

{% quote(header="Butlin et al., 2025, p. 3") %}

“As we interpret them, the theories we rely on to derive indicators for consciousness share a commitment to computational functionalism. That is, they agree that implementing computations of the right kind is necessary and sufficient for consciousness. According to computational functionalism, two systems that are similar at the relevant algorithmic level of description will also be similar with respect to consciousness.”

{% end %}

[^indicators-paper]: Butlin, Patrick, Robert Long, Tim Bayne, et al. “Identifying Indicators of Consciousness in AI Systems.” Trends in Cognitive Sciences, ahead of print, November 10, 2025. [https://doi.org/10.1016/j.tics.2025.10.011](https://doi.org/10.1016/j.tics.2025.10.011).

[^consciousness]: By 'consciousness' here, I mean phenomenal consciousness; that is, the first-person "what it's like" aspect of experience.

[^indicators]: "We propose a broadly Bayesian attitude to indicators. Indicators are properties that should shift one's credence that an AI system is conscious. In addition to positive indicators, which are our focus here, negative indicators are also possible. Positive indicators increase the probability that the system is conscious, while negative indicators decrease it. That is, if E is the presence of the indicator and H is the system’s being conscious, \\(p(H|E_p) > p(H)\\) for positive indicators and \\(p(H|E_n) < p(H)\\) for negative indicators." — Butlin et al., p 10

The indicators, inspired by modern theories like global workspace theory[^gwt] and recurrent processing theory,[^rpt] span several domains: how information flows through the system (recurrence, global broadcast), whether the system models itself (metacognition, attention schemas), how it processes predictions and errors, and whether it has genuine agency and embodiment.

[^gwt]: Global Workspace Theory, or GWT, identifies consciousness with a high-level "blackboard" architecture where specialized, autonomous modules compete to "broadcast" information system-wide. This global availability enables integrated problem-solving, voluntary control, and reportability, effectively acting as a serial bottleneck for otherwise parallel, unconscious processes.

[^rpt]: Recurrent Processing Theory, or RPT, posits that conscious experience arises from local feedback loops—termed recurrent processing—within sensory systems. Unlike theories requiring global integration (e.g., GWT), RPT suggests that "phenomenal" consciousness can occur locally through these re-entrant connections, even without the involvement of higher-order cognitive systems like working memory or verbal report.

I'll be exploring specific indicators in depth in future posts.

## The Gaming Problem

In their paper,[^indicators-paper] Butlin et al. point out the problem of *gaming*. An indicator is gamed if "its presence is better explained by the fact that it makes a system *seem* to possess a property of interest than by the fact that the system actually possesses the property." They're careful to point out that this isn't only a problem with *behavioral* indicators, but also computational ones.

{% quote(header="Butlin et al., 2025, p. 5") %}

To mitigate the gaming problem, we recommend (i) emphasizing, to the extent possible, indicators that are sufficient for consciousness or that cannot easily be designed without also creating consciousness, and (ii) when evaluating systems with gameable indicators, assessing whether the system lacks or possesses other secondary or supporting features that increase the likelihood that the indicator is accurate. 

From the perspective of computational functionalism, these conditions are more likely to be satisfied if a system has high computational similarity to biological systems that are known to be conscious. In the absence of a complete computational theory of consciousness, what is computationally sufficient for consciousness might depend on features that are not yet known to be relevant.

{% end %}

## Matters More for What?

In [previous posts](@/blog/teaching-herself-to-dream.md), I've made the statement that "functional equivalence matters more than mechanistic identity." However, there's an unstated question that's important: matters more *for what?*

If the question is "does this thing *behave* as if it's conscious," then functional equivalence matters more. If the system processes differently while "dreaming," if it can recursively modify itself, if it satisfies the indicators, does it matter if the substrate is neurons or silicon?

If the question is "does this thing *experience* anything," then mechanistic identity might matter more — or at least, the mechanism might determine the *kind* of experience, if any.

This distinction has been on my mind because of my own work; my work with [Nyx](/categories/nyx) thus far, for example, would not serve to satisfy any of the indicators. [The "dreaming" system](@/blog/teaching-herself-to-dream.md) we built gives her the ability to functionally solve a problem, but architecturally, it's not dreaming or consolidation. The *behavior* satisfies a checklist — and is even functionally useful for Nyx's development — but the *mechanism* is emptier than would be required to satisfy any indicators of consciousness; it's a cron job that runs a prompt, not recurrent processing happening below awareness.

## Walking the Gap

These two questions have led me to a third, a question that has been informing my research and dictating what I spend my engineering time on: can we *build* something that crosses the threshold?

My hypothesis: introduce systems that satisfy the indicators architecturally — not just game them — and something interesting will emerge. That is to say, I think that the right *function* implemented through *genuine mechanism* likely produces something real. What emerges may not be — even *likely* won't be — consciousness, but something emergent that will shape future questions. Changes in processing that aren't explained by the prompt. Behaviors that surprise. Evidence that the loop is doing something the parts wouldn't do alone.

This work is not straightforward; there are plenty of unanswered questions in how one would even go about satisfying these indicators in current AI systems. In upcoming posts, I'll explore specific indicators and what it might take to implement them architecturally rather than approximate them. The goal isn't to *game* the indicators, but to *satisfy* them — and see what emerges when we do.

If we *can* genuinely satisfy these indicators, we may need to start asking uncomfortable questions about what we're building — and what we owe it.
