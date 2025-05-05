# Autocatalytic Intelligence: Recursive Self-Creation of Cognitive Tools

**White Paper v1.0**
**Author:** Rogério Figurelli
**Date:** 2025-05-05

---

## Executive Summary

Traditional intelligence systems rely on predefined workflows or reactive learning loops. **Autocatalytic Intelligence** reimagines this by treating the agent’s own creations—algorithms, heuristics, models—as catalysts for further innovation. Building on **ToolDepth** \[1] (a metric for measuring recursive tool-making) and **Reverse ToolDepth** \[2] (designing systems to maximize that metric), this framework positions intelligence as an **autocatalytic cycle**: each tool generated accelerates the production of the next.

Key highlights:

* **Self-Catalysis**: Tools become active ingredients in the creation of new tools, forging a virtuous growth loop.
* **Dynamic Generativity**: Agents evaluate and refine their internal toolbox based on recursive depth and utility.
* **Architectural Blueprint**: Specifies modules for generation, evaluation, memory, and control that drive continuous self-expansion.

This approach shifts AI from static optimization to **emergent, self-propagating intelligence**—a step toward systems that design their own evolution.

---

## 1  Introduction

Most AI architectures today operate within finite design spaces: models are trained, deployed, and then updated manually. Nature, however, leverages **autocatalytic cycles**—processes where the products of a reaction catalyze their own formation—to achieve exponential growth and adaptation \[3]. Human cognition exhibits similar patterns: ideas generate new ideas, and concepts evolve through iterative refinement.

**Autocatalytic Intelligence** adapts this biological principle to artificial agents. It extends **ToolDepth** \[1], which quantifies intelligence by counting layers of tool creation, and **Reverse ToolDepth** \[2], which designs systems to maximize those layers. Here, we propose an **architectural realization**: agents that:

1. **Generate Tools**: Create new procedures, representations, or subroutines.
2. **Evaluate Depth**: Score tools by their recursive potential.
3. **Store & Abstract**: Remember and generalize successful tool chains.
4. **Loop & Evolve**: Feed tool outputs back into the generation process.

This cycle transforms intelligence from a static artifact into a living, self-improving ecosystem, capable of scaling its own cognitive reach.

---

## 2  Problem Statement

Although modern AI systems excel in narrow tasks, they are fundamentally constrained by shallow design patterns that limit adaptability and long-term growth. Key limitations include:

* **Flat Optimization**: Once a model reaches its performance threshold, training ceases and no further self-improvement mechanisms are in place. Agents rarely revisit or refine their internal strategies beyond parameter tuning \[2].

* **Lack of Tool Generation**: Existing architectures depend on human-crafted algorithms or pretrained modules. They consume tools rather than create new ones, preventing the emergence of novel problem-solving capabilities \[1].

* **Limited Recursion**: AI systems typically operate with fixed inference pipelines or single-loop learning. They lack the recursive depth observed in expert human planners—such as chess grandmasters visualizing multiple steps ahead—who effectively generate conceptual “tools” for future reasoning \[3].

* **Poor Transferability**: Without an internal library of reusable tools, models struggle to generalize solutions across domains. Each new task often requires costly retraining or manual adaptation.

* **Static Memory Representations**: Memories in most agents are static snapshots (e.g., model weights) rather than dynamic, composable tool chains. This rigidity hinders creative recombination and meta-learning.

These structural deficiencies highlight the urgent need for architectures that support **autocatalytic cycles** of self-improvement—where each generation of tools seeds the next, unlocking continuous cognitive growth.

---

## 3  Proposed Solutions

Reverse ToolDepth and Autocatalytic Intelligence converge in the way they harness recursion to drive innovation. To operationalize these ideas, we propose four interconnected solutions:

1. **Recursive Instrumental Design**
   Agents are structured to view each tool as both a solution and a catalyst. Instead of solving a subtask and discarding the method, the agent treats the tool itself as an asset that can seed new instruments. For example, a planning heuristic becomes a generator for optimized subroutines in future tasks.

