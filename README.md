# ICPC Preparation Plan — Zero to Regional Contender (IIT Guwahati)

**Start Date:** 16 September 2026  
**ICPC Preliminary Round:** 3 October 2026 (17-Day Intensive Sprint)  
**Extended Regional & Meta Hacker Cup Phase:** 4 October → 15 November 2026  
**Target Sites:** ICPC Kanpur & Amritapuri Regionals  
**Sleep Schedule:** 1:00 AM / 1:30 AM → 8:30 AM / 9:00 AM (Daytime Contest Aligned)  
**Target Rating Range:** Bulletproof at **1300–1600**, Stretch at **1600–1750** on High-Yield Topics  

---

## 1. Ground Truth & Strategic Calibration

### The IIT Guwahati Reality & The College Quota
IIT Guwahati is one of the most competitive ICPC environments in India (20+ active teams, CMs, Masters, and INOI veterans). 
* **The Real Gate:** The institute quota limits qualification to the **top 2 to 4 teams per college per regional site** (Amritapuri ~3–4 teams, Kanpur ~2–3 teams).
* **The Qualifying Score:** The top 2 IITG teams will solve 4–6 problems. To grab the 3rd or 4th slot, your team **must solve 3 problems cleanly with near-zero penalties**, with a strong push on Problem 4. 
* **The Formula:**
  * 2 Problems Solved $\implies$ 0% chance of qualification.
  * 3 Problems + 4 WAs $\implies$ Knocked out by another IITG team with fewer penalties.
  * 3 Problems + 0–1 WA (under 120 mins) $\implies$ **~85% qualification chance**.
  * 4 Problems Solved $\implies$ **Guaranteed Regional qualification**.

### Your Profiles & Team Balance
* **You (`adarak`):** Specialist / max 1678. 422 problems solved. **Outstanding 91.4% submission accuracy** (427 OK vs 40 WA). Strong math/greedy foundation, building independent derivation on Div 2 B/C without Discord hints.
* **Teammate 2 (`12crack_head`):** Pupil (1241), but 957 problems solved (188 in 1500–1600, 138 in 1700–1800). High pattern exposure, but severe penalty accumulation (764 WAs).
* **Team Lead (`ShinChan5`):** Specialist (1444). 93 contests, 967 problems solved (261 Problem C's, 139 Problem D's). Veteran contestant, but also prone to penalty spikes (711 WAs).

### Your "Specialist Weapon" Strategy
You do **not** need to practice every random 1800 problem (skip Li Chao, flows, centroid decomposition, HLD). Instead, you become a **deadly specialist in the exact 5 topics that appear in Problems 1, 2, 3, and 4**:
1. **Ad-hoc & Greedy Invariants** (up to 1600) — Solve Problem 1 in 15 mins with 0 WAs.
2. **Two Pointers & Sliding Window** (up to 1650) — High frequency in Problem 2 & 3.
3. **Binary Search on Answer** (up to 1650) — Dominates Problem 2 & 3.
4. **Number Theory & Modular Arithmetic** (up to 1600) — Dominates Problem 2.
5. **Graph BFS / Shortest Paths / DSU** (up to 1700) — Dominates Problem 3 & 4.

---

## 2. The 25 Core Patterns Checklist (Your 1300–1500 Arsenal)

At the 1300–1500 level, competitive programming consists of approximately **25 canonical patterns**. You do not need 300 problems to learn them; you need **3 to 4 clean variations of each pattern** ($25 \times 3\text{–}4 \approx 80\text{–}100$ problems total over 16 days = **5 to 7 problems/day**).

