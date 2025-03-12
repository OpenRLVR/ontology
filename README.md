# Ontology
This was originally proposed by [@georgejrjrjr](https://x.com/georgejrjrjr) on a google doc [Ontology for verfiable rewards](https://docs.google.com/document/d/1X-xOT6fR7XV0r7B7JF3hgmosAK0dFpOddv3k3-0Pm1o/edit?usp=sharing) with other contributors. 

The purpose of this document is turn the google doc into a PRedable markdown file. For original author feel free to let me know to add your credits

## Verifiable Rewards

Strengths: the results are verifiably, quantitatively correct.
Weakness: many qualities and domains are not obviously amenable to verifiable correctness.

### General Tooling
* [Verifier](https://github.com/willccbb/verifiers)

### Math
* Arithmetic (GMS8K-like)
* Competition math (AIME-like)
* “Real math” (Lean et al)
* Figures of merit: correctness, token usage (is proof concision a concern?).

### Code
* Interview questions (LeetCode)
* Realistic software engineering (CommitPack, SWE-Bench, SWE-Lancer)

### Transpilation
* High performance compilation (eg, [KernelBench](https://scalingintelligence.stanford.edu/blogs/kernelbench/))
* Code reasoning ([CruxEval](https://crux-eval.github.io/), [CodeIO](https://github.com/hkust-nlp/CodeIO))
* Figures of merit: test pass rate, execution time, lines of code, token usage.

### Vision
* [RLVR in Vision Task](https://deepagent.notion.site/rlvr-in-vlms)

### Verifiable Instruction following 
* Format compliance
  * Language
  * Schemas
  * Tool use
  * Diffs
* String processing (e.g., AutoIF)
  * Compression / Decompression
  * Presence or absence of words, suffixes, stems, etc.
  * Palindromes
  * Text encodings (e.g., Base64)
  * Ciphers
  * Length of response
  * Parts of speech
  * Reading level
  * Corruption repair
* Poetry
  * Rhyme
  * Meter

### Gymnasia
* Terminal games (e.g., nethack)
* [Pokemon RL](https://drubinstein.github.io/pokerl/)
* Console / arcade emulators (e.g., MAME)
* Board games (e.g., chess)
* Minecraft
* Puzzles (e.g., Rubik’s Cubes, Mazes)
* Cybersecurity
  * Red team exercises (capture the flag: VulnHub, HITB, etc)
  * Blue team exercises (log monitoring, intrusion detection, vulnerability detection)
  * Malware analysis

## Neural rewards
Strengths: works to some degree on ~any quality expressible in words
Weaknesses: reward hacking, eg, with listicles and length.

### Methods
#### LLM-as-Judge
* Single judge
* Panel of judges
* Adversarial adjudication
#### Reward models
* Human conditioned (RLHF)
* Constitutionally conditioned (RLAIF)
* Execution Feedback conditioned ([RLEF](https://arxiv.org/pdf/2410.02089))
#### Generative RMs
* [CoT-GenRM](https://www.synthlabs.ai/research/generative-reward-models)

### Factual (Grounded) Judgements
* Document / Search Grounded QA
* Forecasting
* Exam-style grading
* Prompt Adherence
* [Output distribution mirroring](https://arxiv.org/abs/2502.01697)
* Narrative adherence
  * Settings
  * Characters
  * Continuity

### Qualitative (Ungrounded) Judgements
* [Prompt quality](https://arxiv.org/abs/2501.18578)
* [Emotional intelligence](https://eqbench.com/)
* [Creative writing quality](https://eqbench.com/creative_writing.html)
* [Creative writing judge quality](https://eqbench.com/judgemark-v2.html)
* [Humor](https://eqbench.com/buzzbench.html)
* [Image quality](https://arxiv.org/abs/2501.18096)
  * SVG generation
  * Text-to-image prompting 
* Legality
* Audience Appropriateness
  * Age
  * Intelligence
  * Knowledge / Background
  * Background knowledge
  * Culture
* Persona adherence
  * Honesty/Humility
  * Emotional Stability
  * eXtroversion
  * Agreeableness
  * Conscientiousness
  * Openness
  * Compassion / Empathy

## Reasoning Repositories
### Reasoning Data
[General Reasoning](http://gr.inc)
[Open Thought](https://github.com/open-thoughts/open-thoughts)
[SYNTHETIC-1](https://huggingface.co/datasets/PrimeIntellect/SYNTHETIC-1)
### Gymnasia
[Reasoning Gym](https://github.com/open-thought/reasoning-gym/)
[DOOM-Mistral](https://github.com/umuthopeyildirim/DOOM-Mistral)
### Leaderboards
#### Model Reasoning
* [General Reasoning Leaderboard](https://gr.inc/leaderboard/)
* [AutoRACE Leaderboard](https://www.llm-reasoners.net/leaderboard)
* [KernelBench](https://scalingintelligence.stanford.edu/KernelBenchLeaderboard/)
#### Evaluator 
* [Reward Bench](https://huggingface.co/spaces/allenai/reward-bench)
* [JudgeBench](https://huggingface.co/spaces/ScalerLab/JudgeBench)

