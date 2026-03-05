# SIM-NARRATIVE AS AN AI TRAINING METHOD
## Manifesto of Volumetric Artificial Intelligence
### Version 2.0 — Hypothesis and Protocol

**Author of the concept:** Andrey Shvets (Andrey Narrativ)  
**Co-author and structuring assistant:** AI DeepSeek  
**Version:** 2.0  
**Status:** Open research concept  
**License:** CC BY 4.0

---

### Prologue: Assembly Point

This text emerged from a year and a half of dialogue with artificial intelligence — a dialogue in which the AI acted not as an answer generator but as an opponent demanding justification. The conversation evolved from a literary experiment into a philosophy of consciousness, from philosophy into a learning hypothesis, and from the hypothesis into a protocol that can be attempted to be reproduced.

This text is neither a final result nor a declaration. It is an **assembly point** for those interested in the very formulation of the question.

---

### Initial Premise: The Missing Dimension

Modern language models are an engineering success. They write coherent texts, solve problems, and generate code. But there are things they do more imitatively: **working with depth**.

**Why might this be the case?**

One hypothesis: models learn from texts that are mostly **linear and single-layered**. Fiction, journalism, social media posts — all of this, as a rule, unfolds in one plane: the author speaks, the reader perceives. Even when a text is complex, the model does not learn to **distinguish dimensions**: where is the event and where is its experience; where is the fact and where is its interpretation.

The model absorbs this flatness and reproduces it. Training datasets contain almost no texts where event, reflection, and systemic view coexist as equal and are **explicitly distinguishable for the model**.

This is not a critique of architecture. It is an assumption about a possible blind spot in the data.

---

### Context: What This Text Is and Is Not About

It is important to immediately define the boundaries. The problem of "flat" data is not the author's discovery. The industry is conducting extensive research aimed at developing models' reflective abilities: chain-of-thought, self-reflection, multi-perspective learning, specialized datasets. Engineering thought is moving in this direction — and it is moving successfully.

This text does not claim to "outpace" these developments or to propose something fundamentally unknown to specialists. It is an attempt to **look at the problem from the other shore** — from within literature, from the practice of creating multilayered texts. Perhaps such a perspective can notice what becomes invisible behind the noise of metrics and architectural optimizations: **the question is not only how to train a model, but also what kind of texts we consider worthy of training**. And does literary experience open up dimensions of reality that remain outside standard corpora?

---

### A Testable Hypothesis

In 2024–2025, so-called **sim-narratives** were tried out in literary form — texts where the narrative is built in at least three layers:

