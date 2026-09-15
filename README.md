# ICPC Preparation Plan — 1100 CF → ICPC Prelim

**Start:** 16 September 2026  
**Prelim:** 3 October 2026  
**Extended plan:** 16 September → 15 November 2026  
**Wake:** 12:00 PM  
**Sleep:** 4:00 AM

This plan assumes:
- Current Codeforces rating: ~1100
- You do **not** yet know many advanced structures such as segment trees, Li Chao trees, advanced/group DP, HLD, etc.
- You can realistically devote ~10–12 hours/day to high-quality competitive programming.
- The immediate objective is the **October 3 ICPC prelim**, not maximizing Codeforces rating.
- You are preparing as the strongest/primary problem solver on the team, so breadth, implementation speed, and contest judgment matter.

CSES currently has **400 problems**, following the May 2025 expansion by 100 problems. The current set includes the classical sections plus newer difficult material in Range Queries, Trees, Mathematics, Bitwise Operations, Advanced Graphs, Counting, and Additional Problems. Use it as a structured curriculum rather than solving all 400 sequentially.

---

# 1. Daily Base Schedule

## Normal training day

| Time | Block | Objective |
|---|---|---|
| 12:00–12:45 | Wake / food / shower | Get fully awake |
| 12:45–3:15 | **Algorithm Learning + Targeted Practice** | Build missing CP toolkit |
| 3:15–3:45 | Break | Walk / food |
| 3:45–6:15 | **Codeforces Problems** | Rating + pattern recognition |
| 6:15–7:00 | Break / meal | |
| 7:00–9:00 | **Implementation Training** | Make known techniques fast |
| 9:00–9:30 | Break | |
| 9:30–12:30 | **ICPC Practice / Virtual** | Contest skills + problem selection |
| 12:30–1:15 | Dinner / break | |
| 1:15–2:45 | **CSES / AtCoder** | Reinforcement + different styles |
| 2:45–3:30 | **Review / Upsolving** | Turn failures into knowledge |
| 3:30–4:00 | Wind down | Prepare for sleep |

### Daily actual CP target

- **10.5–12 high-quality hours**
- 4–8 normal CF problems depending on difficulty
- 1–3 CSES/AtCoder problems
- 1 implementation drill session
- Contest/virtual work every day during the final 18-day sprint

Do not measure success by raw problem count. Measure:
1. problems independently solved
2. solve time
3. number of bugs/penalties
4. hardest idea independently derived
5. techniques moved from `LEARN → WEAK → MASTERED`

---

# 2. Rules for Problem Solving

## For problems near your rating

Use a timer.

### 800–1000
Target: **10–20 min**

### 1000–1100
Target: **15–25 min**

### 1100–1200
Target: **20–30 min**

### 1200–1300
Target: **25–40 min**

### 1300–1400
Target: **35–50 min**

### 1400–1600
Target: **45–75 min**

## For deep problems

During CSES/deep-thinking blocks:

- Give the problem **60–120 minutes**
- No editorial initially
- Write brute force first
- Derive constraints
- Find the key observation
- Only then look at the editorial if genuinely stuck

If the missing technique is something you have never learned, do **not** spend 3 hours pretending you can magically invent the data structure.

Instead:

`20–40 min attempt → learn technique → close editorial → reimplement → solve 2–4 more`

---

# 3. What "Algorithm Learning" Means

You currently need to build a coherent toolkit.

## Tier 1 — Immediate

- Prefix sums
- Difference arrays
- Sorting
- Frequency maps / sets
- Two pointers
- Sliding window
- Binary search
- Binary search on answer
- Greedy
- Stack / queue / deque
- Monotonic stack
- Basic recursion
- BFS
- DFS
- Connected components
- Basic tree traversal
- Basic dynamic programming
- Bit manipulation
- GCD / LCM
- Sieve
- Basic modular arithmetic
- Priority queue

## Tier 2 — Learn before prelim if possible

