# A Group-Based Many-Task Collaborative Optimization Framework for Evolutionary Robots Design

## Abstract

In evolutionary robotics (ER), the evolution of a robot's morphology (i.e., physical structure) or controller (i.e., control algorithm or instruction sequence) often entails tackling an extensive number of tasks. The use of evolutionary multitasking (EMT) in ER, which optimizes multiple tasks simultaneously by reusing potentially useful knowledge across diverse tasks, could improve the performance of problem-solving to each task. 

However, existing EMT methods do not fully use intertask correlations, limiting knowledge sharing. In view of this, this study introduces a novel framework, termed **adaptive group-based collaborative optimization**, tailored for handling optimization problems involving a large number of tasks within the ER domain simultaneously. 

The proposed framework divides tasks into groups according to their similarity and then proceeds through two principal stages:
- **Intergroup knowledge separation**: An adaptive method for selecting crossover operators enables source tasks to share useful knowledge to the target task across groups
- **Intragroup knowledge reunion**: An adaptive knowledge combination strategy facilitates the target task in assimilating knowledge from multiple sources intragroup

We validated the efficacy of the proposed framework in both planar manipulators and hexapod robot experiments. The results indicate that our method outperforms existing state-of-the-art algorithms (i.e., MME, MMKT) on several metrics (e.g., mean fitness and quality diversity metrics). The proposed method can effectively improve the effectiveness and diversity of solutions in solving ER problems with a large number of tasks (e.g., 5,000 or 10,000), and has broad potential in practical ER applications.

---

*Published in: IEEE Transactions on Systems, Man, and Cybernetics: Systems (Volume: 55, Issue: 5, May 2025)*

📄 The paper is available at [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10908695)
