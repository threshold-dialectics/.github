# Threshold Dialectics: Understanding Complex Systems and Enabling Active Robustness

Welcome to the official GitHub organization for the book **"Threshold Dialectics: Understanding Complex Systems and Enabling Active Robustness"** by Axel Pond. This organization is the central hub for the 21 repositories containing all the source code for simulations, data analyses, and figures presented in the book. Our mission is to foster an open, collaborative, and reproducible research community around these ideas.

---

## What is Threshold Dialectics?

Why do complex adaptive systems—from financial markets and power grids to ecosystems and organizations—so often unravel abruptly, collapsing seemingly without warning after long periods of apparent stability?

**Threshold Dialectics (TD)** offers a fundamentally new perspective on this enduring question. It argues that systemic collapse is not primarily a scalar-threshold problem (a single variable crossing a static line) but a **coupled-velocity problem**. Stability erodes most rapidly, and collapse becomes imminent, not when one resource dial simply hits red, but when the drift velocities of a system's core adaptive capacities become significantly large and detrimentally correlated.

### The Three Core Adaptive Levers

At the heart of TD lie three fundamental adaptive capacities, or "levers," whose dynamic interplay governs a system's viability:

*   **Perception Gain:** The system's sensitivity or responsiveness to new information and prediction errors. Higher gain enhances vigilance but incurs costs in energy and noise amplification.
*   **Policy Precision:** The confidence or rigidity with which the system selects actions or adheres to its current operational model. High precision enables efficiency but can lead to brittleness and a failure to adapt.
*   **Energetic Slack:** The system's reserve capacity (e.g., energy, capital, redundant pathways) available to absorb shocks and fuel adaptation.

### The Tolerance Sheet: A Dynamic Frontier of Viability

The combined state of these three levers defines a dynamic boundary called the **Tolerance Sheet**. This geometric surface in the system's state space represents the maximum systemic strain (e.g., unresolved prediction error) the system can withstand.

Collapse occurs when the system's strain exceeds this dynamically changing capacity.

### Key Diagnostics: The Speed and Couple Indices

TD focuses on the *velocities* of the levers as the most potent early warning signals. The two primary diagnostics are:

*   **Speed Index:** Measures the joint rate of change of policy precision and energetic slack, indicating the magnitude of structural drift.
*   **Couple Index:** Measures the correlation or synchrony of these drifts, revealing how risk is amplified by detrimental coupling.

### The Goal: Enabling Active Robustness

Ultimately, the goal of Threshold Dialectics is not merely to predict collapse, but to enable **Active Robustness**—a system's capacity to proactively and dynamically maintain its viability in the face of uncertainty and change. This involves using TD diagnostics to guide intelligent, timely interventions that steer the system away from its viability boundaries.

## About the Book

The book, *Threshold Dialectics: Understanding Complex Systems and Enabling Active Robustness*, presents a comprehensive exposition of this framework. It rigorously develops TD by intertwining three essential methodologies:

1.  **Developing the Theory:** Laying out the conceptual foundations from first principles and grounding them in Karl Friston's Active Inference framework and the Free Energy Principle.
2.  **Providing the Mathematics:** Offering formal derivations for key constructs like the Tolerance Sheet and the energetic costs of the levers.
3.  **Validating and Discovering through Simulation:** Using computational simulation as a parallel pillar of discovery to instantiate principles, test diagnostic performance, and explore emergent phenomena like the "Phoenix Loop" of post-collapse recovery.

This book is written for researchers, systems operators, engineers, students, and policymakers interested in the dynamics of complex systems, resilience, and adaptation.

## Navigating the Repositories

This organization hosts the main repository for the book itself, along with 21 chapter-specific repositories containing all the code used for simulations, analyses, and figures.

### Chapter-Specific Repositories

The code for each chapter is organized into its own repository to ensure clarity and modularity. The table below maps each chapter of the book to its corresponding repository.

