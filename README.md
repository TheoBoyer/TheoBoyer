### Théo Boyer

Deep learning engineer cooking the anti-entropy machine.

# Startups
* Dec 2024 – Jul 2026 · Duon Labs, co-founder & CTO: probabilistic forecasting for financial markets. I built the ML side end to end, from data collection to a generative model pretrained from scratch and served in production.
* Jul 2023 – Nov 2024 · Expect Pulse, co-founder & Director of Science and Technology: Pulsar, a foundation model for zero-shot time-series forecasting with uncertainty quantification.

# Personal Projects
* Jul 2026 · [brokefish](https://github.com/TheoBoyer/brokefish): a chess engine that learns only from self-play, trained on a single laptop GPU.
* Feb 2022 · [Manual bounding box annotation app](https://github.com/TheoBoyer/Manual-bbox-annotation-tool), built during the Kaggle Happywhale competition.
* May 2021 · [TMForge](https://github.com/TheoBoyer/TMForge): an open source tool for reinforcement learning on Trackmania 2020.
* Dec 2018 · [gan-from-scratch](https://github.com/TheoBoyer/gan-from-scratch): a GAN on MNIST written with the low-level features of tfjs.

# Open source contributions

## [openai/whisper](https://github.com/openai/whisper)
* 🟩 May 2023 · [Resolve Inference Selection Bug Affecting Transcription Quality](https://github.com/openai/whisper/pull/1377): When different temperatures are considered, the current code is returning the sample computed with the highest temperature. I suggested changing this behavior to return the sample that has the best logprob. Even tho this PR wasn't merged in the official repo, the idea has been adopted and improved since in the [faster-whisper](https://github.com/SYSTRAN/faster-whisper) repository with [this PR](https://github.com/SYSTRAN/faster-whisper/pull/356)
* 🟪 Apr 2023 · [Avoid computing higher temperatures on no_speech segments](https://github.com/openai/whisper/pull/1279): In Whisper, the voice activity detection token is computed before decoding the actual transcribed sentence. I realized that in the code, the sentence was computed multiple times with different temperatures unnecessarily in the case where the segment was silent.

# Get in touch !
* Connect on [X](https://twitter.com/ted_engineer)
* Connect in [Linkedin](https://www.linkedin.com/in/th%C3%A9o-boyer/)