Track your mastery of these patterns:
- [ ] **1. Prefix Sums & Prefix XOR:** $O(1)$ range queries without trees.
- [ ] **2. Difference Arrays:** $O(1)$ range updates, $O(N)$ sweep reconstruction.
- [ ] **3. Two Pointers (Opposite Ends):** Pair sums, palindromes, container boundaries.
- [ ] **4. Two Pointers / Sliding Window (Same Direction):** Subarrays with frequency maps.
- [ ] **5. Coordinate Compression:** Compressing coordinates $10^9 \to 2 \cdot 10^5$.
- [ ] **6. Binary Search on Answer:** Monotonic feasibility predicates ("Can we achieve $X$?").
- [ ] **7. Monotonic Stack:** Nearest smaller/greater element in $O(N)$, histogram areas.
- [ ] **8. Greedy Exchange Arguments:** Sorting by deadline, end-time, or ratios ($A_i/B_i$).
- [ ] **9. Contribution to Total Sum:** Counting how many subarrays or pairs element $i$ contributes to.
- [ ] **10. Parity & Invariants under Swaps:** Even/odd parity, cycle counts, permutation parity.
- [ ] **11. Working Backwards:** Reversing the simulation starting from the target state.
- [ ] **12. Modular Arithmetic Basics:** Fast exponentiation `pow_mod`, Fermat's inverse $a^{M-2} \pmod M$.
- [ ] **13. Sieve & Prime Factorization:** $O(N \log \log N)$ sieve, prime omega, divisor precomputation.
- [ ] **14. GCD / LCM Invariants:** Prefix/suffix GCDs, $\gcd(a, b) = \gcd(a, b - a)$.
- [ ] **15. Bitwise Independence:** Processing bit $0$ to bit $30$ as 30 independent 1D problems.
- [ ] **16. Bitmask Brute Force:** Subsets for $N \le 20$ ($2^N$ states).
- [ ] **17. 1D Dynamic Programming:** State formulation, jump transitions, memory reduction.
- [ ] **18. Knapsack / Subset Sum DP:** 0/1 knapsack, space compression to 1D array.
- [ ] **19. Grid DP:** Counting paths, blocking cells, DAG transitions on matrices.
- [ ] **20. Graph BFS / Flood Fill:** 2D grid components, unweighted shortest paths.
- [ ] **21. Disjoint Set Union (DSU):** Cycle detection, connected components, Kruskal's MST.
- [ ] **22. Tree Traversal & Diameters:** Subtree sizes, 2-BFS tree diameter.
- [ ] **23. Constructive & Checkerboard Patterns:** Parity coloring, alternating placements.
- [ ] **24. Small $N$ Manual Brute Force:** Testing $N \le 4$ on paper to reveal hidden formulas.
- [ ] **25. Custom Sorting & Tie-Breaking:** Multi-key sorting with lambdas and structs.

---

## 3. Daily Problem Quota: Exactly 6 to 8 Problems (The Volume Law)

* **Why not 15–20 problems?** Solving 10 easy (800–1000) problems burns 2 hours on things you already know, giving cheap dopamine with zero rating growth. Trying to do twenty 1400+ problems leads to brain exhaustion, careless guesses, and passive editorial reading.
* **The Math:** 25 patterns $\times$ 3–4 variations = **~80 to 100 problems total**. Over 16 active days, **6 to 8 focused problems per day** completely covers the entire 1300–1500 curriculum without causing pre-contest burnout.

---

## 4. Escaping the "Discord Spectator Trap"

Because you previously solved contests on Discord while friends discussed observations, you have passive comprehension without active derivation muscle.

### The Active Derivation Protocol (Mandatory for Sprint)
1. **Total Isolation:** No Discord, no voice chat, no stream during solving blocks.
2. **Paper-First Rule (20-Minute Minimum):**
   * Never touch the keyboard immediately.
   * Manually trace small samples on paper ($N = 3, 4, 5$).
   * Ask: *What invariant holds? What happens when I sort? Is the answer monotonic? What is the parity?*
3. **Constraint Reverse-Engineering:**
   * $N \le 20 \implies O(2^N)$ (Bitmask / Brute Force)
   * $N \le 500 \implies O(N^3)$ (Floyd-Warshall, 3-nested loops)
   * $N \le 2000 \implies O(N^2)$ (Simple 2D DP, all pairs)
   * $N \le 2 \cdot 10^5 \implies O(N \log N)$ or $O(N)$ (Sorting, Two Pointers, Binary Search, Prefix Sums, BFS/DFS, DSU)
