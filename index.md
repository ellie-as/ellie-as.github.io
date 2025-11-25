---
layout: default
title: "Home"
---

# About

Hi, I'm Ellie. I'm a postdoctoral researcher in Tim Behrens' lab at Oxford, working on how our brains learn predictive models of the world offline, how frontal cortex develops useful abstractions, and how this relates to recent advances in AI. Previously, I did my PhD with Neil Burgess at University College London, modelling systems consolidation as the training of generative models in cortex on replayed memories. Before that, I worked in machine learning in the UK Civil Service for a few years. 


## Projects

(Under construction.)

- **A generative model of memory construction and consolidation**  
  *Eleanor Spens and Neil Burgess, Nature Human Behaviour (2024)*  
  **Link:** [https://www.nature.com/articles/s41562-023-01799-z](https://www.nature.com/articles/s41562-023-01799-z)  
  **Blog:** [Springer Communities post](https://communities.springernature.com/posts/a-generative-model-of-memory-construction-and-consolidation)  
  **Abstract:** Episodic memories are (re)constructed, share neural substrates with imagination, combine unique features with schema-based predictions and show schema-based distortions that increase with consolidation. Here we present a computational model in which hippocampal replay (from an autoassociative network) trains generative models (variational autoencoders) to (re)create sensory experiences from latent variable representations in entorhinal, medial prefrontal and anterolateral temporal cortices via the hippocampal formation. Simulations show effects of memory age and hippocampal lesions in agreement with previous models, but also provide mechanisms for semantic memory, imagination, episodic future thinking, relational inference and schema-based distortions including boundary extension. The model explains how unique sensory and predictable conceptual elements of memories are stored and reconstructed by efficiently combining both hippocampal and neocortical systems, optimizing the use of limited hippocampal storage for new and unusual information. Overall, we believe hippocampal replay training generative models provides a comprehensive account of memory construction, imagination and consolidation.  
  **TL;DR:** As memories are replayed over the course of systems consolidation, they update a generative model of the world that supports memory as well as reasoning about future situations. Even right after an experience, remembering involves imagining the past based on concepts, combining some stored details with expectations about what happened.

- **Hippocampo-neocortical interaction as compressive retrieval-augmented generation**  
  *Eleanor Spens and Neil Burgess, Under Review*  
  **Link:** [https://www.biorxiv.org/content/10.1101/2024.11.04.621950v3](https://www.biorxiv.org/content/10.1101/2024.11.04.621950v3)  
  **Abstract:** Many cognitive functions involve interplay between episodic (hippocampal) and semantic (neocortical) systems, but the mechanisms are unclear. We present a computational model in which sequential experiences are encoded in hippocampus in compressed form and replayed to train a neocortical generative network. This network captures the gist of specific episodes and extracts statistical patterns that generalise to new situations, enabling efficient reconstruction of the past and prediction of the future. The two systems interact during recall and prediction, with the hippocampus retrieving relevant episodic information into working memory as a basis for generation using the ‘general knowledge’ of the neocortical network. We simulate this interaction as ‘retrieval-augmented generation’, with the addition of mechanisms to compress episodic memories into hippocampus and to consolidate them into neocortex. The model explains changes to memories over time, including schema-based distortions, and shows how recent episodic and semantic memory contribute to new problem solving.  

- **Modelling the control of offline processing with reinforcement learning**  
  *Eleanor Spens, Neil Burgess, and Tim Behrens, NeurIPS (2025)*  
  **Link:** [https://openreview.net/pdf?id=BFW1fkB8ck](https://openreview.net/pdf?id=BFW1fkB8ck)  
  **Abstract:** Brains reorganise knowledge offline to improve future behaviour, with ‘replay’ involved in consolidating memories, abstracting patterns from experience, and simulating new scenarios. However, there are few models of how the brain might orchestrate these processes, and of when different types of replay might be useful. Here we propose a framework in which a meta-controller learns to coordinate offline learning of a lower-level agent or model in ‘sleep’ phases to maximise reward in an ‘awake’ phase. The meta-controller selects among several actions, such as learning from recent memories in a hippocampal store, abstracting patterns from memories into a ‘world model’, and learning from generated data. In addition, the meta-controller learns to estimate the value of each episode, enabling the prioritisation of past events in memory replay, or of new simulations in generative replay. Using image classification, maze solving, and relational inference tasks, we show that the meta-controller learns an adaptive curriculum for offline learning. This lays the groundwork for normative predictions about replay in a range of experimental neuroscience tasks.  
  **TL;DR:** We present a framework in which a meta-controller chooses among metacognitive actions during ‘sleep’, inspired by offline processing in brains, to optimise behaviour during ‘wake’. The system also learns what to replay or simulate, enabling normative predictions about optimal offline learning.

  
## Contact

- Email: ellie.spens@ndcn.ox.ac.uk
- GitHub: [@ellie-as](https://github.com/ellie-as)
