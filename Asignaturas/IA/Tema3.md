# Lesson 3

- [Lesson 3](#lesson-3)
    - [Goal-based agents](#goal-based-agents)
    - [Why search?](#why-search)
    - [Problem-solving agents](#problem-solving-agents)
      - [**Goal formulation:**](#goal-formulation)
      - [**Problem formulation:**](#problem-formulation)
    - [Environment](#environment)
    - [State space search](#state-space-search)
    - [Tree search](#tree-search)
  - [Search strategies](#search-strategies)
    - [Summary](#summary)
    - [Performances measures of search](#performances-measures-of-search)
    - [Uninformed search strategies](#uninformed-search-strategies)
      - [**Breadth-first search**](#breadth-first-search)
      - [**Depth-first search**](#depth-first-search)
      - [**Depth-limited search**](#depth-limited-search)
      - [**Iterative deepening search**](#iterative-deepening-search)

<br>
<br>

### Goal-based agents

- Have a concept of the future
- Can consider impact of action on future states
- Capable of comparing desirability of states relative to a goal
- Agent’s job: identify best course of actions to reach goal
- Can be accomplished by searching through possible states and actions

**An example:**
If you want to go on a trip:
<br>

![goal-based_example](img/goal-based_example.png)  

- First goal:
  - Go to the airport..
- Formulate problem:
  - States: different roads
  - Actions: drive between roads / choose next road
- Find a solution:
  - Requence of roads

### Why search?

- **Why not Dijkstra's Algorithm?**
  - Want to search in unknown & infinite spaces Combine search with “exploration” (Ex: autonomous rover on Mars must search an unknown space)
  - Want to search based on agent’s actions, w/ unknown connections
(Ex: web crawler may not know what connections are available on a URL before visiting it)
  - The agent may not know the result of an action before trying it

### Problem-solving agents

These are the following steps which require to solve a problem:

#### **Goal formulation:**

This one is the first and simple step in problem-solving. It organizes finite steps to formulate a target/goals which require some action to achieve the goal. Today the formulation of the goal is based on AI agents.

- Agent creates goal based on:
  - Current environment
  - Evaluation metrics
- How does a goal help?
  - Guidance when state is ambiguous
  - Narrows down potential choices

#### **Problem formulation:**

It is one of the core steps of problem-solving which decides what action should be taken to achieve the formulated goal. In AI this core part is dependent upon software agent which consisted of the following components to formulate the associated problem.

- A **state** is a representation of problem elements at a given moment.
- A **State space** is the set of all states reachable from the **initial state**.
- A state space forms a graph in which the nodes are states and the arcs between nodes are **actions**.
- In fact, the initial state and the actions define the state space.

**An exammple: the vaccum model:**
<br>

![vaccum_model](img/vaccum-model.png)  

- States:
  - location, dirt
- Actions:
  - left, right, suck
- Goal:
  - celean world

State space graph:
<br>

![picture 3](img/state-grapth.png)  

### Environment

- **Observable** / Partially: know the initial state
- **Static** / Dynamic: the states don’t change when the agent search
- **Deterministic** / Stochastic: the next state is defined only by current
- **Discrete** / Continuous: time management

### State space search

- The formal definition does not talk about the way in which the information must be stored in the states or what are the operators that allow to pass from one state to the other.
- Depends on the specific problem.
- The formal definition gives a general framework that allows us to apply different methods to solving the problem.

### Tree search

- Explore space by generating successors of already-explored states (“expanding” states).
- Evaluate every generated state: is it a goal state?

## Search strategies

- The search strategy is defined when we choose the order in which the nodes are expanded
- Types:
  - Uninformed or blind search: only available information is used in the problem definition (cost is not considered).
  - Informed or heuristic search: the agent has additional information about the problem (estimate the cost to the goal).

### Summary

- Generate the **search space** by applying actions to the initial state and all further resulting states.
- **Problem**: initial state, actions, transition model, goal test.
- **Solution**: sequence of actions to goal.
- **Tree-search** (don’t remember visited nodes) vs. **Graph-search** (do remember them).
- **Search strategy** (Uninformed vs Informed).

### Performances measures of search

- Completeness: Always find a solution (if one exists)?
- Time complexity: Number of nodes generated
- Space complexity: Maximum number of nodes in memory
- Optimality: Always find a least-cost solution?
- Time and space complexity are measured in terms of
  - b: Maximum branching factor of the search tree
  - d: Depth of the least-cost solution
  - m: Maximum depth of the state space (maybe $\infty$)

### Uninformed search strategies

- Uninformed search strategies use only the information available in the problem definition
- No analysis or knowledge of states, only:
  - Generate successor nodes
  - Check for goal state
- Specifically, no comparison of states

<u>**Types of search:**</u>

- Breadth-first search
- Depth-first search
- Depth-limited search
- Iterative deepening search

#### **Breadth-first search**

Breadth-first search on a simple binary tree. At each stage, the node to be expanded next is indicated by the triangular marker.
<br>

![Breadth-first](img/Breadth-first.png)

#### **Depth-first search**

Depth-first search on a simple binary tree. At each stage, the node to be expanded next is the deepest node indicated by the triangular marker.
<br>

![Depth-first](img/Depth-first.png)  

#### **Depth-limited search**

In a depth-limited search, there can be a depth limit. If the depth limit is reached, the search is terminated. This is called **depth-limited search**. If the depth limit is set to infinity, then the search is equivalent to a depth-first search.
<br>

![Depth-limit](img/Depth-limit.png)  

#### **Iterative deepening search**

Iterative deepening search is a combination of depth-first search and breadth-first search. It is a depth-first search with a depth limit. The depth limit is increased after each iteration. The search is terminated when the goal is found or the depth limit is set to infinity.
<br>

![picture 4](img/Iterative-deepening.png)  