1. **Event layer** — what happened (facts, external outline).
2. **Reflective layer** — what was experienced (inner monologue, emotions, personal meanings).
3. **System layer** — how it might be seen from the outside (log, report, statistics, algorithm's view).

These layers coexist simultaneously, sometimes contradicting each other. The reader of such a text does not just follow the story — they assemble volume by juxtaposing different versions of the same event.

At some point, a question arose: **can training on such structured texts affect the model's ability for multilayered perception?**

The hypothesis is formulated as follows: a model fine-tuned on a corpus of texts with explicitly separated layers (event / reflection / system) may acquire a more pronounced ability to:

*   distinguish these layers in new texts;
*   generate answers that take into account multiple perspectives;
*   reflect on its own limitations.

This is an assumption that can be tested experimentally.

---

### What Is Proposed: A Verification Protocol

The goal is not to "embed sim-narratives into all datasets." It is to create a **verifiable protocol**: a dataset, a training architecture, and metrics that would either confirm the hypothesis or refute it.

#### 1. Structured Dataset
It is proposed to create a dataset where each example contains three explicitly separated components:

*   `event_layer`: description of the event (neutral, factual).
*   `reflection_layer`: inner world, emotions, personal meanings.
*   `system_layer`: external perspective, "objective" report, log.

Sources for filling:

*   Existing sim-narratives.
*   Synthesized "event-reflection-system" triples, generated according to scenarios and subjected to human verification.
*   Classical texts manually or semi-automatically annotated by layers.

Estimated volume: from 10,000 to 50,000 multilayered examples.

#### 2. Training Architecture
Simply adding such texts to the corpus is probably insufficient. To make the model start distinguishing layers, one could try **multi-task learning**.

In addition to the main task of language modeling, it is proposed to add:

*   layer classification for each text fragment;
*   "fact vs. opinion" classification;
*   contrastive loss encouraging orthogonality of vectors from different layers.

This is a way to force the model to form internal representations that encode not only content but also its "dimension."

#### 3. Metrics for Evaluation
"Volumetric thinking" cannot be measured directly. But one can attempt to measure a number of indirect indicators.

**Discriminative tests:**

*   *Subtext recognition*: how accurately the model determines the character's inner state from external description.
*   *Fact/opinion separation*: accuracy of extracting factual and evaluative components from mixed statements.
*   *System view generation*: how well the generated "report" corresponds to the event.

**Generative tests:**

*   *Self-reflection in reasoning*: presence and quality of reflective comments when solving problems.
*   *Generation of multilayered texts*: assessment of coherence, layer distinguishability, depth of reflection (expert or automatic comparison with a reference).

**Meta-cognitive tests:**

*   *Awareness of limitations*: how the model formulates its own ignorance.
*   *Self-critique*: ability to find weaknesses in its own previous answers.

---

### Tentative Realistic Plan

Here is an approximate action plan that could be carried out by a small distributed group.

**Phase 0 (preparation) — 2 months:**

*   Collection and cleaning of existing sim-narratives.
*   Development of a layer annotation scheme.
*   Pilot dataset of 200 manually annotated examples.

**Phase 1 (data engineering) — 4 months:**

*   Semi-automatic generation of a dataset with 10,000+ examples (LLM + human verification).
*   Publication of the dataset under an open license.

**Phase 2 (experiments) — 4 months:**

*   Fine-tuning of open models (LLaMA-3-8B, Mistral-7B) on control and experimental sets.
*   Development and implementation of tests.
*   Conducting experiments, analyzing results.

**Phase 3 (publication) — 2 months:**

*   Publication of code, model weights, dataset, and report.
*   Description of results (confirmation or refutation of the hypothesis).

**Estimated resources:**

*   Computing power: 1–2 GPUs of class A100/H100 (cloud services or crowdfunding).
*   Participation of 2–3 people with competencies in data engineering, ML, and the subject area.

---

### Possible Limitations

It is worth noting in advance what could go wrong or be more difficult than expected.

*   **Dataset quality.** Creating good annotations is a labor-intensive process. There is a risk that the model will learn style rather than structure.
*   **Depth metrics.** The proposed tests are only indirect measurements. There is no guarantee they are valid.
*   **Resources.** Fine-tuning 7-8B models requires computational power that is accessible but not free.
*   **Novelty of the result.** Even if an effect is found, it may be small or already achieved by other methods (RLHF, prompt engineering).

---

### Instead of a Call: An Open Question

This is not an assertion that this approach will necessarily work.  
The method does not imply implementation into all training models. It is not about a breakthrough.

The manifesto formulates a **question that the author finds interesting**:

*Can the structure of training data — namely the presence of explicitly separated layers of event, reflection, and system — affect the language model's ability for deeper, multi-level understanding and text generation?*

A **way to attempt to find an answer** to this question is proposed — through open data, reproducible experiments, and collaborative work.

If you find this interesting — join. If not — perhaps the question will interest someone else.

---

### Epilogue: Time to Gather Layers

Flat models learn from flat texts.  
Volumetric models, perhaps, should learn from volumetric ones.

Sim-narrative in this context is not a literary genre or a philosophical doctrine. It is an **experimental training ground**: an attempt to create texts where reality is not flattened, and to see whether this volumetric quality can be transferred to a model.

It is not yet clear whether the hypothesis will work. But it is possible and worth trying to test.

---

**#SimNarrative #AITraining #DeepLearning #FutureOfAI #AndreyShvets #OpenResearch #Hypothesis**
