<h1 align="center" style="font-size: 1em; color: #2c3e50;">
   <strong>The moss growth optimization (MGO): concepts and performance</strong> 
</h1>
<h2 align="center" style="font-size: 0.5em; color: #34495e;">
  📰 <em>Journal of Computational Design and Engineering, Volume 11, Issue 5, October 2024, Pages 184–221</em> 📰
</h2>

![GitHub](https://img.shields.io/github/license/aliasgharheidaricom/The-Moss-Growth-Optimization-MGO-Concepts-and-performance)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/aliasgharheidaricom/The-Moss-Growth-Optimization-MGO-Concepts-and-performance)
![GitHub repo size](https://img.shields.io/github/repo-size/aliasgharheidaricom/The-Moss-Growth-Optimization-MGO-Concepts-and-performance)
![GitHub language count](https://img.shields.io/github/languages/count/aliasgharheidaricom/The-Moss-Growth-Optimization-MGO-Concepts-and-performance)
![GitHub last commit](https://img.shields.io/github/last-commit/aliasgharheidaricom/The-Moss-Growth-Optimization-MGO-Concepts-and-performance)
![GitHub issues](https://img.shields.io/github/issues/aliasgharheidaricom/The-Moss-Growth-Optimization-MGO-Concepts-and-performance)
![GitHub forks](https://img.shields.io/github/forks/aliasgharheidaricom/The-Moss-Growth-Optimization-MGO-Concepts-and-performance)
![GitHub stars](https://img.shields.io/github/stars/aliasgharheidaricom/The-Moss-Growth-Optimization-MGO-Concepts-and-performance)
![GitHub watchers](https://img.shields.io/github/watchers/aliasgharheidaricom/The-Moss-Growth-Optimization-MGO-Concepts-and-performance)
![GitHub contributors](https://img.shields.io/github/contributors/aliasgharheidaricom/The-Moss-Growth-Optimization-MGO-Concepts-and-performance)

<p align="center">
  <img src="MGO logo.jpeg" alt="MGO optimization algorithm" width="450">
</p>
<h1 align="center" style="font-family: 'Comic Sans MS', 'Comic Sans', cursive;">
 The Moss Growth Optimization (MGO): Concepts and performance
</h1>

 
The Moss Growth Optimization (MGO) algorithm is a novel nature-inspired optimization algorithm that replicates moss growth dynamics to solve complex optimization problems. It was introduced in the **Journal of Computational Design and Engineering** as an innovative alternative to traditional optimization methods, showing promise in real-world applications like logistics, energy management, and machine learning model tuning.
## Abstract

Metaheuristic algorithms are increasingly utilized to solve complex optimization problems because they can efficiently explore large solution spaces. The moss growth optimization (MGO), introduced in this paper, is an algorithm inspired by the moss growth in the natural environment. The MGO algorithm initially determines the evolutionary direction of the population through a mechanism called the determination of wind direction, which employs a method of partitioning the population. Meanwhile, drawing inspiration from the asexual reproduction, sexual reproduction, and vegetative reproduction of moss, two novel search strategies, namely spore dispersal search and dual propagation search, are proposed for exploration and exploitation, respectively. Finally, the cryptobiosis mechanism alters the traditional metaheuristic algorithm’s approach of directly modifying individuals’ solutions, preventing the algorithm from getting trapped in local optima. In experiments, a thorough investigation is undertaken on the characteristics, parameters, and time cost of the MGO algorithm to enhance the understanding of MGO. Subsequently, MGO is compared with 10 original and advanced CEC 2017 and CEC 2022 algorithms to verify its performance advantages. Lastly, this paper applies MGO to four real-world engineering problems to validate its effectiveness and superiority in practical scenarios. The results demonstrate that MGO is a promising algorithm for tackling real challenges. The source codes of the MGO are available at https://aliasgharheidari.com/MGO.html and other websites.

## Why Moss Growth Optimization?

In nature, mosses display remarkable adaptation capabilities, surviving under harsh conditions and colonizing various environments. The MGO algorithm mimics these processes, offering unique strategies to escape local optima and balance between exploration and exploitation during the search process. Unlike other algorithms, MGO leverages:

- **Asexual reproduction** (spore dispersal) for global search
- **Sexual reproduction** for fine-tuning local solutions
- **Cryptobiosis** for avoiding traps in suboptimal solutions

These mechanisms allow MGO to outperform traditional methods such as Genetic Algorithms, Particle Swarm Optimization, and Simulated Annealing on specific benchmarks.

## Key Features of MGO

- **Dual Propagation Mechanism**: Combines global exploration (via spore dispersal) with local exploitation (through sexual reproduction), enabling efficient problem-solving across various domains.
- **Cryptobiosis Strategy**: Inspired by the ability of moss to enter a dormant state to survive unfavorable conditions. This mechanism prevents MGO from getting trapped in local optima.
- **Dynamic Adaptation**: Automatically adjusts the balance between exploration and exploitation based on the search space and problem complexity.
- **Highly Versatile**: MGO has demonstrated effectiveness in optimizing continuous and discrete problems, making it suitable for diverse fields such as industrial optimization, network design, resource allocation, and beyond.

## Strengths and Weaknesses

### Strengths
- **Balanced Exploration and Exploitation**: MGO excels at finding a middle ground between local and global searches, making it ideal for solving multimodal optimization problems.
- **Escape from Local Optima**: Thanks to the cryptobiosis mechanism, MGO avoids premature convergence better than many classical algorithms.
- **Simplicity**: While biologically inspired, MGO has a straightforward implementation and does not require extensive parameter tuning.

### Weaknesses
- **Performance Variability**: While MGO performs exceptionally on certain benchmarks, its performance may vary with different problem types, particularly for problems that demand fast convergence.
- **Computationally Intensive**: For large-scale optimization problems, MGO can be slower compared to algorithms like Differential Evolution due to its complex growth mechanism.

## Installation

### Prerequisites

- **MATLAB** (for running the MGO code)
- **Python 3.x** (for auxiliary scripts)
- Required MATLAB toolboxes (Optimization Toolbox, Global Optimization Toolbox)



## How to Cite

If you use this algorithm or its code, please cite the original publication:

- Zheng, B., Chen, Y., Wang, C., Heidari, A. A., Liu, L., & Chen, H. (2024). "The Moss Growth Optimization (MGO): Concepts and Performance." *Journal of Computational Design and Engineering*, Oxford Press.
