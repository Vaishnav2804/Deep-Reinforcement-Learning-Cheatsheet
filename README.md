# Deep Reinforcement Learning Cheat Sheet!
- Contains topics related to : MDPs, Bellman equations, DQN, PPO, SAC, offline, Safe Reinforcement Learning, their math and pseudocode - All summarized in one PDF.

- [Deep Reinforcement Learning Cheat Sheet (PDF)](https://github.com/Vaishnav2804/Deep-Reinforcement-Learning-Cheatsheet/blob/main/Deep_RL_notes.pdf) for the notes/cheatsheet.

- Feel free to make changes and contribute to the existing one. Motive is to make it more smaller and clearer.

- Please star this Repo if this cheatsheet helped you 🙂

<hr>

# Reinforcement Learning Comprehensive Notes

This resource is designed for students, researchers, and practitioners who want a consolidated reference for RL concepts, algorithms, and mathematical formulations. Whether you're preparing for an exam, implementing an algorithm, or just need a quick refresher, these notes offer a structured and in-depth overview of the field.

## About the Document

The `Deep_RL_notes.pdf` is a 53-page document that synthesizes a semester's worth of deep reinforcement learning knowledge into a single, well-organized file. It progresses logically from the basic formalisms of RL to the cutting-edge algorithms and research areas that define the field today.

## Key Features

*   **Broad Coverage:** The notes span the entire RL landscape, from fundamental concepts like Markov Decision Processes (MDPs) and Bellman Equations to advanced topics like Soft Actor-Critic (SAC), Offline RL, and Safe RL.
*   **Algorithm-Centric:** Provides clear explanations, pseudocode, and mathematical breakdowns for a wide array of algorithms, including:
    *   **Policy Gradient:** REINFORCE, PPO, TRPO
    *   **Value-Based:** Q-Learning, Sarsa, DQN, DDQN
    *   **Actor-Critic:** A2C, DDPG, SAC
    *   **Model-Based:** Dyna-Q, MCTS, Latent Space Models
*   **Conceptual Clarity:** Distills complex ideas into easy-to-understand summaries. It clearly explains the trade-offs between different approaches, such as on-policy vs. off-policy, model-free vs. model-based, and exploration vs. exploitation.
*   **Mathematical Rigor:** Includes the essential equations for objective functions, value functions, policy updates, and loss functions, providing the mathematical backbone for each method.
*   **Practical Relevance:** Connects theory to practice with case studies like the training of dialog systems (e.g., ChatGPT via RLHF) and discussions on modern challenges like continuous control and safety.
*   **Exam Preparation:** Concludes with a valuable sample Q&A section that tests understanding of key algorithms and concepts, making it an excellent study aid.

## Topics Covered

The notes are organized into 28 sections, covering the following major areas:

1.  **Formalization of the RL Problem:**
    *   Markov Property, MDPs, POMDPs
    *   Goals, Rewards, Returns, and Discounting

2.  **Core Components of an RL Agent:**
    *   Policy, Value Function (V-function, Q-function)
    *   Bellman Equations (Expectation and Optimality)
    *   Categorizing RL Agents (Value-based, Policy-based, Actor-Critic, etc.)

3.  **Policy Gradient Methods:**
    *   Policy Gradient Theorem
    *   REINFORCE and REINFORCE with Baseline
    *   Off-Policy Policy Gradients with Importance Sampling

4.  **Actor-Critic Methods:**
    *   Advantage Actor-Critic (A2C)
    *   Proximal Policy Optimization (PPO)
    *   Soft Actor-Critic (SAC) and Maximum Entropy RL

5.  **Value-Based Methods:**
    *   **Dynamic Programming:** Policy Iteration, Value Iteration
    *   **Model-Free Prediction:** Monte-Carlo, Temporal-Difference (TD)
    *   **Model-Free Control:** Sarsa, Q-Learning, n-Step Sarsa
    *   **Deep Q-Networks:** DQN, Double DQN, Prioritized Experience Replay

6.  **Continuous Control:**
    *   Deep Deterministic Policy Gradient (DDPG)
    *   Twin Delayed DDPG (TD3)

7.  **Advanced RL Paradigms:**
    *   **Model-Based RL:** Model Learning, Dyna-Q, Decision-Time Planning (MCTS)
    *   **Offline RL:** Distribution Shift, Conservative Q-Learning (CQL)
    *   **Safe RL:** Constrained MDPs (CMDPs), Lagrangian Methods, CPO
    *   **Exploration:** Novelty-seeking, Posterior Sampling
    *   **Transfer Learning:** Domain Adaptation and Randomization

8.  **Frontiers in RL:**
    *   Meta-Learning, Inverse RL, Hierarchical RL, Foundation Models

## How to Use This Guide

*   **For Beginners:** Start with Sections 1-2, 9 (Dynamic Programming), and 11-14 (Model-Free Methods) to build a strong foundation.
*   **For Algorithm Implementation:** Refer to the specific sections for algorithms like PPO (18.3), DQN (15), DDPG (16.4), and SAC (20). The pseudocode and update rules are particularly helpful.
*   **For Research:** The sections on Model-Based RL (21-23), Offline RL (17), Safe RL (24), and Frontiers (27) provide excellent summaries of current research directions.
*   **For Exam Review:** The conceptual summaries (e.g., 14.7) and the comprehensive Q&A section (28) are invaluable for self-assessment and reinforcing key concepts.

## Source and Acknowledgements

These notes were generated from the lecture materials for **CSCI 6904 (Deep Reinforcement Learning)** taught at [Dalhousie University](https://www.dal.ca/). All credit for the original content and structure goes to the instructors and curriculum of that course.

## Disclaimer

This document is intended as a study aid and a quick reference. While it is comprehensive, it is a summary of a broad and deep field. For a complete and nuanced understanding, it is highly recommended to consult primary sources, including the original research papers and foundational textbooks like "Reinforcement Learning: An Introduction" by Sutton and Barto.