- DSU
- Fenwick tree
- Segment tree
- Dijkstra
- 0–1 BFS
- MST / Kruskal / Prim
- Topological sort
- LCA
- Binary lifting
- Euler tour on trees
- Basic combinatorics
- Basic shortest paths
- Bridges / articulation points
- SCC

## Tier 3 — Exposure only before prelim

Do not make these your main focus yet:

- HLD
- Li Chao tree
- Convex hull trick
- Centroid decomposition
- Advanced DP / group DP
- Flows
- Advanced matching
- Suffix automaton
- Advanced geometry
- Advanced persistent structures

Knowing that these techniques exist is useful. Mastering them before the prelim is not worth sacrificing the fundamentals.

---

# 4. Codeforces Strategy

Do NOT do:

`50 × 800–1000 → 50 × 1000–1200 → 50 × 1200–1400`

Instead keep a moving difficulty distribution.

## Phase A — Current level

For ~10 problems:

- 3 × 900–1100
- 3 × 1000–1200
- 2 × 1200–1300
- 1 × 1300–1400
- 1 × 1400–1600

When 1100–1200 becomes comfortable, shift upward.

## Important rule

Every day should contain at least:
- several problems you are expected to solve
- one problem that stretches you
- one problem where failure teaches you something

This prevents both stagnation and overload.

---

# 5. Implementation Training

The goal is to make standard techniques almost mechanical.

## Daily 2-hour implementation block

### 30 min — Template reconstruction

Without looking at notes, implement one:

- BFS
- DFS
- DSU
- Dijkstra
- Fenwick
- Segment tree
- LCA
- sieve
- modular arithmetic

### 60 min — Speedrun

Take 2–3 problems whose ideas you already understand.

Implement from scratch.

Target:

- easy: 10–15 min
- medium: 15–25 min
- standard data structure: 15–25 min

### 30 min — Debugging

Review:
- indexing mistakes
- overflow
- unnecessary complexity
- bad data structures
- repeated bugs

Maintain a `BUG_LOG.md`.

---

# 6. ICPC Practice

ICPC is not Codeforces with three people.

Train:

- reading speed
- problem selection
- parallelization
- communication
- implementation ownership
- debugging
- penalty management

## During a real virtual

Use:

### First 20–30 minutes
Read as many problems as possible.

Classify:

`A = almost certainly solvable`

`B = likely solvable after observation`

`C = hard / unclear`

Then attack A problems first.

## As the potential carry

Your job is not to personally solve everything.

Your job is to maximize team output.

When practicing solo, ask:

> Which problems would I assign to teammate 1, teammate 2, and myself?

Even if you are not actually assigning them.

---

# PART I — PRELIM SPRINT

# 16 September → 3 October

## Wednesday — 16 Sep
### Theme: Baseline + fundamentals

**Algorithm**
- Prefix sums
- Difference arrays
- Frequency counting
- Basic complexity analysis

**CF**
- 4–6 problems, mainly 900–1100

**CSES**
- Static Range Sum Queries
- Maximum Subarray Sum
- Distinct Numbers
- Apartments

**Implementation**
- prefix sum
- frequency map
- sorting + two pointer

**Night review**
Record:
- what you know
- what you completely don't know
- 10 most common mistakes

---

## 17 Sep
### Theme: Two pointers + sliding window

**Learn**
- two pointers
- fixed window
- variable window
- frequency maintenance

**CF**
- 5–7 problems around 900–1200

**CSES**
- Ferris Wheel
- Playlist
- Distinct Values Subarrays

**Implementation**
- two pointer template from memory

---

## 18 Sep
### Theme: Binary search

**Learn**
- ordinary binary search
- lower/upper bound
- binary search on answer
- monotonic predicates

**CF**
- 5–6 around 1000–1200

**CSES**
- Factory Machines
- Array Division

**Implementation**
- write 3 binary-search variants without notes

---

## 19 Sep
### Theme: Greedy

**Learn**
- sorting + greedy
- exchange-style reasoning
- interval scheduling