4. **Strict Editorial Rules:**
   * **1200–1400 problems:** Give 25–30 minutes on paper. Derive brute force first. If stuck, read *only the first hint*.
   * **1400–1650 problems:** Give 40–50 minutes on paper. Trace edge cases. If stuck, read the observation paragraph, close it, and implement completely independently.
   * Never copy-paste editorial code. If you cannot code it after reading the idea, you did not understand it.

---

## 5. Daily Base Schedule (Daytime Contest Aligned)

| Time | Block | Focus |
|---|---|---|
| **8:30 – 9:15 AM** | Wake / Shower / Breakfast | Sunlight exposure, hydration, full alertness |
| **9:15 AM – 12:45 PM** | **Block 1: Theory Lecture & Foundation Drill** (3.5h) | • **9:15 – 10:15 AM (60m):** Watch video lecture / read USACO Guide or CP-Algorithms<br>• **10:15 – 10:45 AM (30m):** Code template from memory on paper & IDE<br>• **10:45 AM – 12:45 PM (2h):** Apply technique to 2–3 CSES foundation problems |
| **12:45 – 1:45 PM** | Lunch & Walk | Clear head |
| **1:45 – 5:15 PM** | **Block 2: Solo CF Difficulty Ladder (1200–1700)** (3.5h) | Timed solo contest simulation: 1x 1100 (speed warm-up), 2x 1300–1400, 1x 1500–1600, 1x 1600–1700 |
| **5:15 – 6:15 PM** | Break / Workout / Dinner | Step completely away from screens |
| **6:15 – 9:15 PM** | **Block 3: ICPC Past Prelim Problems & Speedrun** (3.0h) | Gym 106179, CodeDrills archives, stress testing, team coordination mock blocks |
| **9:15 – 9:45 PM** | Snack & Rest | |
| **9:45 – 12:15 AM** | **Block 4: Deep Upsolving & Bug Logging** (2.5h) | Upsolve failed problems from Block 2 & 3, update `BUG_LOG.md`, reimplement clean ACs |
| **12:15 – 1:00 AM** | Wind down & Prep | No screen reading; sleep by 1:00 / 1:30 AM |

**Total Pure CP Work:** ~12.5 focused hours per day.

#### Your Local TLE Eliminators Lecture Library (`/home/rustam/Downloads/Courses`):
Do **NOT** try to watch Level 2 Live $\to$ Level 3 Self $\to$ Level 3 Live $\to$ Level 4 Live sequentially like a TV show. That is **180+ hours of video** (over 11 hours of watching per day with zero problem solving). 

Instead, treat your local TLE folder as an **On-Demand Tactical Armoury**: each morning at 9:15 AM, you watch **only** the 45–60 min lecture corresponding to the day's specific sprint topic:
* **Level 2 Course / Self Paced:** Best for Prefix Sums/Diff arrays (`week6`), Monotonic Stacks, and Basic Binary Search.
* **Level 3 Self Paced & Course:** Best for Two Pointers/Sliding Window (`Week 6` / files `11.Two_Pointers_Introduction.mp4`, `9.Sliding_Window.mp4`), Number Theory (`Week 7` / `14.Number_Theory_1.mp4`), and Greedy (`Week 2` / `1.Greedy_Algoritham_1.mp4`).
* **Level 4 Course:** Best for DP Beginner/Intermediate (`Week 1 & 2`), Graphs BFS/DFS (`Week 8`), DSU & Shortest Paths (`Week 9 & 10`).

---

## 6. ICPC Contest Rules, Penalty Control & Stress Testing

### The 20-Minute Penalty Rule
In ICPC, penalty = `(Submission Time in Minutes) + (20 × Rejected Submissions)`.  
* Team X: 3 solves at minute 40, 80, 120 with 0 penalties = **240 total penalty**.
* Team Y: 3 solves at minute 40, 80, 120 with 4 WAs = **320 total penalty**.  
**Team X beats Team Y.** At the college cutoff boundary, penalty differences dictate who goes to Regionals.

### The 3-Minute Stress-Testing Template
When you or your teammates suspect a bug or WA on Problem 1/2/3, run this stress script:

