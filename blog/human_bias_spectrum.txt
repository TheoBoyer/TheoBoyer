The human-bias spectrum

Today we can safely say that learning algorithms are somewhat solved, they are not perfect but could be enough to envision an AGI in the following years.
Then the obvious question is  “What sort of data would lead a learning algorithm to AGI ?”
I identified a spectrum on which every approach can be placed that I call the “Human-bias spectrum”.

There is a fundamental tradeoff in this race to intelligence.
On each end of the spectrum are two radical approaches that rely on different assumptions.

Sitting at the right end is the language stack. This is the part of the spectrum that is the closest to human intelligence. It relies on the assumption that human intelligence is somewhat unique and that one should leverage humanity’s legacy to solve intelligence. The base building block of this stack is language. This is the path most of today’s AI community is on with OpenAI leading the pack. The main bet that they are doing is that language is to intelligence what Turing machines are to computation. While a machine must be Turing-complete to be able to perform computation, language would need to be Intelligence-complete to be sufficient to achieve AGI.
Language stack is simply the quickest path to AGI provided that this assumption is true. Furthermore, language data is currently very easy to gather at scale.

Now let me introduce to you the underdog sitting at the left end of the spectrum: the information stack. On this end, one considers that human intelligence is biased, and therefore, a learning algorithm should rely on the rawest signal possible. Why limit the system’s photon perception to a human’s visual spectrum when it could see any wavelength ? Why bother with language to find a fundamental model of physics ? This side of the spectrum assumes that anything useful in human intelligence would emerge regardless from a pure interpretation of signals coming from the real world without the filter of any human bias.

For my two cents of where to be on this spectrum, I will take the example of AlphaGO.

The first superhuman version of AlphaGO was made in two stages:
The first stage was pre-training on GO grandmaster games. Only in the second stage would the algorithm play against itself to improve via Reinforcement learning.
This was the quickest path to superhuman GO machines because master games contained knowledge of thousands of years of human theory of GO, and therefore it was a shortcut to start near the human level. As you might guess, this approach is sitting on the far right of the spectrum.

But one year later, Deepmind introduced AlphaZero. AlphaZero was trained from scratch without any human knowledge just via self-play, and ultimately obliterated AlphaGO. As you might guess, AlphaZero is on the far left of the spectrum.

Therefore my two cents is that the language stack will win in the short to mid-term whereas the information stack might win in the long run.

[](https://github.com/TheoBoyer/TheoBoyer/blob/main/assets/human_bias_spectrum.png?raw=true)