**CF**
- 5–6 around 1000–1200
- 1 problem around 1300

**CSES**
- Movie Festival
- Tasks and Deadlines
- Reading Books

---

## 20 Sep
### Theme: Stack / queue / monotonic structures

**Learn**
- stack
- queue
- deque
- monotonic stack

**CF**
- 5–7 around 1000–1250

**CSES**
- Nearest Smaller Values
- Playlist
- Towers

**Implementation**
- monotonic stack from scratch

---

## 21 Sep
### Theme: BFS / DFS

**Learn**
- graph representation
- BFS
- DFS
- components
- grid graphs

**CF**
- 4–6 graph problems

**CSES**
- Counting Rooms
- Labyrinth
- Building Roads
- Building Teams

---

## 22 Sep
### Theme: Trees + recursion

**Learn**
- rooted tree
- subtree
- depth
- parent
- diameter
- tree DP basics

**CF**
- 4–5 tree problems around 1000–1300

**CSES**
- Subordinates
- Tree Diameter
- Tree Matching

---

## 23 Sep
### Theme: Basic DP

**Learn**
- state
- transition
- base cases
- 1D/2D DP
- knapsack-style DP
- counting DP

**CF**
- 5–6 DP problems around 1000–1300

**CSES**
- Dice Combinations
- Minimizing Coins
- Coin Combinations I
- Removing Digits

---

## 24 Sep
### Theme: DP reinforcement + bit manipulation

**Learn**
- subset/state thinking
- bit operations
- bitmask basics

**CF**
- 4–6 problems

**CSES**
- Money Sums
- Bit Strings
- Counting Bits

**Extra**
Attempt **SOS Bit Problem** only as exposure. Do not panic if you cannot solve it; it is beyond your current core curriculum.

---

## 25 Sep
### Theme: DSU + MST

**Learn**
- DSU
- path compression
- union by size/rank
- Kruskal
- MST intuition

**CF**
- 4–5 DSU/graph problems

**CSES**
- Road Reparation

**Implementation**
- DSU from memory
- Kruskal from memory

---

## 26 Sep
### Theme: Fenwick Tree

**Learn**
- point update
- prefix query
- range sum
- coordinate compression

**CF**
- 3–5 relevant problems

**CSES**
- Dynamic Range Sum Queries
- List Removals

**Implementation**
Build Fenwick from scratch twice.

---

## 27 Sep
### Theme: Segment Tree

This is your first genuinely important advanced data structure.

**Learn**
- tree representation
- build
- range query
- point update
- merge function
- iterative vs recursive implementation

**Do not learn lazy propagation deeply yet.**

**CSES**
- Dynamic Range Minimum Queries
- Range Xor Queries
- Prefix Sum Queries

**Implementation**
- basic segment tree from scratch
- 2 timed implementations

---

## 28 Sep
### Theme: Shortest paths

**Learn**
- BFS shortest path
- 0–1 BFS
- Dijkstra

**CF**
- 4–5 problems

**CSES**
- Shortest Routes I
- Message Route

**Implementation**
Dijkstra from memory.

---

## 29 Sep
### Theme: LCA / binary lifting

**Learn**
- parent table
- lifting
- LCA
- depth
- tree path basics

**CSES**
- Company Queries I
- Company Queries II
- Distance Queries

Do not go into HLD yet.

---

## 30 Sep
# FULL ICPC VIRTUAL

Treat this as a dress rehearsal.

**5 hours**

Use a recent ICPC regional problem set.

Rules:
- contest conditions
- no editorial
- no random browsing
- strict submission discipline
- practice team communication if teammates are available

### After contest: 2–3h upsolve

For every unsolved problem:

Classify it:

`Didn't know technique`

`Missed observation`

`Implementation mistake`

`Time management mistake`

This classification is extremely important.

---

## 1 Oct
### Final knowledge consolidation

No huge new topics.

Review:

- binary search
- greedy
- BFS/DFS
- DP
- DSU
- Fenwick
- segment tree
- Dijkstra
- LCA
- basic number theory

