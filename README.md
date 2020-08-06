# Master's Thesis 
#### Text Generation with BERT Embeddings, WordNet senses and Frame Embeddings built on FrameNet graph.

The objective of this thesis is to blend state-of-the-art neural architectures with the still scarcely exploited potential of symbolic knowledge bases, to contribute tackling one of the biggest open problems in artificial intelligence in a specific subfield of natural language processing (NLP): commonsense reasoning in text generation.

Given a set of concepts (expressed by nouns and verbs), the goal is to generate a short sentence that acts as a description of a scene, plausible according to human commonsense knowledge. This problem can be seen as a special case of constrained text generation, with two major challenges: the generation of sentences given an unordered set of keywords with potential morphological changes, and the comprehension of commonsense relations between sets of concepts, finding an appropriate composition.

Since most recent approaches to the problem show no interest in the use of symbolic knowledge resources, this work intends to take the best of both worlds (neural/symbolic), lying at their intersection.
The recently proven capabilities of transformer models are leveraged in com- bination with word sense disambiguation and frame embeddings extracted from FrameNet, an English language knowledge base built upon the theory of Frame Semantics.

The evaluation has been conducted on Commongen, a dataset suitably built for this purpose. A long pre-processing phase, including disambiguation of nominal entities, has been conducted, before training the model for three main scenarios: raw text (as baseline); disambiguated text; disambiguated text with frame embeddings.

The approach has been evaluated on a manually built test-set from the post-processed initial dataset, by means of BLEU and ROUGE metrics. The proposed approach leads to an increase in performance with respect to the baseline, achieving promising results on both automatic metrics, and suggesting further steps to refine our methodology.

[Link to AMSLaurea](https://amslaurea.unibo.it/20397/)