```python
# stress.py - Put in your CP directory
import random, subprocess, sys

def generate_test():
    n = random.randint(1, 10)
    a = [random.randint(1, 20) for _ in range(n)]
    return f"{n}\n" + " ".join(map(str, a)) + "\n"

# Loop until a mismatch occurs
for t in range(1, 1000):
    test = generate_test()
    with open("in.txt", "w") as f: f.write(test)
    
    out_fast = subprocess.check_output("./solution < in.txt", shell=True).decode()
    out_brute = subprocess.check_output("./brute < in.txt", shell=True).decode()
    
    if out_fast.strip() != out_brute.strip():
        print(f"Failed on test {t}:")
        print(test)
        print(f"Fast: {out_fast} | Brute: {out_brute}")
        sys.exit(0)
print("All 1000 tests passed!")
```

---

## 7. PART I: 17-DAY PRELIM SPRINT (16 Sep → 3 Oct)

Every day pairs **CSES foundational mastery** with **Codeforces 1300–1700 targeted practice** and **Past ICPC Prelim problems**.

---

### Day 1 (Wed, 16 Sep) — Problem 1 Mastery & Edge Cases (Special 4:00 PM Kickoff)

> **Day 1 Schedule:** Designed to start at **4:00 PM** following the completion of the two Level 2 Self-Paced Binary Search videos (`29.Binary_Search.mp4` & `30.Binary_Search-Problem-solving.mp4`). The standard 8:30 AM schedule resumes strictly on Day 2.