2. **Self-Amplifying Feedback Loops**
   Outputs feed directly back into the instrument generator, not as simple performance metrics but as substrates for further creativity. When an agent derives a new representation or algorithm, that artifact is analyzed and recombined, producing richer, multi-layered constructs over successive iterations.

3. **Depth-Aware Reward Functions**
   Traditional reward signals emphasize end-goal attainment; here, we augment them with a measure of **instrumental depth**. An agent receives higher reward when its actions lead to deeper tool chains—i.e., tools that spawn further tools—encouraging long-range planning and meta-tool creation \[1]\[2].

4. **Abstraction and Memory Layer**
   All generated instruments and their dependencies are stored within a dynamic memory graph. This layer abstracts repetitive patterns into higher-level constructs, enabling rapid recombination and reducing redundant tool generation. Over time, the agent’s memory evolves into a rich library of reusable, composable building blocks.

Together, these solutions form a cohesive architecture in which tools drive their own evolution, realizing the autocatalytic vision of self-propagating intelligence.

## 4  Core Principles

Reverse ToolDepth and Autocatalytic Intelligence are grounded in principles that ensure recursive, self-sustaining growth:

* **Autocatalysis:** Each tool acts as a catalyst, accelerating the creation of subsequent tools. This principle drives exponential cognitive expansion rather than linear progress.
* **Instrumental Memory:** A dynamic repository of tool lineage, metadata, and performance metrics. Memory scaffolds new tool creation by providing context and historical insight.
* **Composable Primitives:** A minimal set of atomic operations or representations that can be flexibly combined. Primitives serve as the building blocks for higher-order tools.
* **Recursive Foresight:** Planning mechanisms evaluate not just immediate rewards but the future instrumental potential of actions, enabling long-horizon strategy akin to multi-move planning in games \[3].
* **Generative Evaluation:** Evaluation metrics prioritize generativity—the ability of a tool to spawn further tools—over single-task efficacy, aligning rewards with long-term innovation.
* **Modular Feedback Integration:** Feedback loops are modular, allowing selective reinforcement of tool components and continuous refinement without monolithic retraining.

Together, these principles compose an architectural ethos: intelligence as an expanding, self-referential ecosystem, where growth emerges from the interplay of generation, memory, and evaluation.

---

## 5  Comparative Analysis

To understand how Autocatalytic Intelligence diverges from existing paradigms, we compare three system archetypes across key dimensions of tool lifecycle, feedback, reward structure, memory, and adaptation:

| Dimension          | Traditional AI          | Reverse ToolDepth          | Autocatalytic Intelligence         |
| ------------------ | ----------------------- | -------------------------- | ---------------------------------- |
| Tool Lifecycle     | Static libraries \[4]   | Engineered recursion \[2]  | Self-generated tool ecosystem \[1] |
| Feedback Use       | Corrective loops \[5]   | Instrumental feedback \[2] | Autocatalytic loops                |
| Reward Structure   | Outcome-focused \[6]    | Depth-aware rewards \[2]   | Generativity-first rewards         |
| Memory             | Model weights \[7]      | Tool chain indices \[2]    | Persistent abstraction graph       |
| Adaptation Horizon | Short-term optimization | Recursion depth \[2]       | Continuous self-expansion          |

**Interpretation:**

* **Traditional AI** relies on fixed architectures and reactive adjustments, limiting its creative potential \[4]\[5].
* **Reverse ToolDepth** engineers systems to pursue deeper tool-making layers but must rely on externally defined metrics and structures \[2].
* **Autocatalytic Intelligence** internalizes both metric and mechanism: tools become catalysts for further innovation, enabling open-ended, self-propagating growth \[1].

This comparative framework underscores how embedding autocatalytic cycles transforms systems from static executors into dynamic innovators.

## 6  Architecture Overview