**Implementation**
Write each core template from memory.

**CF**
3–4 medium problems only.

**CSES**
2–3 problems from your weakest topics.

Sleep normally.

---

## 2 Oct
# TAPER DAY

Do NOT grind 12 hours.

### 12:45–3:00
Light problem solving:
- 3 easy/medium problems

### 3:30–5:00
Template review

### 5:00 onward
Very light review.

No new advanced algorithm.

Prepare:
- compiler
- snippets
- team communication strategy
- contest environment

Go to sleep at a reasonable time.

---

# 3 October — PRELIM

Do not attempt to "learn CP" today.

Your job:

**Read → classify → solve easy problems → communicate → avoid unnecessary bugs.**

First 30 minutes:
- read aggressively
- identify easy construction/math/implementation problems

When stuck:
- explicitly tell teammate what you tried
- move to another problem
- return later

Do not emotionally attach yourself to one problem.

---

# PART II — EXTENDED 2-MONTH PLAN

# 4–10 October — Consolidation

Now that the prelim is over:

### Main goals
- identify weaknesses
- build stronger data structures
- push CF rating upward

Daily:

**3h CF**

**3h algorithm learning**

**2h implementation**

**3h CSES/ICPC**

**1h review**

Topics:

- segment tree properly
- lazy propagation
- Fenwick variations
- LCA
- tree techniques
- SCC
- bridges/articulation points

---

# 11–17 October — Intermediate Graphs + DP

Topics:

- SCC
- topological DP
- DAG
- shortest path variants
- tree DP
- rerooting intuition
- bitmask DP
- digit DP introduction

CF target:
**1100–1500**

CSES:
- Graph Algorithms
- DP
- Tree Algorithms

One hard problem/day.

---

# 18–24 October — Range Queries + Advanced Trees

Topics:

- lazy segment tree
- coordinate compression
- offline queries
- sweep line
- Euler tour
- subtree queries
- HLD introduction

CSES:
- Range Query section
- Path Queries
- Subtree Queries
- Path Queries II

At this stage start attempting some 1400–1600 CF problems seriously.

---

# 25–31 October — Number Theory + Combinatorics

Topics:

- modular inverse
- fast exponentiation
- combinatorics
- factorial / inverse factorial
- binomial coefficients
- inclusion-exclusion
- gcd tricks
- divisor functions
- Euler phi
- Möbius introduction
- probability basics

CSES:
- Mathematics
- Counting

Do not memorize formulas without understanding why they work.

---

# 1–7 November — Advanced Problem Solving

Now begin intentionally exposing yourself to:

- 1600–1800 CF
- hard CSES
- AtCoder harder problems

Topics:

- advanced DP
- optimization DP
- bitmask DP
- advanced graph techniques
- flow introduction
- matching introduction
- convex hull trick
- Li Chao tree

This is where **Li Chao becomes worth your time**.

Not before the foundation.

---

# 8–15 November — Mixed ICPC Training

Every 2–3 days:

**Full 5-hour virtual**

Other days:

- 2h CF medium/hard
- 2h CSES
- 2h implementation
- 2h algorithm study
- 2h upsolve

Main metric:

> Can you recognize the algorithm family faster?

---

# 7. CSES Problem Philosophy

Do not try to "finish CSES."

The current set has **400 problems**, including many recent additions, so completion is not the right immediate objective. citeturn188261search0turn188261search3

Instead use CSES as:

## Foundation
- Introductory
- Sorting and Searching
- basic DP
- basic Graphs

## Technique building
- Range Queries
- Tree Algorithms
- Mathematics

## Ceiling training
- Bitwise Operations
- Advanced Graph Problems
- Counting
- Additional Problems

The current CSES set contains problems such as:
- `Range Updates and Sums`
- `Path Queries II`
- `Fixed-Length Paths II`
- `Graph Girth`
- `Acyclic Graph Edges`
- `Xor Pyramid Peak`
- `SOS Bit Problem`
- `Empty String`