#### Today's Exact Timetable (16 Sep):
| Time | Block | Tasks |
|---|---|---|
| **1:40 – 3:15 PM** | **Pre-Start** | Watch `29.Binary_Search.mp4` & `30.Binary_Search-Problem-solving.mp4` ($1.25\times/1.5\times$). Level 2 Self Paced officially 100% complete! |
| **3:15 – 4:00 PM** | **Lunch & Prep** | Lunch, hydration, notebook ready at desk. |
| **4:00 – 6:30 PM** (2.5h) | **Block 1: CSES Foundation** | **1.** [*Distinct Numbers*](https://cses.fi/problemset/task/1621) (Sorting baseline, 10m)<br>**2.** [*Static Range Sum Queries*](https://cses.fi/problemset/task/1646) (Prefix sums baseline, 15m)<br>**3.** [*Maximum Subarray Sum*](https://cses.fi/problemset/task/1643) (Kadane’s / prefix min, 25m)<br>**Drill:** Write 2D prefix sum formula from memory on paper. |
| **6:30 – 7:00 PM** (30m) | **Break** | Walk, stretch, snack. Step away from screens. |
| **7:00 – 9:30 PM** (2.5h) | **Block 2: Solo CF Ladder** | Timed solo contest simulation (no Discord):<br>• **1x 1000** (Warm-up speed, strictly 0 WA, < 10m)<br>• **2x 1200–1300** (`math`, `implementation`, 20–25m paper derivation)<br>• **1x 1400–1500** (`greedy`, `sortings`, 35–45m) |
| **9:30 – 10:15 PM** (45m) | **Dinner** | Meal & relax. |
| **10:15 – 11:30 PM** (1.25h) | **Block 3: Past Prelim Problem** | Solve **Buy K Get 1 Free** (from official ICPC 2024 Prelim / [Gym 106179](https://codeforces.com/gym/106179)).<br>Verify constraints, dry-run $N=1$, submit with **zero penalties**. |
| **11:30 – 12:45 AM** (1.25h) | **Block 4: Bug Log & Review** | • Log any WAs, TLEs, or edge-case slips into `BUG_LOG.md`.<br>• Upsolve whichever problem was hardest today. |
| **12:45 – 1:15 AM** | **Wind Down & Sleep** | Shut off all screens. **Sleep by 1:15 AM** to wake up fresh at 8:30 AM tomorrow. |

---

### Day 2 (Thu, 17 Sep) — Prefix Sums, Difference Arrays & Prefix XOR
* **Goal:** Range query and range update operations in $O(1)$ without trees.
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 2 Course/week6/` (Difference Array & 2D Prefix Sums)
* **CSES Problemset:**
  1. *Range Xor Queries* (Solve via prefix XOR in $O(1)$, NOT segment tree!)
  2. *Subarray Sums I* (Prefix sums + map)
  3. *Subarray Divisibility* (Prefix sums + modulo logic)
* **Codeforces Solo Block:**
  - 2x 1300–1400 (`data structures`, `prefix sums`)
  - 1x 1500–1600 (`constructive algorithms`)
* **Implementation Drill:** 2D prefix sums and difference array update/reconstruct from memory.

---

### Day 3 (Fri, 18 Sep) — Two Pointers & Sliding Window (Problem 2 & 3 Core)
* **Goal:** Turn $O(N^2)$ subarray/pair searches into $O(N)$. Master coordinate sorting.
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 3 Self Paced/11.Two_Pointers_Introduction.mp4` & `9.Sliding_Window.mp4` (or `Level 3 Course/Week 6` by Priyansh Agarwal)
* **CSES Problemset:**
  1. *Ferris Wheel* (Two pointers greedy pairing)
  2. *Playlist* (Two pointers with hash map / frequency array)
  3. *Sum of Three Values* (Sorting + two pointers $O(N^2)$)
* **Codeforces Solo Block:**
  - 2x 1300–1400 (`two pointers`)
  - 1x 1500–1650 (`two pointers`, `binary search`)
* **Past Prelim Problem:** *Collisions* (ICPC 2024 Prelim / Gym 106179) — 1D coordinate sorting + two pointers.

---

### Day 4 (Sat, 19 Sep) — Binary Search on Answer (Problem 2 & 3 Core)
* **Goal:** Recognize "maximize the minimum" or monotonic feasibility predicates.
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 3 Self Paced/2.Binary_Search_on_answer.mp4`
* **CSES Problemset:**
  1. *Factory Machines* (Binary search on answer)
  2. *Array Division* (Classic partition binary search)
  3. *Concert Tickets* (`std::multiset::upper_bound`)
* **Codeforces Solo Block:**
  - 2x 1300–1400 (`binary search`)
  - 1x 1500–1650 (`binary search on answer`)
* **Implementation Drill:** Floating-point binary search vs integer binary search boundaries.

---

### Day 5 (Sun, 20 Sep) — Number Theory & Modular Arithmetic (Problem 2 Core)
* **Goal:** Master the math patterns that appear in Problem 2 of nearly every ICPC round.
* **Theory:** Fast binary exponentiation $O(\log P)$, Fermat's Little Theorem for inverse ($a^{M-2} \pmod M$), GCD / Sieve $O(N \log \log N)$.
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 3 Self Paced/14.Number_Theory_1.mp4` & `15.Number_Theory_2.mp4` (or `Level 3 Course/Week 7`)
* **CSES Problemset:**
  1. *Exponentiation* & *Exponentiation II* (Binary exponentiation & Euler totient)
  2. *Common Divisors* (GCD frequency counting in $O(N + V \log V)$)
  3. *Counting Divisors* (Sieve precomputation)
* **Codeforces Solo Block:**
  - 2x 1300–1400 (`number theory`)
  - 1x 1500–1600 (`math`, `combinatorics`)
* **Past Prelim Problem:** *Bincatmod* (ICPC 2024 Prelim / Gym 106179) — binary concatenation modulo $M$.

---

### Day 6 (Mon, 21 Sep) — Greedy Invariants & Exchange Arguments
* **Goal:** Prove why local optimal choices yield global solutions; master custom comparators.
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 3 Self Paced/1.Greedy_Algoritham_1.mp4` & `20.Greedy_Algo_2.mp4`
* **CSES Problemset:**
  1. *Movie Festival* (Interval scheduling)
  2. *Tasks and Deadlines* (Exchange argument: shortest deadline first)
  3. *Towers* (Greedy placement with multiset / binary search)
* **Codeforces Solo Block:**
  - 2x 1300–1400 (`greedy`)
  - 1x 1500–1650 (`greedy`, `exchange argument`)
* **Past Prelim Problem:** *Reduction Game* (ICPC 2023 Prelim / CodeDrills) — greedy sorting logic.

---

### Day 7 (Tue, 22 Sep) — Monotonic Stacks & Queues (Problem 3 & 4 Core)
* **Goal:** Finding the nearest smaller/greater element in $O(N)$; subarray range extrema.
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 2 Course/week3/` (Stack, Monotonic Stack & Queue)
* **CSES Problemset:**
  1. *Nearest Smaller Values* (Classic monotonic stack)
  2. *Advertisement* (Largest rectangle under histogram — pure monotonic stack)
* **Codeforces Solo Block:**
  - 2x 1300–1450 (`data structures`, `monotonic stack`)
  - 1x 1500–1650 (`stacks`)
* **Past Prelim Problem:** *Game-2048* (ICPC 2024 Prelim / Gym 106179) — stack simulation.

---

### Day 8 (Wed, 23 Sep) — Graph BFS, DFS & 2D Grids (Problem 3 Core)
* **Goal:** Grid traversals, connected components, shortest path in unweighted graphs.
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 4 Course/Week 8/1. Graphs 1  05-06-2023 TLE 4 by Priyansh Agarwal.mp4`
* **CSES Problemset:**
  1. *Counting Rooms* (Grid connected components)
  2. *Labyrinth* (BFS shortest path + path reconstruction)
  3. *Building Roads* & *Building Teams* (Components & bipartite 2-coloring)
* **Codeforces Solo Block:**
  - 2x 1300–1400 (`dfs and similar`, `graphs`)
  - 1x 1500–1650 (`graphs`, `shortest paths`)
* **Implementation Drill:** 2D grid direction vectors `dx[]/dy[]` and path reconstruction with parent pointer.

---

### Day 9 (Thu, 24 Sep) — Trees as Graphs & Tree Diameters
* **Goal:** Rooted trees, subtree sizes, tree traversal, diameter via 2-BFS.
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 4 Course/Week 6/` (Trees Beginner / Tree Traversal)
* **CSES Problemset:**
  1. *Subordinates* (Subtree size calculation)
  2. *Tree Diameter* (2-BFS or DFS approach)
  3. *Tree Distances I* (Prefix/suffix traversal or tree diameter property)
* **Codeforces Solo Block:**
  - 2x 1300–1400 (`trees`)
  - 1x 1500–1650 (`trees`, `dfs and similar`)

---

### Day 10 (Fri, 25 Sep) — DSU & Shortest Paths (Problem 3 & 4 Core)
* **Goal:** Connectivity updates, cycle detection, Dijkstra, Floyd-Warshall.
* **Theory:** 
  - Dijkstra $O((V + E) \log V)$ using `std::priority_queue`
  - 0–1 BFS using `std::deque`
  - Floyd-Warshall $O(V^3)$ (for dense graphs $V \le 400$)
  - DSU with path compression & size union $O(\alpha(N))$
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 4 Course/Week 9/2. DSU  14-06-23 TLE Level 4 by Dev Karan.mp4` & `Week 10/1_Graphs_MST_+_floyd_Warshall_17_06_2023_TLE_Level_4_by_Dev_Karan.mp4`
* **CSES Problemset:**
  1. *Shortest Routes I* (Dijkstra)
  2. *Road Reparation* (Kruskal's MST with DSU)
  3. *Road Construction* (DSU component count & maximum component size)
* **Codeforces Solo Block:**
  - 2x 1300–1400 (`dsu`, `graphs`)
  - 1x 1500–1650 (`dsu`, `shortest paths`)
* **Past Prelim Problem:** *Equations* (ICPC 2024 Prelim / Gym 106179) — DSU graph cycle detection.

---

### Day 11 (Sat, 26 Sep) — Dynamic Programming I: Fundamentals & 1D
* **Goal:** State formulation, DAG transitions, eliminating recursion overhead.
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 4 Course/Week 1/` (`Lecture 1.1 & 1.2 DP Beginner`) or `Level 3 Course/Week 9/1. DP 1 by Priyansh Agarwal.mp4`
* **CSES Problemset:**
  1. *Dice Combinations* (1D state transition)
  2. *Minimizing Coins* (Coin change min coins)
  3. *Coin Combinations I* (Coin change ordered combinations)
  4. *Removing Digits* (Greedy vs DP)
* **Codeforces Solo Block:**
  - 2x 1300–1400 (`dp`)
  - 1x 1500–1650 (`dp`)

---

### Day 12 (Sun, 27 Sep) — Dynamic Programming II: 2D & Knapsack
* **Goal:** Subset sum, 0/1 knapsack, space-optimized 1D arrays.
* **TLE Lecture (Block 1):** `TLE Eliminators 7.0 Batch - Level 4 Course/Week 2/` (`Lecture 2.1 & 2.2 DP Intermediate`) or `Level 3 Course/Week 9/2. DP 2 by Priyansh Agarwal.mp4`
* **CSES Problemset:**
  1. *Grid Paths* (Grid counting DP)
  2. *Book Shop* (Classic 0/1 Knapsack with 1D space optimization)
  3. *Money Sums* (Subset sums via boolean DP)
* **Codeforces Solo Block:**
  - 2x 1300–1400 (`dp`)
  - 1x 1500–1650 (`dp`, `bitmasks`)

---

### Day 13 (Mon, 28 Sep) — Constructive & Invariant Thinking (Div 2 B/C Specialty)
* **Goal:** Solving non-standard problems where no textbook algorithm applies.
* **Theory:** Parity invariants, symmetry, working backward from target, small $N$ brute-forcing.
* **Codeforces Solo Block:**
  - 4x 1300–1500 problems tagged `constructive algorithms` / `math`.
  - Enforce 25 minutes of paper derivation before coding.
* **Stress Testing:** Setup `stress.py` and run against a brute force on 1 constructive problem.

---

### Day 14 (Tue, 29 Sep) — Team Strategy Sync & TRD Assembly
* **Team Sync (2 hours with `12crack_head` and `ShinChan5`):**
  - Define roles: Who reads which half of the problem set in the first 10 minutes?
  - Enforce the **Zero Penalty Gatekeeper Rule**: Nobody submits without testing $N=1$, max constraints, and overflow.
  - Compile the 25-page printed Team Reference Document (TRD).
* **Solo Drill:** Timed speedrun of 4 problems (1200–1400). Target: 100% first-try AC.

---

### Day 15 (Wed, 30 Sep) — FULL 5-HOUR TEAM ICPC VIRTUAL CONTEST
* **Simulate Real Contest Conditions:**
  - Full 5-hour uninterrupted block (preferably 10:00 AM – 3:00 PM or 2:00 PM – 7:00 PM).
  - Use **Codeforces Gym 106179** (ICPC 2024 Online Preliminary) or ICPC Amritapuri/Kanpur 2023.
  - Enforce single-computer or strict machine coordination.
  - Track penalty time rigorously.
* **Post-Contest (2 hours):**
  - Categorize every unsolved or penalized problem:
    * *Missed observation*
    * *Implementation bug / Overflow*
    * *Wrong problem order choice*
  - Immediately upsolve the problem that was closest to AC.

---

### Day 16 (Thu, 1 Oct) — Virtual Upsolving & Speed Rehearsal
* **Morning:** Upsolve remaining 1–2 reachable problems from the Sep 30 contest.
* **Afternoon (3 hours):** Mini speed virtual (solve 3 easy-medium problems within 90 minutes).
* **Evening:** Template lock. Print your Team Reference Document. Review all entries in `BUG_LOG.md`.

---

### Day 17 (Fri, 2 Oct) — TAPER DAY (Rest & Mental Sharpness)
* **Do NOT grind 12 hours today.** Burning your mental energy 24 hours before the contest destroys analytical capability.
* **10:00 AM – 1:00 PM:** Light warm-up (2 easy Div 2 A/B problems just to keep hands moving).
* **2:00 – 4:00 PM:** Verify compiler flags, fast I/O snippets, team communication links, backup internet, contest portal logins.
* **Evening:** Healthy meal, walk, relax. **Sleep strictly by 11:30 PM.**

---

### Day 18 (Sat, 3 Oct) — ICPC PRELIMINARY ROUND
* **Breakfast:** Clean meal + caffeine 45 minutes before start.
* **First 15 Minutes:**
  - You scan Problems A, B, C; Teammate 2 scans D, E; Team Lead scans F, G.
  - Identify the easiest problem immediately.
* **During Contest:**
  - Put first AC on the board within 25 minutes.
  - Never submit without dry-running $N = 1$, all-zeros, max constraints, and overflow.
  - If stuck for > 20 min with no progress, leave the keyboard, write state on paper, or switch problems.

---

## 8. PART II: EXTENDED REGIONAL & META HACKER CUP PHASE (4 Oct → 15 Nov)

Following the prelim, your goal shifts from rapid triage to genuine algorithmic depth: elevating your Codeforces rating from 1450 to 1700+ and preparing for on-site Regionals and Meta Hacker Cup.

### Phase Objectives
1. **CF Rating Push:** Push solo rating into 1500–1700 range.
2. **Meta Hacker Cup Focus:** Large input sizes ($T$ test cases, file I/O, heavy recursion limits, corner-case defense).
3. **Advanced Algorithmic Toolkit:** Segment Trees, Lazy Propagation, LCA, Coordinate Compression, Combinatorics.

### Weekly Progression

#### Week 1 (4–10 Oct): Range Queries (Fenwick & Segment Trees)
* **Concepts:** Point update, Range sum, Segment Tree iterative vs recursive, Dynamic Range Minimum Queries.
* **CSES:** *Dynamic Range Sum Queries*, *Dynamic Range Minimum Queries*, *List Removals*.
* **CF Goal:** 1400–1600 range queries.

#### Week 2 (11–17 Oct): Trees & Binary Lifting
* **Concepts:** Binary lifting on trees, LCA in $O(\log N)$, tree path queries, Euler tour representation.
* **CSES:** *Company Queries I & II*, *Distance Queries*, *Path Queries*.
* **CF Goal:** Tree DP and LCA problems.

#### Week 3 (18–24 Oct): Combinatorics & Math for Hacker Cup
* **Concepts:** Factorials, inverse factorials, stars & bars, inclusion-exclusion, linear sieve.
* **CSES:** *Binomial Coefficients*, *Creating Strings II*, *Distributing Apples*, *Christmas Party*.
* **Meta Hacker Cup Prep:** Practice past Hacker Cup Practice / Round 1 problems under timed file I/O.

#### Week 4 (25–31 Oct): Advanced DP & Segment Tree with Lazy Propagation
* **Concepts:** Range update range query, Lazy propagation segment tree, Bitmask DP basics ($O(N \cdot 2^N)$).
* **CSES:** *Range Update Queries*, *Polynomial Queries*, *Matching* (Bitmask DP).

#### Week 5 & 6 (1–15 Nov): Full Regional Virtuals
* Complete two full 5-hour Regional virtuals per week with teammates.
* Focus on Problem C/D level: graph algorithms (SCC / Dijkstra variants), intermediate DP, and combined data structures.

---

## 9. Problem Tracking & Bug Prevention

Create this exact directory layout:

```text
~/icpc/
├── BUG_LOG.md           # Every penalty and bug analyzed
├── TRD/                 # Team Reference Document templates (C++)
│   ├── math.cpp
│   ├── graph.cpp
│   ├── dsu.cpp
│   └── stress.py
└── upsolving/           # Code for problems solved post-contest
```

### Format for `BUG_LOG.md`
Whenever you get a WA or TLE during training, record it before opening the editorial:

```markdown
### [Date] - Problem Name (URL)
* **Verdict:** WA / TLE / MLE / RTE
* **Root Cause:** (e.g., used `int` instead of `long long`; loop went to $N-1$ instead of $N$; didn't clear adjacency list between test cases)
* **Why did I miss it?** (Rushed submission without testing $N=1$)
* **Rule to Prevent:** (Always test $N = 1$ and check max constraint sum $\le 10^9$)
```

---

## 10. Summary Checklist for Success

1. **Fix sleep immediately:** Be in bed by 1:00 AM, up by 8:30 AM. No exceptions.
2. **Cut out passive Discord spectatorship:** Think solo on paper.
3. **Master your role:** Zero penalties on Problem A/B; provide the team an instant lead.
4. **Stress test before submitting:** A 3-minute local script beats a 20-minute penalty every time.
5. **Stick to the high-yield curriculum:** Don't chase 2200-rated data structures when clean greedy, binary search, and DSU are what win Prelim qualification.