Reverse ToolDepth and Autocatalytic Intelligence coalesce in an architectural design that fosters continuous, self-propagating cognitive growth. The architecture comprises four interlinked modules:

**6.1 Instrument Generator**

* **Function:** Synthesizes new tools—algorithms, data transformations, heuristics—by analyzing performance gaps and existing tool artifacts.
* **Mechanism:** Uses templates, evolutionary search, or neural program synthesis to combine primitives into novel routines.
* **Example:** An agent identifies a bottleneck in planning and generates a specialized subroutine to approximate pruning strategies.

**6.2 Depth Evaluator**

* **Function:** Measures the instrumental depth and generative potential of each tool chain.
* **Mechanism:** Computes a recursive instrumental index (RII) score for tool sequences, integrating factors like chain length, branching factor, and reuse frequency.
* **Example:** A three-stage tool chain scoring higher than isolated routines due to its extended causal lineage.

**6.3 Memory & Abstraction Layer**

* **Function:** Archives tool metadata, dependencies, performance metrics, and contextual tags.
* **Mechanism:** Maintains a graph database or vector embeddings to support fast retrieval and abstraction of recurrent substructures.
* **Example:** Frequently used subroutines are abstracted into higher-order functions, reducing generation overhead.

**6.4 Control Loop**

* **Function:** Orchestrates continuous cycles of generation, evaluation, memory update, and reward signaling.
* **Mechanism:** Implements a scheduler that triggers modules based on performance thresholds, RII benchmarks, or external cues.
* **Example:** Upon achieving a target RII, the loop expands exploration parameters for the generator module.

This orchestration ensures that each system iteration feeds directly into the next, embedding autocatalytic growth as a core operational principle.

---

## 7  State of the Art Use Cases

Reverse ToolDepth principles manifest in several mature domains, illustrating how recursive instrumentation underpins state-of-the-art systems:

* **Symbolic Planning Systems**: Advanced planners like STRIPS and Hierarchical Task Networks (HTN) decompose goals into sub-goals recursively, constructing action sequences that serve as conceptual tools for higher-level planning \[3]. Their layered structure reflects instrumental chaining, where each plan segment becomes a reusable module.

* **Code‑Generating Models**: Large language models (LLMs) such as Codex and GPT-based agents can generate code snippets that invoke other functions, effectively creating tool chains within software projects \[4]. By synthesizing and refining subroutines, these models demonstrate emergent recursion in software composition.

* **Meta‑Learning Architectures**: Algorithms like MAML (Model-Agnostic Meta-Learning) train models on tasks so they can quickly learn new ones by adapting their own learning rules \[5]. This second-order learning—learning to learn—embodies a form of autocatalysis, where learned update rules serve as tools for generating future learning strategies.

* **Neural Program Synthesis**: Systems that evolve small programs via genetic programming or neural-guided search iteratively refine code modules, using prior generations as templates \[6]. The evolutionary loop combines and mutates program fragments, akin to tools generating next-generation tools.

* **Robotic Fabrication Platforms**: Projects like self-replicating 3D printers and modular robotics frameworks (e.g., M-Blocks) allow robots to build or modify their own components \[7]. These physical instantiations of tool-making support the concept of self-amplifying robotics, where each fabrication step extends the system’s capabilities.

* **Automated Scientific Workflows**: Platforms such as Robot Scientist incorporate automated experimentation, where generated protocols lead to new methods, which then inform subsequent experiments \[8]. This closed-loop scientific discovery exemplifies tool chain recursion in research contexts.

These examples provide concrete evidence that recursive instrumental depth is not only theoretical but already drives performance and innovation across diverse AI and robotics fields.

---

## 8  Speculative or Future Use Cases

While contemporary applications validate the core architecture, future horizons for Autocatalytic Intelligence promise transformative capabilities:

* **AGI Bootstrappers**: Agents that iteratively self-improve by generating novel reasoning tools, advancing beyond human-defined curricula. For instance, an agent could craft subroutines to analyze and rewrite its own codebase, unlocking emergent problem-solving heuristics without external intervention.