Some of these should be thought of as **future problems**, not immediate homework. citeturn188261search1

---

# 8. How to Use Editorials

Use this protocol.

## Level 1 problem

If you cannot solve after ~20–25 min:

Read the editorial.

Then immediately re-solve.

## Level 2 problem

Try 40–60 min.

Then editorial if stuck.

## Level 3 problem

Try 60–120 min.

Editorial is allowed only after a genuine attempt.

After reading:

**Close the editorial.**

Then write the solution yourself.

Never count:

> "I understood the editorial"

as equivalent to:

> "I can solve it."

---

# 9. Your Personal Problem Log

Create:

```text
CP/
├── problems.md
├── algorithms.md
├── bugs.md
├── templates/
└── mistakes.md
```

For every important problem:

```text
Problem:
Rating:
Topic:
My approach:
Where I got stuck:
Key observation:
Final technique:
Implementation detail:
Would I recognize this again?
```

For bugs:

```text
Date:
Problem:
Bug:
Why it happened:
How to prevent it:
```

---

# 10. Weekly Metrics

Every 7 days record:

| Metric | Goal |
|---|---:|
| CF problems solved | 30–50 |
| CSES problems | 10–20 |
| AtCoder problems | 5–10 |
| Full ICPC virtuals | 1–3 |
| New algorithms learned | 2–4 |
| Timed implementations | 10+ |
| Hard problems seriously attempted | 5–10 |

Do not force these numbers if problem difficulty is high.

**5 hard, deeply understood problems can be worth more than 20 trivial ACs.**

---

# 11. The Most Important Skill Order

Your progression should roughly be:

```text
Basic implementation
        ↓
Prefix sums / sorting / maps
        ↓
Two pointers / binary search / greedy
        ↓
Stack / queue / monotonic structures
        ↓
BFS / DFS / trees
        ↓
Basic DP
        ↓
DSU
        ↓
Shortest paths
        ↓
Fenwick
        ↓
Segment tree
        ↓
LCA / binary lifting
        ↓
SCC / bridges / articulation
        ↓
Advanced DP / tree techniques
        ↓
HLD / flow / advanced strings
        ↓
Li Chao / CHT / advanced optimizations
```

This is the order I'd use for **your current knowledge**, not the order in which these topics happen to appear on a random website.

---

# 12. The Core Principle

You are currently around **1100**, so your most valuable improvement is not becoming capable of solving 2200-rated problems immediately.

It is becoming the person who sees a problem and thinks:

> "This is binary search on answer."

> "This is just DSU."

> "This is a tree DP."

> "This needs offline queries."

> "This is a segment tree."

> "This is Dijkstra."

That vocabulary grows your solve rate enormously.

Then the next stage is:

> "None of the standard techniques work. I need a new observation."

That is where your peak thinking ability starts developing.

So for the next few weeks, your strategy is:

**BUILD THE TOOLKIT → DRILL THE TOOLKIT → APPLY IT → CONTEST → UPSOLVE → REPEAT.**

Do not chase Li Chao trees while you still have gaps in BFS, DP, DSU, Fenwick, segment tree, shortest paths, and LCA.

---

# Final Target

### By October 3

You want:

- strong 900–1200 speed
- decent 1200–1300 recognition
- exposure to 1300–1500
- core graph knowledge
- basic DP
- DSU
- Fenwick
- basic segment tree
- Dijkstra
- LCA/binary lifting
- significantly faster implementation
- actual ICPC contest experience

### By November 15

You want to be moving toward:

- reliable 1300–1500 CF performance
- exposure to 1600–1800
- strong standard algorithm toolkit
- several advanced topics
- substantially better ICPC problem selection
- much stronger implementation speed
- enough depth to start attacking 1800+ ideas seriously

**Do not judge the plan by whether your Codeforces rating reaches a particular number by October 3. Judge it by how many more problems become recognizable and implementable under contest pressure.**
