---
title: Why Compression is Fundamental
date: 2024-07-26 20:34 +0200
categories: [Thoughts, Universe]
tags: [agent, universe, compression, observer, philosophy]     # TAG names should always be lowercase

media_subpath: /assets/post_content/compression/

pin: false
math: true

image:
  path: compression.png
---

> Data compression is the process of encoding information using fewer bits than the original representation
{: .prompt-info }

With this article, I hope to offer some interesting perspectives on what perception is, what observing in general means, and why the process of compression is fundamental to self-sustaining systems, including us.
I will touch on some tangents, including fractals, Cybernetics, Stephen Wolfram's Observer Theory, and Karl Friston's Free Energy Principle.

## How I Think of Compression and Information

First of all, we clear up any confusion about information, as it is necessary to understand data compression.
In a computational paradigm, where everything is states and transition functions, **information can be defined as meaningful differences in changes of states**.
Of course, meaningful is a subjective term: information here is not an objective property but depends on the interpreter's ability to process the input.
Although quite intuitive, I dislike the wobbly nature of this definition. It does not allow for much reasoning and is not quantifiable.

A precise, quantifiable, and universal definition of information is given by the founder of Information Theory, [Claude Shannon](https://en.wikipedia.org/wiki/Claude_Shannon), utilizing probability theory.
He quantifies information by entropy $$ H $$. Entropy ($$ \approx $$ degree of unorderedness) is a term connected to the [Second Law of Thermodynamics](https://en.wikipedia.org/wiki/Second_law_of_thermodynamics).

Entropy is the logarithm of states in a system that are consistent with what is known about that system. So high entropy means that many different configurations are equally probable, making it hard or impossible to predict the real one.
Intuitively, think of **entropy** as being determined by the number of possible microscopic states that would give rise to the same macroscopic state we can observe (e.g., gas particles in a box).

Coming back to Shannon, we can define information in an event as the inverse proportion to the event's probability, represented by entropy $$ H $$:

$$ H(x) = p(x) \log_2{\frac{1}{p(x)}} $$

Where $$ p(x) $$ is the probability of an event $$ x $$ inferred by our current models, and $$ H(x) $$ is the information released when observing $$ x $$.
The more uncertain we are about the occurrence of that event, the more information is being transmitted when it is observed (**high degree of uncertainty $$ \rightarrow $$ high information content**).

For us humans, the degree of information in events is tied to its degree of surprisal, given our current understanding of the world (produced by our world model).
But hold up, I made a jump here; before proceeding, we should understand data compression and its role here.

To me, data is *arbitrarily inflated information*, transmittable on carrier material (e.g., bits, charges...).
The point is that data bears information mixed with arbitrary noise, which can be reduced to pure information with the process of compression.

A simple example are fractals, as explained in my first post [Fractal Worlds](https://lineick.github.io/posts/Fractal-Worlds/).
While infinitely intricate and complex, the patterns are reducible to a simple function. The process of finding a shorter representation (function + compressed data) of the observed pattern is what we call compression.
In the case of the Mandelbrot fractal, all we need to know to reproduce it is a simple recursive function (the series), and its initial value.

**Maximum compression** is the process of extracting all correlations and means of order until we only have entropic residue left, which is not further reducible.
We end up with a compression function and entropic residue (noise). In the process of decompression, we use the inverse of the found compression function and input its entropic residue, obtaining the original data as its output.

## Compression in Nature

Processing information asks for computational resources.
In nature, cells propagate evolutionary learnings through their genome, which stores important information about the organism in a compressed manner.
We also see fractal patterns everywhere in nature. We find them in the structure of trees or plants like [romanesco](https://en.wikipedia.org/wiki/Romanesco_broccoli), on shells, and more.
The reason? Stability, compressibility, easy to build with self-organizing systems, error-resistance, and more. If you are interested, I highly recommend watching this [video](https://www.youtube.com/watch?v=OMB1JLIdwNA) from NanoRooms on YouTube.

## Ok, But Why Is Compression Fundamental?

Short answer: On a low level, living organisms do nothing except compressing information about their environment. Sounds too simple? It's even more general...

It applies to all observers in the universe.

To survive in a changing environment, a being has to sustain itself (homeostasis) by anticipating future states, or in short, by predicting its environment.
A **system that controls future states is called an agent** (It acts on the future). To do this, it needs to build models of its environment to predict what happens next, and act based on its predictions aligned with a goal (usually homeostasis).

The process of predicting future states is limited by the computational capacity of the agent.
To make sense of incoming data, one needs to compress it, as the process of compression extracts information in the form of compression functions, resembling correlations and order in the data.
To self-sustain, a system needs to minimize the prediction error in its world model.
This principle is famously known as the [Free Energy Principle](https://arxiv.org/pdf/2201.06387) and entails many interesting ideas, also explaining how consciousness might work.

If the inflowing data is not compressible, it bears no information and does not allow for modeling.
The system simply cannot predict anything from entropic residue/noise/randomness. Observation, the process of compressing environmental data, and therefore also agency become impossible.
No self-sustaining structures, such as humans and all known life, can emerge (entropy is a one-way function).

Some (meta-)physical theories imply that the global information in the universe might be zero, such as suggested in symmetry paradigms including [Zero Ontology](https://www.hedweb.com/witherall/zero.htm).
Fortunately, this does not deny that predictable structure exists locally, as is obviously the case for our perceived universe, following clear laws of physics, predicting our environment in spacetime.

In the Wolfram Physics Project (metaphysical computational model for the Universe initiated by Stephen Wolfram), such local predictable structures are described as *pockets of reducibility* in a computationally irreducible structure.
This would be a paradox if the pockets were reducible in a lossless (exact) manner. When we talk about the compression observers do, we always assume imperfect, lossy compression, an estimation of the original.
I plan to elaborate on reducibility in computation in a future article. So let's proceed with the implications of the fact that all we do on a low level is *(lossy) compression*.

## The Implications

If all we do is compression through learning models of our environment (culminating in a world model), we as humans are future state predictors, shaped by evolution to sustain our species.
Evolution is probably not a fundamental, but an emergent rule, a phenomenon of scarcity. Structures are self-sustaining by harvesting negentropy (exploiting order) from their environment.
As order is a limited resource (only exists in pockets of reducibility), systems compete with each other, inhabiting and therefore blocking spacetime for other self-sustaining systems on their level of existence.

On earth, we currently dominate most levels of interest; our intelligence allowed us to build structure and harvest negentropy in regions where no other organism is able to compete.

It is a universal law that entropy is increasing over time. As previously mentioned, it is a unidirectional phenomenon in time. On a low level, we build structure for species-homeostasis by harvesting structure somewhere else;
it is a limited resource, decreasing over time.

On a side note, it seems that we currently fail in projecting ourselves far into the future, leading to us playing the short game, exploiting resources on our planet for short-term profit,
without aiming to maximize order over long time spans (e.g., thousands or millions of years).

Another implication touches again on the entropic residue compression produces.
When I listened to a podcast with Michael Levin, a computational biologist, he played with an interesting answer to the [Fermi Paradox](https://en.wikipedia.org/wiki/Fermi_paradox).
One reason why we have not detected any alien life yet might be that they are so far advanced and therefore so efficient in compression (e.g., in operating, communicating) that all they leave behind is highly entropic residue, which sounds like noise to us.

## Wild Ideas

The reasonable part of this post might end here for most people. The following is neither useful nor grounded in much evidence; see it as a thought experiment, a wild guess, fascinating to think about, although probably untrue.

So I leave you with a crazy idea: What if the whole universe is one big compression process?

### Everything as a Compression Process

It is true that entropy in the universe only increases, as it does in the input of an incremental compression function.
In this idea, matter is the input incrementally getting compressed, while the mental states are the compression function acting on the matter.

Over time, everything tends towards increasing entropy, with pockets of low entropy where observers like us can exist and predict our surroundings.
We exploit these regions by further compressing the environment, contributing to the universe's ultimate entropic residue.

This process can be seen as a global compression function, where our individual consciousnesses are isolated instances (multithreaded).
The mental acts as a compression/decompression function, while the physical world is its entropic residue.
Our universe's complexity and structure allow for gradual compression, with recursion and evolving functions creating time and experience, hinting at a functionalist and potentially panpsychist view of consciousness.

---

This post was quite abstract and text-heavy; I hope you still got the main idea.

Thanks for reading! :)

## Further Sources

I highly recommend:

- Watching Stephen Wolfram's [TED talk](https://www.youtube.com/watch?v=fLMZAHyrpyo) and reading into [Wolfram Physics](https://www.wolframphysics.org/technical-introduction/).
- Stephen Wolfram's post on [Observer Theory](https://writings.stephenwolfram.com/2023/12/observer-theory/)
- Michael Levin on the TOE podcast [Consciousness, Biology, Universal Mind, Emergence](https://www.youtube.com/watch?v=c8iFtaltX-s) (This is where he mentions the alien compression idea from earlier)
- Joscha Bach presentation [From Agents to Agency](https://www.youtube.com/watch?v=ocJcq_7MW1U)
- Karl Friston explaining the [Free Energy Principle (FEP)](https://www.youtube.com/watch?v=NIu_dJGyIQI)

Finally, I recommend a great book, comprising how consciousness may work, including biology, neuroscience, the FEP, and the here mentioned definition of information by Shannon: [The Hidden Spring](https://g.co/kgs/yVBm493) by Mark Solms.
