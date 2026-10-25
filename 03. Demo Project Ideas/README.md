# 03 · Demo Project Ideas

Nine **ready-to-adapt** ideas. Each is sized for **~1 month** with AI assistance **if** you spend real time understanding the code.

> These are **starting points, not final projects.** Add your own exceptional features for maintaining originality. Teams with identical ideas must have clearly different implementations and extra features.

## Comparison Matrix

| # | Project | Primary OS concept | Difficulty | Language | Links to lab works |
|---|---------|-------------------|-----------|----------|----------------------|
| 01 | CPU Scheduling Simulator | CPU scheduling | ⭐⭐ | C / Python | Scheduling |
| 02 | Mini Shell | Processes, pipes, signals | ⭐⭐⭐ | C | fork/pipe |
| 03 | Memory Management Simulator | Paging, page replacement | ⭐⭐ | C / Python | Page replacement |
| 04 | Deadlock Toolkit | Deadlock avoidance/detection | ⭐⭐ | C / Python | Banker's |
| 05 | Process Synchronization Lab | Threads, semaphores, mutex | ⭐⭐⭐ | C | Partly |
| 06 | Mini File System | File system, inodes | ⭐⭐⭐ | C | New |
| 07 | Process & System Monitor | `/proc`, process info | ⭐⭐ | C | New |
| 08 | Disk Scheduling Simulator | I/O & disk scheduling | ⭐ | C / Python | New |
| 09 | IPC Job Queue Server | Message queue, shared memory | ⭐⭐⭐ | C | IPC |

⭐ = beginner friendly · ⭐⭐ = moderate · ⭐⭐⭐ = needs careful learning

## Which One Should I Pick?

| If you are... | Consider |
|---------------|----------|
| New to C and Linux | 01, 03, 04, 08 |
| Comfortable with C pointers | 02, 05, 07 |
| Want maximum "wow" in demo | 02, 05, 07 |
| Want the safest, most explainable project | 01, 03, 04 |
| Want depth and challenge | 06, 09 |

## Combining Ideas (Advanced Teams of 3)
Only combine if the **Must-have list stays small**:
- 01 + 08 → "Unified Scheduling Simulator" (CPU and disk)
- 03 + 04 → "Resource Management Suite"
- 02 + 07 → "Shell with built-in process monitor"

## Common Structure in Every Idea File
1. Overview · 2. OS concepts · 3. Features (Must/Should/Could) · 4. Suggested design · 5. Four-week plan · 6. Demo scenario · 7. "You must be able to explain" list · 8. Pitfalls · 9. Exceptions for originality

## Quality Bar for *Any* Idea
- Menu or CLI that does not crash on bad input
- Sample input files in `/examples`
- At least 10 documented tests
- A README that lets a stranger run it in 5 minutes
- Every file explained in `/docs/CODE_EXPLANATIONS.md`
