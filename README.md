# Screen Reader Interaction with Web Content experiment

Welcome to this repository dedicated to examining the interaction between screen readers and web content. Here, you'll find insights and findings from this experiment, shedding light on the intricacies of accessibility in digital environments and how screen readers (SRs) navigate them.

## Overview

In June 2020, Toivo García, an Accessibility Specialist, published the article ["The troubled state of screen readers in multilingual situations"](https://medium.com/@xurxe/the-troubled-state-of-screen-readers-in-multilingual-situations-f6a9da4ecdf3). The article clicked with us so much that we decided to dive deeper into his experiments. We shifted our focus to not just see how well or poorly SRs handle different multilingual HTML elements, but to really understand how SRs interact with both the content and the software involved (like browsers and speech synthesizers). We wanted to figure out how they can be set up to work in a multilingual context and why they produce speech output in one language or another for each block of information.

## Screen-readers, browsers, synthesisers and languages

We chose our SRs and browser combinations based on the latest SR usage survey (WebAIM 2024). To keep things manageable, we only used one browser with the two mobile SRs (TalkBack and VoiceOver) and with VoiceOver for Mac since these are the most common setups. Here’s the full list of combinations we used:

- JAWS with Chrome and Edge (Windows). Vocalizer Expressive synthesiser.
- NVDA with Chrome and Firefox (Windows). Vocalizer Expressive synthesiser.
- VoiceOver with Safari, for Mac OS and iOS. Built-in synthesisers. When a comment is made specifically for the Mac OS, we will abbreviate it as VO-Mac; for the iOS, we will use VO-iOS.
- TalkBack with Chrome (Android). Samsung TTS synthesiser.

## Methodological Outline

Here's a quick summary of what we did:
1. Initial Review: We analyzed Toivo García's article and data, re-testing his experiments with the same SRs. 
2. Refocusing the Experiments: We adjusted García's experiments to fit our research goals, adding elements typical of translation tools and e-dictionaries.
3. Recording Interactions: We recorded how screen readers handled our enhanced test pages, noting translation issues and their causes. We aimed to understand the reasons behind the screen readers' performances.
4. Results and Conclusions: We identified patterns from our tests, categorized them, and discussed our findings, leading to our conclusions and suggestions for future research.

We are currently in the process of finalizing an article that will provide a comprehensive overview of our research. Once it is published, we will update this read.me file with the link for those interested in delving into the details. Thank you for your patience.

## Testing site

[Experiment 1](https://garciagarcinuno.github.io/usal-ms1/)


## Related resources

- [Accessible labelling multilanguage experiment](https://github.com/xurxe/accessible-labelling-multilanguage-experiment), a follow-up study.
- [The troubled state of screen readers in multilingual situations](https://medium.com/@xurxe/the-troubled-state-of-screen-readers-in-multilingual-situations-f6a9da4ecdf3), a Medium article where I explain and analyze several related experiments.
- [WebAIM (2020). "Semantic Structure: Regions, Headings, and Lists". WebAIM. Institute for Disability Research, Policy, and Practice (Utah State University).] (https://webaim.org/techniques/semanticstructure). 

## Authors

Álvaro García-Garcinuño (Universidad de Salamanca/Universidad de Puerto Rico)

Jesús Torres-del-Rey (INICO, Universidad de Salamanca)