| Part | Chapter | Title | Repository Link |
| :--: | :---: | :--- | :--- |
| **I** | **1-3** | **Foundations: The Theoretical Landscape of Threshold Dialectics** | "(Conceptual chapters - no primary code repo)" |
| **II** | **4** | **The Tolerance Sheet: Mathematical Derivation** | ([https://github.com/threshold-dialectics/chap04-tolerance-sheet](https://github.com/threshold-dialectics/chap4_tolerance_sheet)) |
| **II** | **5** | **Energetics of Perception and Information** | [["chap05-energetics-perception"](https://github.com/threshold-dialectics/chap05-energetics-perception)](https://github.com/threshold-dialectics/chap5_perception_gain_optimization) |
| **II** | **6** | **Lever Dynamics and Diagnostics: The Speed & Couple Indices** | [["chap06-diagnostics-speed-couple"](https://github.com/threshold-dialectics/chap06-diagnostics-speed-couple)](https://github.com/threshold-dialectics/chap6_escape_the_potential_well) |
| **III**| **7** | **Instantiating TD in an FEP-Driven Agent** | [["chap07-fep-agent-instantiation"](https://github.com/threshold-dialectics/chap07-fep-agent-instantiation) ](https://github.com/threshold-dialectics/chap7_emergence_of_TD_from_FEP)|
| **III**| **8** | **A Simulation Experiment for Early Warning Signals** | [["chap08-ews-simulation-study"](https://github.com/threshold-dialectics/chap08-ews-simulation-study)](https://github.com/threshold-dialectics/chap8_early_warning_signals_TD) |
| **III**| **9** | **Adaptive Lever Management: From Heuristics to RL** |[ ["chap09-adaptive-lever-management"](https://github.com/threshold-dialectics/chap09-adaptive-lever-management) ](https://github.com/threshold-dialectics/chap9_active_gain_reinforcement_learning_agent)|
| **IV** | **11**| **Identifying and Classifying the Stages of the Phoenix Loop** | [["chap11-phoenix-loop-classification"](https://github.com/threshold-dialectics/chap11-phoenix-loop-classification) ](https://github.com/threshold-dialectics/chap11_phoenix_loop_classification)|
| **IV** | **12**| **Emergence of the Phoenix Loop from System Dynamics** | [["chap12-phoenix-loop-emergence"](https://github.com/threshold-dialectics/chap12-phoenix-loop-emergence) ](https://github.com/threshold-dialectics/chap12_phoenix_loop_emergence_from_FEP)|
| **V** | **14**| **The Evolving Architecture of Resilience ($w_k$ Self-Organization)** | [["chap14-wk-evolution"](https://github.com/threshold-dialectics/chap14-wk-evolution) ](https://github.com/threshold-dialectics/chap14_evolved_tolerance_sheet)|
| **V** | **15**| **Simulating TD with Sandpile Dynamics** |[ ["chap15-sandpile-simulations"](https://github.com/threshold-dialectics/chap15-sandpile-simulations) ](https://github.com/threshold-dialectics/chap15_sandpile_dynamics)|
| **VI** | **16**| **Fractals as Frozen Signatures of Threshold Dynamics** |[ ["chap16-fractal-signatures"](https://github.com/threshold-dialectics/chap16-fractal-signatures) ](https://github.com/threshold-dialectics/chap16_fractals_experiment_16C)|
| **VI** | **17**| **TD and Emergence: Form and Networks** | [["chap17-emergence-of-form"](https://github.com/threshold-dialectics/chap17-emergence-of-form) ](https://github.com/threshold-dialectics/chap17_evolution)|
| **VI** | **18**| **Scaling Threshold Dialectics: Nested Systems** |[ ["chap18-scaling-td"](https://github.com/threshold-dialectics/chap18-scaling-td)](https://github.com/threshold-dialectics/chap18_scaling_experiment_18A) |

## Getting Started and Contributing

We warmly encourage you to explore, critique, and build upon this work. The spirit of this organization is open science.

1.  **Explore:** Navigate to a chapter-specific repository that interests you. Each repository contains its own "README.md" with details on the simulations, code structure, and how to run the experiments.
2.  **Engage:** If you find any issues, have questions, or want to suggest improvements, please open an issue in the relevant repository. For general book-related feedback or errata, please use the issue tracker in the main ["book-threshold-dialectics"](https://github.com/threshold-dialectics/book-threshold-dialectics) repository.
3.  **Contribute:** We welcome contributions! Please see our general "CONTRIBUTING.md" guidelines for more information on how to contribute to the project.

All code across this organization is licensed under the [MIT License](LICENSE.md).

## Citing This Work

If you use the concepts, code, or data from this project in your research, we would be grateful for a citation.

To cite the book:

@book{pond2025threshold,
  author    = {Axel Pond},
  title     = {Threshold Dialectics: Understanding Complex Systems and Enabling Active Robustness},
  year      = {2025},
  isbn      = {978-82-693862-2-6},
  publisher = {Amazon Kindle Direct Publishing},
  url       = {https://www.thresholddialectics.com},
  note      = {Code repository: \url{https://github.com/threshold-dialectics}}
}


## Contact and Community

For questions, discussions, and collaboration inquiries, please use the **Discussions** tab in the main book repository. We look forward to building a vibrant community around the science of systemic resilience.
