### Théo Boyer

25yo deep learning engineer cooking the anti-entropy machine.

# Open source contributions
I believe that open source is extremely important in AI and more generally in software.

## [openai/whisper](https://github.com/openai/whisper)
* 🟩 [Resolve Inference Selection Bug Affecting Transcription Quality](https://github.com/openai/whisper/pull/1377): When different temperatures are considered, the current code is returning the sample computed with the highest temperature. I suggested changing this behavior to return the sample that has the best logprob. Even tho this PR wasn't merged in the official repo, the idea has been adopted and improved since in the [faster-whisper](https://github.com/SYSTRAN/faster-whisper) repository with [this PR](https://github.com/SYSTRAN/faster-whisper/pull/356)
* 🟪 [Avoid computing higher temperatures on no_speech segments](https://github.com/openai/whisper/pull/1279): In Whisper, the voice activity detection token is computed before decoding the actual transcribed sentence. I realized that in the code, the sentence was computed multiple times with different temperatures unnecessarily in the case where the segment was silent.

# Thoughts
* [The human bias spectrum](https://www.linkedin.com/posts/th%C3%A9o-boyer_the-human-bias-spectrum-today-we-can-safely-activity-7140387311304740864-xiBW/)
* [L’humanité a signé son arrêt de mort](https://www.linkedin.com/posts/th%C3%A9o-boyer_groundbreaking-new-book-makes-ai-author-a-activity-7135309335697514498-4sMi/)
* [Il faut arrêter de parler de "l'Intelligence Artificielle"](https://www.linkedin.com/posts/th%C3%A9o-boyer_ia-intelligenceartificielle-deeplearning-activity-7115316457093124096-Lzp9/)
* [Le data drift, ou L'arbre qui cache la forêt](https://www.linkedin.com/posts/th%C3%A9o-boyer_99-of-data-scientists-get-this-dataset-wrong-activity-7110246849625632769-DIft/)

# Get in touch !
* Connect on [X](https://twitter.com/ted_engineer)
* Connect in [Linkedin](https://www.linkedin.com/in/th%C3%A9o-boyer/)