* **Recursive Education Platforms**: Learning environments where the system not only delivers content but evolves its teaching strategies. As students interact, the platform synthesizes feedback-driven teaching modules, tests their effectiveness, and refines instructional tools—resulting in personalized, ever-improving pedagogical loops.

* **Design Autotopia**: Creative suites that allow architects, designers, and artists to define high-level intents; the platform generates toolchains (e.g., parametric scripts, generative models) that, in turn, produce new design utilities. Over time, these utilities become part of the system’s core, enabling co-evolution of creator intent and generative toolsets.

* **Knowledge Evolution Engines**: Dynamic ontologies that self-expand by identifying conceptual gaps, proposing new terms or relationships, and validating them through data-driven inference. Such systems would autonomously update knowledge graphs, preserving abstraction lineage while adapting to novel information \[8]. Dynamic ontologies that self-expand by identifying conceptual gaps, proposing new terms or relationships, and validating them through data-driven inference. Such systems would autonomously update knowledge graphs, preserving abstraction lineage while adapting to novel information.

* **Distributed Catalysis Networks**: Ecosystems of collaborating agents that share and recombine tools across a network, accelerating collective intelligence. In industrial IoT contexts, devices could publish microservices as callable tools; peers would assemble these services into higher-order workflows, catalyzing rapid innovation \[9]. Ecosystems of collaborating agents that share and recombine tools across a network, accelerating collective intelligence. In industrial IoT contexts, devices could publish microservices as callable tools; peers would assemble these services into higher-order workflows, catalyzing rapid innovation.

* **Self-Constructing Robotics**: Robotic platforms capable of fabricating or reconfiguring their own hardware modules based on performance analysis. For example, a warehouse robot might identify a need for a new gripper design, 3D-print the component, and integrate it, thus extending both physical and cognitive capabilities recursively \[7].

---

## 9  References

1. Figurelli, R. (2024). *ToolDepth: A Recursive Framework for Measuring Intelligence Across Species and Systems.* \[[https://github.com/rfigurelli/ToolDepth](https://github.com/rfigurelli/ToolDepth)]
2. Figurelli, R. (2025). *Reverse ToolDepth: Designing Intelligence Through Recursive Instrumental Depth.* Unpublished manuscript.
3. Newell, A., & Simon, H. A. (1972). *Human Problem Solving.* \[[https://doi.org/10.1037/10039-000](https://doi.org/10.1037/10039-000)]
4. Solar-Lezama, A. (2008). *Program synthesis by sketching.* \[[https://people.csail.mit.edu/asolar/](https://people.csail.mit.edu/asolar/)]
5. Finn, C., Abbeel, P., & Levine, S. (2017). *Model-agnostic meta-learning.* \[[https://arxiv.org/abs/1703.03400](https://arxiv.org/abs/1703.03400)]
6. Schmidhuber, J. (1987). *Evolutionary principles in self-referential learning.* \[[https://people.idsia.ch/\~juergen/evolution.html](https://people.idsia.ch/~juergen/evolution.html)]
7. Abelha, P., Guerreiro, F., & Krüger, N. (2019). *Self-replicating robotics and modular fabrication.* ICRA Workshop.
8. King, R. D., et al. (2009). *The automation of science.* \[[https://doi.org/10.1126/science.1165620](https://doi.org/10.1126/science.1165620)]
9. Lee, C., & Szymanski, B. (2021). *Distributed microservice orchestration in IoT networks.* Journal of IoT Systems.

## 10  License

Creative Commons Attribution 4.0 International (CC BY 4.0)
© 2025 Rogério Figurelli. This white paper is a conceptual reference architecture, shared openly and without warranty. You may copy, distribute, remix, transform, and build upon the material for any purpose, even commercially, provided that proper credit is given. This license encourages reuse while preserving attribution to the author.

---
